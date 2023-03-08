# MahdiChallenge
Challenge #1

## User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria
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

HTML modifications:

Title changed to "Digital Marketing"

Comments added:

```

<!-- Header -->

<!-- Main Section -->

<!-- Benefits Section -->

<!-- Footer -->

```

Semantics changed from div to nav in header section

Changed mainImage in header section

Main content grouped in main tag and footer with footer tag

Content class name changed to main

Alt included for each image to dscribe it

Class search engine optimation changed to id to match CSS

All benefit classes changed to id

CSS modifications:

Comments added:

```

/* CSS */

/* Universal selector */

/* No padding/margins */

/* chose this color for the body background */

/* header class used for the header section */

/* this selector is for the h1 heading in the header section */

/* Benefits section combined into one class/id to be efficient */

/* aligns text in the center */

```

ids were simplified to be efficient:

```

#benefit-lead,
#benefit-brand,
#benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

#benefit-lead h3,
#benefit-brand h3,
#benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center; /* aligns text in the center */
}

#benefit-lead img,
#benefit-brand img,
#benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

#search-engine-optimization,
#online-reputation-management,
#social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

#search-engine-optimization img,
#online-reputation-management img,
#social-media-marketing img {
    max-height: 200px;
}

#search-engine-optimization h2,
#online-reputation-management h2,
#social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

```

## Output

The refactored code is ensured to provide easy to read and efficient code.

## Installation

Github repository:

https://github.com/mahdi83777/MahdiChallenge

Deployed application:

https://mahdi83777.github.io/MahdiChallenge/

## References

[Refactoring](https://refactoring.guru/refactoring)

[Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp)

[How to make a good README file](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)