# Recylcing-System
The software solution implemented contained multiple functions which were all then used in a nested loop structure. The functions used were the dispense container function, the load container function, the transfer container function, and the return home function. There were multiple constraints that needed to be considered. Only bottles destined for the same bin will be picked up by the robotic arm. The total mass of the bottles on the hopper must not exceed 90 grams as well. A nested if structure was used with a Boolean variable, conditions that checked if the location of disposal was the same and the mass was less than 90. If the condition variable evaluated to False, no more containers would be loaded. After which the Q-bot would move along the yellow line using data from the line following sensors and adjust its wheel speed accordingly. Color sensors were used to distinguish between the different bins. Using the location stored in the variable, transfer bin location, the program finds the corresponding color coordinates and the bot uses it to find the appropriate bin and dump the bottles. The bot then returns to its home position for the next cycle. The bottle left on the table in the previous cycle would be loaded and the next bottle would only be loaded if they were destined for the same bin. The Q-bot will then continue to do all the procedures mentioned as long as the program is not closed.

![image](https://user-images.githubusercontent.com/87504885/211466041-f1520da9-dfdd-4953-b660-fa35eda83612.png)

