> Download my project and run: npm install

> After that install bootstrap using this : npm install bootstrap@3 jquery --save
update angular-clis.json file's style array:
"styles": [
       "../node_modules/bootstrap/dist/css/bootstrap.min.css"
     ],


> If you want change your port, goto abgular-cli.json file and add this under defaults:
"serve": {
      "port": 4300
    },

> Do ng serve -o (it will open https://localhost:5200) in your default browser
> Check your console in browser to see the output after clicking submit button

# SignupForm

This project is a demo of an Angular application with Forms. You can read the tutorial on [TutsPlus.com](http://code.tutsplus.com/tutorials/introduction-to-forms-in-angular-4-template-driven-forms--cms-29766) Angular has two popular technologies for building forms -- Template driven and Reactive technology. This project demostrates building a real-life signup form using both these techniques

## Choosing the Right Branch

Apart from the master branch, there are two branches. Make sure you are right branch and clone the repo or download the zip file. 

## Running the Development Server

Run `npm install` to install all the packages. Next, try `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
