# Journey in Russia

Since 2020 domestic tourism for Russians has been in particular demand. On this site you can get acquainted and find new russian places in Russia, where you must have time. Here you can find information about the most picturesque places of Russia.

## Functions

On this site the user is able to:

* read information about tourist places and click on links to their representative offices;
* prepare for the trip by using the resources in the "basement";
* go to and learn the blog about the journey to Baikal firsthand.

## Technology stack

The project layout in Figma illustrates the blocks and elements' position in different devices' resolutions.

**Figma**

* [Figma layout link](https://www.figma.com/file/5S2WSbEFL6awjVWJ0NWL8Q/Sprint-3_-Russia-_-desktop-mobile?node-id=28503%3A0)

1. The key technology for the responsive of the website is:
```css
.block {
  display: grid;  
}
```

As well for responsive realization there are flexboxes.

2. The picture with the trains is a backgroud link. The pseudo element `::before` was implemented for this task.

3. The file structure is organized according to BEM methodology, which means flexibility in project modification. Each contextual block can be reused if additional information is needed, or deleted without affecting adjacent blocks.


**Link GitHub Pages**

The project is published [here](https://barbylka.github.io/russian-travel/).

This project was developed as a training course project, thus, any comments on refinement and optimization are welcome!
