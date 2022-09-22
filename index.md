# Federated Learning for Healthcare

Welcome to the Federated Learning tutorial that will be run in conjunction with the [MICCAI](https://conferences.miccai.org/2022/en/) conference!

Federated Learning (FL) is increasingly important in privacy sensitive domains, such as healthcare, where sharing of private/patient data is a barrier to building models that generalize well in the real world and minimize bias.  

In 2021, we led the largest real world federation, with a network of 59 healthcare institutions around the world. Furthermore, leveraging the collaborators of this real-world FL initiative, we led the first ever FL challenge, focusing on the tumor segmentation task, called [The FeTS 2021 challenge](https://miccai2021.fets.ai/). Taking into consideration the value and the interest of the community in this new paradigm for data private multi-institutional collaborations and building upon our experience, we organize this tutorial on FL for healthcare.

The tutorial will teach you how to use state-of-the-art open-source Python library for Federated Learning [OpenFL](https://github.com/intel/openfl).

## When and Where?

September 22nd from 11:50 to 15:20 (SGT time)

Sign up as a virtual tutorial attendee until the day of the event at the [MICCAI Registration Page](https://conferences.miccai.org/2022/en/REGISTRATION.html)

## Organizing Committee 

- Ujjwal Baid, University of Pennsylvania.
- Spyridon Bakas, University of Pennsylvania.
- Patrick Foley, Intel Corporation.
- Sarthak Pati, University of Pennsylvania.
- Prashant Shah, Intel Corporation.
- Mansi Sharma, Intel Corporation.
- Micah Sheller, Intel Corporation.
- Karan Shah, Intel Corporation.

## Tutorial Description

The aim of this tutorial is to facilitate education on how to perform Federated Learning on both simulated and realworld studies. Tutorial structure focuses on specific clearly indicated parts for beginners and for more advanced attendees. Data scientists of different medical imaging communities (e.g., radiology, pathology) are considered during this tutorial on the opportunities and challenges in developing and using FL fortraining Al models acrossinstitutions using privacy preserving techniques. We plan on covering a spectrum of techniques, from software-based approaches that can be considered a method or a metric (e.g., differential privacy), to hardware-based trusted execution computing environments (TEEs).

The motivation for the tutorial is driven by the need to train and validate deep learning models across data silos, to create models that gain knowledge from diverse patient populations and hence generalize well, mitigate bias, and pave the way towards addressing health disparities.

## Preliminary program

### Part I (45 minutes, environment setup)
- Get access to the Google Colab enviroment

### Part II (45 minutes, lecture based)
- Introduction to FL
- Considerations for FL, based on what we learned from: 
  1. The largest known real-world global federation [FeTS](https://www.fets.ai/), and
  2. The first ever proposal challenge on federated learning [MICCAI 2021 FeTS challenge](https://miccai2021.fets.ai/).

### Part III (~2h, Hands on)
- Hands-on and interactive tutorial on simulating federations and training various segmentation and classification models, while taking into account numerous considerations (including but not limited to a) data size across collaborators, b) network delays in sharing model weights).

Data Scientists and Computational Scientists attending this tutorial will be able to adapt their existing centralized algorithms to a federated architecture or build new models. Non-data scientists (e.g., more clinically-oriented attendees of the CLINICAI sessions) will learn about both technical and non-technical considerations setting up federations for training medical Al models. Importantly, attendees will also understand the privacy and security attack vectors and mitigations when using FL.

## Speakers
- Spyridon Bakas, Ph.D., is an Assistant Professor at the University of Pennsylvania, focusing on computational algorithms for oncological imaging, towards improving the clinical practice.

- Patrick Foley is a Senior Deep Learning (DL) Software Engineer at Intel and Lead Architect of OpenFL, an open-source library for FL.

- Mansi Sharma is a Deep Learning (DL) Software Engineer at Intel 
and a developer of OpenFL, an open-source library for FL.

- Karan Shah is an Applied Machine Learning Engineer at Intel and a developer of OpenFL. His interests span Deep Learning, Optimization Theory, Statistics and Cosmology.

- Sarthak Pati, M.Sc., is a Sr. Application Developer at UPenn. He focuses on ML, distributed, and privacy-protected algorithms for healthcare, and currently leads the R&D of the FeTS platform.

### Format

Half day (afternoon), Hands-on

## Proceedings

In favor of open science, transparency, and further communicating the information presented during the tutorial beyond its actual lifecycle during MICCAI 2021, we intend to produce tutorial notes and be part of the MICCAI satellite event proceedings.
