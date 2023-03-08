<h1 align="center">polybar-time-bar</h1>

<p>&nbsp;</p>

A time module for your

<div align="center">
	<picture>
 	 <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/polybar/polybar/master/doc/_static/banner-dark-mode.png">
 	 <img alt="polybar logo" src="https://raw.githubusercontent.com/polybar/polybar/master/doc/_static/banner.png">
	</picture>
</div>

<p>&nbsp;</p>

<p align="center">
	<a href="https://github.com/jamessouth/polybar-time-bar/blob/master/LICENSE"><img src="https://img.shields.io/github/license/jamessouth/polybar-time-bar"></a>
	<a href="https://archlinux.org/"><img src="https://img.shields.io/badge/Linux-d.svg?logoWidth=40&labelColor=d35e49&color=E3C567&logoColor=000000&logo=Linux"></a>
	<a href="https://www.gnu.org/software/bash/manual/"><img src="https://img.shields.io/badge/Bash-d.svg?logoWidth=40&labelColor=4eaa25&color=293137&logoColor=ffffff&logo=GNU%20Bash"></a>
	<img src="https://img.shields.io/badge/awesome-%C6%94%F0%9D%9A%BA%C5%9E-235789.svg">
</p>
<p>&nbsp;</p>

## Description
This repo is a progress bar module that shows how much of the day (or other time period) has passed. It uses the [Unicode code points 2588-F](https://www.unicode.org/charts/PDF/U2580.pdf) (1/8 block to full block) but you can use anything, including [Powerline characters](https://github.com/ryanoasis/powerline-extra-symbols#glyphs). The Stack Overflow answer [here](https://stackoverflow.com/a/68298090) was helpful in developing this module.
<p>&nbsp;</p>

## Installation
Install all of the scripts:
```bash
curl -JOL https://github.com/jamessouth/polybar-time-bar/blob/master/timebar.zip?raw=true && mkdir -pv ~/.config/polybar/timebar && unzip timebar.zip -d ~/.config/polybar/timebar && chmod -R +x ~/.config/polybar/timebar && rm timebar.zip
```
This will download the zip file, create the `timebar` directory in `.config/polybar`, unzip the archive into the `timebar` directory, make each script executable, and delete the zip file. Note that no-break spaces need to be added to the Scroll and Time scripts as described therein.
<p>&nbsp;</p>

## Usage
Please see the wiki.
<p>&nbsp;</p>
