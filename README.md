### Instructions
- Run `npm i` to install the packages
- Run `npm run dev` afterwards to start the dev server, go to the URL which this command outputs.

Everything should be working fine now, you should see a simple webpage with red box with 'Content' in it.

Now open `tailwind.config.js` and uncomment `require('tailwind-children')`, after you save the page should keep on loading indefinitely, when you comment `require('tailwind-children')` again and restart the dev server everything should be working again.
