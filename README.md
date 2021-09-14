<p align="center">
  <a href="https://github.com/ivanmudarth/Contaminot">
    <img src="https://user-images.githubusercontent.com/33183884/133178350-478d55c0-12fb-4910-b646-e443e9906d93.png" alt="Logo" width="100" height="100">
  </a>

  <h1 align="center">Contaminot</h1>
  
  <p align="center">
    Web application to prevent the spread of COVID-19.
  </p>
  <p align="center">
    <a href="https://devpost.com/software/contaminot">View Devpost</a>
  </p>
</p>

</br>

***

# Description
As public health officials repeatedly advise people to stop touching their faces in order to protect themselves against the new coronavirus, many individuals are starting to notice how often they do it and how difficult it is to stop.

Healthcare professionals have warned the public to wash their hands often and to avoid touching their faces, particularly their eyes and mouths, because severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2), the virus which causes COVID-19, can linger on some surfaces for hours or even days.

While it sounds simple enough, many people touch their faces multiple times a day with one study out of the U.S., which came out a few years ago, suggesting it could even be as often as 23 times an hour. We wanted to build a tool that mitigated the spread of the coronavirus by stopping one simple habit -- touching your face!

# What it does
ContamiNot is a web application that detects and notifies when the user touches their face in order to prevent the spread of coronavirus. The facial recognition detector runs in the background so while you using your computer you will receive immediate reminders to put an end to this habit.

The website also keeps track of how frequently and at what time you touch your face. This data is organized and visualized for the user in the form of a graph. This will allow users to see the problem first-hand and hopefully reduce the habit of subconsciously touching your face.

# How We built it
A series of images are grabbed from the video camera during training and assigned to one of two classes – touching or not touching. This is used to train the ML model which will then alert you if your hand is coming too close to your face.

The data visualizer extracts two variables from the facial recognition model -- how many times you have touched your face and at what time each face touch occurred. Using the Chart.js library we were able to graph this data to provide the user with valuable insights.

# Authors

Ivan Mudarth (@ivanmudarth)

Andy Chen (@AndyKChen)

Siddu Palaparthi (@PSiddu)
