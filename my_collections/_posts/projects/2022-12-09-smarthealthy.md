---
layout: post
title:  "2022 Fall Smart & Healthy Building TPC Meeting"
date:   2020-12-09 19:00:00 -0400
categories: jekyll update
---

- [Introduction](#introduction)
- [Time and Location](#time-and-location)
- [Schedule](#schedule)
- [Papers and codes](#papers-and-codes)
  * [Data-Driven Energy Estimation for Indoor Solar-Powered Energy Harvesting Sensors](#data-driven-energy-estimation-for-indoor-solar-powered-energy-harvesting-sensors)
  * [A real-time indoor environmental status dashboard](#a-real-time-indoor-environmental-status-dashboard)
  * [A Cost-Effective Non-Invasive Method for Accurate Occupancy Detection in Conference Rooms Using Environmental Quality Sensors](#a-cost-effective-non-invasive-method-for-accurate-occupancy-detection-in-conference-rooms-using-environmental-quality-sensors)
  * [Room Occupant Identification using Machine Learning](#room-occupant-identification-using-machine-learning)
  * [Measuring Accuracy in Occupant Recall of Environmental Comfort Indicators](#measuring-accuracy-in-occupant-recall-of-environmental-comfort-indicators)

## Introduction
From the time that electricity was brought to buildings, the settings for lighting, ventilation, and temperature were difficult to measure and were usually kept at a uniform level. Also, the cleanliness of the air was difficult to determine, which could be dangerous if chemicals in the air became too dangerous without anyone being alerted. In order to make indoor conditions more comfortable, safe and efficient, a wide variety of sensors have been developed and used in buildings. The most recognizable type of sensor is a thermostat which can measure and change the temperature based on the user’s preferences. Aside from temperature, there are also sensors that are designed to track levels of chemicals such as CO2, VOCs, or PM 2.5 in the air, brightness, humidity, or even the occupancy of a space. Having access to all of this data gives an idea of how building systems should be running on a scheduled basis in order to reduce spending, give the best overall experience for users.

This semester, our class learned about, researched, and implemented methods that help to optimize the indoor experience. In the first half of the semester, we read several proposals that experiment with and advocate for the use of newly designed sensors or programs. We reviewed and discussed the practicality of these ideas and determined if they were truly worth implementing in a real environment or if they still need work. Later on in the class, we practiced pulling and grouping sensor data from the UVA Link Lab and from our own personal sensors. These discussions and assignments gave us the experience we needed to create our own optimized building solutions using sensors. For the latter end of the semester, we have been working in project groups to develop brand new programs using sensors with goals to reduce energy consumption, track new types of data and improve the overall building experience. This site showcases the five final project proposals that our class has developed to finish the semester.

## Time and Location
 **Date**: Saturday, December 10, 2022
**Time**: 2:00PM - 5:00PM
**Location**: UVA Linklab open area

## Schedule

- **2:00 - 2:20**:
All groups arrive and have some time to eat and chat with each other about their projects and experience with the class over the semester. 
- **2:20 - 2:40**:
Group 1 (*Data-Driven Energy Estimation for Indoor Solar-Powered Energy Harvesting Sensors*) gives a 10 minute presentation on their paper followed by a 10 minute class discussion.
- **2:40 - 3:00**:
Group 2 (*A real-time indoor environmental status dashboard*) gives a 10 minute presentation on their paper followed by a 10 minute class discussion.
- **3:00 - 3:20**:
Guest Speaker
- **3:20 - 3:40**:
Group 3 (*A Cost-Effective Non-Invasive Method for Accurate Occupancy Detection in Conference Rooms Using Environmental Quality Sensors*) gives a 10 minute presentation on their paper followed by a 10 minute class discussion.
- **4:00 - 4:20**:
Group 4 (*Room Occupant Identification using Machine Learning*) gives a 10 minute presentation on their paper followed by a 10 minute class discussion.
- **4:20 - 4:40**:
Group 5 *(Measuring Accuracy in Occupant Recall of Environmental Comfort Indicators*) gives a 10 minute presentation on their paper followed by a 10 minute class discussion.
- **4:40 - End**:
Opportunity for a class discussion about the class as a whole, expectations vs. reality, things students found most interesting, ideas for future projects, etc. 


## Papers and codes
### Data-Driven Energy Estimation for Indoor Solar-Powered Energy Harvesting Sensors
<a href="https://dl.acm.org/doi/10.1145/3408308.342762](https://github.com/viswajith-g/Data-Driven-Energy-Estimation-for-Indoor-Solar-Powered-Energy-Harvesting-Sensors"> Github </a>
<a href="https://drive.google.com/file/d/1O9KsrmuXDvobtZ76O8dullRSnuPDG0jB/view?usp=share_link"> Paper </a>
**Authors**: Viswajith Govinda Rajan, Zoraiz Qureshi, Akash Nair, Zichuan Guo
**Abstract**: Energy generation fluctuation leads to uncertainty in the estimation of energy availability which can influence the design of in-door energy harvesting Internet of Things (IoT) devices. Lux sensors may also not be available every time for this estimation, and their estimation is very sensitive to placement. We explore methods for robust data-driven estimation of energy availability for indoor energy harvesting sensors, focusing specifically on solar-powered sensors from different sensors as sources such as motion and acoustic noise sensor data.  

### A real-time indoor environmental status dashboard
[Github](https://github.com/12-plus-1/ieq_dashboard) 
[Paper](https://drive.google.com/file/d/1CPtUY79hvp_KAKulfEddXntqV00pTxXF/view?usp=share_link)
**Authors**: Xinyue Fan, Blake Wang, Anne Zhang, Francis Becker
**Abstract**: We created a web interface that tracks real-time sensor data from select spaces in the Link Lab to generate text prompts for Craiyon, a free and accessible AI text to image generator. We will specifically focus on CO2, temperature and illumination data provided by the linklab sensors which will reflect on the indoor comfort level of the office space. The data values for each category will be used to determine text prompts that generates a coherent image depicting brightness, occupancy and temperature and displayed through an interactive real time dashboard for visualization.

### A Cost-Effective Non-Invasive Method for Accurate Occupancy Detection in Conference Rooms Using Environmental Quality Sensors
[Github]()
[Paper](https://drive.google.com/file/d/1WCO3tWpM7XH3Z6oL7SdGTq-0qO0omhVf/view?usp=share_link) 
**Authors**: Kane Aldrich, Katheryn Flynn, Hamidreza Nabaei, Emmett Rice
**Abstract**: The increasing cost of energy and a greater knowledge of the impact of the environment on human health and pro- ductivity has led to an increased demand for smart solutions and dynamic control to the Heating, Ventilation, and Air Conditioning (HVAC) of buildings. In the context of smart response, the knowledge of occupants in a room allows the HVAC system to respond to the natural degradation of a closed environment when populated. This paper presents an approach using Indoor Air Quality (IAQ) sensors to create a model for the number of occupants in a room. 86% accu- racy in exact occupant number within a conference room is achieved when using a singular 𝐶𝑂2 sensor. The method pre- sented also reduces the cost of sensing by using IAQ sensors rather than intrusive cameras, or high cost motion detection.  

### Room Occupant Identification using Machine Learning
[Github](https://github.com/rnzhou32/SHB-Project) 
[Paper](https://drive.google.com/file/d/1AMfQdLBpTrx0bSzOMcM08Mm8PRJbGT8w/view?usp=share_link) 
**Authors**: Yue Zhu, Xavier Castillo-Vieira, Runnan Zhou, Jiahao Shen, Shuhao Dong
**Abstract**: The room reservation process is being equipped with automation tools in recent years for faster and more convenient service. However, existing systems are not smart enough to verify whether a room is occupied by the group that made the reservation. In this paper, we present a machine-learning-based automation occupancy detection tool to tell whether a periodically reserved room is actually used by the intended applicant or group. We trained the classifier using three machine learning models(SVM, KNN and Bayesian) separately and evaluated their performances on the real-world data set. KNN achieved the best accuracy of 63.5\% among the tested models, which indicates the feasibility of classifying a group’s identity based on spatial sensor readings to a reasonable accuracy level. 

### Measuring Accuracy in Occupant Recall of Environmental Comfort Indicators
Github [link]() 
Paper [link](https://drive.google.com/drive/folders/1H_5zK7ed6w3gr6vkEWPZE9FmYd0Dckxt) 
**Authors**: Tao Jiang, Haoqian Li, Richard Yu, Erzhen Hu, Natalie Ownby
**Abstract**: Many existing studies regarding individual comfort preferences in indoor environments rely on occupants’ recall of environmental trends. Indeed, their reported comfort levels can be greatly affected by their capacity for recall. However, the existing literature has a blind spot when measuring the accuracy of individual perception. In this paper. We conducted a survey of thirteen occupants in the University of Virginia’s Link Lab, which is a climate-controlled smart building which measures environmental quality via a network of sensors. In the survey, we asked about the general trends in environmental comfort indicators (Humidity, Temperature, Noise levels, Light levels, and Air Quality) that they could recall in the Link Lab. Then, we compared their perceptions to actual results pulled from the Link Lab sensors during a similar timeframe over one week. Our results indicated that there did exist some discrepancies when it came to individual opinion and observed trends. 

