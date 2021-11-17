# Software Technology Experiment 7

## Introduction 
The intention behind this experiment assignment is to familiarize the students with messaging systems and the publish/subscribe paradigm.

## Experiment 1: Installation.
Installation went smoothly, I used Chocolatey. 

## Experiment 2: Hello World  
With this experiment I had a lot of trouble. For some reason, my imports for com.rabbitmq were not working in Java. 
So, I tried running the experiment via python. I was able to do the experiment fast on Python in VScode, but then I suffered authentication errors when I tried to push the 
repository to github. In the end, I had to upload the files by drag and dropping them into my browser window ([relevant](https://i.kym-cdn.com/entries/icons/original/000/023/987/overcome.jpg)). 

[Link to code for experiment two](https://github.com/bigmantobs/rabbitmq-hw)

## Experiment 3: Queue Messaging
This experiment went swimmingly.

[Link to code for experiment three](https://github.com/bigmantobs/rabbitmq-work-queues)
### Screenshots
To test the round robin distribution, I sent through 5 tasks in rapid succession, and as seen in the screenshots below; the first worker recieved tasks 1, 3, and 5. This is 
evidence of the distribution method.
![Tasks being sent](https://i.imgur.com/VoWW95a.png)
First worker recieves their expected tasks.
![Tasks recieved by first worker](https://i.imgur.com/T7tPvbm.png)
Second worker recieves their expected tasks.
![Tasks recieved by the second worker](https://i.imgur.com/P5C7fvV.png)

## Experiment 4: Topics
This experiment also went well.
[Link to code for experiment four](https://github.com/bigmantobs/sexpass-7-topics)
### Screenshots
As seen in the screenshots, logs are sent and recieved.
![Emit log](https://i.imgur.com/IMwrwxn.png)
![Recieve log](https://i.imgur.com/9dnLhcN.png)

## Pending issues
I was not able to see any message in the reciever for the first experiment. Fortunately the rest worked well! 
