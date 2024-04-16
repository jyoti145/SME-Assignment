# SME-Assignment
# Outscal Assignment Submission

## Overview
I have resolved the problem of tightcoupling and bidirectional communication which results into the circular dependency between two difference classes Playerview and PlayerController of the game.



## Changes Made
"In the second part of the assignment, a circular dependency issue arose between the PlayerView and PlayerController classes. To address this, we evaluated several potential solutions. One of the approaches considered was the forward declaration method, where the #include "PlayerController.h" statement was removed from the PlayerView.h header file. Instead, we used class `PlayerController` to forward-declare the `PlayerController` class within `PlayerView.h`."

"Based on our analysis and the requirements of the project, we decided to implement the forward declaration approach. This method allowed us to break the circular dependency between the `PlayerView` and `PlayerController` classes by providing the necessary class declaration without including the full definition. Consequently, this solution helped streamline the compilation process and improve code maintainability."

## Instructions
To compile and run the code:
1. Clone this repository to your local machine.
2. Navigate to the directory where the code is located.
3. Compile the code using a C++ compiler (g++, gcc, MingW).
4. Run the executable file.
