<template>
  <div class="about">
    <div class="ani-1 text">一个有信仰的人，至少希望我是</div>
    <div class="ani-2 text">我热爱生活，并且灵魂富有，爱好也尚且广泛</div>
    <div class="ani-3 text">不知道从什么时候开始，我忘记了自己的目标，循规蹈矩的生活，默默苟且</div>
    <div class="ani-4 text">我默许并自认为这就是所谓的脚踏实地</div>
    <div class="ani-5 text">于是我开始扼杀自己的想法，闭上了双眼，放低姿态，抹杀灵魂，降低预期</div>
    <div class="ani-6 text">我觉得我的幸福就快要来，至少我有这么一段时间是这么认为的</div>
    <div class="ani-7 text">但命运貌似并不想我过得太安稳</div>
    <div class="ani-8 text">通过忍耐而得到的所谓的“幸福”貌似并不能维持长久</div>
    <div class="ani-9 text">你不能保证一生中绝对不会出现意外</div>
    <div class="ani-10 text">而更不能保证得是你有即使出现意外也能“紧急避险”的能力</div>
    <div class="ani-11 text">我逐渐愈发意识到这个“能力”对于我而言是极其重要的</div>
    <div class="ani-12 text">没有背景，没有积蓄，没有实力的我现在正是开始的时刻，接下来的日子里，不间断持续努力吧</div>
    <div class="ani-13 text">哪怕你的努力只有一点，若是能积累下来，纵使结果可能仍旧不尽人意，但你总会收获</div>
    <div class="ani-14 text">我坚信这个道理，这是我高中班主任刘毅教会我的，也成为了我一生的信仰</div>
    <div class="ani-15 text">今天的你绝对比昨天的你更强</div>
  </div>
</template>
<style scoped>
@keyframes show-1{
  0%{opacity: 0;left: -10px;}
  100%{opacity: 1;left: 0px;}
}
/* 设定文本出现动画 start */
.ani-15{
  animation: show-1 1s 7s;
  animation-fill-mode:forwards;
}
.ani-14{
  animation: show-1 1s 6.5s;
  animation-fill-mode:forwards;
}
.ani-13{
  animation: show-1 1s 6s;
  animation-fill-mode:forwards;
}
.ani-12{
  animation: show-1 1s 5.5s;
  animation-fill-mode:forwards;
}
.ani-11{
  animation: show-1 1s 5s;
  animation-fill-mode:forwards;
}
.ani-10{
  animation: show-1 1s 4.5s;
  animation-fill-mode:forwards;
}
.ani-9{
  animation: show-1 1s 4s;
  animation-fill-mode:forwards;
}
.ani-8{
  animation: show-1 1s 3.5s;
  animation-fill-mode:forwards;
}
.ani-7{
  animation: show-1 1s 3s;
  animation-fill-mode:forwards;
}
.ani-6{
  animation: show-1 1s 2.5s;
  animation-fill-mode:forwards;
}
.ani-5{
  animation: show-1 1s 2s;
  animation-fill-mode:forwards;
}
.ani-4{
  animation: show-1 1s 1.5s;
  animation-fill-mode:forwards;
}
.ani-3{
  animation: show-1 1s 1s;
  animation-fill-mode:forwards;
}
.ani-2{
  animation: show-1 1s 0.5s;
  animation-fill-mode:forwards;
}
.ani-1{
  animation: show-1 1s;
  animation-fill-mode:forwards; /* 设置动画定格为结束时状态 */
}
/* 设定文本出现动画 end */
/* 设定文本格式 start */
.text{
  opacity: 0;
  position: relative;
  margin: 10px 0;
  font-size: 14px;
  font-weight: 600;
  
}
</style>