<template>
    <div class="">
        <h3>连连看?试一试</h3>
        <!-- 首先试试两块点击消除 -->
        <div class="content">
            <div class="box" :class="[disappeared?'disappeared':'',val_1?'active':'']" @click.stop="com_1"></div>
            <div class="box" :class="[disappeared?'disappeared':'',val_2?'active':'']" style="left:110px" @click.stop="com_2"></div>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return{
            val_1:false,
            val_2:false,
            disappeared:false,
            active1:false,
            active2:false
        }
    },
    methods:{
        com_1(){
            this.val_1=!this.val_1
            this.active1=true
            this.merge()
        },
        com_2(){
            this.val_2=!this.val_2
            this.active2=true
            this.merge()
        },
        merge(){
            if(this.val_1&&this.val_2){
                this.disappeared=true
            }
        },
        blur(){
            this.val_1=false
            this.val_2=false
        }
    }
}
</script>

<style scoped>
.disappeared{
    opacity: 0;
}
.box:hover,.active{
    transform: scale(1.1);
}
.box{
    width: 100px;
    height: 100px;
    border-radius: 10px;
    border: 2px solid;
    box-sizing: border-box;
    position: absolute;
    transition: 0.3s;
}
.content{
    width: 800px;
    margin: 0 auto;
    display: flex;
    position: relative;
}
</style>