
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

### Overusage of div tag

In order to make the code more readable, the over abundance of div tags found in the source code were replaced. Below is an example of how an aside featuring headers, images, and text was updated:

* *Before*

```
<div class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="a graphic representing lead generation"/>
            <figcaption>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </figcaption>
        </div>
        <div class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="a graphic representing brand awareness"/>
            <figcaption>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </figcaption>
        </div>
        <div class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="a graphic representing cost management"/>
            <figcaption>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </figcaption>
        </div>
    </div>
```

* *After*

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
### Misplacement of CSS style sheet

* *Before*

```
<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>Horiseon Social Solution Services, Inc.</title>
</head>
```

* *After*

```
<head>
    <meta charset="UTF-8" />
    <title>Horiseon Social Solution Services, Inc.</title>
    <link rel="stylesheet" href="./assets/css/style.css">
</head>
```

## Missing alt attributes for image elements

* *Before*

```
<section class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </section>
```

* *After*

```
<section class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" alt="a notebook showing a flow chart for the process of SEO" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </section>
```

## Boring and non-descriptive website title

* *Before*

```
<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>website</title>
</head>
```
* *After*

```
<head>
    <meta charset="UTF-8" />
    <title>Horiseon Social Solution Services, Inc.</title>
    <link rel="stylesheet" href="./assets/css/style.css">
</head>
```
