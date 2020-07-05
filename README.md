# Raspberrypi systemctl for AI cam.
![systemctl](https://raw.githubusercontent.com/wiki/linuxkay/raspberrypi_systemctl/images/recording_service.gif)

## Overview

systemctl services for controlling AI CAM
files

detecting.service
- Detect objects based on model which you trained.
recording.service
- Record detected object for 10 seconds and save it to mp4.

## Description
This repository provides systemctl servies for AI cam created in using opencv.
You can make things simple insted of using bash and cron to run python opencv.



## Demo

## VS. 
It used to be running your program every boot by adding @reboot on crontab. It requires you to write crontab and bash script some times.
This became much simpler by using this systemctl method.

## Requirements
Linux has systemd

python3 anaconda if you wish to use.
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
[MIT]

## Author

[linuxkay](https://github.com/linuxkay)
