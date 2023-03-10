---
title: "Projects"
date: 2020-12-28T11:24:32+05:30
draft: false
description: Past and current projects.
---
## Scientific Computing:

### 1. Simulating pressure variation in Earth's heterogeneous rocks 

Pressure in a rock element in Earth's lithosphere may vary from its ambient value and if 
significant, may influence the physical processes. This poses major problems in 
routine use of pressure as a proxy for depth in geodynamic models. This project developed and applied 
physics-based numerical models to simulate pressure deviation in a rheologically distinct rock element in 
an ambient rock medium of a non-linear viscous anisotropic rheology. It was found that the 
pressure deviations in a rock element are in the same order as the deviatoric stress levels and 
hence limited by the strength of rocks. Following figure shows one such example of pressure fields around a heterogeneous element with a different viscosity than the surrounding rocks. The pressure values are normalized with respect to far field stresses.
\
\
![](/media/Pressure1.png)
\
For more info, refer to our publication [here](https://doi.org/10.1016/j.epsl.2018.07.010)
\
Code: [https://github.com/ankibues/MOPLA_Application_Matlab/tree/master/Pressure%20Investigation](https://github.com/ankibues/MOPLA_Application_Matlab/tree/master/Pressure%20Investigation)

### 2. Simulating quartz crystal fabrics 

 Flow variation in quartz aggregates of natural high strain zones in Earth's lithosphere can influence the development of crystallographic fabric and cause problems in its interpretation. If such effect is not accounted for, crucial geological information such as deformation temperature, deformation history and shear sense obtained using crystallographic fabric can be seriously misinterpreted. This project developed and applied a multiscale model coupling [Matlab](https://www.mathworks.com/products/matlab.html)-based MOPLA code with the [Fortran](https://fortran-lang.org/en/)-based VPSC code to simulate the quartz crystallographic fabric under partitioned flow. It was found that the quartz c-axis fabric variation showing apparent opposite senses of shear within a single thin section, can be explained by partitioned flow within the quartz domains and reflect finite strain gradient rather than reversal of vorticity sense as previously thought. Following image shows the quartz crystal fabric changing with increase in strain intensity. This only happens when quartz aggregates are rheologically stronger than the surrounding rockmass.
\
\
![](/media/CPO1.png)
\
For more info, refer to our publication [here](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2020JB021040)
\
Code: [https://github.com/ankibues/MOPLA_Application_Matlab/tree/master/MOPLA_coupling_VPSC](https://github.com/ankibues/MOPLA_Application_Matlab/tree/master/MOPLA_coupling_VPSC)

### 3. Simulating flanking structures in rocks

Flow variation around a rheological heterogeneity (also known as a cutting element) such as a dyke, can form flanking structures, 
which if interpreted incorrectly, can cause problems in understanding regional plate tectonics. This project developed a new model to simulate 3-D flanking structures and demonstrate how flanking structures vary with viscosity, 3-D shape and orientation of cutting element, and finite strains. The following example simulations shows the how different flanking structure might develop around a rock element depending upon its intial orientation.

|Flanking Structure 1 |Flanking Structure 2 | Flanking Structure 3| 
|:-:|:-:|:-:|
|![](/media/Media1.gif)|![](/media/Media2.gif)|![](/media/Media3.gif)|

\
For more info, refer to my thesis [here](https://ir.lib.uwo.ca/etd/7763/)
\
Code: [https://github.com/ankibues/MOPLA_Application_Matlab/tree/master/Flanking%20Structure%20Investigation/Matlab%20files](https://github.com/ankibues/MOPLA_Application_Matlab/tree/master/Flanking%20Structure%20Investigation/Matlab%20files)

## Working at YuJa:

### 1. Compliance Project Management
Over the past one and a half year, I have worked on many compliance projects at YuJa. Compliance simply means making sure that the software and software development practices are in accordance to relevant industry standards, such as accessibility, security, interoperability, etc. For this purpose, I have facilitated audits like:

* [SOC-2 and SOC-3](https://www.aicpa.org/resources/landing/soc-2-and-soc-3)
* [HIPAA](https://www.hhs.gov/hipaa/for-professionals/index.html)
* 1EdTech (Formerly known as IMS Global) [LTI Advantage](http://www.imsglobal.org/lti-advantage-overview) and [Caliper Analytics](http://www.imsglobal.org/activity/caliper)

And maintained documentations such as:
* [HECVAT](https://library.educause.edu/resources/2020/4/higher-education-community-vendor-assessment-toolkit) for assessing security risks in cloud services 
* [VPAT](https://www.itic.org/policy/accessibility/vpat) for accessibility reports


### 2. Automation Testing Using Selenium Framework
Over the past one and a half year, I have been working as a Quality Assurance Engineer at YuJa. With manual testing of software and hardware application already in practice, last year we decided to switch to automation to meet the growing needs of testing at YuJa. We have been developing automated test cases for [YuJa EVP](https://www.yuja.com/show/), which is a web-based platform that enables educational institutions to store, manage, distribute and stream media content. 
\
\
We use [Selenium](https://www.selenium.dev/) based [TestNg](https://testng.org/doc/) framework in Java for automating the test scenarios such as uploading video/audio files, perrform certain types of actions on media files, creating different types of users, etc. 
