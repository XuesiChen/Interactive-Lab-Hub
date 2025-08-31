

# Staging Interaction

**Akash Basu, Benthan Vu, Evan Fang, Sean Lewis, Xuesi Chen**

In the original stage production of Peter Pan, Tinker Bell was represented by a darting light created by a small handheld mirror off-stage, reflecting a little circle of light from a powerful lamp. Tinkerbell communicates her presence through this light to the other characters. See more info [here](https://en.wikipedia.org/wiki/Tinker_Bell). 

There is no actor that plays Tinkerbell--her existence in the play comes from the interactions that the other characters have with her.

For lab this week, we draw on this and other inspirations from theatre to stage interactions with a device where the main mode of display/output for the interactive device you are designing is lighting. You will plot the interaction with a storyboard, and use your computer and a smartphone to experiment with what the interactions will look and feel like. 

_Make sure you read all the instructions and understand the whole of the laboratory activity before starting!_



## Prep

### To start the semester, you will need:
1. Read about Git [here](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F).
2. Set up your own Github "Lab Hub" repository by forking the [Interactive-Lab-Hub repository](https://github.com/FAR-Lab/Interactive-Lab-Hub). To get lab updates, simply [use GitHub's "Sync fork" button when new content is available](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork).

3. Set up the README.md for your Hub repository (for instance, so that it has your name and points to your own Lab 1). You can [learn how to organize and format your README.md here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). Make sure to include links to your submissions so they are easy to find.


### For this lab, you will need:
1. Paper
2. Markers/ Pens
3. Scissors
4. Smart Phone -- The main required feature is that the phone needs to have a browser and display a webpage.
5. Computer -- We will use your computer to host a webpage which also features controls.
6. Found objects and materials -- You will have to costume your phone so that it looks like some other devices. These materials can include doll clothes, a paper lantern, a bottle, human clothes, a pillow case, etc. Be creative!

### Deliverables for this lab are: 
1. 7 Storyboards
1. 3 Sketches/photos of costumed devices
1. Any reflections you have on the process
1. Video sketch of 3 prototyped interactions
1. Submit the items above in the lab1 folder of your class [Github page], either as links or uploaded files. Each group member should post their own copy of the work to their own Lab Hub, even if some of the work is the same from each person in the group.

### The Report
This README.md page in your own repository should be edited to include the work you have done (the deliverables mentioned above). Following the format below, you can delete everything but the headers and the sections between the **stars**. Write the answers to the questions under the starred sentences. Include any material that explains what you did in this lab hub folder, and link it in your README.md for the lab.

## Lab Overview
For this assignment, you are going to:

A) [Plan](#part-a-plan) 

B) [Act out the interaction](#part-b-act-out-the-interaction) 

C) [Prototype the device](#part-c-prototype-the-device)

D) [Wizard the device](#part-d-wizard-the-device) 

E) [Costume the device](#part-e-costume-the-device)

F) [Record the interaction](#part-f-record)

Labs are due on Mondays. Make sure this page is linked to on your main class hub page.

## Part A. Plan 

To stage an interaction with your interactive device, think about:

_Setting:_ Where is this interaction happening? (e.g., a jungle, the kitchen) When is it happening?

_Players:_ Who is involved in the interaction? Who else is there? If you reflect on the design of current day interactive devices like the Amazon Alexa, it’s clear they didn’t take into account people who had roommates, or the presence of children. Think through all the people who are in the setting.

_Activity:_ What is happening between the actors?

_Goals:_ What are the goals of each player? (e.g., jumping to a tree, opening the fridge). 

The interactive device can be anything *except* a computer, a tablet computer or a smart phone, but the main way it interacts needs to be using light.

**Setting: A night club.**
**Players: customers in the club, DJ and some other service workers could also be in the club.**
**Acticity: customers are trying to have a good time, and the service providers are trying to cater a good experience by providing good music, lighting and food.**
**Goals: The goal of the customers are dancing with the music, enjoying the club vibe, spend their money; the goal of the club workers is to provide good music, control lightings and offer good and drinks.**

Storyboards are a tool for visually exploring a users interaction with a device. They are a fast and cheap method to understand user flow, and iterate on a design before attempting to build on it. Take some time to read through this explanation of [storyboarding in UX design](https://www.smashingmagazine.com/2017/10/storyboarding-ux-design/). Sketch seven storyboards of the interactions you are planning. **It does not need to be perfect**, but must get across the behavior of the interactive device and the other characters in the scene. 

<img src="/Lab 1/images/storyboard_int1.png" alt="Interation1" style="width:100%;">
<img src="/Lab 1/images/storyboard_int2.png" alt="Interation2" style="width:100%;">
<img src="/Lab 1/images/storyboard_int3.png" alt="Interation3" style="width:33%;">
<img src="/Lab 1/images/storyboard_int4.png" alt="Interation4" style="width:100%;">
<img src="/Lab 1/images/storyboard_int5.png" alt="Interation5" style="width:100%;">
<img src="/Lab 1/images/storyboard_int6.png" alt="Interation6" style="width:100%;">
<img src="/Lab 1/images/storyboard_int7.png" alt="Interation7" style="width:100%;">
Interaction 8
<img src="/Lab 1/images/storyboard_int8.png" alt="Interation8" style="width:100%;">


Present your ideas to the other people in your breakout room (or in small groups). You can just get feedback from one another or you can work together on the other parts of the lab.

**One of the feedback we got was that the light could also react to the location of where people are clustering**


## Part B. Act out the Interaction

Try physically acting out the interaction you planned. For now, you can just pretend the device is doing the things you’ve scripted for it. 

**Q: Are there things that seemed better on paper than acted out?**

**A: How the light change based on the club population size, especially interaction 3-7, was better on paper than acted out**

**Q: Are there new ideas that occur to you or your collaborator that come up from the acting?**

**A: As a result, Interaction 8 was actually an new idea that occured after acting out the interaction. We wanted to make the light more reactive to people's action than the states of the population size.**

## Part C. Prototype the device

You will be using your smartphone as a stand-in for the device you are prototyping. You will use the browser of your smart phone to act as a “light” and use a remote control interface to remotely change the light on that device. 

Code for the "Tinkerbelle" tool, and instructions for setting up the server and your phone are [here](https://github.com/IRL-CT/tinkerbelle).

We invented this tool for this lab! 

If you run into technical issues with this tool, you can also use a light switch, dimmer, etc. that you can can manually or remotely control.

**Feedbacks on Tinkerbelle: It will be nice if we can add color gradiant or pattern to the color screen; and for the convinience of the project, it will also be helpful to add simple programming ability to allow user to program the light behavior of each interaction** 

## Part D. Wizard the device
Take a little time to set up the wizarding set-up that allows for someone to remotely control the device while someone acts with it. Hint: You can use Zoom to record videos, and you can pin someone’s video feed if that is the scene which you want to record. 

\*\***Include your first attempts at recording the set-up video here.**\*\*

Now, change the goal within the same setting, and update the interaction with the paper prototype. 

\*\***Show the follow-up work here.**\*\*


## Part E. Costume the device

Only now should you start worrying about what the device should look like. Develop three costumes so that you can use your phone as this device.

Think about the setting of the device: is the environment a place where the device could overheat? Is water a danger? Does it need to have bright colors in an emergency setting?

**paper prototype / costume 1**
<img src="/Lab 1/images/prototype1_sketch.png" alt="prototype1_sketch" style="width:100%;">
<img src="/Lab 1/images/prototype1_costume.jpg" alt="prototype1_costume" style="width:50%;"><img src="/Lab 1/images/prototype1_costume2.jpg" alt="prototype1_costume2" style="width:50%;">

**paper prototype / costume 2**
<img src="/Lab 1/images/prototype2_sketch.png" alt="prototype2_sketch" style="width:100%;">
<img src="/Lab 1/images/prototype2_costume.jpg" alt="prototype2_costume" style="width:50%;"><img src="/Lab 1/images/prototype2_costume2.jpg" alt="prototype2_costume2" style="width:50%;">

**paper prototype / costume 3**
<img src="/Lab 1/images/prototype3_sketch.png" alt="prototype3_sketch" style="width:100%;">
<img src="/Lab 1/images/prototype3_costume.jpg" alt="prototype3_costume" style="width:100%;">

**Q: What concerns or opportunitities are influencing the way you've designed the device to look?**

**A: The actual lighting in a club. How realistic our phototype is mimicing the lighting experience in a club.**


## Part F. Record

[![Watch the video](https://img.youtube.com/vi/rX7Hptw_O2s/maxresdefault.jpg)](https://youtu.be/rX7Hptw_O2s)

Please indicate who you collaborated with on this Lab.
Be generous in acknowledging their contributions! And also recognizing any other influences (e.g. from YouTube, Github, Twitter) that informed your design. 

**The collaborators for this lab and their contributions are listed below**

**Akash Batu: Storyboards #1, #2, #3, #4, #5, Wizarding Tinkerbelle**

**Benthan Vu: Costume #1, Paper Prototype #1, Research & Feedback**

**Carrie Wang: Wizarding the Device, Research & Feedback**

**Evan Fang: Costume #2, Paper Prototype #2, Storyboard #8**

**Sean Lewis: Storyboards #6, #7, Setting up Tinkerbelle**

**Xuesi Chen: Costume #3, Paper Prototype #3, Demo Video Recording and Editing**

# Staging Interaction, Part 2 

This describes the second week's work for this lab activity.


## Prep (to be done before Lab on Wednesday)

You will be assigned three partners from other groups. Go to their github pages, view their videos, and provide them with reactions, suggestions & feedback: explain to them what you saw happening in their video. Guess the scene and the goals of the character. Ask them about anything that wasn’t clear. 

\*\***Summarize feedback from your partners here.**\*\*

## Make it your own

Do last week’s assignment again, but this time: 
1) It doesn’t have to (just) use light, 
2) You can use any modality (e.g., vibration, sound) to prototype the behaviors! Again, be creative! Feel free to fork and modify the tinkerbell code! 
3) We will be grading with an emphasis on creativity. 

\*\***Document everything here. (Particularly, we would like to see the storyboard and video, although photos of the prototype are also great.)**\*\*
