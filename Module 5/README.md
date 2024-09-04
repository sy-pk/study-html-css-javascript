# Using Javascript to Build Web Applications  
Enhancing the functionality of our restaurant web application by introducing a fun twist to the Specials menu category.  
Previously, when users clicked on the "Specials" tile on the home page, they were directed to a fixed menu category called "Specials."  
Now, this assignment changes that behavior by redirecting users to a random category page each time they click on the "Specials" tile, whether it’s Lunch, Dinner, Sushi, or any other category.  

In order to accomplish this, we need to change the home HTML snippet and, besides pulling it dynamically from the server, also insert a random category `short_name` into the function call of the following code.  
Previously, the code to send the user to the "Specials" category was this:

```html
<a href="#" onclick="$dc.loadMenuItems('SP');">
```

For this assignment, we changed this line to prepare it for a random category `short_name` to be this:

```html
<a href="#" onclick="$dc.loadMenuItems({{randomCategoryShortName}});">
```
You are NOT allowed to change the `home-snippet.html` file.   
Any adjustments to the value of `randomCategoryShortName` property needs to be done in `js/script.js` file.  

## Preview of [Completed Assignment](https://cailynp.github.io/study-html-css-javascript/Module%205/)
<img width="697" alt="Screenshot 2024-08-23 at 11 28 28 AM" src="https://github.com/user-attachments/assets/21400d36-9b4f-436d-b328-867b044b2be2">| <img width="697" alt="Screenshot 2024-08-23 at 11 28 20 AM" src="https://github.com/user-attachments/assets/3b12a665-749f-4ff8-b982-1a4fea90581b">
--- | --- |
