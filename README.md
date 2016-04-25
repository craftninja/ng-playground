# README

### How did this get made?


#### Inital setup

1. make directory, `git init`, `npm init -y`
1. Change test script to start script with this value:

  ```json
  "start": "http-server -c-1 -o"
  ```

1. touch index, html-ify and add a header to make sure stuff was rendering
1. `npm start`
1. made this awesome README and take notes

#### Add bootstrap

* find the current CDN

#### Add angular

1. find the current CDN
1. in body put `{{1+2}}`
1. add `ng-app` as attribute to html

#### Add input

* Copy and paste from bootstrap horizontal form, edit a wee bit
  * instead of having a form with class form-horizontal, class is on a div

#### Hooked up a model and display on page

1. Added `ng-model="name"` as attribute to input
1. Added `{{name}}` to h1 to output name

two-way data binding!!! omg
