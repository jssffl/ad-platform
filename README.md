# [Ad Platform](https://jssffl.github.io/ad-platform/)
An influencer advertisement platform with SCSS and Javascript

![image](https://github.com/jssffl/ad-platform/blob/main/ad-platform-page.png)

## Description
- The Web is mainly builded by SCSS and compile scss into css by sass-loader in webpack  

### SCSS
- Reset css
- Based on flexbox
- using $variables to define color 
- using @each to generate padding and margin utilities 
- using @mixin to generate number of steps
- using @extend to inherit box-shadow and input-style

### Javascript: 
- Render influencer data to cart list panel
- Listen click event on cards to activate selected card
- Listen click event on buttons to control 1)state of prev button(disabled/active) and content of next button(next/ submit), 2)three state in steps(active/inactive/checked) and 3)corresponding part of form in each step to show

#### How to use
- Select one influencer in card list panel first, and then, follow three steps to enable advertisement service
- First step is to agree on terms of contract
- Second step is to set details for advertisement( like time, target audience)
- Third step is to set default payment account
