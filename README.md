# 2017 Pittsburg Seafood & Music Festival

## About the Project
The Pittsburg Seafood & Music Festival - the two-day, outdoor extravaganza that draws thousands of visitors to Pittsburg every year - has long been one of the keystone events in Contra Costa County. This repo contains the exportable style theme that will be used on the offical event website. 

## How to Contribute
The easiest way to successfully merge a pull request into master would be to open up a feature branch to tackle a specific bug/ feature on the issues section of the repo. Upon completion of a particular feature or bug-fix, merge your code into master and delete your branch. For more details on the typical agile development workflow, take a look at this article: http://blog.hasmanythrough.com/2008/12/18/agile-git-and-the-story-branch-pattern

*[Check out our Waffle Backlog to see what issues are ready to be tackled, and what issues are still being defined](https://waffle.io/MosesSupposes/2017-Pittsburg-Seafood-and-Music-Festival)*

## Development
To get started with development, first clone this repo to your local machine.
```
git clone https://github.com/MosesSupposes/2017-Pittsburg-Seafood-and-Music-Festival/edit/master/README.md
```

[Next, open up the live site in your browser:](https://pittsburgseafoodandmusicfestival.com)

Then, open up the dev tools (F12 for chrome or Crtl/Cmd + Shift + J for firefox). Link the browser's active directory to your cloned directory on your local machine. If done correctly, all of your changes made to the online editor will be reflected in your machine's file system. 

Finally, push your feature additions or bug fixes to master by opening a pull request and awaiting a code review from a fellow team member. (Feel free to request a review!)

__Additional Tips & Guidelines:__
+ Only edit/ create CSS and JS files for this project, no HTML additions! (Unless its header information.)
..+ In the event that you do add an HTML partial, add it in the root directory, not inside of any subfolders, that way our theme package remains exportable to the Weebly platform.
+ To add CSS, include any custom files in the styles folder (obviously), and make sure to link to it in main.less.
..+ Do not edit main.less directly, unless importing an external CSS stylesheet. Here's a helpful resource on how to make CSS additions to a Weebly theme (ignore the direct CMS modification aspect of the article): https://www.webnots.com/how-to-add-css-in-weebly-site/
+ To add a JS script, the Weebly standard-compliant way to do so would be to add any JS files in the assets folder and link to it in the header HTML files. For more detailed information on that subject, check out this article: https://www.webnots.com/how-to-add-javascript-in-weebly-site/
+ [jQuery API Docs](https://jquery.com/)
