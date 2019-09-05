# raspberrypi_systemctl
For controlling AI cam.
====

Overview

## Description
This repository provides systemctl servies for AI cam created in using opencv.
You can make things simple insted of using bash and cron to run python opencv.



## Demo

## VS. 
It used to be running your program every boot requires you to write crontab and bash script some times.
This became much simpler by using systemctl.

## Requirement
Linux has systemd
python3
anaconda if you wish to use.
## Usage
add services /lib/systemd/system/recording.service

sudo systemctl daemon-reload

sudo systemctl start/stop recording service

check status by issueing command 
sudo systemctl status recording.service

Make this serive runs every boot by
sudo systemctl enable recording.service
## Install

## Contribution

## Licence


## Author

[linuxkay](https://github.com/linuxkay)
