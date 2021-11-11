# My own arduino (serjuino v1)
Hi, I decided to make my own arduino.  
To do this, I needed the following components:  


| Components                 | Amount | Price (x1) |
| ---------------------------| ------ | -----:     |
| ATMega328 microcontroller  |   x1   |    $3      |
| Breadboard                 |   x1   |    $2      |
| "Dad-Dad" wires            |   x10  | $1.50      |
| 16 MHz quartz resonator    |   x1   | $0.15      | 
| Capacitor 22 pf            |   x2   |$0.011      |
| Button                     |   x1   |$0.038      |
| USB with wires             |   x1   | $0.27      |
| ---------------------------| ------ | -----      |
|                   Total:   |        |    $7      |
***
Lyrical digression:  
Wiring sceme on the board  
![image](https://user-images.githubusercontent.com/93592475/140606482-9fc43e99-0ef8-444f-8752-bc5dc794dd73.png)  
Atmega328 pinout:  
![image](https://user-images.githubusercontent.com/93592475/140111147-5cb9827c-f40c-48e6-8d88-9414c390dd31.png)
***
 `Сollect all the components in the scheme and you should get the following(click on the picture to watch the video):`
 [![Watch the video](https://user-images.githubusercontent.com/93592475/140606617-4c612684-1575-4e42-b06f-7d2d49b5f73b.png)](https://www.youtube.com/watch?v=veto45xHCA0)
***  
#### !Note: to upload the scratch, we must choose an `Arduino nano board with Atmega328p`!  
The code (Blink) is written in C, not in Arduino C, because pure C takes 173 bytes instead of 983 bytes. 
***  
For another example, I will take a servo and a potentiometer. I will connect the `servo to 9 pins`, and the `potentiometer to A0`(i use 10k). And it will look like this:  
[![Watch the video](https://user-images.githubusercontent.com/48791896/141270178-9c00429b-f17d-42a1-be5f-fef866437083.png)](https://youtu.be/LdQcaEY1qvc)
***
First, I solder all the components to the board.  
![image](https://user-images.githubusercontent.com/48791896/141270921-628d4fea-8ab9-4787-a211-ee69a0ffe1fc.png)  
![image](https://user-images.githubusercontent.com/48791896/141271015-ea02b25c-f64e-4cf9-9671-64b96f6fc9eb.png)  
