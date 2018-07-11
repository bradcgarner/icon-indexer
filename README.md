I love font-awesome!  I use font-awesome everywhere!

This library is a helper for font-awesome.  Feel free to fork it and make your own version.

Here is how I use it:

Decide what types of icons I want to use, such as checkmark, raindrop, or lock.
Create an object key for those icons in the library.
Select the most appropriate font-awesome icon. (Don't worry if it's not perfect... this makes changes easy!)
The library includes a single factory function.

To use:
npm install --save icon-indexer

const { icons } = require('icon-indexer);

const i = icons();

<i className={i.checkmark}></i>

When I want to change an icon (for any reason from personal preference to a new version of font-awesome, to breaking changes in font-awesome), I change it in the library and nowhere else.
