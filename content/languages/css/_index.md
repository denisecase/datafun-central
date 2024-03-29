+++
tags = ["language", "markup", "web"]
title = "CSS"
+++

CSS is a powerful styling language used to add visual effects to web pages.

## Why CSS?

For web developers and designers, Cascading Style Sheets (CSS) is an essential skill for creating attractive and engaging websites.

- CSS helps to create visually appealing layouts and designs that enhance user experience.
- It allows for consistent styling across all pages of a website, making it easier to maintain and update.

## CSS Syntax

- CSS uses a set of rules and declarations to style HTML elements.
- Selectors are used to target specific HTML elements, while properties define the styling rules.

## Free Resources for Learning CSS

- [CSS Tricks](https://css-tricks.com/): A website with a wide range of articles, tutorials, and resources for learning CSS
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS): A comprehensive guide to CSS, with documentation and examples
- [W3Schools CSS Tutorial](https://www.w3schools.com/css/): A free, interactive tutorial for learning CSS, with practical examples and exercises
- [Codecademy CSS Course](https://www.codecademy.com/learn/learn-css): An interactive course that covers the basics of CSS, with hands-on coding exercises
- [CSS Zen Garden](http://www.csszengarden.com/): A showcase of creative CSS designs, with source code available for learning

## File Extensions

- .css

## Using CSS

There is no installation needed to begin using CSS to style web pages. 
CSS is understood by web browsers such as Chrome, Firefox, Safari, and Edge. 
To use CSS, you can define styles in a separate CSS file 
or in the head section of an HTML file using the `<style>` element.

To add a .css file to an HTML file,  
include a `link` in the head section of the HTML file.

```html
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```

An example of styles.css is shown below. 

```css
body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
}

h1 {
  color: #333;
  font-size: 2em;
  margin-bottom: 1em;
}

p {
  color: #666;
  font-size: 1.2em;
  line-height: 1.5;
  margin-bottom: 1.5em;
}
```

## Responsive Design

Responsive design is an approach to web design that aims to 
create websites that adapt to different screen sizes and devices. 
With responsive design, web developers can ensure that their websites 
look and function well on desktops, laptops, tablets, and smartphones, 
and provide a consistent user experience across all devices.

To create responsive websites, CSS is used to define media queries 
that specify different styles and layouts for different screen sizes. 
By using media queries, web developers can adjust the design of their 
websites based on the width of the viewport, the orientation of the device, 
and other factors.

## Design Skills

Good design is an essential aspect of creating effective and engaging websites 
and dashboards. 
CSS plays a crucial role in web design, 
as it allows users to control the visual presentation of their sites
 and create attractive and user-friendly interfaces.

To create good design with CSS, it's important to have a solid understanding of typography, color theory, layout principles, and user experience design. 
Web developers can use CSS to define fonts, colors, spacing, positioning, 
and other visual elements, and use design principles to create a 
cohesive and appealing look and feel.

## Popular CSS Frameworks

Because getting dashboards and web pages to look good on all possible 
screen sizes and orientations, many of us prefer to use professionally-created
CSS rather than our own.

CSS **frameworks** are pre-built libraries of CSS and JavaScript 
code used to streamline web development and create 
consistent and responsive displays. These frameworks are desiged to 
be responsive and look good on screens ranging from mobile devices like
smart phones to large, wall-mounted screens. 
They provide a range of pre-designed elements, such as navigation bars, forms, 
and buttons, that can be easily customized 
and incorporated into dashboards and web projects.

Popular CSS frameworks include Bootstrap, 
Material Design Bootstrap (MDB), Foundation, and Bulma.
These frameworks offer a wide range of design options, robust documentation,
and support from their communities. 

## CSS in Dashboarding Frameworks 

Many popular data analytics dashboarding frameworks 
allow customization for analysts with a knowledge of CSS.

### CSS in Tableau

Tableau provides a range of customization options for dashboard styling, 
including the ability to use custom CSS code to modify the appearance of 
dashboards and reports. Users can create custom themes and apply 
them to their dashboards, or use CSS to modify individual elements such as 
fonts, colors, and backgrounds.

### CSS in Power BI

Power BI allows users to customize the appearance of their dashboards 
using themes and custom CSS code. Users can modify the styling of 
individual elements such as charts, tables, and cards, and can apply custom 
CSS classes to elements for greater control over styling.

### CSS in Plotly

Plotly is a web-based data visualization platform that
provides a range of customization options for dashboard styling, 
including the ability to use custom CSS code to modify the appearance of 
charts and graphs. Users can modify the styling of individual elements 
such as colors, fonts, and backgrounds, and can apply custom CSS
classes to elements for more granular control over styling.

Plotly supports multiple programming languages including Python, R, and JavaScript.

### CSS in Metabase

Metabase is an open-source business intelligence and data analytics platform 
that allows users to 
create interactive dashboards and reports. 
It provides a range of customization options for dashboard styling, 
including the ability to use custom CSS code to modify the 
appearance of dashboards and reports. Users can modify the styling of 
individual elements such as fonts, colors, and backgrounds, 
and can apply custom CSS classes to elements for greater control over styling.

Metabase supports SQL queries and has a web-based interface.

### CSS in Redash

Redash is an open-source data visualization and dashboarding platform 
that allows users to connect to various data sources and 
create interactive dashboards and reports. 
It provides a range of customization options for dashboard styling, 
including the ability to use custom CSS code to modify the appearance 
of dashboards and reports. Users can modify the styling of 
individual elements such as fonts, colors, and backgrounds, 
and can apply custom CSS classes to elements for more granular 
control over styling.

Redash connects to SQL databases, MongoDB, and APIs, 
and includes support for Python scripts.

## See Also

Read more about some of these important options in:

- [Techniques/Data Visualization]({{< ref "/techniques/data-visualization/" >}})