## Introduction
In recent years the browser support for the acrobat pdf plugin is on the downfall. All major browsers today like chrome, firefox, internet explorer and safari don’t support it anymore. Due to this the Acro Forms are not working on the browser. Many companies are struggling to find the support. This is a small attempt to create a hybrid application that allows user to fill html form and then populate the pdf form with that data. This application is a client-side solution to the problem and doesn’t need server-side logic to function.


## Third-party Libraries
I have made minore changes to following library for the solution to work:
[https://github.com/phihag/pdfform.js](https://github.com/phihag/pdfform.js)


## ClockWorks
I have used react with redux to create the single page application. The application is responsive and works on the different screen sizes. The form that user will fill is a Federal W4 form. To demonstrate that solution works, the user can only fill out the first page of pdf form. The application styling is provided using Materil-UI react library.

The application works slightly different on mobile phones as the browsers on the phone won't render the pdf correctly in an iframe. Therefore, on mobile phones instead of displaying pdf in a model window the pdf opens in a spareate page.

The layout of the application is fairly simple. The user progresses in a ste-by-step manner filling out the information on each page. Hitting next updates the application state. Finally in the end the user is presented with an option to preview their data on the pdf form. 

The application is hosted at: [https://manik-dev.github.io/pdffed/](https://manik-dev.github.io/pdffed/) 

The code exists here: [https://github.com/manik-dev/pdffed](https://github.com/manik-dev/pdffed)






