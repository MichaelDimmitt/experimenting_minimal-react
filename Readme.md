Playing around with the package.json provided by johnathanconway as a react base.

https://gist.github.com/jonathanconway/15271dda82b1de39e12eb938ac4a6e8


## Plan: 
1) scaffold facebook create react app in a seperate folder. 
1) eject app from create react app dependency.
2) move the files but not node_modules or package.json.
3) get the thing to work.
4) get the first test to pass. 
5) maybe write some tests or button up to make most stable.
6) change folder/file structure to something I prefer.

7) potentially, link up redux

## A few notes and lessons learned.
1) warning, package.lock file 😰, still 10,000 lines of code.
2) warning, dont clone down create-react-app and move packages folder over. 
<br>they hardcoded dependencies so that it would not play nice.

