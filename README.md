# Car-Parking-System-Using-Raspberry-Pi
# Introduction

Purpose 

We aim to create a smart parking management system that identifies the vehicles accessing the parking spaces using a license plate recognition algorithm (OpenALPR).
Intended Audience and Intended Use
This project is mainly intended for the general public. It would be helpful for people with busy schedules and would make their lives a little more simpler when it comes to searching for a parking spot.

Project Scope

This project aims upon creating an automated parking lot where the cars are allowed parking spots on the basis of their license plate numbers. Instead of traditional methods such as the usage of RFID, we would be using OpenALPR to process the data on cloud to achieve better performance by taking off most of the computational load from Raspberry Pi. Without the use of RFID tags, we would make it economical as well.

# Product Perspective

This project aims to create an automated parking lot where cars are registered for parking spots based on their license plate numbers. The license plates are captured by a camera fitted near the entrance to the parking lot. This data is then sent to the Raspberry Pi. The Pi processes this image by using an external, web-based API, OpenALPR. OpenALPR has a cloud based API that is used to process the data. This helps remove potential processing load from the Pi, which does not have a high power CPU, thus allowing us to execute complex algorithms on the Pi. The API recognises the number plate using its algorithms and returns the plate number hence extracted. The number is then used to allot a parking spot to the car. When the car reaches the exit, it is removed from the spot list and the spot is then indicated as being empty, free to be allocated to other cars.
