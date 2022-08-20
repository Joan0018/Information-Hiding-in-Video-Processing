<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Joan0018/Information-Hiding-in-Video-Processing">
    <img src="https://icons.iconarchive.com/icons/papirus-team/papirus-places/512/folder-red-video-icon.png" alt="Logo" width="80" height="80">
  </a>

  <h4 align="center">Information Hiding in Video Processing</h4>
  <h4 align="center">
    MASTER OF INFORMATION TECHNOLOGY
    <br/>
    Supervisor: Assoc. Prof. Ts. Dr Tew Yiqi
    <br/>
    Contributors: Joan Hau
  </h4>
  <!-- Description Needed-->
  <p align="center">
    <!-- NEED ADDED AFTER FINAL REPORT RUN ORIGINALITY -->
    <a href="https://github.com/Joan0018/Information-Hiding-in-Video-Processing/wiki"><strong>Explore the docs »</strong></a>
    <br />
    <a href="#table-of-content"><strong>Explore more »</strong></a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<a id="table-of-content">
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#introduction">Introduction</a>
      <ul>
        <li><a href="#objective">Objectives</a></li>
        <li><a href="#outcome">Expected Outcome</a></li>
      </ul>
    </li>
    <li>
      <a href="#get-start">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#guide">Guidelines</a>
          <ul>
            <li><a href="#installation">Installation</a></li>
            <li><a href="#build">Build</a></li>
            <li><a href="#execute">Execute</a></li>
            <li><a href="#testing">Testing</a></li>
          </ul>
        </li>
        <li><a href=""></a></li>
      </ul>
    </li>
    <li>
      <a href="#usage">Usage</a>
      <ul>
        <li><a href=""></a></li>
        <li><a href=""></a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>
</a>


<!-- PROJECT INFORMATION-->
<a id="introduction"></a>
## Introduction
<div align=justify>
&nbsp;&nbsp;&nbsp; Information security has gained tremendous importance over the past few decades due to the massive growth of digital communications (Dalal, M. and and Juneja, M., 2021). Video information hiding is one of the most important strategies for providing various video services such as video authentication and augmentation. Video information hiding process refer to inserting various forms of featured information into video streams for security purposes (Thampi, S., 2004), such as inserting the watermarking into the video to represent the originality of the video (Merchant, Shabbir et al., 2003), or for video augmentation purposes, such as depthmap embedding, motion information embedding, and extended-color information. As a result, effective video information hiding techniques are important for a variety of new multimedia application. <br>
&nbsp;&nbsp;&nbsp;Video information hiding technique for compressed video have recently gained a lot of attention, as videos are often stored and transmitted in compressed format. Existing compressed video information hiding methods, such as MPEG, H.264, and H.265/High Efficiency Video Coding (HEVC) have been thoroughly investigated in compression standards. Bhaumik, Arup et al. (2009) using the Least Significant Bit (LSB) approach to hide the data for high resolution AVI (Audio Video Interleave) videos and Singh, et al. (2010) using same method to hide each row of image pixels in multiple frames of the video. Paruchuri, J.K. et al. (2009) proposed an optimized framework by hiding the data into selective Discrete Cosine Transform (DCT) coefficient in compressed video. Y. Tew et al. (2014) modified the structure of coding block and non-zero transform coefficients to embed information. <br>
&nbsp;&nbsp;&nbsp;Despite the success of the above information hiding techniques in previous video compression standards, little work has been done on the proprietary tools provided in the latest video compression standard H.266/Versatile Video Coding (VVC) to further improve information hiding methods. H.266/VVC (X. Liu et al., 2021) uses a hybrid coding framework, including prediction, transformation, quantization, and entropy coding, which was identified as the previous coding standard. However, VVC
introduces many new compression tools to improve the compression efficiency. For internal prediction, VVC introduces some new mechanisms such as matrix-weighted internal prediction (MIP), multiple reference lines (MRL) and cross-component linear model (CCLM), which increases the flexibility of pattern selection and thus is potentially suitable for information hiding.
</div>

<a id="objective"></a>
### Objectives
<ol>
  <li>Protect the secret data of the video by hiding the message in the video and not allowing anyone without the secret key to discover the presence of a "second message" in the played video.</li>
  <li>Provide proper protection on data during transmission.</li>
  <li>Provide an artistic and scientific way of communication for the video sending
process.</li>
</ol>

<a id="outcome"></a>
### Expected Outcome
<div align="justify">
&nbsp;&nbsp;&nbsp;Due to the advancement of Information Technology, the rapid advances in publishing and broadcasting technology require an alternative solution to hiding information. Copyrighting resources such as audio, video and other digital forms can lead to large-scale unauthorized copying. Throughout the research, solve the problem of video information hiding in various information management, at the same time, providing an easier way for hiding information during information transmission through video.
</div>


<!-- GETTING STARTED -->
<a id="get-start"><h2 style="display: inline-block">Getting Started</h2></a>

<!-- Prerequisites -->
<a id="prerequisites"><h2 style="display: inline-block">Prerequisites</h2></a>

*MacOS Xcode and CMake Version 3.12 or higher are required* <br>
:collision:
*Only Applicable on MacOS* 
:collision: <br>
***Refer [Fraunhofer Versatile Video Encoder (VVenC)](https://github.com/fraunhoferhhi/vvenc) for more information.***

<!-- Installation -->
<a id="guide"></a>
## Guidelines

<a id="installation"></a>
### Installation
#### Install XCode
```cpp
https://apps.apple.com/us/app/xcode/id497799835?mt=12
```

#### In Terminal
```cpp
cd/PATH_OF_THE_FILE
```
##### Install Command Line Tools
```cpp
xcode-select --install
```
##### Install Homebrew and Cmake
```cpp
https://code.visualstudio.com/download
```

#### Install Visual Studio Code
```cpp
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

<a id="build"></a>
### Build
```cpp
https://github.com/Joan0018/Information-Hiding-in-Video-Processing/wiki/Build
```
<a id="execute"></a>
### Execute
#### In Terminal
```cpp
cd/PATH_OF_THE_FILE
```
```cpp
cd install/bin
```
```cpp
chmod +x ./vvencapp
```
```cpp
./vvencapp
```

<a id="testing"></a>
### Testing
#### In Terminal
```cpp
./vvencapp --preset tooltest -s 80x44 -r 15 -i ../../test/data/RTn23_80x44p15_f15.yuv -f 8 -o out.vvc
```


<!-- Installation Demo-->
<a id="installationDemo"><h2 style="display: inline-block">Installation Demo</h2></a>

<!-- USAGE EXAMPLES -->
<a id="usage"><h2 style="display: inline-block">Usage</h2></a>

<!-- CONTACT -->
<a id="contact"><h2 style="display: inline-block">Contact</h2></a>

Joan Hau - [Github](https://github.com/Joan0018)

<!-- ACKNOWLEDGEMENTS -->
<a id="acknowledgements"><h2 style="display: inline-block">Acknowledgement</h2></a>
_A Special Thanks To_
* [Fraunhofer Versatile Video Encoder (VVenC)](https://github.com/fraunhoferhhi/vvenc)
* [VVdeC Fraunhofer Versatile Video Decoder v1.2.0](https://www.hhi.fraunhofer.de/fileadmin/Departments/VCA/MC/VVC/vvdec-v1.2.0-v1.pdf)
* [Fraunhofer Versatile Video Decoder (VVdeC)](https://github.com/fraunhoferhhi/vvdec)

<!-- REFERENCES -->
<a id="references"><h2 style="display: inline-block">References</h2></a>
<a href="https://www.hhi.fraunhofer.de/en/departments/vca/technologies-and-solutions/h266-vvc.html">[1]</a>Heinrich-Hertz-Institut, F., 2022, H.266 / VVC – Fraunhofer Heinrich Hertz Institute, viewed 20 August 2022. <<https://www.hhi.fraunhofer.de/en/departments/vca/technologies-and-solutions/h266-vvc.html>>
