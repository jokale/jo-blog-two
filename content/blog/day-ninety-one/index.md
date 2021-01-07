---
title: Day 91!
date: "2021-01-06"
---
Another day another project...

I am  about to start building a  build out this coming soon page  for a fake apparel brand. Still the same concept of having an example and being able to build/replicate the page.
The aim of the project is to ensure users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the form is submitted if:
  - The input field is empty
- The email address is not formatted correctly



This is a preview of the page I will be trying to rebuild: 

![Preview](./preview.jpg)

This project will be slightly different however I will be using javascript as I will need to validate the form when it's submitted.

Once complete I will be using Vercel to deploy the site.

#### Updates:

Created some validation through a handleClick function through an onClick with my submit button :

```
   handleClick (e) {
    var x = document.forms["form"]["email"].value;

    if (x === "") {
      alert("Email must be filled out");
      return false;
    }
    else {
      alert("Thanks we will email you when the store is open!")

    }
  }
  
```

Whereby if the user email input is equal to nothing then the user will get an alert on the page where it reads email must be filled out. 
However I don't want to annoy the user with alerts but rather with text on the page. 
I will keep working on this.

##### My links 
[Medium](https://medium.com/@kalemajoanna)

[LinkedIn](https://www.linkedin.com/in/joanna-e-kalema-a5a5b4136/)

[Portfolio](https://joannathedeveloper.netlify.app/)

