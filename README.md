
# Horiseon Social Solution Services, Inc.

# About this Webpage

This is the homepage for Horiseon Social Solution Services, Inc., a search engine optimization, online reputation management, and social media marketing business.

## Sourcecode Semantic Issues

After reviewing the webpages sourcecode, it became clear that the code was not optimized for accessibilty due to the following issues:

* over usage of the div tag when differentiating between elements within the HTML file 
* incorrect placement of the CSS style sheet within the HTML file
* missing alt attributes for image elements
* boring and non-descriptive website title


## Sourecode Semantic Fixes

In order to make the code more readable, the over abundance of <div> tags found in the source code were replaced. Below is an example of how an aside featuring headers, images, and text was updated:

* **Before**

```
<aside class="benefits">
        <figure class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="a graphic representing lead generation"/>
            <figcaption>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </figcaption>
        </figure>
        <figure class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="a graphic representing brand awareness"/>
            <figcaption>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </figcaption>
        </figure>
        <figure class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="a graphic representing cost management"/>
            <figcaption>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </figcaption>
        </figure>
    </aside>
```

* **After**

```
<aside class="benefits">
        <figure class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="a graphic representing lead generation"/>
            <figcaption>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </figcaption>
        </figure>
        <figure class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="a graphic representing brand awareness"/>
            <figcaption>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </figcaption>
        </figure>
        <figure class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="a graphic representing cost management"/>
            <figcaption>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </figcaption>
        </figure>
    </aside>
```

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```


