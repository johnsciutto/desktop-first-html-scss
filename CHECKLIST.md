# Creating an HTML + CSS Website Checklist

## First

1. [ ] Write down the purpose of the website you want to create.
2. [ ] Make a list of the pages you want your site to have.
3. [ ] Sketch how you want your site to look.
4. [ ] (Optional) Translate the previous sketch to a drawing program.
5. [ ] Identify the individual components of the site. Add individual files for
       them on the sass/components folder.
6. [ ] Package.json: Add the appropriate name, author and description.
7. [x] Choose a CSS Pre-Processor.
8. [ ] Choose a color pallette for your site (Primary, secondary, and tertiary
       colors).
    1. [ ] Choose a primary color.
    2. [ ] Choose a secondary and tertiary color using [this
           website][color-wheel]
    3. [ ] Add them to the CSS variables.
9. [ ] Choose a font-family for your site (for the Body, and a different one for
       the titles).
10. [x] Choose a Mobile-First or Desktop-First approach (This template is for a
        Desktop-First approach).
11. [x] Create an organized file-structure.

## HTML

1. [ ] Structure HTML properly.
2. [ ] For images, use density and resolution switching.

## CSS

1. [ ] Choose good class names (for example, use BEM).
2. [ ] Use fluid, responsive layouts (flexbox and css-grid).
3. [ ] Use relative, responsive units:
    1. rem, em, vh, vw, auto, etc. for fonts and layout width/heights.
    2. %, vh, vw for image sizes.
4. [ ] Write media queries.
    1. [ ] Layouts.
    2. [ ] Typography.
    3. [ ] Components.

## Last

1. [ ] Delete unnecessary code.
2. [ ] Delete unnecessary images.
3. [ ] Make as few HTTP requests as possible.
4. [ ] Run "npm run build:css" to prefix, compile and compress css.

[color-wheel]: (https://www.canva.com/colors/color-wheel/)
