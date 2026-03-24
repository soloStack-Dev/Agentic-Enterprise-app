I created this Agentic application for how create agent in jvm(Java Virtual Mechine) and i use to create the agent using Local LLM name is granite3.2-vision:2b

step 1:
we give instruction what kind of content the ai agent can response for user input based so i created this agent to give instruction you response the content look like 
when user give some topic to create the story so we give information to agent you give content format its adventure with creativity story so i add web search for that 
retrive some story reference create unique adventure story so this is the workflow for how we give instruction to ai agent

![Embabel Ai Agent with Give response Instruction](https://i.ibb.co/xKY49T8R/Screenshot-2026-03-24-190216.png)

step 2:
we give response formate like you give the content in this type 
title --> (Title of the story)
content --> (what kind of in this story)
topic --> what kind of topic user given

![Agent response](https://i.ibb.co/d0LWNF4T/Screenshot-2026-03-24-185617.png)

step 3:
we use Google recently released Antigravity IDE i use to build the Ai agent i face the ERROR take a time one day but ai make some hellucination i try to view the 
problem to fixed 
![antigravity agent response for how to give user input to embabel agent](https://i.ibb.co/HDgNFpXn/Screenshot-2026-03-24-185652.png)

Problem: java Agent framework Embabel Dependencies to add in pom.xml because i try find the right dependencies in online resource but i make repeated error
so finally i find out youtube channel for use Embabel to build ai agent i learn that video to how get dependencies and how build agent so i take reference to build 
agent after i run the app its no error i finally get response when we run the spring application it response the Embabel log i share the image
![Embabel Log](https://i.ibb.co/R4vqHqVc/Screenshot-2026-03-24-195748.png)

step 4:
we give user input to Embabel agent so i give local 2b parameter ai model it's take moment of time to response so i share the input log
Here is it
![user_input](https://i.ibb.co/GvKvyTCD/Screenshot-2026-03-24-185158.png)

step 5:
At the end of the movement get successfull agent resposne the response formate in json
![agent json response](https://i.ibb.co/MYBdhjs/Screenshot-2026-03-24-185231.png)

after the agent response it shown
1. what LLM was used in [granite3.2-vision:2b]
2.Prompt Token was how much token was used
3.Completion token is how much token it take in responsed
4.cost mean how much it take for each request because in my response cost $0.0000 because i use local LLM its run in local not in cloud
