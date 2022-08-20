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
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
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


<!-- ABOUT THE PROJECT -->
<a id="about-the-project"><h2 style="display: inline-block">About The Project</h2></a>


<a id="built-with"><h2 style="display: inline-block">Built With</h2></a>



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
