
# Master Thesis for Robotics Engineering
Repository for latex files for Master Thesis

**Thesis pdf**: [Thesis](https://github.com/torydebra/Master_Thesis_Robotic/blob/master/thesis.pdf)  
**Presentation for thesis defense**: [Presentation](https://github.com/torydebra/Master_Thesis_Robotic/blob/master/presentation.pdf)  
**Source Code**: [Code Repository](https://github.com/torydebra/AUV-Coop-Assembly)

### Thesis Abstract
Robotics is spreading in all the relevant sectors of the human life. The importance of studying this field is confirmed by all the various applications where robots are used: exploration of space and sea, industry, healthcare, transportation and so on. This thesis aims to improve the current state of the art in a particular field: Underwater Robotics. Currently, the research in this area focuses on improving robots capabilities to make them more and more efficient in performing missions autonomously. A particular advancement is towards the cooperation between multiple agents. With cooperation the robotics systems can perform more and more difficult tasks, such as carrying a long and heavy object in an unstructured environment. 
   
Specifically, the problem addressed is an \textit{assembly} one known as the *peg-in-hole* task. In this case, two autonomous manipulators must carry *cooperatively* (at kinematic level) a *peg* and must insert it into an *hole* fixed in the environment. Even if the *peg-in-hole* is a well-known problem, there are no specific studies related to the use of two different autonomous manipulators, especially in underwater scenarios. Among all the possible investigations towards the problem, this work focuses mainly on the kinematic control of the robots. The methods used are part of the Task Priority Inverse Kinematics (TPIK) approach, with a cooperation scheme that permits to exchange as less information as possible between the agents (that is really important being water a big impediment for communication). A force-torque sensor is exploited at kinematic level to help the insertion phase. The results show how the TPIK and the chosen cooperation scheme can be used for the stated problem. The simulated experiments done consider little errors in the hole's pose, that still permit to insert the *peg* but with a lot of frictions and possible stucks. It is shown how can be possible to improve (thanks to the data provided by the force-torque sensor) the insertion phase performed by the two manipulators in presence of these errors.    

Another part of the thesis deals with computer vision algorithms: a third robot exploits  particular methods to estimate the *hole*'s pose. Different techniques are compared to *detect* and to *track* the *hole*, considering the errors they provide in the pose's estimation.    

Even if the problem is simplified (due to its complexity), this thesis could help further works. The focus is on the particular problem stated, but the methods and tools exploited can be useful also for other applications, not only underwater-related. 

