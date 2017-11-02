Spent most of the day on campus studying what local storage is, and taking a high level look at what other students were doing with it. Some weren't even using JSON at all, which I found rather interesting.

Finished up the chart and did some bug fixing on it for a bit, I found out a simple situation was to blame of just not having my chart creation declarations inside of my conditional that determined whether there had been 25 images selected or not, so it just pulled selected/generated data outside of that conditional when there were no event listeners to record which image was selected, and only one round of image generation to measure.

I left campus around 3:30PM, as I had some personal matters to attend to that took up the rest of the evening. I'm not done with the local storage branch of this assignment, but looking forward to getting that all taken care of today.
