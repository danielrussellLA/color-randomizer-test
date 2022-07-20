In App.js, use the provided API url to fetch 6 random color values and display them in the browser. Use the mocks under `src/mocks` as a guide to style.

<!-- Requirements -->

1. Use the API url "https://x-colors.herokuapp.com/api/random?number=6" to fetch 6 random color values.
2. Use colors to create 6 different boxes with 10px in between them.
3. Create a button, 'Randomize Colors'.
4. When this button is clicked, it should refetch the API results for new color values.

<!-- Extra -->

API: https://x-colors.herokuapp.com/

1. Create an input field that accepts a string (in this case a color like 'green'). Don't worry about form validation for now, you can assume the user will always input a valid color string.

2. Once a user types in a color, use the API documentation to fetch 6 hues of that specific color (i.e. green)

3. Given a hard-coded list of colors:
   ['red', 'green', 'blue', 'orange', 'yellow', 'purple']
   Render all the colors in boxes in random color order whenever the button is clicked (shuffle them)
