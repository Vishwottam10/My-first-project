# RANGOLI BOT


Most human work on visual input and process data depending on the visual input of the surrounding, People are not equipped with large number of
sensors rather the visual input are processed in a intelligent manner to get the most sophisticated application or uses of human ideas and thoughts.
Visual representation is an age old process where it is used for learning, teaching and expressing once mind or thinking to another person. In this
system we tried to extend a very specific form of art i.e. Rangoli



As the ideas and technologies develop, it’s clear that
drawing robots can be serious indeed. The development of service robot became popular recently due to the fact that society needs robots to relax
human from the tedious, exhaustive physical efforts and time consuming job. Recent generations of robots has even more resemble to humans like
drawing and artistic capacities as a hand drawn painting does not have the required looks as desired. This motivated researchers to design interactive
drawing robots that can mimic the complexity and style of human modeling of Rangoli by applying Computer Aided Rangoli mechanism. The
project places emphasis on outdoor painting, a domestic application using small robots.

## Multilayered approach 
![](https://i.postimg.cc/26dsYjWT/MULTILAYERED-APPROACH.png)  

## SETUP EXPLANATION:

The best part of this system is its interactive behavior with the haptic device which is carried out using optical sensor for
feedback. This feedback is processed and passed to Arduino placed on the agent through wireless medium for controlling the movement of the 
agent. Arduino is an open-source physical computing platform based on a simple microcontroller board, and a development environment for writing 
software for the board. It is easy to implement, has a simple structure with huge functionality. In this system Arduino UNO board is used. Arduino 
is connected to a wireless device ZigBee for receiving signal from the system through ZigBee shield. For the movement of agent Johnson geared 
wheels having 7inches by 6inches dimension is used, the agent is significantly denoted by a glowing LED on center of the sprinkler in order to 
distinguish it from any other object in the vicinity of the camera. Johnson geared wheels are controlled by Arduino through Dual H-Bridge
which accepts standard TTL logic levels and drive inductive loads such as motors. The Arduino is programmed to control the movement of the 
agent and for spraying color.

Rangoli to be drawn is first browsed and then it is passed through an edge detection filter for extracting the edges of desired Rangoli. Layer 3 
virtually project this edge detected image. The system begins examining starting with one corner then onto the next in a straight manner as it may 
be. Here supposition is that the canvas will be of square or rectangular shape henceforth examining for the focuses is raster scanning method. All the 
while it likewise locates agent’s position at first glance which is projected in layer 4. While scanning, system compares layer1 and Layer3 of the 
multilayered approach. In the wake of getting agent’s position system sends agent to first spot on Physical Layer or Layer 1. From there onwards the 
system will begin spraying the color. The sprayed position and sprayed shape is checked by the camera where it is always sending the live status of 
the depiction to the computer. Computer compares the sprayed image with the desired pattern which helps in keeping track of the working of the 
system. A flowchart is depicted below in figure 3 which explains the processing of this system.

![Haptic device(agent)](https://i.postimg.cc/RFcJMcr3/Whats-App-Image-2021-12-29-at-4-15-03-PM.jpg)

 ![](https://i.postimg.cc/QdWCqp6F/Functionality-2.png)
# Components required 
## 1]Arduino UNO
![](https://lh5.googleusercontent.com/_MVmJGxq2VcGjPmG2inL36D6_DFls6Vho6tdJtDfcPoy63-ZNdGsDstc58HLDQvhka3VB-iR-g_-342oaz1zQwPfY8Nwvx0rRAIvWF004W6QeVTLTU-EET90H8ZLMU8lPLXcbbM) 

## 2]H-Bridge L298
![](https://lh5.googleusercontent.com/u8F9e8Vf98NsGn9QHZ7pD4gzkuotfzUsw3noN3J7ymjAEaCQ6CklQzSaQADZGlh_5Ev9iTCVtreIjJWqfUi3YJ8nIROlaNYZXEsKSA9kn32QVIbxu5ydIUaC6oq27f6SqRXKamQ)

## 3]2200 mAh Battery
![](https://lh4.googleusercontent.com/2Kc8HtaBjQxr_2FHfArEmR8jor0k1hRtwgRK0f0XNpBFxpmpTEkDL0Rd-4oh1Ore5Rons7ddEjs6Pz0JIpsL_NG8plvLYSkn-CHrR3rM105vA6ktcdMi0yCIGw1LhIlJH-aFsuY)

## 4]Caster wheel
![](https://lh6.googleusercontent.com/vS6SVLq8Fv8C_HFTONT29HQGzUmZ0zexwbC8XeK7wHjGSHDlmzcnWxxgPCqDDKYMZ6KxEIaNdQXKGmNAa5hAhtmFfZncdJ0STo-yfILwia-O1mO51MAyNjuouXqcJerktcFbSDs)

## 5]Robot Mount
![](https://lh5.googleusercontent.com/I65_4arV6pF-oEkWnAa_vxKCX7mEFz7BxJnJBD1kSrfz2k1I4lW9rCEdrZL3q_UgWJdENhG9Eg37riEmKV6WjTb4vEwPq3rQxvrEm9xmWfhp4ikYcstVKqDTxwbX8nRHJzpNSEU)

## 6]2 DC motors
![](https://lh4.googleusercontent.com/xrF3MaYEa370v2rcFL5gBWx5AwDt9TKNoK2M-oSLeupp8nOKqQWREym2dtKxJPgwAIoUi5Aji5fPM0FAK2l0t5Cysipp4HhT4RkPr9J6ZDEFUgcJ5Lcv__JE6nxcIlX99MqAzHk)

## 7]Servo motor
![](http://3.bp.blogspot.com/-be-D2xbU-Ig/VRgQZST5zdI/AAAAAAAAAD8/pZLP58HFtLk/s1600/download.jpg)

## 8]Wheels
![](https://lh5.googleusercontent.com/I65_4arV6pF-oEkWnAa_vxKCX7mEFz7BxJnJBD1kSrfz2k1I4lW9rCEdrZL3q_UgWJdENhG9Eg37riEmKV6WjTb4vEwPq3rQxvrEm9xmWfhp4ikYcstVKqDTxwbX8nRHJzpNSEU)

# REFRENCE LINKS: http://iedprojects2015.blogspot.com/2015/03/rangoli-making-robot.html
                  https://www.researchgate.net/publication/286451406_Smart_Structure_for_Automated_Rangoli