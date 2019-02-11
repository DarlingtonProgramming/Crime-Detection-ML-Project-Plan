# Darlington-Senior-Project-Design-Document
This is a project proposal for the Leadership Ventures ML Project developed by David Cao and Sharon Sun.

## Project Information

### Project Category

Machine-Learning Project, Computer Vision Project   

### Market Research

There is apparently no mature commercial product that uses cameras to automatically detect a crime scene and reports it to the police department. For now, the common way for police deparments to get informed about a crime scene is by recieving calls from 911, but it is proven to be not so efficient. During a crime scene, a victim might not be able to call the law enforcement department due to the fact that the law-breaker is taking control. Thus it is really important to have a collection of automatic crime detection devices that are cheap and do not need human engagement. As you can see from our extended objectives, we wanted to design a system that put connected devices into use and automatically detects, reports the crime scene to law enforcement departments. 

### Project Description

This is basically a project that by using pre-trained artificial intelligence models to enable automatic detection of a crime scene. The project is able to read frames form a input camera source (or just simply an input source) and tell if the frame involves a potential law-breaking action.   

### Project Objectives & Description

1. Dataset filtration
    - Because the training of machine learning models really requires huge amounts of data that can be expressed in mathematical terms, and there are not many datasets for us to use to train this model (this is what makes this project difficult), it requires a lot of time for us to search for videos on the internet. 
    - After seleting proper datasets, we have to identify the videos into different catagories and make sure that every frame shows a clear sign of the action of the catagory. It requires a lot of time to filter those videos.
2. Model setup
    - Machine learning program's performance (both on the accuracy side and the speed side) is highly dependent on what algorithms you are using for your program. Selecting a great algorithm during the early stage helps to solve potential problems, and reduces training time (and it also saves energy because the GPU does not need to do much work!)
3. Model training & iteration
    - After deciding what model to use and finish programming it, we will enter this stage. In this stage we will evaluate the successful rate of the model and try out different models not only to boost the performance of the program but also accumulate some ideas and thoughts about how algorithms fits different cases differently.
4. Parameters adjustments
    - Machine learning is like magic, you never know how well your parameters that you put into the algorithm model is going to work, and to get the best results, sometimes you need to change the parameters back and forth. 
5. Distributed System based on Python / C++
    - If we ever had a chance to finish previous steps, we can create a distributed system for people that they can attach their camera to a device that we invent and that device automatically reports suspicious activities to our centural server. The server then sends out a text message to the client saying that their camera detected a suspicious activity. 
    - More business / community plans will be made later.