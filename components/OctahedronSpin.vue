<template>
<ul class='simpleShapes'>
  <li class='side'></li>
  <li class='side'></li>
</ul>
</template>

<style>
/**
 * Pure CSS Real Spinning Octahedron (Triangular Antiprism)
 * http://mathworld.wolfram.com/Octahedron.html
 * http://en.wikipedia.org/wiki/Octahedron
 * http://www.mathsisfun.com/geometry/octahedron.html
 * get triangular faces using this method http://dabblet.com/gist/3805071
 * 
 * Related
 * -------
 * Pure CSS Real Spinning Truncated Cube http://dabblet.com/gist/4543683 
 * Pure CSS Real Spinning Cuboctahedron http://dabblet.com/gist/4548435
 * Pure CSS Real Spinning Rhombic Dodecahedron http://dabblet.com/gist/4550540
 * Pure CSS Real Spinning Rhombicuboctahedron http://dabblet.com/gist/4552374
 * Pure CSS Real Spinning Square Antiprism http://dabblet.com/gist/4556863 
 Shades of green light to dark : 
#98fb98
#88e188
#79c879
#6aaf6a;

shades of blue
#0079c6
#006cb2
#00609e
#00548a
 */
body { overflow: hidden; }
.simpleShapes {
  position: relative;
  margin: 20% auto 1% auto;
  padding: 0;
  width: 16em; height: 16em;
  list-style: none;
  perspective: 100em;
  transform-style: preserve-3d;
  /*animation: rot 600s infinite linear;*/
  cursor: pointer;
}
@keyframes rot {
  from { transform: rotateY(0deg); }
  to { transform: rotateY(360deg); }
}

.side, .side a, .side img { display: block; width: 100%; height: 100%; }
.side {
  position: absolute;
  backface-visibility: hidden;
}

.side:nth-child(1) {
  width: 200px; 
  height: 142px; 
  overflow:hidden;
}
.side:nth-child(1):before{
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: blue;
    transform-origin: 0 100%;        
    transform: rotate(45deg);
}

.side:nth-child(2) {
  transform: translateY(100%);
  width: 200px; 
  height: 142px; 
  overflow:hidden;
}
.side:nth-child(2):before{
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: green;
    transform-origin: left top;       
    transform: rotate(-45deg);
}


</style>
