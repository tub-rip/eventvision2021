![imagen](images/CVPRW2021-banner.jpg)

**June 19, 2021, Saturday. 1st day of CVPR**. Virtual workshop.  
Starts at **10 am [Eastern Time](https://time.is/ET)**;  4 pm [Europe Time](https://time.is/CET).  
Held in conjunction with the [IEEE Conference on Computer Vision and Pattern Recognition](http://cvpr2021.thecvf.com/) 2021.

**Welcome to the Third International Workshop on Event-Based Vision!**  

## Objectives

<div style="text-align: justify">
This workshop is dedicated to event-based cameras, smart cameras, and algorithms processing data from these sensors. Event-based cameras are bio-inspired sensors with the key advantages of microsecond temporal resolution, low latency, very high dynamic range, and low power consumption. Because of these advantages, event-based cameras open frontiers that are unthinkable with standard frame-based cameras (which have been the main sensing technology of the past 60 years). These revolutionary sensors enable the design of a new class of algorithms to track a baseball in the moonlight, build a flying robot with the agility of a fly, and perform structure from motion in challenging lighting conditions and at remarkable speeds. These sensors became commercially available in 2008 and are slowly being adopted in computer vision and robotics. In recent years they have received attention from large companies, e.g. the event-sensor company Prophesee collaborated with Intel and Bosch on a high spatial resolution sensor, Samsung announced mass production of a sensor to be used on hand-held devices, and they have been used in various applications on neuromorphic chips such as IBM’s TrueNorth and Intel’s Loihi. The workshop also considers novel vision sensors, such as pixel processor arrays (PPAs), that perform massively parallel processing near the image plane. Because early vision computations are carried out on-sensor, the resulting systems have high speed and low-power consumption, enabling new embedded vision applications in areas such as robotics, AR/VR, automotive, gaming, surveillance, etc. This workshop will cover the sensing hardware, as well as the processing and learning methods needed to take advantage of the above-mentioned novel cameras.
</div>

## Topics Covered
- Event-based / neuromorphic vision.
- Algorithms: visual odometry, SLAM, 3D reconstruction, optical flow estimation, image intensity reconstruction, recognition, stereo depth reconstruction, feature/object detection, tracking, calibration, sensor fusion (video synthesis, visual-inertial odometry, etc.).
- Model-based, embedded, or learning approaches.
- Event-based signal processing, representation, control, bandwidth control.
- Event-based active vision, event-based sensorimotor integration.
- Event camera datasets and/or simulators.
- Applications in: robotics (navigation, manipulation, drones...), automotive, IoT, AR/VR, space science, inspection, surveillance, crowd counting, physics, biology.
- Near-focal plane processing, such as pixel processor arrays - PPAs (e.g., SCAMP sensor).
- Biologically-inspired vision and smart cameras.
- Novel hardware (cameras, neuromorphic processors, etc.) and/or software platforms.
- New trends and challenges in event-based and/or biologically-inspired vision (SNNs, etc.).
- Event-based vision for computational photography.
- A longer list of related topics is available in the table of content of the [List of Event-based Vision Resources](https://github.com/uzh-rpg/event-based_vision_resources) 

<!-- ## Invited Speakers  
TBA
-->

## List of Talks and Speakers
<details>
<summary>
&#9632; <a href="https://engineering.jhu.edu/csms/team/rec/">Ralph Etienne-Cummings (Johns Hopkins Univ., USA)</a><br>
[Click] <span style="color:tomato;"><b>Learning Spatiotemporal Filters to Track Event-Based Visual Saliency</b></span>.
</summary>
<p>
<b>Abstract</b>: Uncovering the nuances behind visual saliency, or the tendency to gaze in a particular direction or toward a specific object, is critical in understanding what and why the human mind focuses on specific features in a field of vision. There are a wide variety of applications in which saliency would provide significant steps forward, such as: tele-tourism, high-accuracy drone cameras, live-data analysis for traffic, and criminal investigations. More specifically, visual saliency in the form of event-based information is particularly attractive because event-based data encodes information in a more compressed and power efficient manner. In this workshop, we discuss an unsupervised learning scheme to learn spatiotemporal filters that can identify and track salient features in an event-based data stream. We show how decision trees and threshold tracking can learn interesting features that are not easily discernable by the human eye, and further compare our findings to a ground-truth human-based saliency experiment with event-based data. We compare hand-crafted versus learned filters with that of the ground-truth human-based data and stress the need for the first event-based visual saliency ground-truth dataset.</p> 

<p><b>Biography</b>: Ralph Etienne-Cummings, an IEEE Fellow, received his B. Sc. in physics, 1988, from Lincoln University, Pennsylvania.  He completed his M.S.E.E ('91). and Ph.D. ('94) in electrical engineering at the University of Pennsylvania.  Currently, Dr. Etienne-Cummings is a Professor and previous (7/2014 – 7/2020) Chairman of Department of Electrical and Computer Engineering at Johns Hopkins University (JHU).  He was the founding Director of the Institute of Neuromorphic Engineering. He has served as Chairman of various IEEE Circuits and Systems (CAS) Technical Committees and was elected as a member of CAS Board of Governors.  He also serves on numerous editorial boards and was recently appointed Deputy Editor in Chief for the IEEE Transactions on Biomedical Circuits and Systems.  He is the recipient of the NSF’s Career and Office of Naval Research Young Investigator Program Awards, among many other recognitions.  He was a Visiting African Fellow at U. Cape Town, Fulbright Fellowship Grantee, Eminent Visiting Scholar at U. Western Sydney and has also won numerous publication awards, most recently the 2012 Most Outstanding Paper of the IEEE Transaction on Neural Systems and Rehabilitation Engineering.  He was also recognized as a "ScienceMaker", an African American history archive and for the "Indispensable Roles of African Americans at JHU" exhibit. He has published over 250 peer reviewed article, 11 books/chapters and holds 20 patents/applications on his work.
</p>
</details>
<details>
<summary>
&#9632; <a href="http://www2.imse-cnm.csic.es/~bernabe/">Bernabé Linares-Barranco (IMSE-CNM, CSIC and Univ. Seville, Spain)</a><br>
[Click] <span style="color:tomato;"><b>Event-driven convolution based processing</b></span>. 
  <b><a href="https://youtu.be/JyaNT69GWO0"><span style="color:#159957;">Video</span></a>, 
  <a href="https://tub-rip.github.io/eventvision2021/slides/CVPRW21_Bernabe_LinaresBarranco.pdf"><span style="color:#159957;">Slides</span></a></b>
</summary>
<p>
<b>Abstract</b>: We will review some of the event-driven hardware developments in which our lab has been involved, covering from sensitive-DVS to event-driven convolutions on dedicated ASICs, FPGAs, and the SpiNNaker platform, with applications in object recognition or stereo vision. We will show how to train event-driven convnets to minimize the number of required spikes, reducing energy consumption for the same recognition tasks. Additionally, we will present some results on a type of spike-timing-dependent-plasticity, which uses only binary weights combined with stochasticity, and which results in hardware that requires less hardware and energy resources for the same accuracy.</p>

<p><b>Biography</b>: Bernabé Linares-Barranco received a first Ph.D. degree in high-frequency OTA-C oscillator design in June 1990 from the University of Seville, Spain, and a second Ph.D deegree in analog neural network design in December 1991 from Texas A&M University, College-Station, USA.
Since June 1991, he has been a Tenured Scientist at the "Instituto de Microelectrónica deSevilla". From September 1996 to August 1997, he was on sabbatical stay at the Department of Electrical and Computer Engineering of the Johns Hopkins University. During Spring 2002 he was Visiting Associate Professor at the Electrical Engineering Department of Texas A&M University, College-Station, USA. In January 2003 he was promoted to Tenured Researcher, and in January 2004 to Full Professor. Since February 2018, he is the Director of the "Insitituto de Microelectrónica de Sevilla".</p>

<p>He has been involved with circuit design for telecommunication circuits, VLSI emulators of biological neurons, VLSI neural based pattern recognition systems, hearing aids, precision circuit design for instrumentation equipment, VLSI transistor mismatch parameters characterization, and over the past 20 years has been deeply involved with neuromorphic spiking circuits and systems, with strong emphasis on vision and exploiting nanoscale memristive devices for learning. He is co-founder of two start-ups, Prophesee SA (www.prophesee.ai) and GrAI-Matter-Labs SAS (www.graimatterlabs.ai), both on neuromorphic hardware. He has been Associate Editor of the IEEE Transactions on Circuits and Systems Part II, IEEE Transactions on Neural Networks, and "Frontiers in Neuromorphic Engineering". Since Jan. 2021 he is Chief Editor of "Frontiers in Neuromorphic Engineering". He is an IEEE Fellow since January 2010. He is listed among the Standford top 2% most world-wide cited scientist in Electrical and Electronic Engineering (top 0.62%).
</p>
</details>
<details>
<summary>
&#9632; <a href="https://compphotolab.northwestern.edu/">Oliver Cossairt (Northwestern Univ., USA)</a><br>
[Click] <span style="color:tomato;"><b>Hardware and Algorithm Co-design with Event Sensors</b></span>.
</summary>
<p>
<b>Abstract</b>: In this talk I will provide an overview of our research developing hardware/software co-designs with event sensors, focusing on methods to fuse together information acquired from multiple sensing modalities for task-specific processing such as image reconstruction, object detection, and tracking. I will discuss three main thrusts of research, 1) extracting 3D information from event data using structured light, and inverse rendering, 2), fusing event sensor data together with conventional frame-based camera images, and 3) a feedback-driven, chip-host architecture built for lightweight on-camera processing equipped with novel data compression algorithms for high-bandwidth, task-specific chip/host communication. Finally, I will wrap up by briefly discussing our current work in-progress developing spiking-based neural network (SNN) algorithms to leverage similar co-design principles.</p>

<p><b>Biography</b>: Oliver Cossairt is Associate Professor in the Computer Science (CS) and Electrical and Computer Engineering (ECE) departments at Northwestern University. Prof. Cossairt is director of the Computational Photography Laboratory (CPL) at Northwestern University (compphotolab.northwestern.edu), whose research consists of a diverse portfolio, ranging in topics from optics/photonics, computer graphics, computer vision, machine learning and image processing. The general goal of CPL is to develop imaging hardware and algorithms that can be applied across a broad range of physical scales, from nanometer to astronomical. This includes active projects on 3D nano-tomography, computational microscopy , cultural heritage imaging analysis of paintings, structured light and ToF 3D-scanning of macroscopic scenes, de-scattering through fog for remote sensing, and coded aperture imaging for astronomy. Prof. Cossairt has garnered funding from numerous corporate sponsorships (Google, Rambus, Samsung, Omron, Oculus/Facebook, Zoloz/Alibaba) and federal funding agencies (ONR, NIH, DOE, DARPA, IARPA, NSF CAREER Award).
</p>
</details>
<details>
<summary>
&#9632; <a href="https://www.westernsydney.edu.au/marcs/our_team/researchers/gregory_cohen">Gregory Cohen (Western Sydney Univ., Australia)</a><br>
[Click] <span style="color:tomato;"><b>Neuromorphic Vision Applications: From Robotic Foosball to Tracking Space Junk</b></span>.
</summary>
<p>
<b>Abstract</b>: Neuromorphic event-based cameras offer a different way to approach visual imaging tasks and really excel at problems in which they can leverage the unique way that the hardware works. This talk will introduce a range of applications for neuromorphic cameras ranging from tracking space junk and satellites to their applications in robotic foosball and pinball. We will demonstrate real-world results from space tracking with event-based cameras, and introduce our Astrosite mobile neuromorphic telescope observatories - built specifically to leverage the benefits of neuromorphic space imaging. We will describe some of the problems with benchmarking and comparing neuromorphic systems, and show how robotic foosball and robotic pinball machines may be a great way to demonstrate the benefits of neuromorphic systems.</p>

<p><b>Biography</b>: Gregory Cohen is an Associate Professor in Neuromorphic Systems at the International Centre for Neuromorphic Systems (ICNS) at Western Sydney University and program lead for neuromorphic algorithms and space applications. Prior to returning to research from industry, he worked in several start-ups and established engineering and consulting firms including working as a consulting engineer in the field of large-scale HVAC from 2007 to 2009, as an electronic design engineer from 2009 to 2011, and as an expert consultant for Kaiser Economic Development Practice in 2012. He is a pioneer of event-based and neuromorphic sensing for space imaging applications and his research interests include unsupervised feature extraction, bio-inspired machine learning, and neuromorphic computation systems. Greg holds a BSc(Eng), MSc(Eng), and BCom(Hons) from the University of Cape Town, South Africa and a joint PhD from Western Sydney University, Sydney, Australia and the University of Pierre and Marie Curie in Paris, France.
</p>
</details>
<details>
<summary>
&#9632; <a href="http://www.bene-guido.eu/wordpress/">Guido de Croon (TU Delft, Netherlands)</a><br>
[Click] <span style="color:tomato;"><b>Event-based vision and processing for tiny drones</b></span>.
</summary>
<p>
<b>Abstract</b>: Event-based vision and processing hold an important promise for creating autonomous tiny drones. Both promise to be light weight and highly energy efficient, while allowing for high-speed perception and control. For tiny drones, these characteristics are essential, as they are extremely restricted in terms of size, weight and power, while at smaller scales drones become even more agile. In my talk, I will present our work on developing event-based perception and control for tiny autonomous drones. I will delve into the approach we followed for having spiking neural networks learn visual tasks such as optical flow estimation. Furthermore, I will explain our ongoing effort to integrate these networks in autonomously flying drones.</p>

<p><b>Biography</b>: Guido de Croon Received his M.Sc. and Ph.D. in the field of Artificial Intelligence (AI) at Maastricht University, the Netherlands. His research interest lies with computationally efficient, bio-inspired algorithms for robot autonomy, with an emphasis on computer vision. Since 2008 he has worked on algorithms for achieving autonomous flight with small and light-weight flying robots, such as the DelFly flapping wing MAV. In 2011-2012, he was a research fellow in the Advanced Concepts Team of the European Space Agency, where he studied topics such as optical flow based control algorithms for extraterrestrial landing scenarios. After his return at TU Delft, his work has included fully autonomous flight of a 20-gram DelFly, a new theory on active distance perception with optical flow, and a swarm of tiny drones able to explore unknown environments. Currently, he is Full Professor at TU Delft and scientific lead of the Micro Air Vehicle lab (MAVLab) of Delft University of Technology.
</p>
</details>
<details>
<summary>
&#9632; <a href="https://www.kynaneng.com/">Kynan Eng (CEO of iniVation, Switzerland)</a><br>
[Click] <span style="color:tomato;"><b>High-Performance Neuromorphic Vision: From Core Technologies to Applications</b></span>.
</summary>
<p>
<b>Abstract</b>: Neuromorphic event-based vision can enable new levels of enhanced vision sensing in situations where current technologies fail. In this presentation, we provide an overview of our technology, our DV open developer environment, and some real-world application examples.</p>

<p><b>Biography</b>: Kynan Eng is co-founder and CEO at iniVation. Prior to co-founding iniVation, he was PI of a research group at the Institute of Neuroinformatics at the University of Zurich and ETH Zurich. He also worked in the past at ABB and Alstom. He holds a PhD from the ETH Zurich, and degrees in computer science and mechanical engineering from Monash University.
</p>
</details>
<details>
<summary>
&#9632; <a href="https://www3.ntu.edu.sg/home/eechenss/">Shoushun Chen (Founder of CelePixel. Will Semiconductor, China)</a><br>
[Click] <span style="color:tomato;"><b>Development of Event-based Sensor and Applications</b></span>.
</summary>
<p>
<b>Abstract</b>: Event cameras have demonstrated great potential to solve problems in many applications such as robotics, mobile, automotive, gaming and computer vision etc. This talk will introduce the recent development by CelePixel. We will first revisit the pixel architecture, then discuss on the limiting factors of the temporal resolution which could be applicable to other event sensors, finally we will introduce an efficient event-based HCI framework.</p>

<p><b>Biography</b>: Dr. Shoushun Chen received his B.S, M.E and Ph.D degrees in 2000, 2003 and 2007, respectively. He held a postdoc research fellowship in Hong Kong University of Science and Technology for one year after graduation. From Feb 2008 to May 2009 he was a postdoc research associate at Yale University. In July 2009, he joined Nanyang Technological University as a faculty. Dr. Chen is a founder of CelePixel Technology, which is now part of Will Semiconductor.</p>

<p>Dr. Chen is a senior member of IEEE. He serves as a member, Chair-Elect of Sensory Systems Technical Committee, IEEE Circuits and Systems Society (CASS); Associate Editor of IEEE Sensors Journal; Program Director (Smart Sensors) of VIRTUS, IC Design Centre of Excellence; Regular reviewer for a number of international conferences and journals such as TVLSI, TCAS-I/II, TBioCAS, TPAMI, Sensors, TCSVT, etc.</p> 

<p>His research interests include Smart image sensor and imaging system, remote sensing imaging system and mixed signal integrated circuits.
</p>
</details>
<details>
<summary>
&#9632; <a href="https://www.linkedin.com/in/christian-br%C3%A4ndli-b1418a76/">Christian Brändli (CEO of Sony Advanced Visual Sensing AG, Switzerland)</a><br>
[Click] <span style="color:tomato;"><b>Event-Based Computer Vision At Sony AVS</b></span>.
</summary>
<p>
<b>Abstract</b>: Sony Advanced Visual Sensing is a research center of Sony Semiconductor Solutions, the world leader in image sensors. With a long history in the field, Sony AVS works on event-based vision sensors (EVS) and computer vision algorithms. First, the talk will introduce some core principles of event-based processing which have been gathered over the years. The second part of the talk will then highlight some recent applications of event-based algorithms developed at Sony AVS.</p>

<p><b>Biography</b>: Christian Brändli did his PhD at ETH Zurich in the research group of EVS pioneer Prof. Tobi Delbruck at the Institute of Neuroinformatics where he contributed to early event-based vision sensors and algorithms. After his graduation he co-founded the startup Insightness which developed the first stacked event-based image sensor and benchmark-beating algorithms. After the Insightness team joined Sony in 2019 he became the CEO of Sony AVS.
</p>
</details>
<details>
<summary>
&#9632; <a href="https://abisulco.com/about.html">Anthony Bisulco, Daewon Lee, Daniel D. Lee, Volkan Isler (Samsung AI Center NY, USA)</a><br>
[Click] <span style="color:tomato;"><b>High Speed Perception-Action Systems with Event-Based Cameras</b></span>.
</summary>
<p>
<b>Abstract</b>: High-speed perception-action systems are important for mobile robot systems to react in dynamic environments. Event-based cameras have attractive properties for these systems such as high dynamic range, efficient energy use and low latency sensing. At Samsung’s AI Center in NY (SAIC-NY) we have been working on novel DVS-based systems and algorithms to capitalize on these properties. Our previous work in this domain includes a near-chip architecture for low-complexity pedestrian detection on bandwidth-limited networks. In this talk, we will present an overview of our most recent work where the goal is to create high speed perception-action systems for collision avoidance.</p>
  
<p>The introduction of robots to kitchen environments will require avoidance of incoming high-speed moving obstacles such as falling spices, liquids or sharp objects that they should avoid. Our experimental test-bed to explore these systems consists of shooting a toy-dart(22m/s) at a target located on a linear-actuator with a static event-based camera observing the motion head-on. During the dart’s flight, we developed a perception system to extract time to collision and impact location on the camera plane from the event-stream  for triggering a collision avoidance system. The entire dart flight is around 150ms, hence we also analyze the various latencies of the perception-action system and system tradeoffs for collision avoidance. As a result of this analysis, we found an initial observability latency of the dart up to 100ms, which resulted in the use of a telescopic lens to reduce this delay to 20ms. A benefit of using an event-camera in this scenario as opposed to a 60Hz frame-based imager is that the perception process can acquire ~100ms of in-focus events as opposed to one or two motion blurred frames. Inspecting our perception performance using event-data, we established our perception system to estimate time to collision within 24.73% and impact location within 18.4mm on our testing dataset. Overall, our perception system and minimal system latency allows our system to successfully avoid a fast incoming toy dart.</p>

<p><b>Biography</b>: Anthony Bisulco is a researcher at the Samsung Artificial Intelligence Center New York, where he works on projects at the intersection of robotics, machine learning and neuroscience. Anthony received a Master of Engineering degree from Cornell University and a Bachelor of Science degree from Northeastern University. Anthony has performed research in a variety of fields at the European Center for Nuclear Research, Sensing, Imaging, Control, and Actuation Laboratory, Google, Massachusetts Institute of Technology Lincoln Laboratories and Brookhaven National Laboratory.
</p>
</details>

- [Ryad Benosman (Univ. Pittsburgh, USA)](https://mirm-pitt.net/our-people/faculty-staff-bios/ryad-benosman-phd/)
- [Kwabena Boahen (Stanford, USA)](http://web.stanford.edu/group/brainsinsilicon/people.html)
- [Chiara Bartolozzi (IIT, Italy)](https://www.iit.it/people/chiara-bartolozzi)
- [Yulia Sandamirskaya (Intel Labs, Germany)](https://www.linkedin.com/in/yulia-sandamirskaya-0076553/)
- [Robert Mahony (Australian National Univ., Australia)](https://cecs.anu.edu.au/people/robert-mahony)
- [Luca Verre (CEO of Prophesee, France)](https://www.linkedin.com/in/luca-verre-71b6a75/?originalSubdomain=fr)


<!-- 
<details>
<summary>
<b>Title</b>, by <a href="">Speaker (Affiliation)</a>
</summary>
<p>
<b>Abstract</b>:
<b>Biography</b>: 
</p>
</details>
-->

## Schedule

The tentative schedule is the following:

1. Session: Neuromorphic cameras and computing.
2. Session: Event-based sensors in computer vision.
3. Session: Algorithms and Architectures.
4. Session: Industrial companies and applications.
5. Final Panel Discussion


## Accepted Papers
- [v2e: From Video Frames to Realistic DVS Events](papers/2021CVPRW_V2E_From_Video_Frames_to_Realistic_DVS_Events.pdf), and [Suppl mat](papers/2021CVPRW_V2E_From_Video_Frames_to_Realistic_DVS_Events_supp.zip)
- [Differentiable Event Stream Simulator for Non-Rigid 3D Tracking](papers/2021CVPRW_Differentiable_Event_Stream_Simulator_for_Non-Rigid_3D_Tracking.pdf), and [Suppl mat](papers/2021CVPRW_Differentiable_Event_Stream_Simulator_for_Non-Rigid_3D_Tracking_supp.pdf)
- [Comparing Representations in Tracking for Event Camera-based SLAM](papers/2021CVPRW_Comparing_Representations_in_Tracking_for_Event_Camera-based_SLAM.pdf)
- [Image Reconstruction from Neuromorphic Event Cameras using Laplacian-Prediction and Poisson Integration with Spiking and Artificial Neural Networks](papers/2021CVPRW_Image_Reconstruction_from_Neuromorphic_Event_Cameras_using_Laplacian-Prediction.pdf)
- [Detecting Stable Keypoints from Events through Image Gradient Prediction](papers/2021CVPRW_Detecting_Stable_Keypoints_from_Events_through_Image_Gradient_Prediction.pdf)
- [EFI-Net: Video Frame Interpolation from Fusion of Events and Frames](papers/2021CVPRW_EFI-Net_Video_Frame_Interpolation_from_Fusion_of_Events_and_Frames.pdf), and [Suppl. mat](papers/2021CVPRW_EFI-Net_Video_Frame_Interpolation_from_Fusion_of_Events_and_Frames_supp.zip)
- [DVS-OUTLAB: A Neuromorphic Event-Based Long Time Monitoring Dataset for Real-World Outdoor Scenarios](papers/2021CVPRW_DVS-OUTLAB_A_Neuromorphic_Event-Based_Long_Time_Monitoring_Dataset.pdf)
- [N-ROD: a Neuromorphic Dataset for Synthetic-to-Real Domain Adaptation](papers/2021CVPRW_N-ROD_A_Neuromorphic_Dataset_for_Synthetic-to-Real_Domain_Adaptation.pdf)
- [Lifting Monocular Events to 3D Human Poses](papers/2021CVPRW_Lifting_Monocular_Events_to_3D_Human_Poses.pdf)
- [A Cortically-inspired Architecture for Event-based Visual Motion Processing: From Design Principles to Real-world Applications](papers/2021CVPRW_A_Cortically-inspired_Architecture_for_Event-based_Visual_Motion_Processing.pdf)
- [Spike timing-based unsupervised learning of orientation, disparity, and motion representations in a spiking neural network](papers/2021CVPRW_Spike_timing-based_unsupervised_learning_of_orientation_disparity_and_motion_representations.pdf), and [Suppl mat](papers/2021CVPRW_Spike_timing-based_unsupervised_learning_of_orientation_disparity_and_motion_representations_supp.pdf)
- [Feedback control of event cameras](papers/2021CVPRW_Feedback_control_of_event_cameras.pdf)
- [How to Calibrate Your Event Camera](papers/2021CVPRW_How_to_Calibrate_Your_Event_Camera.pdf)
- [Live Demonstration: Incremental Motion Estimation for Event-based Cameras by Dispersion Minimisation](papers/2021CVPRW_Live_Demonstration_Incremental_Motion_Estimation_for_Event-based_Cameras_by_Dispersion_Minimisation.pdf)


### Courtesy presentations                 
<div style="text-align: justify">
  We also invite courtesy presentations (short talks) of related papers that are accepted at CVPR main conference or at other conferences. 
  These presentations provide visibility to your work and help to build a community around the topics of the workshop. 
  Please contact the organizers to make arrangements to showcase your work at the workshop.
</div>

## Organizers
- [Guillermo Gallego](http://www.guillermogallego.es), Technische Universität Berlin and Einstein Center Digital Future, Germany.
- [Davide Scaramuzza](http://rpg.ifi.uzh.ch/people_scaramuzza.html), University of Zurich, Switzerland.
- [Kostas Daniilidis](https://www.cis.upenn.edu/~kostas), University of Pennsylvania, USA. 
- [Cornelia Fermüller](http://users.umiacs.umd.edu/~fer), University of Maryland, USA.
- [Davide Migliore](https://www.linkedin.com/in/davidemigliore), Prophesee, France.

## FAQs
<ul>
  <li><b>What is an event camera?</b> Watch this <a href="https://youtu.be/LauQ6LWTkxM">video explanation</a>.</li>
  <li><b>What are possible applications of event cameras?</b> Check the <b><a href="https://arxiv.org/abs/1904.08405">TPAMI 2020 review paper</a></b>.
  </li>
  <li><b>Where can I buy an event camera?</b> From <a href="https://github.com/uzh-rpg/event-based_vision_resources#companies_sftwr"> Inivation, Prophesee, CelePixel, Insightness</a>.</li>
  <li><b>Are there datasets and simulators that I can play with?</b> Yes, <a href="http://rpg.ifi.uzh.ch/davis_data.html">Dataset</a>. <a href="http://rpg.ifi.uzh.ch/esim.html">Simulator</a>. <a href="https://github.com/uzh-rpg/event-based_vision_resources#datasets">More</a>.</li>
  <li><b>Is there any online course about event-based vision?</b> Yes, check this <a href="https://sites.google.com/view/guillermogallego/teaching/event-based-robot-vision"> course at TU Berlin</a>.</li>
  <li><b>What is the SCAMP sensor?</b> Read this <a href="https://personalpages.manchester.ac.uk/staff/p.dudek/scamp/">page explanation</a>.</li>
  <li><b>What are possible applications of the scamp sensor?</b> Some applications can be found <a href="https://personalpages.manchester.ac.uk/staff/p.dudek/scamp/default.htm#Applications">here</a>.</li>
  <li><b>Where can I buy a SCAMP sensor?</b> It is not commercially available. Contact Prof. <a href="https://personalpages.manchester.ac.uk/staff/p.dudek/pdudek.htm">Piotr Dudek</a>.</li>
  <li><b>Where can I find more information?</b> Check out this <a href="https://github.com/uzh-rpg/event-based_vision_resources">List of Event-based Vision Resources</a>.</li>
</ul>

## Previous Related Workshops
<ul>
  <li><a href="https://robotics.sydney.edu.au/icra-workshop/">ICRA 2020 Workshop on Sensing, Estimating and Understanding the Dynamic World. Session on Event-based camera companies iniVation and Prophesee</a>.</li>
  <li><a href="http://rpg.ifi.uzh.ch/CVPR19_event_vision_workshop.html">CVPR 2019 Second International Workshop on Event-based Vision and Smart Cameras</a>.</li>
  <li><a href="https://www.jmartel.net/irosws-home">IROS 2018 Workshop on Unconventional Sensing and Processing for Robotic Visual Perception</a>.</li>
  <li><a href="http://rpg.ifi.uzh.ch/ICRA17_event_vision_workshop.html">ICRA 2017 First International Workshop on Event-based Vision</a>.</li>
  <li><a href="http://innovative-sensing.mit.edu/">ICRA 2015 Workshop on Innovative Sensing for Robotics, with focus on Neuromorphic Sensors</a>.</li>
  <li><a href="http://www.rit.edu/kgcoe/iros15workshop/papers/IROS2015-WASRoP-Invited-04-slides.pdf">Event-Based Vision for High-Speed Robotics (slides)</a> IROS 2015, Workshop on Alternative Sensing for Robot Perception.</li>
  <li><a href="http://telluride.iniforum.ch">The Telluride Neuromorphic Cognition Engineering Workshops</a>.</li>
  <li><a href="http://capocaccia.iniforum.ch">Capo Caccia Workshops toward Cognitive Neuromorphic Engineering</a>.</li>
</ul>
