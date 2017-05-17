# Pong

## Description
A basic Pong game that I created for a course in Coursera. Since the course used SimpleGUI on CodeSkulptor which is online only, its required dependencies will have to be imported onto the computer.

## Requirements
This will work on Python2 only. The following instructions are for Ubuntu systems.

The `SimpleGUICS2Pygame` module, which implements SimpleGUI will be required. It depends on `Tkinter`, `matplotlib`, and `pygame`.

To install `Tkinter`, run

	sudo apt install python-tk

To install the others, `pip` will need to be installed. Do that with

	sudo apt install python-pip
	
After pip has been installed, run the commands

	pip install matplotlib
	pip install pygame
	pip install SimpleGUICS2Pygame

To verify that all dependencies have been installed, simply run the provided `SimpleGUICS2Pygame_check.py` file with

	python SimpleGUICS2Pygame_check.py
	
## Running
Run the game using
	
	python pong.py
Enjoy!