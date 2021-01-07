---
title: Day 92!
date: "2021-01-07"
---


This is currently how my project is looking :

![Preview](./preview.jpg)

Now that I have completed the styling of the project I am now moving onto the last part of the project which is implementing logic within the form. I am a bit rusty but I am getting there.
Hopefully by today I will have deployed the project on Vercel with the input 100% working.

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


###### Update 2

My project is currently deployed [base apparel](https://base-apparel.jokale.vercel.app/) but I need to tweak the email pattern.

This [Mozilla attribute patterns](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/pattern) link has been helpful in helping distinguish what pattern I need to ensure that only specific things are passed through.
I also didn't realise that these attributes come with automated 'effects' for lack of a better term. Meaning when I give my input a specific pattern to follow if the user inputs something that does not match this input then a little error will come up on the page which is great!


##### My links 
[Medium](https://medium.com/@kalemajoanna)

[LinkedIn](https://www.linkedin.com/in/joanna-e-kalema-a5a5b4136/)

[Portfolio](https://joannathedeveloper.netlify.app/)

