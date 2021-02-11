# Doss-Gollin lab site

This is the source code for the Doss-Gollin Research Group's [web site](github.com/andersenlab/andersenlab.github.io).
Code is forked from the [Andersen Lab](github.com/andersenlab/andersenlab.github.io).

This is intended to be a living document, and lab members are strongly encouraged to suggest improvements to this lab guide.
Don't hesitate to reach out for help on Slack if you're stuck -- contributing to the website is a great learning experience!

## Getting Started

See https://guides.github.com/activities/forking/ for a helpful guide to git workflow

### Clone the repository to your machine

1. Fork the repository on GitHub
1. Clone your forked repository
1. `git submodule update --init --recursive` to get submodules up and running
1. `bundle install` to install required packages. If you don't have bundle set up, you will need to install it (type `which bundle` to see if you have it already)

### Preview the site on your computer

1. Follow the steps above to clone the repository to your machine
1. Open the website in your text editor (ie, VS Code) and make any desired changes
1. `bundle exec jekyll serve -w`

### Update the web site

Once you have made changes and are ready to share them:

1. Stage and commit your changes
1. Push changes (they will go to your fork of the repository on GitHub)
1. Create a pull request. Add a title and description to explain what changes you are making and why!

If you get stuck with this: *ask for help!*
You're not born knowing.

## Common Changes

There are a few things that many members may want to do

### Add yourself to the 'People' page

1. Pick a user ID for yourself; we'll call it your "anchor" (James uses `jdossgollin`).
1. Upload a picture: find a square image of yourself, preferably JPG, and copy it to `assets/img/people/<your_anchor>.jpg`.
1. Open `_data/people.yaml` in your text editor. Use James's information as a template (or use someone else's) and add your own information. To leave a field blank, just delete it!
