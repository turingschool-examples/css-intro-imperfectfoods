# Intro to CSS Practice

## Imperfect Foods Comp Recreation

You will be recreating the comp below.

#### The Comp:
![desktop](https://user-images.githubusercontent.com/51416773/142955257-7a54498c-c349-41b9-9f22-686aed19e067.png)

## Set Up Instructions
1. Fork and clone this repo
2. `cd` into the directory
3. Run `code .` to open the repo in VS Code
4. Run `open index.html` to view your app in the browser

## Instructions
### Some notes:
- The HTML is already there for you, but feel free to change that file as you wish (add elements, add IDs or classes, etc).  
- The CSS file has the font and colors listed for you. You do not need to import anything for the font, we've done that for you (HTML line 5).
- Don't worry about the worn design in the background. We will just make the background one solid color.

<br>

### Iteration 1 (`CSS: Fundamentals` lesson):
- Do *not* worry about the layout (where elements are on the page) yet! We'll get to that after your Flexbox lesson.
- Make the text match the font and sizing from the comp
- Make the colors match the comp
- Make the image sizes match the comp
- Style the button to match the comp

<br>

### Iteration 2 (`CSS: Flexbox` lesson):
**GOAL:**  
Use flexbox to control where the elements are on the page in order to make the layout match the comp.  

**Hints:**  
- You may need to add container elements to your HTML to group the `img`, `h2`, and `p` elements that you're trying to adjust the layout of.
- If you have similar containers holding similar items that you want to layout in a similar way, maybe those containers should all share a class so the flex styling you apply gets applied to all of them.
- While some of the layout work will require flexbox properties, there may be other CSS properties you need to tweak as well to fully match the spacing and layout of the comp.  `text-align`, `padding`, `margin`, `width`, etc
- The picture of the comp above was taken as full screen.  If your browser window is smaller width, parts of that comp will bump to a new line. You are NOT expected to make your CSS responsive (meaning it looks good on small, medium and large screens). Just style it to match the comp when you have it full screen and dont worry about smaller screen sizes.  
<details>
<summary>How to move your dev tools to the bottom of the page</summary>
<br>
In the Chrome Dev Tools, use the ants-on-a-log button to change the "Dock side" of your dev tools so that they show up across the bottom of your browser window, not off to the right side. This will allow your browser window to remain full screen width as you're using the dev tools.  
  
![http://imgur.com/a/H3fZ6TT](https://i.imgur.com/QaDCzhX.png)  

</details>

**Together:**  

As a class, let's do some wireframing on the comp we're trying to match.  
What are the groupings of elements we're trying to adjust the layout of? Lets draw a box around each grouping.  
Then, we can pick one box/grouping to focus on and try to use flexbox to adjust the layout in just that box.

**Ask yourself:**  
- Which elements are in that box?  
- Do they already share a direct parent in my HTML?  Or do I need to add a container element around them in my HTML?  Lets put a visible border around that parent container to help us see it for now.  
- Add flexbox to the parent and first focus on getting the children elements to be arranged in the direction you want - row or column.  Then you can try to adjust the way they're spaced within that box.  
- Once you're successful aligning the layout of the elements in one box, choose another and work on that one. 



