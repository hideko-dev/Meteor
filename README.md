# Meteor

A simple, meter-based to-do list built with Electron and React.

![Meteor](https://raw.githubusercontent.com/Hideko-Dev/Meteor/master/assets/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202023-05-20%20221701.png)

## Download

Nab the latest version from the [Releases](https://github.com/Hideko-Dev/Meteor/releases) page!

## Development

- Clone the repo:

```bash
$ git clone https://github.com/Hideko-Dev/Meteor.git
```

- Go to the project directory and install dependencies:

```bash
$ cd Meteor && npm install
```

To show the Electron application window with your current build:

```bash
$ npm run dev
```

To build a production version:

```bash
$ npm install
$ npm run postinstall
$ npm run pre-electron-pack
$ npm run electron-pack
```

## Contributing

So you want to contribute? Yay! Great! Fun!
I love seeing new PRs for Meteor. That being said, not every pull request will be merged. The general guidelines I'll follow are:

- Does it make developing Meteor easier?
- Does it help other platforms (Windows, Mac, Linux) work better?
- Does it fix a bug?
- Does it break anything?
- Does it stick to the original goal of Meteor (a _simple_, meter-based to-do list)
- Does it reduce the build size?
- Is it necessary?

Regarding that last point, I don't expect all pull requests to be absolutely necessary. New features are good. That being said, if the new features make the app unnecessarily complex in some way without bringing value to the users, it won't be merged.

Please don't be hurt if your PR isn't merged. You're lovely for working on it. If you are thinking about working on something, feel free to make an issue beforehand so that you can make sure it'll be worth your time!
