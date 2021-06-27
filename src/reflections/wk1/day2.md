# Intro to CSS

## What is a Pseudo-Class and what are some of the most common ones you think you will use
A Pseudo-Class is a selector that runs on elements that are in a specific state. I think these are two pseudo-classes we will use:
* example:hover
* example:visited

When I think about common applications I use, most buttons change in some way when they are hovered over. Maybe they get a drop shadow, maybe the color changes. I think users like the acknowledgement that they are in fact hovering over the correct button. Visted is probably not quite as common but, a lot of links do change how they display after they've been visited so the user knows where they've been. I think I would use this one often as well.
## What is Specificity and how might you use it to your benefit?
Specificity is the priority that CSS rules are given when multiple rules are assigned to one element. This can be used to reduce repetitive code. For example, your page may have multiple buttons. You may have one rule for buttons but, for certain ones that you want to look different (maybe a delete button), you can add a rule with higher specificity to change an aspect of that button's appearance. This way, you don't need to have a bunch of different button rules that are almost entirely the same.
## What problems do you think you could run into if you over-utilized the !important feature?
I think my biggest problem is that I would forget about it. I'd think that I wrote a rule with higher specifity and then not understand why it wasn't displaying properly. So, my biggest problem would be wasting time. Along the same vein, if another developer came along and needed to add to my code, they would likely go through the same issues I forsee for myself.


[My Daily Project 'CoolSite'](https://amanda-rice.github.io/CoolSite/)