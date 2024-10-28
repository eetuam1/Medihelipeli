# Medihelipeli

## Introduction
Welcome to the Medihelipeli project! This document serves as a specification guide for game developers, outlining the vision, gameplay mechanics, and quality requirements of the Medihelipeli game. The document is divided into four sections: Introduction, Vision, Functional Requirements, and Quality Requirements. It may be updated during the development process to accommodate new tasks as needed.

## Vision
Medihelipeli is a rescue game where the player’s goal is to save patients across Norway. The player must transport patients from their locations to the nearest hospital (1-2 different hospitals). The helicopter can carry 1-3 patients, and there are a total of 12 patients to rescue. Players need to strategize to ensure that all patients reach the hospital before running out of fuel.

## Functional Requirements
- The game is a single-player experience.
- When the player starts the game, they will be asked if they want to read the backstory. If yes, the backstory will be presented.
- The starting point for the player is a hospital, where they are informed of their location and the distances to their patients.
- Three patients are randomly assigned each time, and the patient list updates when the player visits the hospital.
- The player decides which patient to rescue first by entering the ICAO code of the heliport at the selected location.
- The player can choose to return to the hospital with 1, 2, or 3 rescued patients.
- Every time the player visits a hospital, they receive additional fuel, increasing their range. The list of patients to be rescued updates after each hospital visit.
- The player selects the next airport by entering the ICAO code.
- If the player rescues all 12 patients, they win the game. If they run out of fuel and can no longer reach any heliport, they lose.

## Quality Requirements
Throughout the game, the player can always see how far the helicopter can travel on the remaining fuel. Upon arriving at a new location, players are shown the distance to the nearest hospital, the locations of remaining patients, and all airports they can reach within the remaining distance. Players receive immediate feedback for every action they take.

## Technologies Used
This project is developed using the following languages and technologies:
- JavaScript
- Python
- HTML
- CSS
- HeidiSQL

## Conclusion
Medihelipeli aims to provide an engaging and strategic gaming experience for players. With continuous updates and improvements based on feedback, the game is set to evolve and enhance its playability.
