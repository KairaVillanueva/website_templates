---
layout: default
title: Projects
permalink: /projects/
---

<style>


#nav {
  float-left;
	margin-right: 10px;
}


.e {
  width:100px;
  height:100px;
  float: left;
  background:darkgreen;
  margin-right: 30px;
  margin-left: 40px;
  color: #fff;
  line-height: 95px;
  text-align:center;
  vertical-align: middle;
  line-height: 100px;       /* the same as your div height */

  -webkit-transition: all 2s ease;
  -moz-transition: all 2s ease;
  -o-transition: all 2s ease;
  transition: all 2s ease;
  animation: spin 1s;
  -webkit-animation: spin 1s;
  animation-iteration-count: infinite;
  -webkit-animation-iteration-count: infinite;
  -webkit-animation-direction: alternate;
  -moz-animation-direction: alternate;
  -o-animation-direction: alternate;
  animation-direction: alternate;
}

.e:nth-child(1) {
  animation-delay: 0.5s;
}

.e:nth-child(2) {
  animation-delay: 1s;
  top:0; left:0; right:0; bottom:0;
}

.e:nth-child(3) {
  animation-delay: 1.5s;
  top:0; left:0; right:-20%; bottom:0;
}

@keyframes spin {
  to{background:SeaGreen;}
}

@-webkit-keyframes spin {
  to{background:SeaGreen;}
}

.e:hover {
  transform: rotateZ(540deg);
  border-radius:50%;
}

</style>

<div class="container">

<div class="e"><a href="/writing/"><i class="fa fa-envira fa-4x" aria-hidden="true"></i>
</a></div>
<div class="e"><a href="/games/"><img src="/assets/icons/game.png" width="50px"  height="50px" /></a></div>
<div class="e"><a href="/research/"><img src="/assets/icons/science.png" width="50px" height="50px" /></a></div>
<div class="e"><a href="/organizations/"><img src="/assets/icons/project.png" width="50px"  height="50px" /></a></div>

</div>