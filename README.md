# PersonalTraining
A quick python program for a personal trainer to track clients and their exercises

The intended use of this program is to track client workouts all in one place.
The reason to track workouts is to ensure progress. This program was designed with this in mind. A personal trainer can enter an exercise name within a client's workout and the program will display the previous record of this exercise. For example, if the trainer enters in "bench press" and the exercise has been performed by this client in the past - the previous record will display: "Last performed on 03/14/2022: 250, for 3x12"

This program uses a txt file as a database which contains a dictionary of clients.
Within each client key, there are individual workouts with the workout date as a key.
Within each workout, there is an array of exercises performed on that day each with the same format, another dictionary.

