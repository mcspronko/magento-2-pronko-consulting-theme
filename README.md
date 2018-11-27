# The Pronko Consulting Theme for Magento 2
Welcome to the Pronko Consulting theme repository. This repository contains a custom Magento 2 theme. 

Feel free to customize it for your own purposes.

All development steps and changes are documented and discussed on my [YouTube Channel](https://www.youtube.com/maxpronko).

# Tutorials
This is a collection of videos with explanations on how to build the theme.

Part 1: [Magento 2 Custom Theme: Logo, Navigation and Layout](https://www.youtube.com/watch?v=zdjSvVUYMJo)

Part 2: [Magento 2 Custom Theme: Adding Montserrat and Roboto Fonts](https://youtu.be/dxpfw0cJ-P0)

Part 3: [Magento 2 Custom Theme: Header Content](https://youtu.be/G6qNMIweVlM)

Part 4: [Magento 2 Custom Theme: Adding Google Fonts](https://youtu.be/64JTlq32uPw)

Part 5: [Magento 2 Custom Theme: Footer Links](https://youtu.be/2cXsEcjMQGs)

Part 6: [Magento 2 Custom Theme: Footer Content Styling](https://youtu.be/oGL33ISb1-I)

Part 7: [Magento 2 Custom Theme: Newsletter Block Section](https://www.youtube.com/watch?v=KkXmTnkRYks)

Part 8: [How to speed up Magento 2 theme development by X times](https://www.youtube.com/watch?v=1SOeJN6PcJI)

The Newsletter subscription HTML content for CMS Block.
```html
<div class="title"><h2 class="title">Subscribe for the Newsletter</h2></div>
<div class="subtitle"><p>Be the first to hear about the latest extension releases, special sales and news.</p></div>
    <form id="newsletter-subscription" class="form subscribe" action="" method="post" novalidate="">
        <div class="field newsletter"><label class="label" for="newsletter"><span>Sign Up for Our Newsletter:</span></label>
            <div class="control"><input id="newsletter" name="email" type="email" placeholder="Enter your email" /></div>
        </div>
        <div class="actions"><button class="action subscribe primary" title="Subscribe" type="submit"><span>Subscribe</span> </button></div>
    </form>
<div class="newsletter-illustration"><div class="img"></div></div>
```

Part 9: [Create Contact Us block on a Home Page](https://www.youtube.com/watch?v=hhUwc7tcGTE)

The contact us HTML content for CMS Block.
```html
<div class="modular-row callout showcase-contact-us">
    <div class="max-width">
        <h2 class="title">DELIVERING BEST ECOMMERCE EXPERIENCE</h2>
        <div class="subtitle"><p>As an eCommerce agency we offer everything from first-class development to a consulting that will bring any vision to life</p></div>
        <div class="contact-us-container">
            <div class="actions"><a class="action subscribe primary"><span>Contact Us</span></a></div>
        </div>
    </div>
</div>
```

Part 10: [Showcase Banner on Home Page | Magento 2 Theme Development](https://youtu.be/FVRV_CXVaik)
```html
<div class="modular-row showcase-header">
    <h1 class="title">Magento Ecommerce Solutions Provider</h1>
    <div class="subtitle">We provide high-quality eCommerce solutions and consulting services globally</div>
    <div class="button-container">
        <div class="actions"><a class="action primary" href="{{config path="web/secure/base_url"}}services"><span>Our Services</span></a></div>
    </div>
</div>
```

Part 11: [How to customize Contact Us Form | Magento 2 Theme Development](https://www.youtube.com/watch?v=txtVLgX9adI)   

Part 12: [How to declare Custom Layout for CMS Page/Block/Widget | Magento 2 Theme Development](https://www.youtube.com/watch?v=9RpIRWOQm2Y)   

Part 13: [Media Queries for Responsive Website | Magento 2 Theme Development](https://www.youtube.com/watch?v=vxQUCPoqiDU)

Part 14: [Custom Media Queries | Magento 2 Theme Development](https://youtu.be/3igsEUKRwD4)

Part 15: [Top Menu Labels | Magento 2 Theme Development](https://www.youtube.com/watch?v=HSjEdr9lUso)

Use this HTML to include into the navigation items:
```html
<span class="new">New</span>
```

Part 16: [How to create Banner Widget in Magento 2](https://www.youtube.com/watch?v=LdiuVPXNcQQ)
 - [Pronko Banner Widget](https://github.com/mcspronko/banner-widget) repository
 
Part 17: [How to add testimonials on Home Page | Magento 2 Theme Development](https://www.youtube.com/watch?v=oBpaTSxE5ik)

Part 18: [How to add Owl Carousel jQuery plugin to Magento 2](https://www.youtube.com/watch?v=dW7Ec2nn_60)

Part 19: [Services Container on Home Page | Magento 2 Theme Development](https://www.youtube.com/watch?v=bixkZPFYLng)

Part 20: [Custom Buttons and Magento UI Library | Magento 2 Theme Development](https://www.youtube.com/watch?v=6PcS6QGbR0g)

# About
The Pronko Consulting theme is created to show best practices on Magento 2 theme development. The theme is based on Magento 2 Blank theme.
The repository is created and maintained by [Max Pronko](https://www.maxpronko.com/) and [Pronko Consulting Team](https://www.pronkoconsulting.com). Feel free to contribute. This is a great opportunity to learn custom theme development best practices.

## Development
It is recommended to use [modman](https://github.com/colinmollenhour/modman) package manager for the theme development. Make sure to download modman before use.

Read [Magento 2 Module in a Separate Repository](https://www.maxpronko.com/magento-2-module-in-a-separate-repository/) post for details.

From the root Magento directory run the following command:
```bash
modman clone git@github.com:mcspronko/magento-2-pronko-consulting-theme.git
```

This command will clone the repository into the .modman/magento-2-pronko-consulting-theme directory and create a symlink in the app/code/design/Pronko folder.

Any modifications in the app/code/design/Pronko directory will be reflected in the .modman/magento-2-pronko-consulting-theme.
