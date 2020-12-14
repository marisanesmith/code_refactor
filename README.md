# code_refactor

The purpose of this project is to update a client's existing html and css files to reflect the same layout and design while creating more accessibility for the user. 

## Table of Contents
* [Change Title](#change-title)
* [Activate SEO link to navigate on website](#activate-seo-link-to-navigate-on-website)
* [Add Alt tags to HTML img](#Add-Alt-tags-to-HTML-img)
* [Removing divs and adding sections in HTML](#Removing-divs-and-adding-sections-in-HTML)
* [Removing divs and adding articles in HTML](#Removing-divs-and-adding-articles-in-HTML)
* [Add class tag and change existing class tag in HTML to help consolidate CSS properties](#Add-class-tag-and-change-existing-class-tag-in-HTML-to-help-consolidate-CSS-properties)
* [Combining CSS properties for the class identification of benefit](#Combining-CSS-properties-for-the-class-identification-of-benefit)
* [Combining CSS properties for the class identification of services](#Combining-CSS-properties-for-the-class-identification-of-services)
* [Rearranging CSS Properties in the style css sheet to reflect the html index](#Rearranging-CSS-Properties-in-the-style-css-sheet-to-reflect-the-html-index)
* [Resizing Image digital marketing meeting](#Resizing-Image-digital-marketing-meeting)
* [Providing a URL for the Website](#Providing-a-URL-for-the-Website)
* [Credits](#credits)

## Change Title
1. Change the title of website to reflect the name of the company

## Activate SEO link to navigate on website
1. Add an ID tag to "Search Engine Optimization" to navigate to the Search Engine Optimization section

[without seo id tag](assets/images/without-seo-id-tag.png)

[add seo id tag](assets/images/add-seo-id-tag.png)

## Add Alt tags to HTML img
1. Add description using alt tags in HTML to provide accessability for visually impaired users to understand the image

[add img alt tags](assets/images/img-alt-tags.png)

## Removing divs and adding sections in HTML
1. Identify groups of elements with similar properties 
2. Re-labeled those element groups as sections instead of divs to allow more accessability for the user

[html with divs](assets/images/html-with-divs.png)  

[html with section](assets/images/html-with-sections.png)

## Removing divs and adding articles in HTML
1. Removed and renamed the divs within the individual sections to the tag articles for more accessibility for the user.

[html with divs](assets/images/html-without-articles.png)

[html with article](assets/images/html-with-articles.png)


## Add class tag and change existing class tag in HTML to help consolidate CSS properties
1. Add class tag class="services" to Search Engine Optimization div 
2. Change class tag of online-reputation-management to class="services" 
3. Change class tag of social-media-marketing to class="services" 

[Before adding class tag of services](assets/images/before-class-tag-services.png)  

[After changing class tag to services](assets/images/class-tag-services.png)


## Combining CSS properties for the class identification of benefit 
1. Combined the CSS properties benefit-lead, benefit-brand & benefit-cost to be all inclusive of the class .benefit-all
2. Combined the CSS properties benefit-lead h3, benefit-brand h3 & benefit-cost h3 to be all inclusive of the class .benefit-all h3
3. Combined the CSS properties benefit-lead img, benefit-brand img & benefit-cost img to be all inclusive of the class .benefit-all img

[class with benefits not combined](assets/images/benefits-css-before.png)  

[class with benefits combined](assets/images/benefits-css-after.png)

## Combining CSS properties for the class identification of services
1. Combined the CSS properties search-engine-optimization, online-reputation-management & social-media-marketing to be all inclusive of the class .services
2. Combined the CSS properties search-engine-optimization h2,  online-reputation-management h2 & social-media-marketing h2 to be all inclusive of the class .services h2
3. Combined the CSS properties search-engine-optimization img, online-reputation-management img & social-media-marketing img to be all inclusive of the class .services img

[Before combining CSS properties](assets/images/before-adding-services-css.png)  

[New CSS property of services](assets/images/new-css-services-property.png)

## Rearranging CSS Properties in the style css sheet to reflect the html index
1. In style.css move .content class under .hero class
2. In style.css move the .services, .services h2 and .services img class under .content class
3. In style.css move the p class in between the .services h2 class and .float-left class

[Before Rearranging CSS Properties](assets/images/before-rearrange-css.png)  

[Before Rearranging CSS Properties Second Copy](assets/images/before-rearrange-css-2.png)  

[After Rearranging CSS Properties](assets/images/after-rearrange-css.png)

## Resizing Image "digital-marketing-meeting"
1. Resize the image to a lower pixel ratio to reduce loading time 
2. Perform this by saving the image in lightroom
3. Save the new img as digital-marketing-meeting-2 and replace the original img


## Providing a URL for the Website
1. Open Github.com
2. Create a new Repository
3. Add a repository name and optional description
4. Make the repo public and add a README file
5. Create Repository
6. Inside the repo go to settings, scroll down to GitHub Pages adn publish your site to the Branch: main

[GitHub Live Site](https://marisanesmith.github.io/code_refactor/)

## Credits

* William Chenausky (https://github.com/wchenausky)
* W3 Schools (https://w3schools.com)

