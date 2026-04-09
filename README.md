# Boids Algorithm Simulation with LibGDX

> A graphical simulation of Craig Reynolds' "Boids" algorithm, which models the flocking behavior of birds (or schools of fish).

-----

## Objective

This project visually demonstrates the principles of **emergent behavior**. Each "boid" (agent) makes decisions independently, based only on its local neighbors. The interaction of these simple decisions results in complex and realistic flocking behavior without any centralized coordination.

## The 3 Rules of Boids

The simulation is based on three classic rules that every agent follows:

1.  **Separation:** Move to avoid crowding and collisions with neighboring agents.
2.  **Alignment:** Move toward the average heading of neighboring agents.
3.  **Cohesion:** Move toward the average position (center of mass) of neighboring agents.

-----

## Technologies Used

  * **Language:** Java
  * **Game Framework:** LibGDX
  * **Build Automation:** Gradle

-----

## How to Run

The project uses the Gradle Wrapper, so having Gradle installed on your machine is not required.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/chspDEV/simulacao-boids.git
    ```
2.  **Navigate to the project folder:**
    ```bash
    cd simulacao-boids
    ```
3.  **Run the project:**
      * **On Windows:**
        ```bash
        gradlew.bat run
        ```
      * **On Linux or macOS:**
        ```bash
        ./gradlew run
        ```
