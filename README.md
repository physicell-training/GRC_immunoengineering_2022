# GRC_immunoengineering_2022

This repository collects notes a full walk-thru for online PhysiCell modeling, presented on July 11, 2022 at the 1st Immunoengineering Gordon Research Conference. 

This tutorial can be done for free without any coding experience. It should take 15-30 minutes. (A solid internet connection is strongly recommended.) 

## NanoHub registration
Participants should create a nanoHUB account in advance at https://nanohub.org/register. I suggest using the Google login option. 

## Slides
The live slides for the session are available here: [GRC_immunoengineering_2022 live version](https://github.com/physicell-training/GRC_immunoengineering_2022/raw/main/slides/Macklin-GRC-2022-live.pdf)

The extended slides including this walk-through are here here: [GRC_immunoengineering_2022 extended version](https://github.com/physicell-training/GRC_immunoengineering_2022/raw/main/slides/Macklin-GRC-2022-full.pdf). 

To follow the modeling in the slides, use the [https://nanohub.org/tools/pc4learning](pc4learning) app. 

## Source code 
If you run the desktop version of PhysiCell, you can download the v1, v2, and v3 models here. To prepare, first populate and compile the template project: 

```
make template
make
```

### v1 model
This model has bacteria only. Download the v1 config file: [v1 config](https://github.com/physicell-training/GRC_immunoengineering_2022/raw/main/code/v1.xml), and save it to your config directory (as `v1.xml`). Then run it as: 
```
./project v1.xml 
```
(Windows users: 'project v1.xml'). 

### v2 model
This adds macrophages to the v1 model. Download the v2 config file: [v2 config](https://github.com/physicell-training/GRC_immunoengineering_2022/raw/main/code/v2.xml), and save it to your config directory (as `v2.xml`). Then run it as: 
```
./project v2.xml 
```
(Windows users: `project v2.xml`). 


### v3 model
This adds neutrophils to the v2 model.  Download the v3 config file: [v3 config](https://github.com/physicell-training/GRC_immunoengineering_2022/raw/main/code/v3.xml), and save it to your config directory (as `v3.xml`). Then run it as: 
```
./project v3.xml 
```
(Windows users: `project v3.xml`). 

### Visualization
To make a quick animated gif: 
```
make gif 
```
It will be stored in your output directory. 
