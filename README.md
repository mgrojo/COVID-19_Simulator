# CovidSim
Visual tool to simulate the Covid19 pandemic.

## Table of Contents
<details>
<summary>Click to expand</summary>

1. [Presentation](#Presentation)
2. [Status](#Status)
3. [Prerequisites](#Prerequisites)  
4. [Dependencies](#Dependencies)
5. [Building](#Building)
   1. [Windows](#Windows)
6. [Limitations](#Limitations)
7. [Usage](#Usage)
8. [Acknowledgments](#Acknowledgments)

</details>

## Presentation
<div align="center">

<a>
<img border="0" src="https://github.com/ohenley/covidsim/blob/master/covidsim.png" style="max-width:100%;">
</a>
  
</div>

> Ada code  
> Qt5 driven  
> Based on computations by https://github.com/zertovitch/mathpaqs  
> Implementing https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(20)30260-9/fulltext

<!---![alt text](https://github.com/ohenley/readme-template/blob/master/thug_war.png)--->

## Status
- Works on Windows 10
- Not working on Linux (planned)

## Prerequisites
- win32 platform
- [gnat-ce compiler](https://www.adacore.com/download) 

## Dependencies
#### git submodules
- mathpaqs : [fork](https://github.com/ohenley/mathpaqs) of https://github.com/zertovitch/mathpaqs
- qt5Ada : https://github.com/ohenley/qt5ada

## Building
#### Windows
```
> git clone --recursive https://github.com/ohenley/covidsim.git
> cd covidsim
> gprbuild covidsim.gpr
```

## Limitations
None so far.

## Usage
```
> cd deps/qt5ada/qt5/5.15/bin
> ./covidsim.exe
```

## Acknowledgments
- Based on simulation work by https://github.com/zertovitch
- Using a custom package version of qt5ada thick binding by [Leonid Dulman](https://r3fowwcolhrzycn2yzlzzw-on.drv.tw/AdaStudio/qtada/qt5ada.html)

A big thank to both!
