This README.md is to list my thought process/thoughts/comments/concerns about the project as I go through it.

update 1: project says to add the "style" attribute with the "background-image" property inline in the <div> tags. My understanding is that even though this method of styling is allowed, it is not the "best practice" method. I will change this at the end of the project to include it in the "styles.css" file to see how it affects the project.

update 2: Completed project. This is the final form of the project. The last thing that was added was a transition property to the "panel.active h3" selector so that the h3 content opacity is set to 1 with an ease-in and after a delay.

***
Note: I did remove the "style='background-image url();" attribute from the .panel div elements, and added it to the styles.css file using two methods.

The first method was by adding a .panel+n class to each .panel div, then selecting that class and adding the "background-image" property to the stylesheet.

The second method was by using the .panel:nth-of-type() selector for each of the .panel class, then adding the "background-image" property to each one.

I'm not sure why the instructor of this project chose to put the style attribute in the html. It may have just been for the sake of convenience or simplifying the follow-along process.

My understanding is that putting that attribute/property in the styles.css file would make it easier to make future changes and also optimises the webpage.
***