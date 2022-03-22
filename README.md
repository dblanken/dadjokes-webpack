# Dad jokes (Webpacker testing)

## What is this?

This is my implementation of what Traversy Media created on
[Youtube](https://www.youtube.com/watch?v=IZGNcSuwBZs) to better learn
Webpack.  I found it very fun to create a dad joke generator, so I decided to
place it on here as well.

Brad's original repository is located
[here](https://github.com/bradtraversy/webpack-starter).

I'd like to thank Brad for publishing a youtube on Webpack as it can help me
understand and use Webpacker with Ruby on Rails a bit better than I did
before.

## How do I install this?

You will need the following:
* [npm](https://docs.npmjs.com/cli/v8/commands/npm-install)

Run the following:

* First clone the repo:
```sh
git clone https://github.com/dblanken/dadjokes-webpacker
```

* Then go into the local copy:
```sh
cd dadjokes-webpacker
```

* Install the NPM dependencies
```sh
npm i
```

* Build the assets.  Note that doing this will open a browser with a map
  showing all of the files and dependencies the application uses, which you
  can choose to drill down to.  You can CTRL-C in the CLI to exit the server
  for that.
```sh
npm run build
```

* Run the application.  This will open two browsers:
  * One is the same output as before showing the file mappings; you can close
    it.
  * The other labelled "Webpack App" is the application

```sh
npm run dev
```

* To exit, CTRL-C the webpack server in the CLI.

## What does this do?

It's a dad joke generator.  It uses icanhazdadjoke.com to display a dad joke
to you.  It does all of this using webpack to manage such things as templates,
images, SCSS, HTML generation, etc.

## I found a bug!

Uh, look at Brad's repo, not mine.  This was just a nifty way for me to learn
more about webpack and I wanted to share it with friends.
