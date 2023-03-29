![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Unitarian Christian Timeline

![image](https://user-images.githubusercontent.com/91061592/228402388-21d33f6d-182f-45d7-96a6-f162aa503b58.png)



## Features

Navigation

The Header

menu

![image](https://user-images.githubusercontent.com/91061592/228494874-62c8c311-5262-4fab-bee0-c5633c8ed572.png)

page 1

![image](https://user-images.githubusercontent.com/91061592/228494655-3d4bf812-753b-4b7d-b91f-a4a136f944a8.png)

page 2

![image](https://user-images.githubusercontent.com/91061592/228495027-e3024924-336c-4c96-b4a1-5ebf2671ad4e.png)

page 3

![image](https://user-images.githubusercontent.com/91061592/228495221-ab7ad4e7-c11d-4a0a-b1d0-6c0174ac15de.png)

The Gallery

![image](https://user-images.githubusercontent.com/91061592/228496285-54942212-d789-4c1a-b3a5-d3299e4192f5.png)


The Contact Us Form

![image](https://user-images.githubusercontent.com/91061592/228496614-60e78bee-afe2-4235-8877-ffb8e9f94399.png)


back to top

![image](https://user-images.githubusercontent.com/91061592/228496044-31ffc755-43d9-4002-a5cd-1b73368a5bbf.png)


------

## Validator Testing

![image](https://user-images.githubusercontent.com/91061592/228220812-6e856e1f-8445-4072-a7a0-008e7ea45c1c.png)

## Deployment
------

## Credits

---

Happy coding!

---

**Menu**

I followed this [W3Schools tutorial](https://www.w3schools.com/css/css_navbar_horizontal.asp) 
to implement a Horizontal Navigation Bar

**Floating Back-To-Top Button**

I went on to StackOverflow to find a suitable implementation of a Back-To-Top Button
   I used the one designed by JakeFromSF as seen at 
   [JakeFromSF's button](https://stackoverflow.com/questions/32102747/how-to-make-a-back-to-top-button-using-css-and-html-only)
   
**Images**

To the best of my knowledge, all images used are either Public Domain or pertain to an applicable Creative Commons (CC) licence.
> sirmium.jpg: The picture of "*A scale model of Sirmium in Sremska Mitrovica, Serbia*" is by 
Carole Raddato from FRANKFURT, Germany - Sirmium, Pannonia Inferior, Serbia, CC BY-SA 2.0.

The Photo of [*a child reading the Bible*](https://unsplash.com/photos/NaWKMlp3tVs?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) is by Samantha Sophia on [Unsplash](https://unsplash.com/)

**Bugs**

Longer timeline titles such as " Melito promulgates deicide - 'God is murdered!' " were not being displayed correctly
on mobile screens; therefore I used 
```
@media (max-width: 480px) {
  .timeline h3 {
    font-size: 11px;
  }
}
```
to fix this.

Had to remove the colour from the social media icons as it was leaving a grey rectangle on the page after an icon was selected
These grey rectangles were only visible on mobiles and laptops; not on the desktop!

```
.social-networks i {
  font-size: 160%;
  margin: 1%;
  padding: 5%;
```  
  ~~color: #3a3a3a;~~

} 
