# SME-Assignment
# Assignment Submission

## Overview
This repository contains my solution to the assignment. The assignment required resolving a circular dependency issue between the PlayerView and PlayerController classes in a C++ program.

## Changes Made
In the second part of the assignment, a circular dependency issue arose between the PlayerView and PlayerController classes. To resolve this, I adopted a forward declaration approach by removing the `#include "PlayerController.h"` statement from the PlayerView.h header file. Instead, I forward-declared the PlayerController class using `class PlayerController;` in PlayerView.h.

## Instructions
To compile and run the code:
1. Clone this repository to your local machine.
2. Navigate to the directory where the code is located.
3. Compile the code using a C++ compiler (e.g., g++).
4. Run the compiled executable.
