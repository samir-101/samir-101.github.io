---
title: "Human Presence Detection Using Thermal Camera and STM32 by DFS Cluster Detection"
excerpt: "STM32 H723ZG, MLX90640 and ILI9341 based low resolution thermal camera with bi-linear upscaling<br/><img src='/images/thermal/img1.jpg' height=\"300\" width = \"500\">"
collection: portfolio
---
<div align="center">
  <img src="/images/thermal/img1.jpg" alt="Example Image 1" title="Thesis Test Setup" style="height:30vw; border-radius:8px;">
</div>

It is a low resolution low cost thermal camera with with Video streaming support via USB Serial. The code detects cluster using DFS algorithm and triggers output whenever the cluster size is greater than the threshold. This is a very crude try to detect human presence using MCU. There is also a python client file to stream as video from the thermal camera.

<div align="center" style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px;">
  <img src="/images/thermal/img_13.png" alt="Front CAD View" title="Front CAD View" style="width:10vw; border-radius:8px;">
  <img src="/images/thermal/img_9.png" alt="Front Real View" title="Front Real View" style="width:10vw; border-radius:8px;">
</div>

<p align="center" > <b>
<a href= "https://drive.google.com/file/d/12doL1PNrvsDzEYfPceme25Krje_h22S3/view?usp=drive_link"> Link</a> to video demo
</b>
</p>

<p align="center" > <b>
<a href= "https://github.com/samir-101/thermal-camera-90640"> Link</a> to Github repo
</b>
</p>