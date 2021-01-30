[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/lamact/react-issue-ganttchart)

react-issue-ganttchart
===================

This is a single page application created with React to display Github/(Gitlab) issues as a Gantt chart.  
Repository URL and personal access token are required, but not the rest.  
No backend is required, and the token is stored in a cookie.  

## Demo
https://lamact.github.io/react-issue-ganttchart/

## Requirements
- URL (your repository's path)  
  ex: https://github.com/lamact/react-issue-ganttchart
- Personal Access Token  
  Scopes: public_repo, write:discussion

## How to start on your server

 - clone the repository or download files
 - install dependencies
~~~
yarn install
~~~

 - run server
~~~
yarn start
~~~

- build and deploy for Pages
~~~
yarn deploy
~~~
