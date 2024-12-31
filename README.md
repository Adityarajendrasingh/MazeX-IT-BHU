# Maze Solver Bot (MazeX-IT-BHU)  

The **Maze Solver Bot** is a **line-following and object-detecting robot** designed to navigate through mazes efficiently. It explores all possible paths, stores maze data, and follows the shortest path in subsequent runs while avoiding obstacles and dead ends.  

## Overview  

MazeX-IT-BHU combines robotics and algorithmic problem-solving to tackle maze navigation challenges. Using sensors and a robust algorithm, the bot identifies paths, detects objects, and dynamically adjusts its strategy for efficient traversal.  

## Features  

- **Line Following**:  
  - Tracks a black line on a white surface to navigate through the maze.  

- **Object Detection**:  
  - Detects and avoids obstacles during navigation.  

- **Path Optimization**:  
  - Explores all possible paths in the first run and determines the shortest route.  
  - Avoids dead ends and obstacles dynamically.  

- **Object Counting**:  
  - Counts and displays the number of detected objects at the destination.  

## Tech Stack  

- **Hardware**: Arduino Uno, IR Sensors, Ultrasonic Sensors, Motors  
- **Software**: Arduino IDE, C++  

## How It Works  

1. **Initialization**:  
   - The bot begins its journey by following a predefined black line on a white mat.  

2. **Maze Exploration**:  
   - During the first run, the bot explores all paths, detecting obstacles and dead ends.  

3. **Data Storage**:  
   - Path information is stored in memory for future reference.  

4. **Path Optimization**:  
   - In subsequent runs, the bot selects the shortest path to the destination.  

5. **Object Detection and Counting**:  
   - Objects are detected and counted along the path, with the total count displayed at the endpoint.  
