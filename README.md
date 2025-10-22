# Slither.io JavaScript Bot & Zoom

A user script for Slither.io that combines automated gameplay (bot) and manual zoom controls to enhance your gaming experience.

## Description

This project provides a JavaScript user script that runs in browsers with a userscript manager (like Tampermonkey or Greasemonkey). It automatically controls your snake in Slither.io using a bot algorithm, while also allowing you to adjust the zoom manually for better visibility. Toggle the bot with the `E` key and control zoom using `1` (reset), `8` (zoom out), and `9` (zoom in).  

The bot includes adjustable parameters for chasing prey, avoiding enemies, and optimizing score based on your gameplay. It also saves performance data locally for learning over time.

## Getting Started

### Dependencies

* Userscript manager: [Tampermonkey](https://www.tampermonkey.net/) or [Greasemonkey](https://www.greasespot.net/)
* Compatible browsers: Chrome, Firefox, Edge, or other modern browsers supporting userscripts.
* Internet connection to access Slither.io

### Installing

1. Install a userscript manager in your browser.
2. Create a new userscript in Tampermonkey/Greasemonkey.
3. Copy the content of `Slitherio_Bot_And_Zoom.user.js` into the new script editor.
4. Save and enable the userscript.
5. Visit [Slither.io](http://slither.io) and the script will automatically activate.

### Executing program

* Open Slither.io in your browser with the userscript enabled.
* Use the on-screen UI to toggle the bot.
* Keyboard controls:
E = Toggle Bot
1 = Reset Zoom
8 = Zoom Out
9 = Zoom In

* The bot will automatically navigate, chase prey, and avoid threats.

## Help

* If the bot doesn’t activate, ensure Tampermonkey/Greasemonkey is enabled and the script is active.
* Make sure your browser allows JavaScript and no other scripts block Slither.io functions.

Check Tampermonkey/Greasemonkey dashboard to confirm the script is enabled.


## Authors

Jason j4gwire (Primary Maintainer)   

Original code contributors: j4gwire & Icewerve

## Version History

* 1.2.1
    * Bot & zoom combined in a single script
    * UI enhancements with status display
    * Improved zoom control
* 1.0
    * Initial release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
