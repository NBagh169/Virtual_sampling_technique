﻿# Virtual_sampling_technique
 # 1. Aim
This code will generate spectrogram images by varying the sampling rate both upward and downward without altering the original signal. By adjusting the sampling rate in this manner, the spectrogram patterns at specific frequency bands shift correspondingly. This process allows for the creation of a large number of images, which can then be used to effectively train transfer learning models. 
# 2. Datasets
Two benchmark datasets have been implemented:
a.	CWRU bearing dataset.
b.	Mafaulda bearing dataset.
1.	CWRU bearing dataset: The Case Western Reserve University (CWRU) bearing data were used to evaluate the performance of the model. The test rig consists of a dynamometer (right), a 2 HP motor (left), and a torque transducer/encoder (center). The test rig also includes a set of control electronics and is not shown in the figure. The motor shaft is supported by test bearings. Single-point faults are introduced to these bearings using electro-discharge machining. The vibration data are collected by using accelerometers, which are attached on the housing with magnetic bases. The accelerometers are placed at 12 o’clock position on the drive housing. The data are collected using a 16-channel DAT recorder. Data were collected from a motor-driven mechanical system under four different loads, the motor’s speed was 1797 r/min under no load, and the sampling frequency was 12 kHz. Data were collected from a motor-driven mechanical system under four different loads, the motor’s speed was 1797 r/min under no load, and the sampling frequency was 12 kHz.The bearing dataset consisted of the following four conditions: (1) normal condition (NC), (2) with outer race fault (OF), (3) with inner race fault (IF), and (4) with roller fault (RF). There were three fault diameters (0.18, 0.36, and 0.54 mm) for the IF, OF, and RF cases, respectively. In this paper, only the data of motor speed of 1797 r/min were used. The type of bearing was SKF6205.
The link for the detailed description of the experiment is given below:
https://engineering.case.edu/bearingdatacenter/download-data-file

2.	This database is composed of 1951 multivariate time-series acquired by sensors on a SpectraQuest's Machinery Fault Simulator (MFS) Alignment-Balance-Vibration (ABVT). The 1951 comprises six different simulated states: normal function, imbalance fault, horizontal and vertical misalignment faults and, inner and outer bearing faults. This equipment emulates the dynamic of motors with two shaft-supporting bearings and allows the study of multiple faults, such as imbalanced mass, axis misalignment, and bearing problems. The experimental setup used in this work is illustrated on Figure 2. 



