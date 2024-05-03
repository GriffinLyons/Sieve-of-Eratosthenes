# Demonstrating the Sieve of Eratosthenes in Python with Animation
This was my project for my fall 2023 course in Computational Mathematics at Boston University's Metropolitan College, CS 550.
I covered the Sieve of Eratosthenes, a means of identifying prime numbers by 'sieving out' numbers that could not qualify for prime number status.
(e.g., they are a multiple of any number besides themselves and 1)

I wrote [code to implement the Sieve](https://github.com/GriffinLyons/Sieve-of-Eratosthenes/blob/main/Naive_Sieve_of_Eratosthenes.ipynb) (a non-optimized version, hence 'naive' in my code) and animate it in Python:
![an animated demonstration of the Sieve of Eratosthenes](https://raw.githubusercontent.com/GriffinLyons/Sieve-of-Eratosthenes/main/sieve_of_eratosthenes.gif "Sieve of Eratosthenes")

I gave [a presentation](https://github.com/GriffinLyons/Sieve-of-Eratosthenes/blob/main/Griffin_Lyons_Sieve_of_Eratosthenes_16_Slide_Version.pdf) to my class on the Sieve of Eratosthenes, the importance of prime numbers, and my function in action.

I found that writing the function was relatively straightforward. Animating it, however, was much more difficult.
I learned a lot from tweaking the visuals, adding elements such as the red square to indicate where the deleted non-prime 'was', changing the timing, and other parts of implementing this using matplotlib's FuncAnimation and mpl.
The major drafts of my attempts at animating the Sieve are visible in the linked notebook above, starting from the final version at the top and going back to the earliest attempt at the bottom.
