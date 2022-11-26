# Horiseon - SEO and Digital Marketing 

## Introduction and Description

In this challenge, a marketing agency has hired me to refactor an existing site to make it more accessible so that the website would be optimized for search engines.

My goal would be to follow customer request and go an extra mile by improving the codebase for long-term sustainability. For example, by reworking the CSS to make it more efficient by consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

It is an on-the-job ticket, which means I will begin with a starter code that I need to modify. This week's challenge involves a very important aspect of web development which is **accessibility**.
Web accessibility is an increasingly important consideration for businesses. It ensures that people with disabilities can access a website using assistive technologies such as video captions, screen readers, and braille keyboards. Making a website accessible is also good for business for many reasons, one of them being that accessible sites are better positioned in search engines like Google. It also helps companies avoid litigation that can occur when people with disabilities cannot access their website.

Even though accessibility is a broad topic that can include complex requirements, this challenge acceptance criteria are the following:

* Semantic HTML elements can be found throughout the source code
* HTML elements follow a logical structure independent of styling and positioning
* Image and icon elements contain accessible `alt` attributes
* Heading attributes fall in sequential order
* Title elements contain a concise, descriptive title

The update website can be found at: https://bh00fie.github.io/Horiseon-SEO-and-Digital-Marketing/

## Changes 

Various changes were made to the code to make it more accessible and efficient. 

Starting from the top of the HTML file, the title of the website has changes from "webpage" to "Horiseon - SEO and Digital Marketing experts" which is the customer name:
![Old Title](/assets/images/Title-old.jpg) vs ![New Title](/assets/images/Title-new.jpg)

Moving to the body, previous developer did not use comments and a semantic structure which I have implemented:
![Without Semantic Code](/assets/images/Semantic-old.jpg) vs ![With Semantic Code](/assets/images/Semantic-new.jpg)
In the image above of the old code, it can be also seen that `alt` attributes were not used, fundamental to have an accessible website.
Comments were also missing which helps future developer as well as the customer to understand what each line means and allows to make it easier when upgrading or making any changes to the website.

CSS Stylesheet was also missing comments:
![Old CSS Comments](/assets/images/Comments-old.jpg) vs ![New CSS Comments](/assets/images/Comments-new.jpg)
These are fundamental to make the code clearer and keep track of changes or features.

As the HTML was changed to a sementic structure, many `div` and `class` were taken out such and replaced, a clear example is the navigation bar:
![Old Nav Bar](/assets/images/Nav-old.jpg) vs ![New Nav Bar](/assets/images/Nav-new.jpg)

Also, the stylesheet was full of unnecessary repetition which could slow the webpage done and makes it difficult to make changes in the feature so classes with the same style have been grouped together:
![Old Code with Repetitions](/assets/images/Repititions-old.jpg) vs ![Old Code without Repetitions](/assets/images/Repititions-new.jpg)
By doing so the code went from 201 lines to 128 keeping the webpage look and functionality the same.

As the footer is not a class anymore it was replaced with its own element:
![Old Footer](/assets/images/Footer-old.jpg) vs ![New Footer](/assets/images/Footer-new.jpg)

The final website looks like the following:
![Updated Webpage](/assets/images/Final-website.png)

## Credits

Horiseon webpage and challange taken from: edX 16 week bootcamp Front End Developer on [GitLab] (https://git.bootcampcontent.com/uk-edx-16-week/UK-VIRT-FE-PT-11-2022-U-LOLC)


## License

MIT Licence

---

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
