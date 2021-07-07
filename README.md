

  <h3 align="center">VR Research - Networking</h3>

  <p align="center">
    2021 VR Summer Project 
    
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#Prerequisites for development">Development Prerequisites</a></li>
        <li><a href="#Prerequisites for usage">Usage Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

An easy to use solution to implementing networked multiplayer to the research project as a whole. By using MLAPI from Unity we are able to add multiplayer functionality to user designed environments, characters, and many other things. 

Benefits:
* Increased user engagement.
* Quick and seamless to use.
* Allows for collaboration and virtual meetings. 


### Built With

* [Unity3D](https://unity.com/)



<!-- GETTING STARTED -->
## Getting Started



### Prerequisites for development

* Unity 2021.1.13
  ```
  https://unity3d.com/get-unity/download
  ```
* Any IDE that supports C#

### Prerequisites for usage
* Requirements are limited by Unity game engine requirements, running on both Windows (7, 8, 10) and Mac OS X (10.9+). More information about Unity requirements can be found at: [https://unity3d.com/unity/system-requirements](https://unity3d.com/unity/system-requirements).

<!-- USAGE EXAMPLES -->
## Usage

* Example Video:

[![Demo Video](https://img.youtube.com/vi/nxV61dMYrmI/0.jpg)](https://www.youtube.com/watch?v=nxV61dMYrmI)

By using simple Network transforms and a custom modified Character Controller we are able to have two or more players moving together in a single instance. The character controller has been specially crafted to fit as many models as possible to be easily interchangeable, with spaces for animations being an easy addition once created. Currently the model does not support any physics other than Collision and Gravity, though that can be changed easily in the future, once other features are added. 

* Editor View 

![](https://i.imgur.com/QC4UdMO.png?raw=true)

The current scene is very simple, comprised of a blank ground as well as three obstacles. This is done on purpose to show that we can easily modify the playing field, and will suit our needs in the future to add multiplayer interactable objects. 

* Example of network settings. 

![](https://i.imgur.com/0dqJdsl.png?raw=true)

This shows the default MLAPI connection controller, giving us a lot of control over what each player can connect as or to. 




<!-- ROADMAP -->
## Roadmap

* Completed Features
	* Basic Networking
	*  Synchronized Multiplayer movement
	* Intractability between players
	* Hosting over Internet 
* Future Plans
	* Multiple scenes
	* Menu Scene
	* Interactable objects
	* On-demand spawning of game objects
	* Extend all features to be seamless
	* Allow for player created characters and environments to be instantly networked
	* Client Security



<!-- CONTACT -->
## Contact

TBD

