![World Clocks](https://github.com/sourceduty/World-Clocks-Live-Wallpaper/assets/123030236/c94cd1e0-40d2-4819-9882-a3478c237342)

> Animated and synchronized world clocks.

#

This HTML program creates a dynamic web page that displays a live wallpaper of clocks showing the current time in different cities around the world. The web page uses the HTML5 <canvas> element to draw the clocks, and JavaScript is employed to manage the drawing and updating of the clocks in real-time. The cities represented include New York, London, Paris, Toronto, Moscow, and Tokyo, each associated with their respective time zones.

The resizeCanvas function ensures that the canvas size adapts to the window size, providing a responsive design. This function is called both when the window is resized and initially when the page loads, setting the canvas width and height to match the browser window dimensions. This adaptability ensures that the clocks are always displayed properly, regardless of the screen size or resolution.

The drawClock function is responsible for rendering an individual clock on the canvas. It calculates the current time for each specified time zone, formats the time to a readable string, and computes the angles for the hour, minute, and second hands. It then draws the clock face, the city name, and the current time using various drawing methods available in the Canvas API. This function ensures each clock is visually appealing and accurately represents the current time.

Finally, the drawClocks and updateClocks functions manage the overall layout and continuous updating of the clocks. drawClocks clears the canvas and draws all the clocks in a row, evenly spaced across the width of the canvas. updateClocks calls drawClocks and then uses requestAnimationFrame to repeatedly update the display, ensuring the clocks are updated smoothly and in real-time. This continuous loop creates a dynamic and engaging live wallpaper effect, with the clocks continuously displaying the correct times for their respective cities.

#
Sir Sandford Fleming (1827–1915), a Canadian railway engineer, developed the international standardised time zone system back in 1878.

***
ℹ️ This software is free and open-source; anyone can redistribute it and/or modify it.
