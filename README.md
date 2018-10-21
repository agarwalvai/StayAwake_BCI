# StayAwake_BCI
A very simple and efficient app that prevents you from being a victim of drowsiness/ driver fatigue behind the wheel!
*This was created as a submission for HackGT

## Inspiration

With over three years of experience in transportation research and crash analysis of accidents in the state of Florida, very alarming statistics came to limelight. 25% of all accidents that take place are caused due to driver fatigue and them falling asleep behind the wheel. Only to make this worse, all the currently proposed solutions towards the same are very ** unsustainable and unhealthy **. These include administration of caffeine, energy drinks, several apps that use user reinforcement to make sure that user is positively engaged. However, in a scenario where a split second can determine the fate of your life, it is highly risky  to leave it up to these current solutions. That's where I found the motivation to create this app.
[Image](https://drive.google.com/file/d/1RNfXwEocXtd2fHG5wdd17VhDnsuEh61w/view?usp=sharing)

## What it does

The app interfaces with Emotive Insight headset which has five electrodes to monitor EEG Brainwave data. Websockets within Android Studio use the Emotiv Cortex API to request three different brainwaves (Alpha, Beta and Theta) and calculate User Engagement based on [Link](https://www.ncbi.nlm.nih.gov/pubmed/7647180), and then display it on the screen. Once the engagement level falls below a certain threshold, it creates an alert notification in an attempt to reengage the driver.

## How I built it

I used Android Studio to build the main framework of the app, and web sockets within Android Studio to communicate with the API using JSON. 

## Challenges I ran into

- A lot of interfacing issues with the API using Web Sockets within the realm of the app.

## Accomplishments that I'm proud of

All of the technologies I used for this project were new to me. I am very proud that despite being in a one-man team, and being new to all of the technologies, I was here to see this hackathon to the end, though I will continue working on this project as I learn more with time.

## What I learned

- Interfacing with APIs
-Using JSON
-Using Web Sockets
-Using Android Studio

## What's next for StayAwake_BCI

A good project never comes to an end. I will learn more about the used technologies and will continue with improvising the app. Further scalability can include communication using a FitBit, and other parameters for reducing false positives.

## Relevant Links
Link to Presentation
https://drive.google.com/file/d/1XiTDcO_DfkZRskfbub0In2Zbz3Rw0kM6/view?usp=sharing
Emotiv Cortex API Guide
https://emotiv.github.io/cortex-docs/#introduction
Emotiv Cortex Examples
https://github.com/Emotiv/cortex-example
JSON Url
http://myjson.com/1fya48
Websockets
chrome-extension://pfdhoblngboilpfeibdedpjgfnlcodoo/index.html


