---
title: Sound and Robotics
subtitle:  UE5 as the platform for Real-World Robotic Sound Design and Interaction
description: UE5 as the platform for Real-World Robotic Sound Design and Interaction
featured_image: /images/demo/demo-landscape.jpg -->
---

## CONCEPT:
The field of robot audio lacks standardization and a unified approach for integrating sound design and speech into physical robots. Roboticists often resort to default methods, relying on built-in sounds or common text-to-speech APIs without exploring alternative options. When composers or sound designers are involved, they typically create audio in a workstation without the ability to rapidly test it on a robot or even in a robot simulation. This lack of a common language for audio implementations hampers iterative and collaborative work, hindering the ability to build upon past innovations. Consequently, the audio aspect of robotics has remained stagnant for the past 50 years, with most approaches being derived from film robots like R2-D2.

While the absence of standardization poses challenges for creators, it is important to note that no easy pipeline currently exists for any creator working on robot audio. The process of developing sounds for a robot typically involves using a separate platform for sound creation and then requiring additional skills to synchronize the audio with the robot. This dependence on multiple individuals during sound development inhibits iterative feedback. User testing often relies on pre-recorded videos or limited groups of users, with minimal variation in the tested sounds.

Recent studies have demonstrated that sound plays a crucial role in how humans perceive robots and can significantly impact the [future of human-robot interactions](http://127.0.0.1:4000/project/shimiandprosody). Manipulating sound can enhance key attributes such as [likeability, perceived intelligence, and trust](https://www.researchgate.net/publication/358198614_Emotional_musical_prosody_for_the_enhancement_of_trust_Audio_design_for_robotic_arm_communication)]. In fact, sound can even alter the perception of a robot's core performance, as evidenced by a study in which participants believed a robot had improved [object-picking capabilities due to sound cues](https://www.frontiersin.org/articles/10.3389/frobt.2021.662355/full). The lack of a comprehensive approach to robot audio represents a significant missing ingredient in shaping the way robots will interact with humans in the future, affecting aspects such as safety, performance, and integration.


## THE PLAN:
To address these challenges and pave the way for the future of sound and robotics, our project aims to develop an open-source plugin within UE5. This plugin will revolutionize the creation and integration of sound in robotics. UE5 offers a wealth of sound possibilities, and our plugin will leverage these capabilities to establish a standardized and versatile platform for robot audio development. By seamlessly integrating Metasounds, our plugin will provide creators with a unified framework for designing, testing, and implementing audio on robots.
The open-source nature of the plugin ensures that it will be accessible to a wide community of developers, fostering collaboration and iterative improvements. We envision a future where sound in robotics becomes an integral and evolving component, enabling safer and more engaging human-robot interactions while empowering creators to explore innovative audio experiences.

## WHY UE5: 
Unreal Engine 5 (UE5) is the ideal platform for our project due to its robust and feature-rich environment. By developing our plugin within UE5, we can seamlessly tap into the existing capabilities of Metasounds and Text-to-Speech (TTS) for sound generation. These built-in tools provide powerful audio creation and manipulation features, allowing for dynamic and interactive sound design. Additionally, UE5's 3D capabilities enable us to spatially position and render audio, creating immersive and realistic auditory experiences. Furthermore, UE5's ability to dynamically change audio based on various variables and mappings opens up a whole new realm of possibilities. Combining these capabilities within our plugin will result in a system that surpasses current approaches to robot audio.

## PHYSICAL ROBOT SYSTEMS AND SIMULATIONS: 
Our plugin will seamlessly integrate with both physical robot systems and simulations. This ensures that creators can develop and test audio designs in realistic environments without the need for constant access to physical robots. By bridging the gap between simulations and real-world implementations, we can accelerate the iterative feedback process and facilitate comprehensive sound development for a wide range of robots.

Our plugin will have the ability to integrate with an extensive array of robots. Through collaborations with Macquarie University, Monash University, and Georgia Tech, we will have access to over 30 robot platforms. This extensive robot collection allows us to test and validate our platform across a diverse range of robotic systems, ensuring compatibility and broad applicability.

## OUR SOLUTION: 
Our project aims to achieve the following goals:
1.	Open-Source Standardized Sound Development for Physical Robots: We will provide an open-source platform that standardizes sound development for robot platforms. This unified framework will enable creators to design, implement, and share audio assets seamlessly.
2.	Simulation Environment for Sound Development: We will create a simulation environment where sound development can occur independently from physical robots. This allows for rapid iteration and experimentation without the limitations of physical access.
3.	Online Testing Platform: Our platform will include an online testing feature that allows for remote evaluation of sounds. This eliminates the need for physical proximity to robots and facilitates large-scale user testing.
4.	Incorporating Robot Music: We will explore the integration of robot music within our platform, enabling creators to compose and implement musical elements specifically tailored for robot interactions.


## TEAM:
Our project will involve four key developers:
-	Richard Savery (PhD Georgia Tech), a current research fellow at Macquarie University, and project lead (3 years)
-	Two PhD students who will focus primarily on this project (3 years each)
-	One UE5 Developer (6 Months)

## TIMELINE:
- Y1 Q1: Conduct initial research and planning, identify key functionalities and requirements. Savery, and PhD students commence
- Y1 Q2: Start development of core functionality, including the open-source plugin and simulation environment. UE5 Developer joins. 
- Y1 Q3: Continuation of core functionality development by PhD students, refining features and addressing technical challenges
- Y1 Q4: Conduct internal testing and gather feedback to refine and improve the platform
- Y2 Q1: Release an online beta version for limited testing, recruit undergraduate music and computer science students to participate in the program, expand platform compatibility with additional robot platforms
- Y2 Q2: Analyze beta testing feedback and make necessary improvements, enhance the user interface and overall user experience
- Y2 Q3: Continue development based on user feedback, optimize performance and stability
- Y2 Q4: Prepare for the full release, conduct thorough testing and bug fixing, finalize documentation and support materials
- Y3 Q1: Launch the full version of the platform, initiate workshops and promotional activities to raise awareness and attract users, foster community engagement
- Y3 Q2: Gather user feedback and iterate on the platform, implement additional features and improvements based on user needs
- Y3 Q3: Expand the workshop program, collaborate with educational institutions and industry partners to further promote adoption and usage of the platform
- Y3 Q4: Conduct a comprehensive evaluation of the project's outcomes, assess the impact and gather insights for future development


## OUTCOMES
We envision our project extending beyond the initial three-year funding period, with the goal of establishing a thriving and sustainable community. To achieve this, we plan to organize workshops and create online resources that foster collaboration, knowledge-sharing, and continuous development of the platform. Macquarie University has expressed its commitment to supporting this initiative, ensuring ongoing institutional support.

1.	Open-Source Plugin: The primary outcome of our project will be the development of an open-source plugin that revolutionizes sound design for robot platforms. This plugin will be freely available to the public, empowering creators worldwide to enhance their robots' audio capabilities.
2.	Robot Integration and Sample Sounds: The plugin will include seamless integration with various robot platforms, providing creators with a diverse range of options for incorporating audio into their robotic systems. Additionally, we will provide a library of sample sounds to inspire and guide users in their audio design process.
Academic Publications:
1.	Sound and Robotics Book: We plan to publish a chapter or section about our plugin and its impact within a sound and robotics book. This publication will contribute to the academic understanding of robot audio and its practical applications.
2.	Conferences: We aim to present our research and findings at relevant conferences in the fields of music, robotics, and games. Sharing our work at these conferences will foster dialogue, gather feedback, and inspire further advancements in the intersection of sound and robotics.
Education Element:
1.	Tutorials and Online Resources: We will develop comprehensive tutorials and online resources to guide users in utilizing the plugin effectively. These resources will provide step-by-step instructions, best practices, and examples, enabling a wide range of creators to engage with the platform.
2.	Workshops and PACE Students: Over the course of three years, we will engage 15 PACE students (Professional and Community Engagement program) from Macquarie University. These students will actively participate in sound design and system utilization, gaining practical experience and contributing to the project's development. Additionally, we will organize regular workshops around Sydney, with a focus on hackathons and teaching participants how to use the platform.


## Example Sound and Robotics Projects by the Dev Team

- [Keirzo](https://www.keirzo.com), a rapping, drumming robot

- [Emotional Musical Prosody](https://richardsavery.com/project/shimiandprosody) an approach to non-linguistic sound for robots

- [Forest](https://richardsavery.com/project/forest) Sound for robotic arms

