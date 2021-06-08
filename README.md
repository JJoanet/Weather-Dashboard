# Homework6
MADE IN COLLABORATION with Zach Duty and Matt Reisdorf.

WEATHER DASHBOARD!!!!

This one was actually really fun. A lot of copy pasta for the if statements, but it taught me that I strongly prefer working on backend over front end.

I started this project by building my HTML shell with bootstrap, after everything was properly spaced and sized I moved over to my JS

First thing I did was ensure my API pathing was sound. After establishing a baseline I moved on to migrating that data to my individual cards for current and future weather.

My Input form was next up, and after beginning I soon realized I needed to wrap my fetch commands into a function that would trigger on page load and on user input.

With my input form and button operational I moved on to setting up user geo location, I figured what good is a weather app if it defaults to chicago and doesn't try to grab user's data.

Next I created the buttons that would be generated based on user input, I baked these into the search form.

I linked the generated buttons to an on click event listener tied to the UL they're appended to, and added a stop propagation to ensure only the button I click is the one that triggers.

I stored the previous searches to localstorage so people can pick up where they left off.

Finally, I styled the thing... I was kind of going for a small town vibrant vibe, my partner likes pastel and neon colors so I figured why not.

Hope you enjoy!

![ScreenShot](./assets/imgs/Screenshot.PNG)

## Live Deploy

# ReadmeGenerator

# Contact
Vygoth
JeremyJoanet@Protonmail.com

## Description
This Application allows users to create README files on the fly!

## Table of Contents
- [Usage](#Usage)
- [Installation](#Dependancies)
- [Testing](#Testing)
- [Credits](#Credits)
- [License](#License)
- [Contributing](#Contributing)
- [License Information](#LicenseInfo)
- [Screenshot](#Screenshot)

## Usage
To begin this application, please type node index.js with node installed.

## Dependancies
npm i

## Testing
N/A

## Credits
Zach Duty, Matt Reisdorf

## Contributing
N/A

## Screenshot
![Screenshot](./assets/img/screenshot.png)
