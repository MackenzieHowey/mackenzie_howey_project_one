1. Naming Convention: BEM (Block-Element-Modifier) 


BEM will be used for HTML, CSS, and SCSS:
<! -- Example-->
<div class=”gallery”>
        <h1 class=”gallery__title”>Gallery</h1>
        <img class=”gallery__image gallery__image--large”/>
                        <img class=”gallery__image” />
                        <img class=”gallery__image” />
                </div>




2. SASS (SCSS)


Our project will be organized with the following SASS partials:


* style.scss
   * _header.scss
   * _home.scss
   * _contact.scss
   * _blog.scss
   * _footer.scss
   * _media.scss
   * _setup.scss
   * _variables.scss
   * _mixins.scss


3. Formating
* Single tab (4 spaces) for indentation
* No ID selectors
* Files , folders and project repo follow a consisting naming convention (ie. kabob-case)
* When using selecting multiple element with selectors, give each selector its own line
* Double quotation marks for strings










4. Commenting Style
* Comments at opening
* Comment before each major section(header , main , etc)




5. Colors


* Hex code system will be used (in addition to any variable that may be assigned a hex code colour)






6. Media Queries


/* Portrait tablet and small desktops */
@media (max-width: 940px) {
}


/* Landscape phone to portrait tablet */
@media (max-width: 768px) {
}


/* Landscape phones and down */
@media (max-width: 480px) {
/
