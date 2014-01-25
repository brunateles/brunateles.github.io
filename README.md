=== Instructions

Requirements: Make sure you have an SSH key setup to your Github account (https://help.github.com/articles/generating-ssh-keys).

The following is needed the first time setting up Jekyll in a development machine
(it needs to be run in the console under the project directory):

- git clone git@github.com:brunateles/brunateles.github.io.git
- cd brunateles.github.io
- sudo gem install bundler
- sudo bundle

To run the development server:

- jekyll server --watch

After making changes, send them to github:

- git add --all
- git commit -m "Replace this with your message"
- git push

To publish the changes:

- rake
