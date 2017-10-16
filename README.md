# Demonstrates the issue reported under [angular/angular-cli#7828](https://github.com/angular/angular-cli/issues/7828)

This is the example project demonstrating the issue of Angular CLI not reloading changes of external script files.

Run ng serve and open the webpage.

You will see `hello` logged to the console.

Now edit the `src/update.js` file, change it to something like `console.log('hello world');`. 

Refresh the webpage - you should still see `hello` logged.

The Angular CLI used in this project is 1.4.2. which should based on this [comment](https://github.com/angular/angular-cli/issues/7828#issuecomment-333604019) resolve the issue but as demonstrated it doesn't.
