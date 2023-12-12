The below screen captures are from the app version I used for the Midterm presentation. In the version I'm using for the final, there is a lot more code, however not all of it is complete. 

The below code is the ChatGPT experimental extension, which has text-to-speech and voice input capabilities, as well as text bar for the user to search.
<img width="336" alt="AI Bot Code" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/4bb2618c-5747-4e18-8bda-17a6ce01770e">


The next code screenshots are for the At-Home workout and Arm workout areas, respectively. Which has timers for each excercise for the user to track time doing the exercise, with the timer number visualy changing, a start button to begin the timers, and a button to reset all of the timers for the user to go again. Now Including Stretches page for final, with updated code snippets from Arms and At Home workouts. 

#At Home
<img width="544" alt="AtHomeWO Code" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/df61fae5-4a56-4421-a403-9581954ccd5b">

Updated for final:
<img width="327" alt="New At Home" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/ca3b2ee3-fac6-4a51-973b-2637be249da0">


#Arms
<img width="514" alt="Arm Workout Code" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/98fad447-b265-494b-9180-951c54ffd4a5">

Updated for final:
<img width="355" alt="New Arm Code" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/9ef1719b-3db0-4b20-bf87-5f0fd9cf0e87">


#Stretches
<img width="534" alt="Stretch Code" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/84105291-ba70-4d61-a4dd-7ce2140f5eda">


The next screenshot is of the main menu code, which has the navigations to all the different pages, user can long click and see a description of the page before actually entering, as well as color-responsiveness to user touch for accessibility 

<img width="426" alt="MainScreen Code" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/5dcc6bb5-543e-4231-a941-fe0e123bb47b">


Lastly, the screenshot is for the step counter which has an active text area that changes as the user walks for their step count and estimated calories burned from steps, as well as buttons to start, stop, and reset both counters

<img width="396" alt="Step Calorie Code" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/fcab4ccf-4aea-4990-b735-65ffed117db7">


I will target specific blocks that reoccur heavily throughout the program here and give comments on what they do. 
#Timer
<img width="542" alt="Timer code" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/bb7a82c0-1c46-4bd5-b028-2b1a0b0f90b8">
The above code feautures my main blocks from all 3 of the different workout pages. The initialize global timer/start create the instances of the clock retreival and set the boolean of the start and stop to false(stop), on the left has the button (START) next to the exercise to set the boolean to true (start) which begins the timer through the largest block which updates the text know as //_Timer to be what number the timer is at and have it constantly update as it decreases to zero. 

#Reset Timer
<img width="151" alt="Reset" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/4b8576d6-bcd9-4cb0-93b0-08a147729862">
This code is what resets all of the timers back to 30 once the button on the bottom of the screen has been pushed. It sets all the global timers back to 30 and all global booleans back to false. 

#ChatGPT
<img width="332" alt="Chat" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/81d949ba-b1a8-4d04-9c75-cf082ae3e3c4">
This code is what takes the users input in a text type area, calls a speech recognizer through Android's built in Google assistant and asks if the user would like the text created by ChatGPT to be read aloud or not. 

<img width="264" alt="Answer" src="https://github.com/CSC493-Computing-Design-Practicum/2023-fall-project-ZakJ26/assets/97726639/2c378333-2eab-4a27-b7d7-994fd6e4b80b">
This code is what happens once the speech recognizer has functioned, either yes from the user which results in the Google assistant to begin reading the generated ChatGPT text, or no from the user resulting in an inspirational "you got this" from the Google assistant. 

