# name

artnet_Parser

## Overview

Resolumeから送出されるArtnet信号を再パースするためのソフトウェア。

## Requirement

- Windows and MacOS.
- TouchDesigner 2022.26590.

## Usage

<p align="center">
  <img src="https://user-images.githubusercontent.com/83099549/187180611-54c16d8d-f795-4f7d-be80-049b6fddadb6.png" alt="" width="300px">
</p>

- Receive Resolume artnet signal
  - IP Address 
    - Resolumeから受信しているIPアドレス
  - Net
    - ArtnetのNet値を入力
  - Subnet
    - Subnet値を入力
  - Universe
    - Universe値を入力

- Send USB to dmx signal
  - Active
    - 初期値アクティブですが、一度オフにしてオンにし直すことをおすすめします。
    
- Send Artnet to visualizer signal
  - Receive Resolume artnet signalと基本的に同じです。

- Static channel value
  - CTC
    - default value:32
  - Intencity
    - default value:255
  - Duration
    - default value:70
  - Rate
    - default value:60

## Author

Kazama kazuki.
