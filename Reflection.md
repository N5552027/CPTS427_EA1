# Activity Description

For EA 1, I participated in the Washington State University CrimsonCode Hackathon. The event was held on
February 21st, 2026 and lasted until February 22nd, 2026. During the project, I worked with three people: Calvin 
Jamieson Mansker, Calvin Tallent, and Owen Moore. During the Hackathon, we reinvented the Ring Doorbell Camera system, utilizing the Raspberry Pi Zero 2W and Raspberry Pi Cam 3 Wide NoIR Module and YOLO AI models to detect when a person is in frame and tie identities to faces. 

# Technical Description
The decisions that we made during the event were about what features do we need to drop if we wanted to remain on time with the end of the hackathon. During the hackathon, we struggled with moving the facial recognition model to the application and training the AI model for facial recognition took a while due to the queue for the Kamiak HPC Cluster. I kept a good track of all core features of the app and introduced timelines and ideas to meet and created fallback plans if it seemed like a feature was not ready by certain deadlines. 

# Contributions
During the Hackathon, I helped with the creation of the AI model with Calvin Tallent and bug-tested the Flask Python application with Jamieson and Owen where the AI model displayed the notifications to an admin user. For the AI model, I helped create datasets to recognize everyone within our friend group and asked a few people at the hackathon if they were willing to take photos to add to the dataset.

# Quality Assesment
At the end of the event, I believe that we had a good working product albeit we did not have the time to introduce the facial recognition AI model to the applicaiton due to Python version incompatibility issues. At the end of the hackathon, a lot of us agreed that we could have had a more fleshed out application and hardware appliance if more time was provided for the hackathon. I believe that we would have still approached the theme of the hackathon (Reinventing the Wheel) with the same product, however, we would likely change the order of how we approached the tasks to make our Ring Doorbell Camera. 

# Notes and Links
When I did bug-testing with Owen and Jamieson, I often found the bug on my computer and pointed out the issues to fix on their computer. This was to minimize the amount of merge conflicts and interferences while developing both the AI models and the web application. Also, all of the code used for the application cannot be uploaded to this repository, the AI models are too big and there's a lot of dependencies. Please see the GitHub Repo and Devpost Linked below. 

[Devpost link](https://devpost.com/software/ring-sgtkoh)
[GitHub link](https://github.com/Tallented-Code-bot/CrimsonCode-2026/tree/main)
