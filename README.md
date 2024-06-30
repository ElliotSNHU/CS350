# CS350
Emerging System Architecture and Technology

1. Summarize the project and what problem it was solving.
   - The thermostat project required creation of a task scheduler that is responsible for reading the temperature from the TMP006 sensor on the CCS3220S LaunchXL board. Ambient temperature is displayed in the console along side the setPoint, which simulates a thermostat. If the ambient temp dropped below set temp, the heat, displayed as a 0 for off, 1 for on would change. Finally a timer is used to track, time. 
2. What did you do particularly well?
   - This project went smoothly until I was unable to connect to my device at all. Previous projects did not load and I was running out of options. What I did well was my debugging and research trying to solve this issue. I spent a LOT of time reading documentation, forums, and using Code Composer Studio to try and solve the issue. A solution I found when trying to connect to the device was to launch the program _as_ I plugged the device in. I had zero expectations of this working, because why would it? 
3. Where could you improve?
   - I could have been more efficient with my time. Circumstantially, I was limited in the amount of time I had to work on this project which lead me to attempting the development first and reading documentation when I required it. In a workplace setting, the improvement would be reading the required materials beforehand, which is my standard, but this project is a good reflection point on why I do such things. 
4. What tools and/or resources are you adding to your support network?
   - Online forums have been a lifesaver in certain situations. I could only imagine how difficult debugging an embedded system with the problem I had would have been without any outside input. I eventually found a solution, which is nice, but I also did not fully understand how it helped. It just did. 
5. What skills from this project will be particularly transferable to other projects and/or course work?
   - Understanding embedded systems is a skill that will transfer to any software engineering project. It deepened my knowledge of programming and was good practive in debugging a physical device in tandem with software. 
6. How did you make this project maintainable, readable, and adaptable?
   - A readme is always a good start for a project. These establish the scope and gives a new user all the information they may require. Writing modular code is useful to isolate functions and make changes less confusing. Adding proper documentation along the way is useful to increase readablility and even explainations may be useful for newer developers. As for adaptability, I made sure that I coded in such a way that would allow for future firmware updates would be isolated in use so if the code needed to be updated, it would be user friendly. 
