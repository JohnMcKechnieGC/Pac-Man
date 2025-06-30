# Pac-Man: Ghost Psuedocode and Mazes

This repo contains some initial pseudocode and mazes to support an introduction to programming based on the Pac-Man game.

Having run this session, it took about 1 hour to get to the point of creating the maze and simulating the first game. If you want to concentrate on the code and modifications, you may prefer to run the session with the maze and character counters prepared in advance.

----

## Learning Objectives:
- Understand that programs are sets of step-by-step instructions.
- Recognise sequence, selection (if / otherwise), and iteration (loops).
- Debug and improve an algorithm.
- Experience pair-/group-based problem-solving.

----

## Pac-Man

- Pac-Man is an action maze chase video game developed and published by Namco in 1980.
- Pac-Man must eat all the pellets while avoiding the four ghosts:
    - Blinky (red)
    - Pinky (pink)
    - Inky (cyan)
    - Clyde (orange)
- Each of the four ghosts has its own artificial intelligence (AI), or personality.
- Your challenge today will be to test and refine the AI for the ghosts.

Example video: https://youtu.be/i_OjztdQ8iw

----

## Setting Up
- Form into pairs or groups.
- Get flip-chart paper, markers, and sweets.
- Each group should design and draw their own maze.
    - Use sweets for the pellets and power-pellets.
    - Remember to leave a small rectangular “ghost house” in the centre.
- Make the Pac-Man and Ghost characters as well.
- Rewatch the video or do a little research of your own to figure out how the scoring works and any other rules of the game.

----

## Round 1 — Manual Simulation
- In your groups designate a Pac-Man driver, ghost drivers, and a score-keeper (roles can rotate later).
- Ghosts start in the ghost house.
- Use one ghost algorithm per ghost.
- Each character takes turns to move—one step per turn
    - Pac-Man moves first.
    - When Pac-Man eats a power pellet he gets two moves per turn for the next 10 turns (score-keeper counts).

----

## Debrief: What Went Wrong?
- Was it easy to follow the instructions for each ghost, or were the instruction sometimes unclear?
- Did Pac-Man escape too easily?
- How did the ghosts react when Pac-Man ate a power pellet?
- Was it easy to keep score?
- Were the rules of the game clear or were you unsure what to do sometimes?
- What else did you notice?
- **How might we make the ghosts smarter?**

----

## Redesign Time
- Groups rewrite the ghost pseudocode to be “smarter”
    - E.g. switch to “flee mode” when frightened.
    - Be sure to use plain language and structure your pseudocode clearly.
- Run the game again with the updated code.
    - Did your change(s) help?
    - You can stop and restart as often as you want to as you refine the behaviour.
- Is it better to make several changes at once or just one change at a time?
- You are welcome to swap mazes with different groups to test your pseudocode in new situations.

----

## Reflection
- How did code changes affect behaviour?
- Can you think of real-world examples where algorithms control behaviour?
- What are some programming concepts that we used today?
    - Pseudocode
    - Algorithms
    - Sequence
    - Selection
    - Iteration
    - Calculations
    - Testing
    - Debugging
