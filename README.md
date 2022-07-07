# HTML 5

### Headings 

#### H1 heading should be what your page is about. There should only be one H1 per page.
#### Same goes for MAIN tag. There should only be one MAIN tag per page.
##### HR tags should be used when there is a separation in topics on the site

### Images

#### Images used on site must have an alt attribute, but TITLE attribute is not required, but adds complimentary text when hovered over the image.

#### WIDTH and HEIGHT are comming back as recomended to be provided in img tags to prevent "Cummulative layout shift". To prevent "shifting" of the page in the browser when images get loaded. This informs the browser how much space something that will be loaded is goint to take/require, the size and the aspect ratio.
##### Images dimentions can later be manipulated with CSS.

#### Another recomended attribute for images is LOADING. loading="lazy" should be the default to help with performance and internet data usage. loading"eager" is used when we want some image to be loader quickly.

#### figcaption tag explains the image a little closer and tells the browser that text in figcaption tag is related to the image, but it and the image in IMG tag must be wrapped around in FIGURE tag. Figure tag element also adds space and indentation around the image.
##### Figure tag element is not just for images. It can also be used for examples of code with CODE tag element.

### Semantic tags in HTML5

#### Semantic tags provide structure to a web page as well as making page accessible to screen readers and  other assisstive technology 

#### If there are multiple of the same tags/elements on the page, it is important to label them for assisstive technology, using aria-labels

##### TIME tag is also used by assisstive technology

### Tables

### Forms

#### Adding a form to a webpage allows us to get information from our users. More importantly, it allows user to send us information if they choose to.
#### action attribute is automatically added to a form tag. Where we want to send the information is what we put in it (usualy our own server).
#### Method attribute is methos we want to use. could be Get, Post...
#### Content of form is mostly inputs and labels, every input should have a label. Label has For attribute, which should match the ID attribute of the associated input.
#### Input should have type attribute, as well as name and ID attribute. Name and Id attributes in input should match. Input ID and label FOR attributes must absolutely match!
##### Name attribute of the input is how it is indentified on the server level. Information we send to the server will be labeled with the input's ID attribute.
##### Input of type TEL can and should have pattern attribute, a pettern for expected phone number type (regular expression). TEL type input with pattern should also bring up the numeric keypad on mobile devices when typed in.
#### Slect group with Options can have OPTGROUP tag around some of the options to group those options together, as well as MULTIPLE attribute and SIZE attribute to have multiple options shown from the start.
#### FIELDSET tag in form can be used to organbize the form into different section, wehn/if the form gets large. Along with LEGEND tag, to give semantic meaning to our form.