# CodeClause_Flappy_Bird_game
Modules Used:
==> math
Python has a built-in math module. It is a standard module, so we don't need to install it separately. We only have to import it into the program we want to use. We can import the module, like any other module of Python, using import math to implement the functions to perform mathematical operations.

Since the source code of this module is in the C language, it provides access to the functionalities of the underlying C library. For instance,
eg: # This program will show the calculation of square root using the math module  
# importing the math module  
import math  
print(math.sqrt( 9 ))  

Output: 3.0

==>os
Python OS module provides the facility to establish the interaction between the user and the operating system. It offers many useful OS functions that are used to perform OS-based tasks and get related information about operating system. The OS comes under Python's standard utility modules.

==> from random import randint
the randint() method in Python returns a random integer value between the two lower and higher limits (including both limits) provided as two parameters.
It should be noted that this method is only capable of generating integer-type random value.
eg: #randint() Syntax
randint(lower limit , upper limit)
Here,
lower limit is the starting point from and including which the random integer would be generated,
uppwer limit is the stopping point up to which the method would return the random integer.
The above example returns an integer N where N>=beg and N<=end.

==> from collections import deque
A double-ended queue, or deque, has the feature of adding and removing elements from either end. The Deque module is a part of collections library. It has the methods for adding and removing elements which can be invoked directly with arguments. In the below program we import the collections module and declare a deque. Without need of any class we use the in-built implement these methods directly.
eg: import collections
# Create a deque
DoubleEnded = collections.deque(["Mon","Tue","Wed"])
print (DoubleEnded)

# Append to the right
print("Adding to the right: ")
DoubleEnded.append("Thu")
print (DoubleEnded)

# append to the left
print("Adding to the left: ")
DoubleEnded.appendleft("Sun")
print (DoubleEnded)

# Remove from the right
print("Removing from the right: ")
DoubleEnded.pop()
print (DoubleEnded)

# Remove from the left
print("Removing from the left: ")
DoubleEnded.popleft()
print (DoubleEnded)

# Reverse the dequeue
print("Reversing the deque: ")
DoubleEnded.reverse()
print (DoubleEnded)

output: When the above code is executed, it produces the following result:

deque(['Mon', 'Tue', 'Wed'])
Adding to the right: 
deque(['Mon', 'Tue', 'Wed', 'Thu'])
Adding to the left: 
deque(['Sun', 'Mon', 'Tue', 'Wed', 'Thu'])
Removing from the right: 
deque(['Sun', 'Mon', 'Tue', 'Wed'])
Removing from the left: 
deque(['Mon', 'Tue', 'Wed'])
Reversing the deque: 
deque(['Wed', 'Tue', 'Mon'])

==>pygame
pygame is a Python wrapper for the SDL library, which stands for Simple DirectMedia Layer. SDL provides cross-platform access to your system's underlying multimedia hardware components, such as sound, video, mouse, keyboard, and joystick. pygame started life as a replacement for the stalled PySDL project.

==> from pygame.locals import *
This module contains various constants used by pygame. Its contents are automatically placed in the pygame module namespace. However, an application can use pygame.locals to include only the pygame constants with a from pygame.locals import *.
Detailed descriptions of the various constants can be found throughout the pygame documentation. Here are the locations of some of them.
=> The pygame.displaypygame module to control the display window and screen module contains flags like FULLSCREEN used by pygame.display.set_mode()Initialize a window or screen for display.
=> The pygame.eventpygame module for interacting with events and queues module contains the various event types.
=> The pygame.keypygame module to work with the keyboard module lists the keyboard constants and modifiers (K_* and MOD_*) relating to the key and mod attributes of the KEYDOWN and KEYUP events.
=> The pygame.timepygame module for monitoring time module defines TIMER_RESOLUTION.

