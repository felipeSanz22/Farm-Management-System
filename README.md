# Project Import Cargo Management

## Description:

Technologies used: C#, HTML
Team: Developed collaboratively with a classmate
University: ORT Uruguay University
Course: Programming II – Second Semester, Information Technology Analyst Program

This project was developed as part of the Programming I course during the second semester of the Information Technology Analyst program at ORT Uruguay University. Together with one of my classmates, we built a web-based system requested by a livestock farm dedicated to purchasing and fattening cattle and sheep.

The goal was to create an intuitive tool for employees to manage and organize the farm's daily operations, including animal registration, task scheduling, and activity tracking. The application features a simple user interface and role-specific menus to improve usability and efficiency in routine farm work.

# Main Functionalities of the Farm Management System
The application supports two types of users: Peón (Farm Worker) and Capataz (Foreman). The core functionalities available to both user roles include:

## F01 – Animal Listing
Displays a complete list of registered animals (both cattle and sheep).

Shows each animal's ID, breed, weight, sex, and vaccination records.

## F02 – Paddock Filtering by Area and Capacity
Allows users to input a minimum area and minimum number of animals.

Returns paddocks (potreros) that meet or exceed both criteria.

Displays paddock ID, description, total hectares, and maximum capacity.

## F03 – Set Wool Price per Kilogram
Enables setting the price per kg of wool for all sheep.

Automatically updates the price across all existing ovine records.

## F04 – Register New Cattle (Bovino)
Users can register new bovine animals by providing required data like:

Type of feeding (enum-controlled)

Unique ID (validated)

Sex (enum-controlled)

Breed, acquisition and feeding cost, weight, hybrid status, birthdate

Data is validated and the newly registered animal is displayed for confirmation.
