Prompt Questions:

Summarize the project and what problem it was solving.
What did you do particularly well?
Where could you improve?
What tools and/or resources are you adding to your support network?
What skills from this project will be particularly transferable to other projects and/or course work?
How did you make this project maintainable, readable, and adaptable?

Response:

  The purpose of this project was to create a thermostat interface for an HVAC system. The goal was a system with three states: off, heat, and cool. 
This was accomplished using the python statemachine library. I feel like I did a good job overcoming a lack of hardware. I did not have three buttons,
I only had two. To overcome this, I did some slight redesigning to make it work with two buttons, where one button increases temp, one decreases temp, 
and pressing both simultaneously mimicks the third button which cycles through the states. This was surprisingly simple. One thing I could improve is
part of this system where the buttons are pressed simultaneously. Because of the way I implemented this, one button is inevitably registered before the other,
and so we get an erroneous increase or decrease of the temperature. This is not a serious issue, because the user can see the set point and correct it after
changing states. I would imagine we could create a separate thread to handle the button events, with a slight buffer window before execution to ensure there
is no extra adjustment to the temperature. I feel like this project really helped me learn more about using code to manipulate devices in the real world. 
This is useful in many different areas of the technology industry, and my experience here has me better prepared for working on similar systems. Also, now
that I have all of this hardware and a general idea of how to use it, I plan to tinker with new circuits and programs to further my understanding. The code
is fairly straighforward and was already well commented, but I made sure to include comments on all of the code I included to ensure maintainability in the future.
