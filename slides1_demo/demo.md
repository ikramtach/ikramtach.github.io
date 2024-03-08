% Accessibility Toolkit for OER: Images
% Ikram Tachfint Chakir
% Marzo 2024

# First part: Introduction

## General info

Images and graphics play a vital role in enhancing content comprehension and accessibility, particularly for individuals with cognitive and learning disabilities. 

## Goal of web accessibility

* To make images and graphics "visible" to all users is one of the first principles of web accessibility. 
* To make images and graphics "visible" alternative text **("alt text")** needs to be added.
* Alternative text provides a textual alternative to non-text content in web pages.

## Accessible images offer several benefits:

- **People using screen readers:** Alt text can be read aloud or rendered as Braille.
- **People using speech input software:** Users can navigate to images using voice commands.
- **People browsing speech-enabled websites:** Alt text can be read aloud.
- **Mobile web users:** Images can be disabled, particularly for data-roaming.
- **Search engine optimization:** Indexed images.

## Note 

It's crucial to note that removing images from websites (often termed as "text-only versions") diminishes accessibility and functionality for users in various situations.

# Second part: Basic Principles of Image Accessibility

## 1. Alt Attribute for Every Image

- **Every image must have an alt attribute.**
- Alternative text (alt-text) is crucial for accessibility.

## 2. Providing Alternative Text

- Alternative text can be provided in the "alt attribute" or in the surrounding context of the image.
- It should present the **CONTENT** and **FUNCTION** of the image.

## 3. Context Matters

- Appropriate alternative text depends heavily on the image's context.
- Decorative images still need an alt attribute, but it should be null alt="".

## 4. Succinct and Descriptive

- Alternative text should be succinct and avoid phrases like "images of..." or "graphic of...".
- Alt text of a functional image (e.g., an image within a link) should describe the function as well as the content.

# Third part: Type of Images

## 1. Informative Images

- Graphically represent concepts and information.
- Provide a short description conveying essential information.
- [Learn More about Informative Images](https://www.w3.org/WAI/tutorials/images/informative/)

## Example

![Push the cap down and turn it counter-clockwise (from right to left)](co.jpeg)

## 2. Decorative Images

- Add visual decoration to the page.
- Provide a null text alternative (alt="").
- [Learn More about Decorative Images](https://www.w3.org/WAI/tutorials/images/decorative/)

## 3. Functional Images

- Used as links or buttons.
- Describe the functionality rather than the visual image.
- [Learn More about Functional Images](https://www.w3.org/WAI/tutorials/images/functional/)

## 4. Images of Text

- Readable text presented within an image.
- Avoid if possible, but if used, ensure the alt text matches the image text.
- [Learn More about Images of Text](https://www.w3.org/WAI/tutorials/images/textual/)

## 5. Complex Images (e.g., Graphs, Diagrams)

- Convey data or detailed information.
- Provide a full-text equivalent.
- [Learn More about Complex Images ](https://www.w3.org/WAI/tutorials/images/complex/)

## 6. Groups of Images

- Multiple images convey a single piece of information.
- One image should convey the information for the entire group.
- [Learn More about Groups of Images](https://www.w3.org/WAI/tutorials/images/groups/)

## 7. Image Maps

- Images contain multiple clickable areas.
- Provide an overall context for the set of links.
- Each clickable area should have descriptive alternative text.
- [Learn More about Image Maps](https://www.w3.org/WAI/tutorials/images/imagemap/)

# Conclusion

## Web accessibility is essential for ensuring equal access to online content for all individuals. 

## Remember, accessibility benefits not only individuals with disabilities but also enhances the user experience for all users. 

## Let's continue striving for a more accessible and inclusive web.



