## How to make a page more accecible

> It's important to check de contrast of colours, the are pages to check it.
> Make it operable only with the keyboard for the paeople with movement disability
> Make it understable for everyone
>**The writting is important! Use "https://rytr.me/" to help you to do it right!**
>**Make it accessible for all everyone, you can use "a11yproject.com/checklist" or "lighthouse" to check it**
>**Use the guide https://jfhector.github.io/accessibility-guidelines/ to build your pages**


## CSS
> Conventional structure of CSS "https://education-team-2020.s3.eu-west-1.amazonaws.com/web-frontend-vue/css-structure-anatomy.png"
> The "*" affects all the document
> In CSS is better to avoid the CamelCase declaration, use the "-" like spaces instead. GenísIsCool (Wrong) Genís-is-cool (right)
>**Use the "id" only in unique tags of high gerarcacy like sections.**
> The identificators "id" only applies in one element to avoid future errors
> To "call" the id on the style.css, use #"name of id"
> The class "class" is infinite, reutilizable, the id is unique 
> If you need help to choose the colors for your page, you can use "https://coolors.co/"
> If I want to affect a particular element inside some other declared element I will use ">" for exemple   id-inicial > p, h1 {[...]} but isn't possible to concadenate (id-inicial > div > p)

### Pseudo Selectors
> You can use pseudo selectors to input simple animations on your web like :focus
> To point one element you use the name of element, the ":" and the type of pseudo selectors that you want.       For example: .paragraph:focus

### FlexBox
> https://css-tricks.com/snippets/css/a-guide-to-flexbox/