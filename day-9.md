Today was pretty brutal. I was working on the footer totals column for the table, and spent abut 2-3 hours just trying to identify how in my code I could get those figures.

I attempted to find ways to shove it in nested for loops and somehow pull the data from the created objects, since my prototype method that calculated the hourly and daily totals for each individual store was only being utilized within a for loop in the table body section.

Nothing. Just overly complex explorations of how, with those nested for loops, I could get the necessary data.

The TAs tried to work with me in the context of the for loop, but to no avail aside from Michael keying in to the fact that if I could get that data into an array, it would be simple to create the hourly totals footer cells. He brought up the idea of creating an array with 14 0's (like this hourlyStoreTotals = [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]). That ended up being critical, as all I needed was to define that as a variable outside of the prototype method, and then set it equal to another variable that was already being calculated (and a nearly identical line of code) that was calculating the daily total for each individual store object.

2 lines of code to get that information..... 2 lines.

Anyways, I learned I needed to take a step back from what I'm doing if it's making me angry (which it definitely was) and perhaps not try to be so unnecessarily complex in my solutions as that can create a rabbit hole I can easily get lost in for hours, as I did.
