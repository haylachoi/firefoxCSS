## Setup and installation
1. Clone this repository or download the `userChrome.css` file to your local machine
2. On Firefox, go to `about:config`, click *"Accept the Risk and Continue"* and enable `toolkit.legacyUserProfileCustomizations.stylesheets`
3. Go to `about:profiles`, locate your profile under *"This is the profile in use and it cannot be deleted"* and open the directory
4. On the profile directory folder, open (or create) the folder `chrome`
5. Copy the `userChrome.css` file to `chrome`
6. Restart the browser to apply the theme

## Customization

By default, all buttons and icons are hidden, except for the *"Application Menu"* (☰) button. This includes:
- The window control buttons (minimize, resize and close window)
- Backward and foward buttons
- Extensions button
- All tabs (⌄) button
- "This time search with..." when searching in the url
- ALL URL bar icons (permissons, bookmarks, extension icon, picture-in-picture, tracking protection, reader mode and translations)

You can change the visibility of elements in the `userChrome.css` file, just delete or comment out the lines or blocks for the ones you want to see.


## Credits
Forked from [mimipile/firefoxCSS](https://github.com/mimipile/firefoxCSS)
