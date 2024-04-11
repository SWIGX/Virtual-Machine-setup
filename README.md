
# How to setup a Virtual Machine for SWIGX 

This repository serves as a guide on how to create an Ubuntu virtual machine for development purposes

## 1. Downloads

### Download VirtualBox

https://www.virtualbox.org/wiki/Downloads

### Download ISO Image

_Choose the LTS version of Ubuntu_

https://ubuntu.com/download/desktop

## 2. Tutorial

Follow below tutorial to setup the virtual machine.

https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview

## Troubleshooting

### "My terminal is not working / is not starting"

- Go to Settings
- Go to Language and Region
- Change language to "English (United Kingdom)" - otherwise the terminal will not work.

### "When I press a button on my keyboard, a different key is written on screen"

- Go to Settings
- Go to Keyboard
- Change Input Source to "Danish (Windows)"
  - Click '+'
  - Click the three dots
  - Click "Other"
  - Click "Danish (Windows)"
- Remove the language that was already there

### "The dates etc. are wrong"

- Go to Settings
- Go to Language and Region
- Change format to "Denmark"

### "When I open my virtual machine, the screen is black"

- Go to VirtualBox Launcher
- Choose the virtual machine not working in the list on the left
- Click Settings 
- Go to Display
- Set Video Memory to a larger value (e.g. 100MB)


