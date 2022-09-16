# Free Resume Scanner - Frontend

Free Resume Scanner is open source-- feel free to clone the code and change it as you like but please do keep the license present.

We use [Plausible](https://plausible.io) for data analytics, which collects no user data.

We don't collect any of your no resume data whenever you submit it to our [backend lambda](https://github.com/toul-codes/free-resume-scanner-review-api)

We hope that it helps you both for your resume and as a dev for a starting framework for building web apps with blog 
components to bring your ideas to the web--without going broke.

## How to work on the Frontend 

Clone the repository and run `hugo serve` this will start a server on `localhost:1313` with hot reload so that each time
a file is changed the website is refreshed with the latest changes.

### To change the Feel of the project 

#### Update the CSS
Update the `static/css/stylec.css` this contains most of the code used to style the website.

#### Bootstrap 5

There is a suboptimal import of bootstrap 5 in the `index.html` file so you can use Bootstrap to further style the app 
page of the site. However, it is preferred to keep the app page simple.

### Open a PR

Once the changes have been made then open a PR and someone from the project will review it to make sure nothing breaks.
