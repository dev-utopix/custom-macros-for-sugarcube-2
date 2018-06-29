## Chapel's Custom Macro Collection 

### Contents
 * [The Dialog API Macro Set](./docs/dialog-api-macro-set.md)
 * [The Dropdown Macro](./docs/dropdown.md)
 * [The Event Macros](./docs/event-macros.md)
 * [The Fading Macro Set](./docs/fading-macros.md)
 * [The File System Macro Set](./docs/file-system-macros.md)
 * [The First Macro](./docs/first-macro.md)
 * [The Fullscreen Macros](./docs/fullscreen-macros.md)
 * [The Message Macro](./docs/message-macro.md)
 * [The Notify Macro](./docs/notify-macro.md)
 * [The Operations API](./docs/operations-api.md)
 * [The Playtime System](./docs/playtime-system.md)
 * [The Simple Inventory System](./docs/simple-inventory.md)
 * [The Typing Simulation Macro](./docs/type-sim.md)

### Installation Guide

To install these macros, all you need is the code.  It is highly recommended that you stall the minified version (found in the `scripts/minified/` directory), as these versions will have improved performance.  You will only need the non-minified versions if you plan to edit the code in some way.

To install these macros, you will need to be using the most recent version of SugarCube 2 in most cases, and this is almost never the version that comes with Twine 2.  See [SugarCube's website](http://www.motoslave.net/sugarcube/2/#downloads) for updating / installation instructions.

For **Twine 2** users: copy and paste the required JavaScript code from this repo into your [story JavaScript area](https://twinery.org/wiki/twine2:adding_custom_javascript_and_css).  Some macros may also require CSS code, which goes in your story stylehseet.

For **Twine 1**, you'll need to copy and paste the JavaSCript portions into a script-tagged passage, and the CSS portions (if any) into a stylesheet-tagged passage. You can create new passages and add the tags yourself, or right-click on a blank spot in the editor and select new script here and new stylesheet here to generate each passage.

For **Twee2**, refer to [its documentation](https://dan-q.github.io/twee2/documentation.html#twee2-syntax-special-passages) for how to create the tagged passages you need.

For **Tweego**, simply place the code in `.js` and `.css` files as appropriate and include them in your directory / command line options just as you would any other code files.

#### Installation: Troubleshooting

If you're having issues, please try the following.  Before copying the script you want, find a button above the code on the right called `raw` and click it.  Try using this code instead.

Make sure you're using the latest version of SugarCube 2 and your preferred compiler.

Make sure that any code above my scripts in your JavaScript ends with a semicolon (`;`), and try testing without my code again to make sure you didn't overwrite a chunk of the code.

If none of those common solutions get you to the problem, open an issue.  Be sure to tell me the exact version of SugarCube (found in the `Change story format` menu option in Twine 2) and the exact version of your compiler (for Twine 2, the bottom right on the story list).

Also try to screen grab or copy/paste any specific error messages.

### General Troubleshooting

If a script doesn't seem to be working right, remember:
 * Everything is case-sensitive--`<<message>>` and `<<MESSAGE>>` are not going to point to the same macro.
 * Follow the instructions carefully.  There are a few places where my macros break with traditional SugarCube things, like the orders of arguments and stuff.  I'm trying to hew closer to SugarCube's standards moving forward, though.
 * Make sure you're using SugarCube 2, the most recent version you can.  This is very rarely the same as the version packaged with Twine 2 or the other compilers.

If you're reasonably sure you've read the docs and are using the right version and such, feel free to open an issue.

### I Need Help!

If you're having an issue with these macros and suspect that it's operator error rather than a bug, you can still open an issue, but a faster way to get help would be to post in one of these Twine communities:

 * [The Official Twine Q&A](https://twinery.org/questions/)
 * [The Official Twine Discord Server](https://discordapp.com/invite/n5dJvPp)
 * [The Unoffical Twine Subreddit](https://www.reddit.com/r/twinegames/)

### You Don't Write Good...

Please take a minute and help me out by reporting any errors in the documentation via an issue, or pull request a fix if you've got the time and know-how.  Both are greatly appreciated.

### WAIT! WHERE'S THE X MACRO???????

Some macros were just too good for this world. Some turned out to be really bad ideas. Some were just so poorly written that they'll take a long time to reimplement.  That said, if a macro you need / want / like isn't here, you can [go here](https://github.com/ChapelR/custom-macros-for-sugarcube-2/releases/tag/v1.6.1) to download the original collection as it was in it's prime.

### Credit and Attribution

This code is dedicated to the public domain.  You don't need to provide credit, attribution, or anything else.  You could even pass it off as your own!

If you do wish to credit me, you can credit me as Chapel, but please do not imply that I directly worked on your game.

If you have any questions or concerns about this, refer to the [license](https://github.com/ChapelR/custom-macros-for-sugarcube-2/blob/master/LICENSE).