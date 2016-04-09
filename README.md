
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
	<meta name="generator" content="Software RVG HTML Editor (www.software-rvg.com)">
    <meta name="dcterms.created" content="ju., 21 ene. 2016 21:29:24 GMT">
    <meta name="description" content="Software RVG advanced designs_Magic_ball">
    <meta name="keywords" content="Software RVG,Advanced designs,magic ball">
    <title>SOFTWARE RVG Advanced Designs</title>
    
    <style type="text/css">    
    <!--
	body {
      color:#E91414;
      background-color:#111111;
      background-image:url('Background Image');
      background-repeat:no-repeat; width:1000px;
  margin-left:auto;
  margin-right:auto;
  font-family: "Arial", sans-serif;
  color:blue;
  text-align:center;
  font-size:30px;
}
    } .header {
  width:500px;
  margin-left:auto;
  margin-right:auto;
  font-family: "Arial", sans-serif;
  color:blue;
  text-align:center;
  font-size:30px;
}
.header h3 {
color:blue;
  opacity:0.9;
}
.header h2{color:#40FF00}
header h5 {color:#00FFFF}
.header small {
color:red;
  opacity:0.9;
  font-size:20px;
}
/* PEN STARTS */ 
.circle {
  width:40px;
  margin:0 auto;
  margin-top:200px;
   animation: rotateround 10s linear infinite;
     transition: transform 200ms linear;
    transform-style: preserve-3d;
}
$panels: 10;
$rows: 20;
$h: 0;
$hStep: 360/($panels*$rows);
@for $r from 0 to $rows {
  @for $i from 0 to $panels {
    $x: $r * 360deg / $rows;
    $y: $i * 180deg / $panels;
    
    $count: $r*$panels + $i;
    
    .face:nth-child(#{$count}) {
    width:40px;
    height:40px;
    border: 1px solid black;
    background:hsl($h, 50%, 70%);
    opacity:0.9;
    border-radius:50%;
    position: absolute;
    transform: rotateY($y) rotateX($x) translateZ(200px);  
    margin-top:0px;
    animation:big-#{$count} 30s linear infinite;
 
  }
    @keyframes big-#{$count} {
      0% {
        transform: rotateY($y + 0deg) rotateX($x + 0deg) translateZ(200px);
      }
      
      50% {
        transform: rotateY($y + 0deg) rotateX($x + 0deg) translateZ(200px);
      }
      
      100% {
        transform: rotateY($y + 0deg) rotateX($x + 0deg) translateZ(200px);
      }
      
    }
    
    $h: $h + $hStep;
    
  }
}
@keyframes rotateround {
  0% {
    transform: rotateX(0deg) rotateY(20deg);
  }
  100% {
    transform: rotateX(360deg) rotateY(380deg);
  }
  
}
<head><script src="//assets.codepen.io/assets/editor/live/console_runner-ac6f22d6f99e61f8e835261f461f1027.js"></script>
<meta charset="UTF-8"><meta name="robots" content="noindex"><link rel="canonical" href="http://codepen.io/samirc/pen/yePNvJ">
<link href="https://fonts.googleapis.com/css?family=Montserrat:700" rel="stylesheet" type="text/css">
<style class="cp-pen-styles">.header {
  width: 500px;
  margin-left: auto;
  margin-right: auto;
  font-family: 'Montserrat', sans-serif;
  color: blue;
  text-align: center;
  font-size: 30px;
}
			.header h3 {
			  opacity: 0.9;
}
.header small {
  opacity: 0.9;
  font-size: 20px;
}																														
.header h4 {color:#00FFFF;
  opacity: 0.9;
  font-size: 20px;
}																														
.container {
  width: 600px;
  padding: 30px;
  height: 430px;
  box-shadow: 0px 1px 2px 0px rgba(50, 50, 50, 0.5);
  margin-left: auto;
  margin-right: auto;
}
.footer {
  width: 900px;
  height: 100px;
  margin-top: 10px;
  margin-left: auto;
  margin-right: auto;
}
.footer > h4 {
  font-family: 'Montserrat', sans-serif;
  color: red;
  text-align: center;
  font-size: 20px;
  opacity: 0.9;
  margin-left: auto;
  margin-right: auto;
}
.img > a {
  margin-top: -20px;
}
.footer .img {
  width: 200px;
  margin-left: auto;
  margin-right: auto;
}
.img > a > img {
  width: 50px;
  display: inline;
}
.img > h4 {
  font-family: 'Montserrat', sans-serif;
  color: blue;
  text-align: center;
  font-size: 15px;
  opacity: 0.9;
  margin-left: auto;
  display: inline;
  margin-right: auto;
  margin-top: -10px;
}
/* PEN STARTS */
.circle {
  width: 40px;
  margin: 0 auto;
  margin-top: 200px;
  animation: rotateround 10s linear infinite;
  transition: transform 200ms linear;
  transform-style: preserve-3d;
}
.face:nth-child(0) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98c8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(0deg) translateZ(200px);
  margin-top: 0px;
  animation: big-0 30s linear infinite;
}
@keyframes big-0 {
  0% {
    transform: rotateY(0deg) rotateX(0deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(0deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(0deg) translateZ(200px);
  }
}
.face:nth-child(1) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98f8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(0deg) translateZ(200px);
  margin-top: 0px;
  animation: big-1 30s linear infinite;
}
@keyframes big-1 {
  0% {
    transform: rotateY(18deg) rotateX(0deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(0deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(0deg) translateZ(200px);
  }
}
.face:nth-child(2) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9918c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(0deg) translateZ(200px);
  margin-top: 0px;
  animation: big-2 30s linear infinite;
}
@keyframes big-2 {
  0% {
    transform: rotateY(36deg) rotateX(0deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(0deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(0deg) translateZ(200px);
  }
}
.face:nth-child(3) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9938c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(0deg) translateZ(200px);
  margin-top: 0px;
  animation: big-3 30s linear infinite;
}
@keyframes big-3 {
  0% {
    transform: rotateY(54deg) rotateX(0deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(0deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(0deg) translateZ(200px);
  }
}
.face:nth-child(4) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9958c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(0deg) translateZ(200px);
  margin-top: 0px;
  animation: big-4 30s linear infinite;
}
@keyframes big-4 {
  0% {
    transform: rotateY(72deg) rotateX(0deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(0deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(0deg) translateZ(200px);
  }
}
.face:nth-child(5) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9988c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(0deg) translateZ(200px);
  margin-top: 0px;
  animation: big-5 30s linear infinite;
}
@keyframes big-5 {
  0% {
    transform: rotateY(90deg) rotateX(0deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(0deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(0deg) translateZ(200px);
  }
}
.face:nth-child(6) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d99a8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(0deg) translateZ(200px);
  margin-top: 0px;
  animation: big-6 30s linear infinite;
}
@keyframes big-6 {
  0% {
    transform: rotateY(108deg) rotateX(0deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(0deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(0deg) translateZ(200px);
  }
}
.face:nth-child(7) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d99c8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(0deg) translateZ(200px);
  margin-top: 0px;
  animation: big-7 30s linear infinite;
}
@keyframes big-7 {
  0% {
    transform: rotateY(126deg) rotateX(0deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(0deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(0deg) translateZ(200px);
  }
}
.face:nth-child(8) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d99f8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(0deg) translateZ(200px);
  margin-top: 0px;
  animation: big-8 30s linear infinite;
}
@keyframes big-8 {
  0% {
    transform: rotateY(144deg) rotateX(0deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(0deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(0deg) translateZ(200px);
  }
}
.face:nth-child(9) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9a18c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(0deg) translateZ(200px);
  margin-top: 0px;
  animation: big-9 30s linear infinite;
}
@keyframes big-9 {
  0% {
    transform: rotateY(162deg) rotateX(0deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(0deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(0deg) translateZ(200px);
  }
}
.face:nth-child(10) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9a38c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(18deg) translateZ(200px);
  margin-top: 0px;
  animation: big-10 30s linear infinite;
}
@keyframes big-10 {
  0% {
    transform: rotateY(0deg) rotateX(18deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(18deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(18deg) translateZ(200px);
  }
}
.face:nth-child(11) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9a58c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(18deg) translateZ(200px);
  margin-top: 0px;
  animation: big-11 30s linear infinite;
}
@keyframes big-11 {
  0% {
    transform: rotateY(18deg) rotateX(18deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(18deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(18deg) translateZ(200px);
  }
}
.face:nth-child(12) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9a88c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(18deg) translateZ(200px);
  margin-top: 0px;
  animation: big-12 30s linear infinite;
}
@keyframes big-12 {
  0% {
    transform: rotateY(36deg) rotateX(18deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(18deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(18deg) translateZ(200px);
  }
}
.face:nth-child(13) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9aa8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(18deg) translateZ(200px);
  margin-top: 0px;
  animation: big-13 30s linear infinite;
}
@keyframes big-13 {
  0% {
    transform: rotateY(54deg) rotateX(18deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(18deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(18deg) translateZ(200px);
  }
}
.face:nth-child(14) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9ac8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(18deg) translateZ(200px);
  margin-top: 0px;
  animation: big-14 30s linear infinite;
}
@keyframes big-14 {
  0% {
    transform: rotateY(72deg) rotateX(18deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(18deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(18deg) translateZ(200px);
  }
}
.face:nth-child(15) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9af8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(18deg) translateZ(200px);
  margin-top: 0px;
  animation: big-15 30s linear infinite;
}
@keyframes big-15 {
  0% {
    transform: rotateY(90deg) rotateX(18deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(18deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(18deg) translateZ(200px);
  }
}
.face:nth-child(16) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9b18c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(18deg) translateZ(200px);
  margin-top: 0px;
  animation: big-16 30s linear infinite;
}
@keyframes big-16 {
  0% {
    transform: rotateY(108deg) rotateX(18deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(18deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(18deg) translateZ(200px);
  }
}
.face:nth-child(17) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9b38c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(18deg) translateZ(200px);
  margin-top: 0px;
  animation: big-17 30s linear infinite;
}
@keyframes big-17 {
  0% {
    transform: rotateY(126deg) rotateX(18deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(18deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(18deg) translateZ(200px);
  }
}
.face:nth-child(18) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9b68c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(18deg) translateZ(200px);
  margin-top: 0px;
  animation: big-18 30s linear infinite;
}
@keyframes big-18 {
  0% {
    transform: rotateY(144deg) rotateX(18deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(18deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(18deg) translateZ(200px);
  }
}
.face:nth-child(19) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9b88c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(18deg) translateZ(200px);
  margin-top: 0px;
  animation: big-19 30s linear infinite;
}
@keyframes big-19 {
  0% {
    transform: rotateY(162deg) rotateX(18deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(18deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(18deg) translateZ(200px);
  }
}
.face:nth-child(20) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9ba8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(36deg) translateZ(200px);
  margin-top: 0px;
  animation: big-20 30s linear infinite;
}
@keyframes big-20 {
  0% {
    transform: rotateY(0deg) rotateX(36deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(36deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(36deg) translateZ(200px);
  }
}
.face:nth-child(21) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9bc8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(36deg) translateZ(200px);
  margin-top: 0px;
  animation: big-21 30s linear infinite;
}
@keyframes big-21 {
  0% {
    transform: rotateY(18deg) rotateX(36deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(36deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(36deg) translateZ(200px);
  }
}
.face:nth-child(22) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9bf8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(36deg) translateZ(200px);
  margin-top: 0px;
  animation: big-22 30s linear infinite;
}
@keyframes big-22 {
  0% {
    transform: rotateY(36deg) rotateX(36deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(36deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(36deg) translateZ(200px);
  }
}
.face:nth-child(23) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9c18c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(36deg) translateZ(200px);
  margin-top: 0px;
  animation: big-23 30s linear infinite;
}
@keyframes big-23 {
  0% {
    transform: rotateY(54deg) rotateX(36deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(36deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(36deg) translateZ(200px);
  }
}
.face:nth-child(24) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9c38c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(36deg) translateZ(200px);
  margin-top: 0px;
  animation: big-24 30s linear infinite;
}
@keyframes big-24 {
  0% {
    transform: rotateY(72deg) rotateX(36deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(36deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(36deg) translateZ(200px);
  }
}
.face:nth-child(25) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9c68c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(36deg) translateZ(200px);
  margin-top: 0px;
  animation: big-25 30s linear infinite;
}
@keyframes big-25 {
  0% {
    transform: rotateY(90deg) rotateX(36deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(36deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(36deg) translateZ(200px);
  }
}
.face:nth-child(26) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9c88c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(36deg) translateZ(200px);
  margin-top: 0px;
  animation: big-26 30s linear infinite;
}
@keyframes big-26 {
  0% {
    transform: rotateY(108deg) rotateX(36deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(36deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(36deg) translateZ(200px);
  }
}
.face:nth-child(27) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9ca8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(36deg) translateZ(200px);
  margin-top: 0px;
  animation: big-27 30s linear infinite;
}
@keyframes big-27 {
  0% {
    transform: rotateY(126deg) rotateX(36deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(36deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(36deg) translateZ(200px);
  }
}
.face:nth-child(28) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9cd8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(36deg) translateZ(200px);
  margin-top: 0px;
  animation: big-28 30s linear infinite;
}
@keyframes big-28 {
  0% {
    transform: rotateY(144deg) rotateX(36deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(36deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(36deg) translateZ(200px);
  }
}
.face:nth-child(29) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9cf8c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(36deg) translateZ(200px);
  margin-top: 0px;
  animation: big-29 30s linear infinite;
}
@keyframes big-29 {
  0% {
    transform: rotateY(162deg) rotateX(36deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(36deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(36deg) translateZ(200px);
  }
}
.face:nth-child(30) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9d18c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(54deg) translateZ(200px);
  margin-top: 0px;
  animation: big-30 30s linear infinite;
}
@keyframes big-30 {
  0% {
    transform: rotateY(0deg) rotateX(54deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(54deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(54deg) translateZ(200px);
  }
}
.face:nth-child(31) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9d38c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(54deg) translateZ(200px);
  margin-top: 0px;
  animation: big-31 30s linear infinite;
}
@keyframes big-31 {
  0% {
    transform: rotateY(18deg) rotateX(54deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(54deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(54deg) translateZ(200px);
  }
}
.face:nth-child(32) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9d68c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(54deg) translateZ(200px);
  margin-top: 0px;
  animation: big-32 30s linear infinite;
}
@keyframes big-32 {
  0% {
    transform: rotateY(36deg) rotateX(54deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(54deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(54deg) translateZ(200px);
  }
}
.face:nth-child(33) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d9d88c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(54deg) translateZ(200px);
  margin-top: 0px;
  animation: big-33 30s linear infinite;
}
@keyframes big-33 {
  0% {
    transform: rotateY(54deg) rotateX(54deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(54deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(54deg) translateZ(200px);
  }
}
.face:nth-child(34) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d7d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(54deg) translateZ(200px);
  margin-top: 0px;
  animation: big-34 30s linear infinite;
}
@keyframes big-34 {
  0% {
    transform: rotateY(72deg) rotateX(54deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(54deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(54deg) translateZ(200px);
  }
}
.face:nth-child(35) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d5d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(54deg) translateZ(200px);
  margin-top: 0px;
  animation: big-35 30s linear infinite;
}
@keyframes big-35 {
  0% {
    transform: rotateY(90deg) rotateX(54deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(54deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(54deg) translateZ(200px);
  }
}
.face:nth-child(36) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d3d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(54deg) translateZ(200px);
  margin-top: 0px;
  animation: big-36 30s linear infinite;
}
@keyframes big-36 {
  0% {
    transform: rotateY(108deg) rotateX(54deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(54deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(54deg) translateZ(200px);
  }
}
.face:nth-child(37) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d0d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(54deg) translateZ(200px);
  margin-top: 0px;
  animation: big-37 30s linear infinite;
}
@keyframes big-37 {
  0% {
    transform: rotateY(126deg) rotateX(54deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(54deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(54deg) translateZ(200px);
  }
}
.face:nth-child(38) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #ced98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(54deg) translateZ(200px);
  margin-top: 0px;
  animation: big-38 30s linear infinite;
}
@keyframes big-38 {
  0% {
    transform: rotateY(144deg) rotateX(54deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(54deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(54deg) translateZ(200px);
  }
}
.face:nth-child(39) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #ccd98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(54deg) translateZ(200px);
  margin-top: 0px;
  animation: big-39 30s linear infinite;
}
@keyframes big-39 {
  0% {
    transform: rotateY(162deg) rotateX(54deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(54deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(54deg) translateZ(200px);
  }
}
.face:nth-child(40) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #c9d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(72deg) translateZ(200px);
  margin-top: 0px;
  animation: big-40 30s linear infinite;
}
@keyframes big-40 {
  0% {
    transform: rotateY(0deg) rotateX(72deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(72deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(72deg) translateZ(200px);
  }
}
.face:nth-child(41) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #c7d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(72deg) translateZ(200px);
  margin-top: 0px;
  animation: big-41 30s linear infinite;
}
@keyframes big-41 {
  0% {
    transform: rotateY(18deg) rotateX(72deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(72deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(72deg) translateZ(200px);
  }
}
.face:nth-child(42) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #c5d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(72deg) translateZ(200px);
  margin-top: 0px;
  animation: big-42 30s linear infinite;
}
@keyframes big-42 {
  0% {
    transform: rotateY(36deg) rotateX(72deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(72deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(72deg) translateZ(200px);
  }
}
.face:nth-child(43) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #c3d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(72deg) translateZ(200px);
  margin-top: 0px;
  animation: big-43 30s linear infinite;
}
@keyframes big-43 {
  0% {
    transform: rotateY(54deg) rotateX(72deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(72deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(72deg) translateZ(200px);
  }
}
.face:nth-child(44) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #c0d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(72deg) translateZ(200px);
  margin-top: 0px;
  animation: big-44 30s linear infinite;
}
@keyframes big-44 {
  0% {
    transform: rotateY(72deg) rotateX(72deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(72deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(72deg) translateZ(200px);
  }
}
.face:nth-child(45) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #bed98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(72deg) translateZ(200px);
  margin-top: 0px;
  animation: big-45 30s linear infinite;
}
@keyframes big-45 {
  0% {
    transform: rotateY(90deg) rotateX(72deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(72deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(72deg) translateZ(200px);
  }
}
.face:nth-child(46) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #bcd98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(72deg) translateZ(200px);
  margin-top: 0px;
  animation: big-46 30s linear infinite;
}
@keyframes big-46 {
  0% {
    transform: rotateY(108deg) rotateX(72deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(72deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(72deg) translateZ(200px);
  }
}
.face:nth-child(47) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #b9d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(72deg) translateZ(200px);
  margin-top: 0px;
  animation: big-47 30s linear infinite;
}
@keyframes big-47 {
  0% {
    transform: rotateY(126deg) rotateX(72deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(72deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(72deg) translateZ(200px);
  }
}
.face:nth-child(48) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #b7d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(72deg) translateZ(200px);
  margin-top: 0px;
  animation: big-48 30s linear infinite;
}
@keyframes big-48 {
  0% {
    transform: rotateY(144deg) rotateX(72deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(72deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(72deg) translateZ(200px);
  }
}
.face:nth-child(49) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #b5d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(72deg) translateZ(200px);
  margin-top: 0px;
  animation: big-49 30s linear infinite;
}
@keyframes big-49 {
  0% {
    transform: rotateY(162deg) rotateX(72deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(72deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(72deg) translateZ(200px);
  }
}
.face:nth-child(50) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #b3d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(90deg) translateZ(200px);
  margin-top: 0px;
  animation: big-50 30s linear infinite;
}
@keyframes big-50 {
  0% {
    transform: rotateY(0deg) rotateX(90deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(90deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(90deg) translateZ(200px);
  }
}
.face:nth-child(51) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #b0d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(90deg) translateZ(200px);
  margin-top: 0px;
  animation: big-51 30s linear infinite;
}
@keyframes big-51 {
  0% {
    transform: rotateY(18deg) rotateX(90deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(90deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(90deg) translateZ(200px);
  }
}
.face:nth-child(52) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #aed98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(90deg) translateZ(200px);
  margin-top: 0px;
  animation: big-52 30s linear infinite;
}
@keyframes big-52 {
  0% {
    transform: rotateY(36deg) rotateX(90deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(90deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(90deg) translateZ(200px);
  }
}
.face:nth-child(53) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #acd98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(90deg) translateZ(200px);
  margin-top: 0px;
  animation: big-53 30s linear infinite;
}
@keyframes big-53 {
  0% {
    transform: rotateY(54deg) rotateX(90deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(90deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(90deg) translateZ(200px);
  }
}
.face:nth-child(54) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #a9d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(90deg) translateZ(200px);
  margin-top: 0px;
  animation: big-54 30s linear infinite;
}
@keyframes big-54 {
  0% {
    transform: rotateY(72deg) rotateX(90deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(90deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(90deg) translateZ(200px);
  }
}
.face:nth-child(55) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #a7d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(90deg) translateZ(200px);
  margin-top: 0px;
  animation: big-55 30s linear infinite;
}
@keyframes big-55 {
  0% {
    transform: rotateY(90deg) rotateX(90deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(90deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(90deg) translateZ(200px);
  }
}
.face:nth-child(56) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #a5d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(90deg) translateZ(200px);
  margin-top: 0px;
  animation: big-56 30s linear infinite;
}
@keyframes big-56 {
  0% {
    transform: rotateY(108deg) rotateX(90deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(90deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(90deg) translateZ(200px);
  }
}
.face:nth-child(57) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #a2d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(90deg) translateZ(200px);
  margin-top: 0px;
  animation: big-57 30s linear infinite;
}
@keyframes big-57 {
  0% {
    transform: rotateY(126deg) rotateX(90deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(90deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(90deg) translateZ(200px);
  }
}
.face:nth-child(58) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #a0d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(90deg) translateZ(200px);
  margin-top: 0px;
  animation: big-58 30s linear infinite;
}
@keyframes big-58 {
  0% {
    transform: rotateY(144deg) rotateX(90deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(90deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(90deg) translateZ(200px);
  }
}
.face:nth-child(59) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #9ed98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(90deg) translateZ(200px);
  margin-top: 0px;
  animation: big-59 30s linear infinite;
}
@keyframes big-59 {
  0% {
    transform: rotateY(162deg) rotateX(90deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(90deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(90deg) translateZ(200px);
  }
}
.face:nth-child(60) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #9cd98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(108deg) translateZ(200px);
  margin-top: 0px;
  animation: big-60 30s linear infinite;
}
@keyframes big-60 {
  0% {
    transform: rotateY(0deg) rotateX(108deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(108deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(108deg) translateZ(200px);
  }
}
.face:nth-child(61) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #99d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(108deg) translateZ(200px);
  margin-top: 0px;
  animation: big-61 30s linear infinite;
}
@keyframes big-61 {
  0% {
    transform: rotateY(18deg) rotateX(108deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(108deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(108deg) translateZ(200px);
  }
}
.face:nth-child(62) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #97d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(108deg) translateZ(200px);
  margin-top: 0px;
  animation: big-62 30s linear infinite;
}
@keyframes big-62 {
  0% {
    transform: rotateY(36deg) rotateX(108deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(108deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(108deg) translateZ(200px);
  }
}
.face:nth-child(63) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #95d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(108deg) translateZ(200px);
  margin-top: 0px;
  animation: big-63 30s linear infinite;
}
@keyframes big-63 {
  0% {
    transform: rotateY(54deg) rotateX(108deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(108deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(108deg) translateZ(200px);
  }
}
.face:nth-child(64) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #92d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(108deg) translateZ(200px);
  margin-top: 0px;
  animation: big-64 30s linear infinite;
}
@keyframes big-64 {
  0% {
    transform: rotateY(72deg) rotateX(108deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(108deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(108deg) translateZ(200px);
  }
}
.face:nth-child(65) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #90d98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(108deg) translateZ(200px);
  margin-top: 0px;
  animation: big-65 30s linear infinite;
}
@keyframes big-65 {
  0% {
    transform: rotateY(90deg) rotateX(108deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(108deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(108deg) translateZ(200px);
  }
}
.face:nth-child(66) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8ed98c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(108deg) translateZ(200px);
  margin-top: 0px;
  animation: big-66 30s linear infinite;
}
@keyframes big-66 {
  0% {
    transform: rotateY(108deg) rotateX(108deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(108deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(108deg) translateZ(200px);
  }
}
.face:nth-child(67) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd98d;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(108deg) translateZ(200px);
  margin-top: 0px;
  animation: big-67 30s linear infinite;
}
@keyframes big-67 {
  0% {
    transform: rotateY(126deg) rotateX(108deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(108deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(108deg) translateZ(200px);
  }
}
.face:nth-child(68) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd98f;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(108deg) translateZ(200px);
  margin-top: 0px;
  animation: big-68 30s linear infinite;
}
@keyframes big-68 {
  0% {
    transform: rotateY(144deg) rotateX(108deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(108deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(108deg) translateZ(200px);
  }
}
.face:nth-child(69) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd992;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(108deg) translateZ(200px);
  margin-top: 0px;
  animation: big-69 30s linear infinite;
}
@keyframes big-69 {
  0% {
    transform: rotateY(162deg) rotateX(108deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(108deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(108deg) translateZ(200px);
  }
}
.face:nth-child(70) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd994;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(126deg) translateZ(200px);
  margin-top: 0px;
  animation: big-70 30s linear infinite;
}
@keyframes big-70 {
  0% {
    transform: rotateY(0deg) rotateX(126deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(126deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(126deg) translateZ(200px);
  }
}
.face:nth-child(71) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd996;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(126deg) translateZ(200px);
  margin-top: 0px;
  animation: big-71 30s linear infinite;
}
@keyframes big-71 {
  0% {
    transform: rotateY(18deg) rotateX(126deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(126deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(126deg) translateZ(200px);
  }
}
.face:nth-child(72) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd998;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(126deg) translateZ(200px);
  margin-top: 0px;
  animation: big-72 30s linear infinite;
}
@keyframes big-72 {
  0% {
    transform: rotateY(36deg) rotateX(126deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(126deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(126deg) translateZ(200px);
  }
}
.face:nth-child(73) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd99b;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(126deg) translateZ(200px);
  margin-top: 0px;
  animation: big-73 30s linear infinite;
}
@keyframes big-73 {
  0% {
    transform: rotateY(54deg) rotateX(126deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(126deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(126deg) translateZ(200px);
  }
}
.face:nth-child(74) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd99d;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(126deg) translateZ(200px);
  margin-top: 0px;
  animation: big-74 30s linear infinite;
}
@keyframes big-74 {
  0% {
    transform: rotateY(72deg) rotateX(126deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(126deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(126deg) translateZ(200px);
  }
}
.face:nth-child(75) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd99f;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(126deg) translateZ(200px);
  margin-top: 0px;
  animation: big-75 30s linear infinite;
}
@keyframes big-75 {
  0% {
    transform: rotateY(90deg) rotateX(126deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(126deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(126deg) translateZ(200px);
  }
}
.face:nth-child(76) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9a2;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(126deg) translateZ(200px);
  margin-top: 0px;
  animation: big-76 30s linear infinite;
}
@keyframes big-76 {
  0% {
    transform: rotateY(108deg) rotateX(126deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(126deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(126deg) translateZ(200px);
  }
}
.face:nth-child(77) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9a4;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(126deg) translateZ(200px);
  margin-top: 0px;
  animation: big-77 30s linear infinite;
}
@keyframes big-77 {
  0% {
    transform: rotateY(126deg) rotateX(126deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(126deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(126deg) translateZ(200px);
  }
}
.face:nth-child(78) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9a6;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(126deg) translateZ(200px);
  margin-top: 0px;
  animation: big-78 30s linear infinite;
}
@keyframes big-78 {
  0% {
    transform: rotateY(144deg) rotateX(126deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(126deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(126deg) translateZ(200px);
  }
}
.face:nth-child(79) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9a9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(126deg) translateZ(200px);
  margin-top: 0px;
  animation: big-79 30s linear infinite;
}
@keyframes big-79 {
  0% {
    transform: rotateY(162deg) rotateX(126deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(126deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(126deg) translateZ(200px);
  }
}
.face:nth-child(80) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9ab;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(144deg) translateZ(200px);
  margin-top: 0px;
  animation: big-80 30s linear infinite;
}
@keyframes big-80 {
  0% {
    transform: rotateY(0deg) rotateX(144deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(144deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(144deg) translateZ(200px);
  }
}
.face:nth-child(81) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9ad;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(144deg) translateZ(200px);
  margin-top: 0px;
  animation: big-81 30s linear infinite;
}
@keyframes big-81 {
  0% {
    transform: rotateY(18deg) rotateX(144deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(144deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(144deg) translateZ(200px);
  }
}
.face:nth-child(82) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9af;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(144deg) translateZ(200px);
  margin-top: 0px;
  animation: big-82 30s linear infinite;
}
@keyframes big-82 {
  0% {
    transform: rotateY(36deg) rotateX(144deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(144deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(144deg) translateZ(200px);
  }
}
.face:nth-child(83) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9b2;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(144deg) translateZ(200px);
  margin-top: 0px;
  animation: big-83 30s linear infinite;
}
@keyframes big-83 {
  0% {
    transform: rotateY(54deg) rotateX(144deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(144deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(144deg) translateZ(200px);
  }
}
.face:nth-child(84) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9b4;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(144deg) translateZ(200px);
  margin-top: 0px;
  animation: big-84 30s linear infinite;
}
@keyframes big-84 {
  0% {
    transform: rotateY(72deg) rotateX(144deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(144deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(144deg) translateZ(200px);
  }
}
.face:nth-child(85) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9b6;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(144deg) translateZ(200px);
  margin-top: 0px;
  animation: big-85 30s linear infinite;
}
@keyframes big-85 {
  0% {
    transform: rotateY(90deg) rotateX(144deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(144deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(144deg) translateZ(200px);
  }
}
.face:nth-child(86) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9b9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(144deg) translateZ(200px);
  margin-top: 0px;
  animation: big-86 30s linear infinite;
}
@keyframes big-86 {
  0% {
    transform: rotateY(108deg) rotateX(144deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(144deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(144deg) translateZ(200px);
  }
}
.face:nth-child(87) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9bb;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(144deg) translateZ(200px);
  margin-top: 0px;
  animation: big-87 30s linear infinite;
}
@keyframes big-87 {
  0% {
    transform: rotateY(126deg) rotateX(144deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(144deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(144deg) translateZ(200px);
  }
}
.face:nth-child(88) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9bd;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(144deg) translateZ(200px);
  margin-top: 0px;
  animation: big-88 30s linear infinite;
}
@keyframes big-88 {
  0% {
    transform: rotateY(144deg) rotateX(144deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(144deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(144deg) translateZ(200px);
  }
}
.face:nth-child(89) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9c0;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(144deg) translateZ(200px);
  margin-top: 0px;
  animation: big-89 30s linear infinite;
}
@keyframes big-89 {
  0% {
    transform: rotateY(162deg) rotateX(144deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(144deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(144deg) translateZ(200px);
  }
}
.face:nth-child(90) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9c2;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(162deg) translateZ(200px);
  margin-top: 0px;
  animation: big-90 30s linear infinite;
}
@keyframes big-90 {
  0% {
    transform: rotateY(0deg) rotateX(162deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(162deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(162deg) translateZ(200px);
  }
}
.face:nth-child(91) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9c4;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(162deg) translateZ(200px);
  margin-top: 0px;
  animation: big-91 30s linear infinite;
}
@keyframes big-91 {
  0% {
    transform: rotateY(18deg) rotateX(162deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(162deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(162deg) translateZ(200px);
  }
}
.face:nth-child(92) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9c6;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(162deg) translateZ(200px);
  margin-top: 0px;
  animation: big-92 30s linear infinite;
}
@keyframes big-92 {
  0% {
    transform: rotateY(36deg) rotateX(162deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(162deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(162deg) translateZ(200px);
  }
}
.face:nth-child(93) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9c9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(162deg) translateZ(200px);
  margin-top: 0px;
  animation: big-93 30s linear infinite;
}
@keyframes big-93 {
  0% {
    transform: rotateY(54deg) rotateX(162deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(162deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(162deg) translateZ(200px);
  }
}
.face:nth-child(94) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9cb;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(162deg) translateZ(200px);
  margin-top: 0px;
  animation: big-94 30s linear infinite;
}
@keyframes big-94 {
  0% {
    transform: rotateY(72deg) rotateX(162deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(162deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(162deg) translateZ(200px);
  }
}
.face:nth-child(95) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9cd;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(162deg) translateZ(200px);
  margin-top: 0px;
  animation: big-95 30s linear infinite;
}
@keyframes big-95 {
  0% {
    transform: rotateY(90deg) rotateX(162deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(162deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(162deg) translateZ(200px);
  }
}
.face:nth-child(96) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9d0;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(162deg) translateZ(200px);
  margin-top: 0px;
  animation: big-96 30s linear infinite;
}
@keyframes big-96 {
  0% {
    transform: rotateY(108deg) rotateX(162deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(162deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(162deg) translateZ(200px);
  }
}
.face:nth-child(97) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9d2;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(162deg) translateZ(200px);
  margin-top: 0px;
  animation: big-97 30s linear infinite;
}
@keyframes big-97 {
  0% {
    transform: rotateY(126deg) rotateX(162deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(162deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(162deg) translateZ(200px);
  }
}
.face:nth-child(98) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9d4;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(162deg) translateZ(200px);
  margin-top: 0px;
  animation: big-98 30s linear infinite;
}
@keyframes big-98 {
  0% {
    transform: rotateY(144deg) rotateX(162deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(162deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(162deg) translateZ(200px);
  }
}
.face:nth-child(99) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9d6;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(162deg) translateZ(200px);
  margin-top: 0px;
  animation: big-99 30s linear infinite;
}
@keyframes big-99 {
  0% {
    transform: rotateY(162deg) rotateX(162deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(162deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(162deg) translateZ(200px);
  }
}
.face:nth-child(100) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd9d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(180deg) translateZ(200px);
  margin-top: 0px;
  animation: big-100 30s linear infinite;
}
@keyframes big-100 {
  0% {
    transform: rotateY(0deg) rotateX(180deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(180deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(180deg) translateZ(200px);
  }
}
.face:nth-child(101) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd6d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(180deg) translateZ(200px);
  margin-top: 0px;
  animation: big-101 30s linear infinite;
}
@keyframes big-101 {
  0% {
    transform: rotateY(18deg) rotateX(180deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(180deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(180deg) translateZ(200px);
  }
}
.face:nth-child(102) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd4d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(180deg) translateZ(200px);
  margin-top: 0px;
  animation: big-102 30s linear infinite;
}
@keyframes big-102 {
  0% {
    transform: rotateY(36deg) rotateX(180deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(180deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(180deg) translateZ(200px);
  }
}
.face:nth-child(103) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd2d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(180deg) translateZ(200px);
  margin-top: 0px;
  animation: big-103 30s linear infinite;
}
@keyframes big-103 {
  0% {
    transform: rotateY(54deg) rotateX(180deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(180deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(180deg) translateZ(200px);
  }
}
.face:nth-child(104) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cd0d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(180deg) translateZ(200px);
  margin-top: 0px;
  animation: big-104 30s linear infinite;
}
@keyframes big-104 {
  0% {
    transform: rotateY(72deg) rotateX(180deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(180deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(180deg) translateZ(200px);
  }
}
.face:nth-child(105) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8ccdd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(180deg) translateZ(200px);
  margin-top: 0px;
  animation: big-105 30s linear infinite;
}
@keyframes big-105 {
  0% {
    transform: rotateY(90deg) rotateX(180deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(180deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(180deg) translateZ(200px);
  }
}
.face:nth-child(106) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8ccbd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(180deg) translateZ(200px);
  margin-top: 0px;
  animation: big-106 30s linear infinite;
}
@keyframes big-106 {
  0% {
    transform: rotateY(108deg) rotateX(180deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(180deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(180deg) translateZ(200px);
  }
}
.face:nth-child(107) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cc9d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(180deg) translateZ(200px);
  margin-top: 0px;
  animation: big-107 30s linear infinite;
}
@keyframes big-107 {
  0% {
    transform: rotateY(126deg) rotateX(180deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(180deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(180deg) translateZ(200px);
  }
}
.face:nth-child(108) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cc6d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(180deg) translateZ(200px);
  margin-top: 0px;
  animation: big-108 30s linear infinite;
}
@keyframes big-108 {
  0% {
    transform: rotateY(144deg) rotateX(180deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(180deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(180deg) translateZ(200px);
  }
}
.face:nth-child(109) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cc4d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(180deg) translateZ(200px);
  margin-top: 0px;
  animation: big-109 30s linear infinite;
}
@keyframes big-109 {
  0% {
    transform: rotateY(162deg) rotateX(180deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(180deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(180deg) translateZ(200px);
  }
}
.face:nth-child(110) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cc2d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(198deg) translateZ(200px);
  margin-top: 0px;
  animation: big-110 30s linear infinite;
}
@keyframes big-110 {
  0% {
    transform: rotateY(0deg) rotateX(198deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(198deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(198deg) translateZ(200px);
  }
}
.face:nth-child(111) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cc0d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(198deg) translateZ(200px);
  margin-top: 0px;
  animation: big-111 30s linear infinite;
}
@keyframes big-111 {
  0% {
    transform: rotateY(18deg) rotateX(198deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(198deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(198deg) translateZ(200px);
  }
}
.face:nth-child(112) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cbdd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(198deg) translateZ(200px);
  margin-top: 0px;
  animation: big-112 30s linear infinite;
}
@keyframes big-112 {
  0% {
    transform: rotateY(36deg) rotateX(198deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(198deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(198deg) translateZ(200px);
  }
}
.face:nth-child(113) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cbbd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(198deg) translateZ(200px);
  margin-top: 0px;
  animation: big-113 30s linear infinite;
}
@keyframes big-113 {
  0% {
    transform: rotateY(54deg) rotateX(198deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(198deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(198deg) translateZ(200px);
  }
}
.face:nth-child(114) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cb9d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(198deg) translateZ(200px);
  margin-top: 0px;
  animation: big-114 30s linear infinite;
}
@keyframes big-114 {
  0% {
    transform: rotateY(72deg) rotateX(198deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(198deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(198deg) translateZ(200px);
  }
}
.face:nth-child(115) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cb6d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(198deg) translateZ(200px);
  margin-top: 0px;
  animation: big-115 30s linear infinite;
}
@keyframes big-115 {
  0% {
    transform: rotateY(90deg) rotateX(198deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(198deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(198deg) translateZ(200px);
  }
}
.face:nth-child(116) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cb4d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(198deg) translateZ(200px);
  margin-top: 0px;
  animation: big-116 30s linear infinite;
}
@keyframes big-116 {
  0% {
    transform: rotateY(108deg) rotateX(198deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(198deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(198deg) translateZ(200px);
  }
}
.face:nth-child(117) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cb2d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(198deg) translateZ(200px);
  margin-top: 0px;
  animation: big-117 30s linear infinite;
}
@keyframes big-117 {
  0% {
    transform: rotateY(126deg) rotateX(198deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(198deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(198deg) translateZ(200px);
  }
}
.face:nth-child(118) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cafd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(198deg) translateZ(200px);
  margin-top: 0px;
  animation: big-118 30s linear infinite;
}
@keyframes big-118 {
  0% {
    transform: rotateY(144deg) rotateX(198deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(198deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(198deg) translateZ(200px);
  }
}
.face:nth-child(119) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cadd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(198deg) translateZ(200px);
  margin-top: 0px;
  animation: big-119 30s linear infinite;
}
@keyframes big-119 {
  0% {
    transform: rotateY(162deg) rotateX(198deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(198deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(198deg) translateZ(200px);
  }
}
.face:nth-child(120) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8cabd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(216deg) translateZ(200px);
  margin-top: 0px;
  animation: big-120 30s linear infinite;
}
@keyframes big-120 {
  0% {
    transform: rotateY(0deg) rotateX(216deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(216deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(216deg) translateZ(200px);
  }
}
.face:nth-child(121) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8ca9d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(216deg) translateZ(200px);
  margin-top: 0px;
  animation: big-121 30s linear infinite;
}
@keyframes big-121 {
  0% {
    transform: rotateY(18deg) rotateX(216deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(216deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(216deg) translateZ(200px);
  }
}
.face:nth-child(122) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8ca6d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(216deg) translateZ(200px);
  margin-top: 0px;
  animation: big-122 30s linear infinite;
}
@keyframes big-122 {
  0% {
    transform: rotateY(36deg) rotateX(216deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(216deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(216deg) translateZ(200px);
  }
}
.face:nth-child(123) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8ca4d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(216deg) translateZ(200px);
  margin-top: 0px;
  animation: big-123 30s linear infinite;
}
@keyframes big-123 {
  0% {
    transform: rotateY(54deg) rotateX(216deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(216deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(216deg) translateZ(200px);
  }
}
.face:nth-child(124) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8ca2d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(216deg) translateZ(200px);
  margin-top: 0px;
  animation: big-124 30s linear infinite;
}
@keyframes big-124 {
  0% {
    transform: rotateY(72deg) rotateX(216deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(216deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(216deg) translateZ(200px);
  }
}
.face:nth-child(125) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8c9fd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(216deg) translateZ(200px);
  margin-top: 0px;
  animation: big-125 30s linear infinite;
}
@keyframes big-125 {
  0% {
    transform: rotateY(90deg) rotateX(216deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(216deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(216deg) translateZ(200px);
  }
}
.face:nth-child(126) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8c9dd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(216deg) translateZ(200px);
  margin-top: 0px;
  animation: big-126 30s linear infinite;
}
@keyframes big-126 {
  0% {
    transform: rotateY(108deg) rotateX(216deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(216deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(216deg) translateZ(200px);
  }
}
.face:nth-child(127) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8c9bd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(216deg) translateZ(200px);
  margin-top: 0px;
  animation: big-127 30s linear infinite;
}
@keyframes big-127 {
  0% {
    transform: rotateY(126deg) rotateX(216deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(216deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(216deg) translateZ(200px);
  }
}
.face:nth-child(128) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8c98d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(216deg) translateZ(200px);
  margin-top: 0px;
  animation: big-128 30s linear infinite;
}
@keyframes big-128 {
  0% {
    transform: rotateY(144deg) rotateX(216deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(216deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(216deg) translateZ(200px);
  }
}
.face:nth-child(129) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8c96d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(216deg) translateZ(200px);
  margin-top: 0px;
  animation: big-129 30s linear infinite;
}
@keyframes big-129 {
  0% {
    transform: rotateY(162deg) rotateX(216deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(216deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(216deg) translateZ(200px);
  }
}
.face:nth-child(130) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8c94d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(234deg) translateZ(200px);
  margin-top: 0px;
  animation: big-130 30s linear infinite;
}
@keyframes big-130 {
  0% {
    transform: rotateY(0deg) rotateX(234deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(234deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(234deg) translateZ(200px);
  }
}
.face:nth-child(131) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8c92d9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(234deg) translateZ(200px);
  margin-top: 0px;
  animation: big-131 30s linear infinite;
}
@keyframes big-131 {
  0% {
    transform: rotateY(18deg) rotateX(234deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(234deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(234deg) translateZ(200px);
  }
}
.face:nth-child(132) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8c8fd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(234deg) translateZ(200px);
  margin-top: 0px;
  animation: big-132 30s linear infinite;
}
@keyframes big-132 {
  0% {
    transform: rotateY(36deg) rotateX(234deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(234deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(234deg) translateZ(200px);
  }
}
.face:nth-child(133) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8c8dd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(234deg) translateZ(200px);
  margin-top: 0px;
  animation: big-133 30s linear infinite;
}
@keyframes big-133 {
  0% {
    transform: rotateY(54deg) rotateX(234deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(234deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(234deg) translateZ(200px);
  }
}
.face:nth-child(134) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #8e8cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(234deg) translateZ(200px);
  margin-top: 0px;
  animation: big-134 30s linear infinite;
}
@keyframes big-134 {
  0% {
    transform: rotateY(72deg) rotateX(234deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(234deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(234deg) translateZ(200px);
  }
}
.face:nth-child(135) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #908cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(234deg) translateZ(200px);
  margin-top: 0px;
  animation: big-135 30s linear infinite;
}
@keyframes big-135 {
  0% {
    transform: rotateY(90deg) rotateX(234deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(234deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(234deg) translateZ(200px);
  }
}
.face:nth-child(136) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #928cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(234deg) translateZ(200px);
  margin-top: 0px;
  animation: big-136 30s linear infinite;
}
@keyframes big-136 {
  0% {
    transform: rotateY(108deg) rotateX(234deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(234deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(234deg) translateZ(200px);
  }
}
.face:nth-child(137) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #958cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(234deg) translateZ(200px);
  margin-top: 0px;
  animation: big-137 30s linear infinite;
}
@keyframes big-137 {
  0% {
    transform: rotateY(126deg) rotateX(234deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(234deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(234deg) translateZ(200px);
  }
}
.face:nth-child(138) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #978cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(234deg) translateZ(200px);
  margin-top: 0px;
  animation: big-138 30s linear infinite;
}
@keyframes big-138 {
  0% {
    transform: rotateY(144deg) rotateX(234deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(234deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(234deg) translateZ(200px);
  }
}
.face:nth-child(139) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #998cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(234deg) translateZ(200px);
  margin-top: 0px;
  animation: big-139 30s linear infinite;
}
@keyframes big-139 {
  0% {
    transform: rotateY(162deg) rotateX(234deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(234deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(234deg) translateZ(200px);
  }
}
.face:nth-child(140) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #9c8cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(252deg) translateZ(200px);
  margin-top: 0px;
  animation: big-140 30s linear infinite;
}
@keyframes big-140 {
  0% {
    transform: rotateY(0deg) rotateX(252deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(252deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(252deg) translateZ(200px);
  }
}
.face:nth-child(141) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #9e8cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(252deg) translateZ(200px);
  margin-top: 0px;
  animation: big-141 30s linear infinite;
}
@keyframes big-141 {
  0% {
    transform: rotateY(18deg) rotateX(252deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(252deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(252deg) translateZ(200px);
  }
}
.face:nth-child(142) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #a08cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(252deg) translateZ(200px);
  margin-top: 0px;
  animation: big-142 30s linear infinite;
}
@keyframes big-142 {
  0% {
    transform: rotateY(36deg) rotateX(252deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(252deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(252deg) translateZ(200px);
  }
}
.face:nth-child(143) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #a28cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(252deg) translateZ(200px);
  margin-top: 0px;
  animation: big-143 30s linear infinite;
}
@keyframes big-143 {
  0% {
    transform: rotateY(54deg) rotateX(252deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(252deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(252deg) translateZ(200px);
  }
}
.face:nth-child(144) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #a58cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(252deg) translateZ(200px);
  margin-top: 0px;
  animation: big-144 30s linear infinite;
}
@keyframes big-144 {
  0% {
    transform: rotateY(72deg) rotateX(252deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(252deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(252deg) translateZ(200px);
  }
}
.face:nth-child(145) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #a78cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(252deg) translateZ(200px);
  margin-top: 0px;
  animation: big-145 30s linear infinite;
}
@keyframes big-145 {
  0% {
    transform: rotateY(90deg) rotateX(252deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(252deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(252deg) translateZ(200px);
  }
}
.face:nth-child(146) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #a98cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(252deg) translateZ(200px);
  margin-top: 0px;
  animation: big-146 30s linear infinite;
}
@keyframes big-146 {
  0% {
    transform: rotateY(108deg) rotateX(252deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(252deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(252deg) translateZ(200px);
  }
}
.face:nth-child(147) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #ac8cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(252deg) translateZ(200px);
  margin-top: 0px;
  animation: big-147 30s linear infinite;
}
@keyframes big-147 {
  0% {
    transform: rotateY(126deg) rotateX(252deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(252deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(252deg) translateZ(200px);
  }
}
.face:nth-child(148) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #ae8cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(252deg) translateZ(200px);
  margin-top: 0px;
  animation: big-148 30s linear infinite;
}
@keyframes big-148 {
  0% {
    transform: rotateY(144deg) rotateX(252deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(252deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(252deg) translateZ(200px);
  }
}
.face:nth-child(149) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #b08cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(252deg) translateZ(200px);
  margin-top: 0px;
  animation: big-149 30s linear infinite;
}
@keyframes big-149 {
  0% {
    transform: rotateY(162deg) rotateX(252deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(252deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(252deg) translateZ(200px);
  }
}
.face:nth-child(150) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #b38cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(270deg) translateZ(200px);
  margin-top: 0px;
  animation: big-150 30s linear infinite;
}
@keyframes big-150 {
  0% {
    transform: rotateY(0deg) rotateX(270deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(270deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(270deg) translateZ(200px);
  }
}
.face:nth-child(151) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #b58cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(270deg) translateZ(200px);
  margin-top: 0px;
  animation: big-151 30s linear infinite;
}
@keyframes big-151 {
  0% {
    transform: rotateY(18deg) rotateX(270deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(270deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(270deg) translateZ(200px);
  }
}
.face:nth-child(152) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #b78cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(270deg) translateZ(200px);
  margin-top: 0px;
  animation: big-152 30s linear infinite;
}
@keyframes big-152 {
  0% {
    transform: rotateY(36deg) rotateX(270deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(270deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(270deg) translateZ(200px);
  }
}
.face:nth-child(153) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #b98cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(270deg) translateZ(200px);
  margin-top: 0px;
  animation: big-153 30s linear infinite;
}
@keyframes big-153 {
  0% {
    transform: rotateY(54deg) rotateX(270deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(270deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(270deg) translateZ(200px);
  }
}
.face:nth-child(154) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #bc8cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(270deg) translateZ(200px);
  margin-top: 0px;
  animation: big-154 30s linear infinite;
}
@keyframes big-154 {
  0% {
    transform: rotateY(72deg) rotateX(270deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(270deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(270deg) translateZ(200px);
  }
}
.face:nth-child(155) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #be8cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(270deg) translateZ(200px);
  margin-top: 0px;
  animation: big-155 30s linear infinite;
}
@keyframes big-155 {
  0% {
    transform: rotateY(90deg) rotateX(270deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(270deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(270deg) translateZ(200px);
  }
}
.face:nth-child(156) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #c08cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(270deg) translateZ(200px);
  margin-top: 0px;
  animation: big-156 30s linear infinite;
}
@keyframes big-156 {
  0% {
    transform: rotateY(108deg) rotateX(270deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(270deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(270deg) translateZ(200px);
  }
}
.face:nth-child(157) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #c38cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(270deg) translateZ(200px);
  margin-top: 0px;
  animation: big-157 30s linear infinite;
}
@keyframes big-157 {
  0% {
    transform: rotateY(126deg) rotateX(270deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(270deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(270deg) translateZ(200px);
  }
}
.face:nth-child(158) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #c58cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(270deg) translateZ(200px);
  margin-top: 0px;
  animation: big-158 30s linear infinite;
}
@keyframes big-158 {
  0% {
    transform: rotateY(144deg) rotateX(270deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(270deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(270deg) translateZ(200px);
  }
}
.face:nth-child(159) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #c78cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(270deg) translateZ(200px);
  margin-top: 0px;
  animation: big-159 30s linear infinite;
}
@keyframes big-159 {
  0% {
    transform: rotateY(162deg) rotateX(270deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(270deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(270deg) translateZ(200px);
  }
}
.face:nth-child(160) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #c98cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(288deg) translateZ(200px);
  margin-top: 0px;
  animation: big-160 30s linear infinite;
}
@keyframes big-160 {
  0% {
    transform: rotateY(0deg) rotateX(288deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(288deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(288deg) translateZ(200px);
  }
}
.face:nth-child(161) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #cc8cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(288deg) translateZ(200px);
  margin-top: 0px;
  animation: big-161 30s linear infinite;
}
@keyframes big-161 {
  0% {
    transform: rotateY(18deg) rotateX(288deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(288deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(288deg) translateZ(200px);
  }
}
.face:nth-child(162) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #ce8cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(288deg) translateZ(200px);
  margin-top: 0px;
  animation: big-162 30s linear infinite;
}
@keyframes big-162 {
  0% {
    transform: rotateY(36deg) rotateX(288deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(288deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(288deg) translateZ(200px);
  }
}
.face:nth-child(163) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d08cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(288deg) translateZ(200px);
  margin-top: 0px;
  animation: big-163 30s linear infinite;
}
@keyframes big-163 {
  0% {
    transform: rotateY(54deg) rotateX(288deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(288deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(288deg) translateZ(200px);
  }
}
.face:nth-child(164) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d38cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(288deg) translateZ(200px);
  margin-top: 0px;
  animation: big-164 30s linear infinite;
}
@keyframes big-164 {
  0% {
    transform: rotateY(72deg) rotateX(288deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(288deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(288deg) translateZ(200px);
  }
}
.face:nth-child(165) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d58cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(288deg) translateZ(200px);
  margin-top: 0px;
  animation: big-165 30s linear infinite;
}
@keyframes big-165 {
  0% {
    transform: rotateY(90deg) rotateX(288deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(288deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(288deg) translateZ(200px);
  }
}
.face:nth-child(166) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d78cd9;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(288deg) translateZ(200px);
  margin-top: 0px;
  animation: big-166 30s linear infinite;
}
@keyframes big-166 {
  0% {
    transform: rotateY(108deg) rotateX(288deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(288deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(288deg) translateZ(200px);
  }
}
.face:nth-child(167) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cd8;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(288deg) translateZ(200px);
  margin-top: 0px;
  animation: big-167 30s linear infinite;
}
@keyframes big-167 {
  0% {
    transform: rotateY(126deg) rotateX(288deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(288deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(288deg) translateZ(200px);
  }
}
.face:nth-child(168) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cd6;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(288deg) translateZ(200px);
  margin-top: 0px;
  animation: big-168 30s linear infinite;
}
@keyframes big-168 {
  0% {
    transform: rotateY(144deg) rotateX(288deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(288deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(288deg) translateZ(200px);
  }
}
.face:nth-child(169) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cd3;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(288deg) translateZ(200px);
  margin-top: 0px;
  animation: big-169 30s linear infinite;
}
@keyframes big-169 {
  0% {
    transform: rotateY(162deg) rotateX(288deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(288deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(288deg) translateZ(200px);
  }
}
.face:nth-child(170) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cd1;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(306deg) translateZ(200px);
  margin-top: 0px;
  animation: big-170 30s linear infinite;
}
@keyframes big-170 {
  0% {
    transform: rotateY(0deg) rotateX(306deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(306deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(306deg) translateZ(200px);
  }
}
.face:nth-child(171) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98ccf;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(306deg) translateZ(200px);
  margin-top: 0px;
  animation: big-171 30s linear infinite;
}
@keyframes big-171 {
  0% {
    transform: rotateY(18deg) rotateX(306deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(306deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(306deg) translateZ(200px);
  }
}
.face:nth-child(172) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98ccd;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(306deg) translateZ(200px);
  margin-top: 0px;
  animation: big-172 30s linear infinite;
}
@keyframes big-172 {
  0% {
    transform: rotateY(36deg) rotateX(306deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(306deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(306deg) translateZ(200px);
  }
}
.face:nth-child(173) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cca;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(306deg) translateZ(200px);
  margin-top: 0px;
  animation: big-173 30s linear infinite;
}
@keyframes big-173 {
  0% {
    transform: rotateY(54deg) rotateX(306deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(306deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(306deg) translateZ(200px);
  }
}
.face:nth-child(174) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cc8;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(306deg) translateZ(200px);
  margin-top: 0px;
  animation: big-174 30s linear infinite;
}
@keyframes big-174 {
  0% {
    transform: rotateY(72deg) rotateX(306deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(306deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(306deg) translateZ(200px);
  }
}
.face:nth-child(175) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cc6;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(306deg) translateZ(200px);
  margin-top: 0px;
  animation: big-175 30s linear infinite;
}
@keyframes big-175 {
  0% {
    transform: rotateY(90deg) rotateX(306deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(306deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(306deg) translateZ(200px);
  }
}
.face:nth-child(176) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cc3;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(306deg) translateZ(200px);
  margin-top: 0px;
  animation: big-176 30s linear infinite;
}
@keyframes big-176 {
  0% {
    transform: rotateY(108deg) rotateX(306deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(306deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(306deg) translateZ(200px);
  }
}
.face:nth-child(177) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cc1;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(306deg) translateZ(200px);
  margin-top: 0px;
  animation: big-177 30s linear infinite;
}
@keyframes big-177 {
  0% {
    transform: rotateY(126deg) rotateX(306deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(306deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(306deg) translateZ(200px);
  }
}
.face:nth-child(178) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cbf;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(306deg) translateZ(200px);
  margin-top: 0px;
  animation: big-178 30s linear infinite;
}
@keyframes big-178 {
  0% {
    transform: rotateY(144deg) rotateX(306deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(306deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(306deg) translateZ(200px);
  }
}
.face:nth-child(179) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cbc;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(306deg) translateZ(200px);
  margin-top: 0px;
  animation: big-179 30s linear infinite;
}
@keyframes big-179 {
  0% {
    transform: rotateY(162deg) rotateX(306deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(306deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(306deg) translateZ(200px);
  }
}
.face:nth-child(180) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cba;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(324deg) translateZ(200px);
  margin-top: 0px;
  animation: big-180 30s linear infinite;
}
@keyframes big-180 {
  0% {
    transform: rotateY(0deg) rotateX(324deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(324deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(324deg) translateZ(200px);
  }
}
.face:nth-child(181) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cb8;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(324deg) translateZ(200px);
  margin-top: 0px;
  animation: big-181 30s linear infinite;
}
@keyframes big-181 {
  0% {
    transform: rotateY(18deg) rotateX(324deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(324deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(324deg) translateZ(200px);
  }
}
.face:nth-child(182) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cb6;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(324deg) translateZ(200px);
  margin-top: 0px;
  animation: big-182 30s linear infinite;
}
@keyframes big-182 {
  0% {
    transform: rotateY(36deg) rotateX(324deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(324deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(324deg) translateZ(200px);
  }
}
.face:nth-child(183) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cb3;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(324deg) translateZ(200px);
  margin-top: 0px;
  animation: big-183 30s linear infinite;
}
@keyframes big-183 {
  0% {
    transform: rotateY(54deg) rotateX(324deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(324deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(324deg) translateZ(200px);
  }
}
.face:nth-child(184) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cb1;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(324deg) translateZ(200px);
  margin-top: 0px;
  animation: big-184 30s linear infinite;
}
@keyframes big-184 {
  0% {
    transform: rotateY(72deg) rotateX(324deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(324deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(324deg) translateZ(200px);
  }
}
.face:nth-child(185) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98caf;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(324deg) translateZ(200px);
  margin-top: 0px;
  animation: big-185 30s linear infinite;
}
@keyframes big-185 {
  0% {
    transform: rotateY(90deg) rotateX(324deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(324deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(324deg) translateZ(200px);
  }
}
.face:nth-child(186) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98cac;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(324deg) translateZ(200px);
  margin-top: 0px;
  animation: big-186 30s linear infinite;
}
@keyframes big-186 {
  0% {
    transform: rotateY(108deg) rotateX(324deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(324deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(324deg) translateZ(200px);
  }
}
.face:nth-child(187) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98caa;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(324deg) translateZ(200px);
  margin-top: 0px;
  animation: big-187 30s linear infinite;
}
@keyframes big-187 {
  0% {
    transform: rotateY(126deg) rotateX(324deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(324deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(324deg) translateZ(200px);
  }
}
.face:nth-child(188) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98ca8;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(324deg) translateZ(200px);
  margin-top: 0px;
  animation: big-188 30s linear infinite;
}
@keyframes big-188 {
  0% {
    transform: rotateY(144deg) rotateX(324deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(324deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(324deg) translateZ(200px);
  }
}
.face:nth-child(189) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98ca5;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(324deg) translateZ(200px);
  margin-top: 0px;
  animation: big-189 30s linear infinite;
}
@keyframes big-189 {
  0% {
    transform: rotateY(162deg) rotateX(324deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(324deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(324deg) translateZ(200px);
  }
}
.face:nth-child(190) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98ca3;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(0deg) rotateX(342deg) translateZ(200px);
  margin-top: 0px;
  animation: big-190 30s linear infinite;
}
@keyframes big-190 {
  0% {
    transform: rotateY(0deg) rotateX(342deg) translateZ(200px);
  }
  50% {
    transform: rotateY(0deg) rotateX(342deg) translateZ(200px);
  }
  100% {
    transform: rotateY(0deg) rotateX(342deg) translateZ(200px);
  }
}
.face:nth-child(191) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98ca1;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(18deg) rotateX(342deg) translateZ(200px);
  margin-top: 0px;
  animation: big-191 30s linear infinite;
}
@keyframes big-191 {
  0% {
    transform: rotateY(18deg) rotateX(342deg) translateZ(200px);
  }
  50% {
    transform: rotateY(18deg) rotateX(342deg) translateZ(200px);
  }
  100% {
    transform: rotateY(18deg) rotateX(342deg) translateZ(200px);
  }
}
.face:nth-child(192) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98c9f;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(36deg) rotateX(342deg) translateZ(200px);
  margin-top: 0px;
  animation: big-192 30s linear infinite;
}
@keyframes big-192 {
  0% {
    transform: rotateY(36deg) rotateX(342deg) translateZ(200px);
  }
  50% {
    transform: rotateY(36deg) rotateX(342deg) translateZ(200px);
  }
  100% {
    transform: rotateY(36deg) rotateX(342deg) translateZ(200px);
  }
}
.face:nth-child(193) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98c9c;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(54deg) rotateX(342deg) translateZ(200px);
  margin-top: 0px;
  animation: big-193 30s linear infinite;
}
@keyframes big-193 {
  0% {
    transform: rotateY(54deg) rotateX(342deg) translateZ(200px);
  }
  50% {
    transform: rotateY(54deg) rotateX(342deg) translateZ(200px);
  }
  100% {
    transform: rotateY(54deg) rotateX(342deg) translateZ(200px);
  }
}
.face:nth-child(194) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98c9a;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(72deg) rotateX(342deg) translateZ(200px);
  margin-top: 0px;
  animation: big-194 30s linear infinite;
}
@keyframes big-194 {
  0% {
    transform: rotateY(72deg) rotateX(342deg) translateZ(200px);
  }
  50% {
    transform: rotateY(72deg) rotateX(342deg) translateZ(200px);
  }
  100% {
    transform: rotateY(72deg) rotateX(342deg) translateZ(200px);
  }
}
.face:nth-child(195) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98c98;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(90deg) rotateX(342deg) translateZ(200px);
  margin-top: 0px;
  animation: big-195 30s linear infinite;
}
@keyframes big-195 {
  0% {
    transform: rotateY(90deg) rotateX(342deg) translateZ(200px);
  }
  50% {
    transform: rotateY(90deg) rotateX(342deg) translateZ(200px);
  }
  100% {
    transform: rotateY(90deg) rotateX(342deg) translateZ(200px);
  }
}
.face:nth-child(196) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98c95;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(108deg) rotateX(342deg) translateZ(200px);
  margin-top: 0px;
  animation: big-196 30s linear infinite;
}
@keyframes big-196 {
  0% {
    transform: rotateY(108deg) rotateX(342deg) translateZ(200px);
  }
  50% {
    transform: rotateY(108deg) rotateX(342deg) translateZ(200px);
  }
  100% {
    transform: rotateY(108deg) rotateX(342deg) translateZ(200px);
  }
}
.face:nth-child(197) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98c93;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(126deg) rotateX(342deg) translateZ(200px);
  margin-top: 0px;
  animation: big-197 30s linear infinite;
}
@keyframes big-197 {
  0% {
    transform: rotateY(126deg) rotateX(342deg) translateZ(200px);
  }
  50% {
    transform: rotateY(126deg) rotateX(342deg) translateZ(200px);
  }
  100% {
    transform: rotateY(126deg) rotateX(342deg) translateZ(200px);
  }
}
.face:nth-child(198) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98c91;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(144deg) rotateX(342deg) translateZ(200px);
  margin-top: 0px;
  animation: big-198 30s linear infinite;
}
@keyframes big-198 {
  0% {
    transform: rotateY(144deg) rotateX(342deg) translateZ(200px);
  }
  50% {
    transform: rotateY(144deg) rotateX(342deg) translateZ(200px);
  }
  100% {
    transform: rotateY(144deg) rotateX(342deg) translateZ(200px);
  }
}
.face:nth-child(199) {
  width: 40px;
  height: 40px;
  border: 0px solid black;
  background: #d98c8f;
  opacity: 0.6;
  border-radius: 50%;
  position: absolute;
  transform: rotateY(162deg) rotateX(342deg) translateZ(200px);
  margin-top: 0px;
  animation: big-199 30s linear infinite;
}
@keyframes big-199 {
  0% {
    transform: rotateY(162deg) rotateX(342deg) translateZ(200px);
  }
  50% {
    transform: rotateY(162deg) rotateX(342deg) translateZ(200px);
  }
  100% {
    transform: rotateY(162deg) rotateX(342deg) translateZ(200px);
  }
}
@keyframes rotateround {
  0% {
    transform: rotateX(0deg) rotateY(20deg);
  }
  100% {
    transform: rotateX(360deg) rotateY(380deg);
  }
}
</style></head>
    <!--
    body {
      color:#000000;
      background-color:#FF00FF;
      background-image:url('Background Image');
      background-repeat:no-repeat;
    }
    a  { color:#0000FF; }
    a:visited { color:#800080; }
    a:hover { color:#008000; }
    a:active { color:#FF0000; }
    -->
    </style>
    <!--[if IE]>
    <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
  </head>
  <body itemscope itemtype="http://schema.org/MediaObject">
<body>
<div class="header">
  <h3><strong>MAGIC BALL ROTATING </strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<small>by SOFTWARE RVG</small></h3>
  <h2>mozilla hispano&nbsp;<h4>" blog de labs "</h4></h2> 
</div>
<div class="container">
  <div class="circle">
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
    <div class="face"></div>
  </div>
</div>
<div class="footer">
  <h4>SOFTWARE RVG en Twitter</h4>
  <div class="img">
    <a href="https://twitter.com/intent/follow?original_referer=https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Fsanta%2F1.1149.21%2Fstatic%2Fexternal%2Ftwitter.html%3Falign%3Dleft%26compId%3Dcomp-ieykc65q%26href%3Dhttps%253A%252F%252Ftwitter.com%252FSoftwareRVG%26lang%3Des%26origin%3Dhttp%253A%252F%252Fwww.software-rvg.com%26screen_name%3DSoftwareRVG%26show_count%3Dtrue%26show_screen_name%3Dtrue%26widgetType%3DFOLLOW&amp;ref_src=twsrc%5Etfw&amp;region=follow_link&amp;screen_name=SoftwareRVG&amp;tw_p=followbutton" title="Sigue a Rober113 (@SoftwareRVG) en Twitter" id="follow-button" class="btn"><i></i><span class="label" id="l">Seguir a <b>@SoftwareRVG</b></span></a>
	<div class="byline">
      <img src="https://3.bp.blogspot.com/-SSIfWR01A4w/Vs9bJ91mJhI/AAAAAAAAB9I/qEnEqQWJRig/s320/SOFTWARE%2BRVG-Icon%2Bapp.jpg" height="155" border="0" width="160">
    </a>
    
  </div>
</div>

<script src="//codepen.io/assets/editor/live/css_live_reload_init.js"></script>

  </body>
</html>

    Status API Training Shop Blog About 

    © 2016 GitHub, Inc. Terms Privacy Security Contact Help 

