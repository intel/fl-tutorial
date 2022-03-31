## Federated Learning for Healthcare

Wellcome to the Federated Learning tutorial that will be run in conjunction with the [MICCAI](https://conferences.miccai.org/2022/en/) conference!

Federated Learning (FL) is increasingly important in privacy sensitive domains, such as healthcare, where sharing of private/patient data is barrier to building models that generalize well in the real world and minimize bias.  

In 2021, we have led the largest real world federation, with a network of 59 healthcare institutions around the world. Furthermore, leveraging the collaborators of this real-world FL initiative, we led the first ever FL challenge, focusing on the task of tumor segmentation [The FeTS 2021 challenge](https://miccai2021.fets.ai/). Taking into consideration the value and the interest of our community in this new paradigm for data private multi-institutional collaborations, and also building upon our experience, we invite you to this tutorial on FL for healthcare.

The tutorial will teach you how to use state-of-the-art open-source Python library for Federated Learning [OpenFL](https://github.com/intel/openfl).

## Organizing Committee 

- David Austin, Intel Corporation.
- Spyridon Bakas, University of Pennsylvania.
- Patrick Foley, Intel Corporation.
- Alexey Gruzdev,Intel Corporation.
- Sarthak Pati, University of Pennsylvania.
- Olga Perepelkina, Intel Corporation.
- Prashant Shah, Intel Corporation.
- Micah Sheller, Intel Corporation.

## Tutorial Description

The aim of this tutorial is to facilitate education on how to perform federated learning on both simulated and realworld studies. Tutorial structure focuses on specific clearly indicated parts for beginners and for more advanced attendees. Data scientists of different medical imaging communities (e.g., radiology, pathology) are considered during this tutorial on the opportunities and challenges in developing and using FL fortraining Al models acrossinstitutions using privacy preserving techniques. We plan on covering a spectrum of techniques, from software-based approaches that can be considered a method or a metric (e.g., differential privacy), to hardware-based trusted execution computing environments (TEEs).

The motivation for the tutorial is driven by the need to train and validate deep learning models across data silos, to create models that gain knowledge from diverse patient populations and hence generalize well, mitigate bias, and pave the way towards addressing health disparities.

### Preliminary program

#### Part I (2 first hours — lecture based)
- Introduction to FL
- Considerations for FL, based on what we learned from: i) the largest know nreal-world global federation [FeTS](https://www.fets.ai/), and, ii) the first ever proposal challenge on federated learning [MICCAI 2021 FeTS challenge](https://miccai2021.fets.ai/).

#### Part II (2 second hours — Hands on)
- Hands-on and interactive tutorial on simulating federations and training various segmentation and classification models, while taking into account numerous considerations (including but not limited to a) data size across collaborators, b) network delays in sharing model weights).

The data scientists and computational scientists that attend the tutorial will be able to adapt their existing centralized algorithms to a federated architecture or build new models. Non-data scientists (e.g., more clinically-oriented attendees of the CLINICAI sessions) will learn about both technical and non-technical considerations setting up federations for training medical Al models. Importantly attendees will also understand the privacy and security attack vectors and mitigations when using FL.

### Speakers

- Spyridon Bakas, Ph.D., is an Assistant Professor at the University of Pennsylvania, focusing on computational algorithms for oncological imaging, towards improving the clinical practice.

- Patrick Foley is a senior deep learning (DL) software engineer at Intel and lead architect of OpenFL, an open-source library for FL.

- Olga Perepelkina, Ph.D., is a AI Product Manager at Intel, an Assistant Professor at Higher School of Economics, Industrial Adviser at University of Glasgow. Olga is leading product strategy of OpenFL development.

- Alexey Gruzdev is Al Software Engineering Manager at Intel, leading group of engineers developing OpenFL. Prior to this role, Alexey was a DL Algorithm developer focusing on Computer Vision, in the OpenVINO project. Alexey holds a master’s degree in Computer Science from Higher School of Economics.

- Mansi Sharma is a deep learning (DL) software engineer at Intel and a developer of OpenFL, an open-source library for FL.

- Sarthak Pati, M.Sc., is a Sr Application Developer at the UPenn. He focuses on ML, distributed, and privacy-protected algorithms for healthcare, and currently leads the R&D of the FeTS platform.

### Format

Half day (afternoon), Hands-on

### Proceedings

In favor of open science, transparency, and further communicating the information presented during the tutorial beyond its actual lifecycle during MICCAI 2021, we intend to produce tutorial notes and be part of the MICCAI satellite event proceedings.
