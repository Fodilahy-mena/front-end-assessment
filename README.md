# Front-end assessment

A mockup-to-website example to be used as an assessment

## Getting started

- Fork this repo to your own github account
- Clone your github account version of the repo (e.g. `STUDENT_NAME/front-end-assessment` ) to your computer.
- Work in your `main` branch

## The design

I'd recommend downloading the Figma App if you haven't already.

### On Figma.com

You can [find the mockup on Figma](https://www.figma.com/file/SC3HqLUP9hGBfn93mIwxkS/Sports-App-homepage-Responsive-Revised)

### As a `.fig` file

You can [find the `.fig` file in the source folder of this repo](source-materials/sports-app.fig).

Open the `.fig` in the Figma App, or import it/drag it into the Figma.com workspace in your browser.

## Resources

I've extracted all the images in multiple formats, and placed them in the `source-material/imagery` folder.

So too with downloading the fonts. Have a look in the `source-material/fonts` folder.

## Development

The `webroot` folder is where all your work should go. You'll notice there's already an `index.html` and the supporting folders inside the `webroot`.

## Requirements

Your work on the site header, and masthead will be the primary focus of this assessment.
i.e. you must first deliver these two elements, so that they can be marked.

The rest of the components of the site, we'll do later as an exercise.

### Marking

Your work will be marked on the following criteria:

- Git
  - Commits, commit messages, and their frequency (how often you commit)
- Code
  - All code should be:
    - well-formatted and clean
    - easy to understand
    - self-documenting
    - using comments when needed
    - named well (e.g. class names should be relevant)
  - HTML
    - Use of HTML elements
    - Accessible
  - CSS
    - Well-structured and easy to find relevant files
    - Good / consistent naming conventions (methodologies)
    - Reliable and simple techniques used (e.g. Flex vs. Grid vs. Normal flow, etc)
- Results
  - Should work in both Firefox and Chrome
  - Responsive, supporting mobile and desktop devices
  - Be accessible (You should use accessibility techniques we've covered in our courses)
  - Accurate as possible (Your end product should look as similar to the designs as possible

### Bonus marks

Bonus points will be awarded for code that uses:

- a new technique you had to research while doing this assessment
- elegant (thoughtful) solutions to complex problems
- going the extra mile (putting in more effort to push for high quality or delight)

<!-- *********************** -->

## Continue as an exercise
### About sass

#### Install the Project

We use `npm i` to install our project.

#### Run css

We use `npm run css:watch` every time we make a change in our css.

#### Steps to start sass

- Create an new branch out of your branch for example: `sass` or `my-sass`.
- Work on your new branch
- On github, we run `npm init` command.
- Press enter, enter... until we get this from github: `Is this OK? (Y/N)` we accept it so `y`
- Git add and commit
- The run a command `npm i -D node-sass` (Div dependancy).
- Create a `.gitignore` file inside of your repository. Aligne with readme.mdn. Indide the `.gitignore` file, we type `node_modules` so that it will be ignored.
- We copy thi inside of package.json file `"scripts": {
    "css": "node-sass scss -o webroot/css"`
- Move all of your css files to scss folder by running `git mv webroot/css scss` command. And rename all css file with `_` underscore at the begining and `scss` at the end. Note: The `index.css` will be renamed as `index.scss` without `_` at hte begining. And link all of the `scss` files in `index.scss` file.
- Add and commit.
- We run `npm run css` on VsCode terminal.
- Then we add `"css:watch": "npm run css && node-sass scss -w -o webroot/css"` in package.json after the reccent one with a comma.
- The run `npm run css:watch` on VsCode terminal.

- Git checkout your main branch and merge your new branch to it, and push.

***Tnat's all!***

