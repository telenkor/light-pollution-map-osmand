<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<div align="center">
  <h1 align="center">Light pollution Map OsmAnd+</h1>

  <p align="center">
    Offline Light pollution Atlas for the OsmAnd+ Android application
    <br />
    <a href="https://github.com/telenkor/light-pollution-map-osmand/releases"><strong>Get the latest release</strong></a>
    <br />
  </p>
</div>

[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/telenkor/light-pollution-map-osmand/blob/main/README.md)
[![ru](https://img.shields.io/badge/lang-ru-green.svg)](https://github.com/telenkor/light-pollution-map-osmand/blob/main/README.ru.md)

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#disclaimer">Disclaimer</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Screenshot_20250425-215210_OsmAnd+](https://github.com/user-attachments/assets/2d919701-6686-43a4-9989-b75f710672da)

If you are into astronomy, the most important thing is how dark the sky is above you. There are many resources for this, both paid and free, where you can see the level of sky illumination in any area.
In my subjective opinion, the best such resource is the [Light Pollution Atlas](https://djlorenz.github.io/astronomy/lp/overlay/dark.html) by [David J. Lorenz](https://djlorenz.github.io/), the source code of which can be found [here](https://github.com/djlorenz/djlorenz.github.io).

However, the online service is not always convenient and you want to have a permanent map at hand. Since one of the most convenient navigation programs is [OsmAnd+](https://osmand.net/), I decided to transfer the [Light Pollution Atlas](https://djlorenz.github.io/astronomy/lp/overlay/dark.html) to it.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To install the Light pollution Map, you do not need deep knowledge or root privileges.

### Prerequisites

First, download the Light-pollution-20xx.sqlitedb file from the <a href="https://github.com/telenkor/light-pollution-map-osmand/releases"><strong>Releases</strong></a> to your Android phone/tablet.
After that you need to find out where the OsmAnd+ program data is stored.
There are only two options:
* Internal memory
* Micro-SD card

If you have difficulty determining the storage, the screenshots below show how you can find out its location:

<details>
  <summary>Find storage location</summary>
  <br />
  
  ![0_1](https://github.com/user-attachments/assets/5873eb81-c835-4595-a6f4-6e32b5d73d1e)
  <br />
  
  ![0_2](https://github.com/user-attachments/assets/e33a47bd-6881-4e40-bd82-ab8543d16906)
  <br />
</details>

### Installation

1. You need to move the Light-pollution-20xx.sqlitedb file to this path:
```
/YOUR STORAGE/Android/data/net.osmand.plus/files/tiles
```

2. You need to activate the "Online maps" plugin in the OsmAnd+ settings:

   ![01](https://github.com/user-attachments/assets/accadc86-f2b6-4980-be56-093bf3710268)


3. Set the Light pollution Map as the top layer:

   ![Screenshot_20250425-223214_OsmAnd+_conf_map](https://github.com/user-attachments/assets/045d887d-74f7-49cf-b229-a81941770a58)

   ![Screenshot_20250425-223238_OsmAnd+_map2](https://github.com/user-attachments/assets/db8d720c-0a84-4bed-ac9c-36099ae51012)

4. Everything is ready.
   <br />
   It will be displayed on top of the main map.
   Using the blue slider at the bottom of the screen we can adjust the transparency of the Light pollution Map layer:

   ![Screenshot_20250425-215210_OsmAnd+_slider](https://github.com/user-attachments/assets/a4e9125f-198b-43bc-a816-77c8022af63c)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Disclaimer

The project was tested on the OsmAnd+ v4.8.4 application and Android 8, 14.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
