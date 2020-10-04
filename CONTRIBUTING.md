# Contributing (Magister Magic)
### Requirements
1. To contribute you must have access and a decent understanding of the Magister website 
2. Familiarity with the css root (variable) system 
3. Try to leave existing comments intact 

## Contributing to the Source
1. Fork the project
2. Add the stylecode related to your update to all [distribution files](https://github.com/Trigstur/MagisterMagic/tree/master/dist) 
3. Define the type of update by putting it under a comment as followed
```css
/* ==> what the rule(s) are intended to do here <== */
body {
display: none;
}
```
4. Updates should be put at the bottom of the css (including its comments) and synced across all [distribution files](https://github.com/Trigstur/MagisterMagic/tree/master/dist) (at the same spot)
5. Ensure that all colours are defined by a (existing) variable  
6. Pull your fork, please provide a description
7. Await curation



## Contributing to the Colorbook
Contributing to the [/colorbook](https://github.com/Trigstur/MagisterMagic/tree/master/colorbook) is the easiest way to contribute to the project
1. Fork the project
2. Create a new file within your forks [/colorbook](https://github.com/Trigstur/MagisterMagic/tree/master/colorbook) 
3. Coppy paste the base root 
```css
:root {
    --bck1: #fff;
    /* Main Background */
    --txt1: #fff;
    /* Text On Background */
    --alttxt1: #fff;
    /* Alternative Text On Background */
    
    --sidenav: #fff;
    /* Color Sidenav */
    --altsidenav: #fff;
    /* Sidenav Reversed */
   
    --box1: #fff;
    /* Box Background */
    --boxtxt1: #fff;
    /* Text on Box */
    
    --innerbox: #fff;
    /*  Color InnerBox */
    --altinnerbox: #fff;
    /* Color Innerbox Reversed */
    --altinnerbox2: #fff;  
    /* Color Innerbox Alternative */
    --innerborder: #fff;
    /* Color Inner Border */  
    
    --hovinnerbox: #fff;
    /* Hover Inner Box */
    --althovinnerbox: #fff;
    /* Hover Inner Box Reversed */
    
    --innercontext: #fff;
    /* Inner Context */
    --altinnercontext: #fff;
    /* Inner Context Reversed */
    
    --alert: #fff;
    /* Alert Color */
    --altalert: #fff;
    /* Alert Reversed Color */

    --btn1: #fff;
    /* Button */
    --hovbtn1: #fff;
    /* Hover Button */
    
    --txtbtn1: #fff;
    /* Text Button 1 */
    --hovtxtbtn1: #fff;
    /* Hover Text Button */
    
    --primary-background: var(--sidenav);
    --secondary-background: var(--altsidenav);
}
```
4. And change the colors to your liking
5. Pull your fork to the project and await curation
