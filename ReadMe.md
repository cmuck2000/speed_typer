# Speed Typer ReadMe

---

![beterhomescreen.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/beterhomescreen.png)

taken on an ultra wide monitor

[Speed Typer](https://cmuck2000.github.io/speed_typer/)

## Design

---

- Colour Scheme
    
    ![colorscheme.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/colorscheme.png)
    
    I used [https://colorpalettes.colorion.co](https://colorpalettes.colorion.co/#top) to pick a colour scheme. I picked this icey mix of white,grey and blue as i thought it looked very sleek and modern, and suited the UI of my site
    
- Typography
    - 'Roboto', sans-serif;
    - 'Gemunu Libre', sans-serif;
    
     I chose these fonts as I thought they had a sleek and modern feel which suited the rest of my site. I also tested multiple fonts for visibility as I had to ensure it would be easy to read and duplicate by typing it out with no issues.
    

### Home Page Wireframe

![webwireframe.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/webwireframe.png)

---

### Mobile Wireframe

![mobile wireframe.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/mobile_wireframe.png)

---

## Features

---

### Responsiveness

---

![responsive.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/responsive.png)

fully responsive across all device sizes

---

 the game is designed to respond well to any screen size, even though it is targeted at pc users using a keyboard to improve their typing, it was built using a mobile first design to allow for easy loading and layouts on smaller devices.

### main game box

---

![game_running.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/game_running.png)

this is the main game box of the site. I have made it as intuitive as possible, with big UI elements and a clear purpose for everything. the i icon opens up a pop up with more information. the progress bar tracks the time remaining, and displays Get Ready! and Done! when they occur. the play button begins an audible timer before the game starts. The black score tracker displays a live score as you submit words. Each click on the input has an audible noise, and the word above dynamically turns its characters green or red if your input matches.

### button bar

---

![buttons.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/buttons.png)

---

these toggle buttons allow the user to customise the game experience to their liking on the fly with no confusing menus. it allows them to mute/unmute the game sound, change the length of the words they are typing, and change their username. all of the buttons update to reflect what the user has selected.

### Highscore Table

---

![table.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/table.png)

---

after each game is completed the table is automatically updated to reflect the username,score and time of all games played. there is no limit to how many can be stored so it adds an element of repeatability and competitiveness to an otherwise repetitive game.

### Information/username pop up

---

![infoscreen.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/infoscreen.png)

---

this box fades into view when the information or  change username buttons are pressed, and it also loads in to begin once the other DOM content has been loaded. it features a brief summary of how to start a game and control the website, and offers a prompt to change the username for record keeping.

(note the black box on the input is my password manager i could no disable for the photo not a UI element)

### Alert

---

![alert.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/alert.png)

---

this alert is triggered once the username is changed to confirm to the user what the new username they have selected is.

### Footer

---

![footer.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/footer.png)

the footer features my trademark, a link to the git hub repo for any curios players or devs and my linkedin profile for anyone who is impressed by the project. it is high contrast so it is easy to notice and read but it suits the theme of the sites still.

---

## Technologies Used

### Languages Used

- HTML
- CSS
- JS

### Programs Used

1. Google Fonts:
    - Google fonts were used to import the fonts.
2. Git
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
3. GitHub:
    - GitHub is used to store the projects code after being pushed from Git.
4. Balsamiq:
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.
5. Notion
    - I used notion to organise protypes of my JS functions and use things like to do lists to help the project run smoothly.
6. FontAwesome
    - I used FontAwesome to import the icons for the website
    
    ---
    

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

- W3C Markup Validator

![htmlval.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/htmlval.png)

---

- W3C CSS Validator

![cssval.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/cssval.png)

---

- JSlint

![jslint.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/jslint.png)

the js validator orignally had multiple  variable and forgotten syntax errors that I went and dealt with, but the first one listed here broke my code to alter in any way. it is still functional just not "best practice"  according to JSlint.

there is also multiple errors for lines above 80 chars which is because of the way I imported them in so I am ignoring them

### Further Testing

![lighthouse.png](Speed%20Typer%20ReadMe%20f9b7ef65c78a4483b2a13b445321c3b4/lighthouse.png)

---

- lighthouse was also used to test the website and received the scores above.
- The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
- The website was viewed on a variety of devices such as Desktop, Laptop, iPad, iPhone 11.
- Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

---

### Known Bugs

- Despite my best efforts I could not get the favicon I made to work.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps.

### Python web server

a Python web server was used during development to test changes live.

## Credits

### Code

- the function of comapring the input and the displayed string and rendering a new word comes from

[Build A Speed Typing Game With JavaScript - Tutorial](https://www.youtube.com/watch?v=R-7eQIHRszQ&ab_channel=WebDevSimplified)

- **w3schools:** I used the this website as my go to reference when I could not remeber the logic or syntax to implement something.

### Content

- The color scheme was taken from an online colour pallete which i referenced in the color section above
- this repo for the long list of commonly used words that I used to create arrays to pull values for the game from.

[GitHub - first20hours/google-10000-english: This repo contains a list of the 10,000 most common English words in order of frequency, as determined by n-gram frequency analysis of the Google's Trillion Word Corpus.](https://github.com/first20hours/google-10000-english)

### Acknowledgements

- My Mentor for continuous helpful feedback.
- My friends for testing the game for me
