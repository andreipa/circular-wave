# Circular Wave Technical Assessment #

For this assessment we'll need you to fix some broken code.

## What we are looking for ##

This assessment is all about your problem solving and grasp of JavaScript. You shouldn't need any libraries or frameworks, just vanilla JS (ECMAScript 5). We are not testing your knowledge of the latest and greatest ES6 - although if you want to use it you're welcome.

## Guidance ##

* You'll probably benefit from using a debugger. We recommend using Chrome and Chrome DevTools for this
* You won't need to touch any file except for `testfile.js`
* You can leave `index.html` alone - any classes / IDs you need are already referenced in `testfile.js` and you shouldn't need to do any extra DOM manipulation
* Don't go looking for clues in `server.js` - it's minified and won't help anyway.
* Use of libraries isn't necessary
* Feel free to use the internet if you get stuck

## What the app should do ##

On running `index.html` in a browser, the app should simply show a list of line items of employee shifts. On pressing the "Get next" button, the app should

1. Change the text and style of the "Get next" button to "Loading..."
2. Synchronously retrieve a random number of record IDs from a "server" (this is simulated and doesn't require an internet connection)
3. Asynchronously retrieve the corresponding records from the "server", only proceeding when all records have been received
4. Sort the records in date order, oldest first
5. Render the records into the table
6. Calculate total hours worked and render them into the table
7. Reset the button to its original state

## What you need to fix ##

1. Ensure the "Get data" button changes its appearance correctly
2. Aggregate the "async" data returned from the server, only proceeding once all responses are received
3. Sort the records according to date, oldest first
4. Ensure the records render properly in the table
5. Ensure the totals are correct
6. Ensure the button returns to its starting "Get data" state


There is no time limit, although you can reckon on around 2 - 3 hours. You don't have to finish it all - we are looking for clear thinking and problem solving more than perfect code or JS knowledge. just get as far as you can. When you've finished, save the whole folder and email it to us at info@circularwave.co.uk along with how long you spent.

Thanks!
