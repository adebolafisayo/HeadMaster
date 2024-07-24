
# Welcome to Headmaster README file

We are a classy barbershop located in the heart of Leeds, providing top-notch grooming services for our esteemed clients.

This document serves as a guide to understand who we are, what we do, and how to interact with us.

![alt text](/images/image.png)

## Features

### Navigation

* The navigation button should be by the left of the page.
* The navigation text should be black in color.
* The navigation text should be in upper case.
* When the navigation link is clicked, it should take the customer to the specific section.

![alt text](/images/image-1.png)

### About Us (Homepage)

* Given a customer lands on the homepage, the "about us" text is displayed right under a text that says "THE GENTLEMEN'S BARBERSHOP".
* The about us text background should have a color of mediumaquamarine.
* When the "about us" button is clicked, it navigates the customer to another page.

![alt text](/images/image-2.png)

### About Us Page

* Given a customer is navigated to the "about us" page, show a paragraph that describes the Headmaster business.
* On the Headmaster "about us" page, display the price list.

![alt text](/images/image-3.png)
![alt text](/images/image-4.png)

### Book An Appointment

* Given a customer clicks on the "BOOK AN APPOINTMENT" button on the navigation link in the homepage, then they land on the "Schedule appointment" button.
* When the "schedule appointment" is clicked, the customer is navigated to the book appointment page.
* When a customer clicks on a timeslot, they are navigated to the User information page.

![alt text](/images/image-5.png)
![alt text](/images/image-6.png)
![alt text](/images/image-7.png)

### User Information Page

* Add fields for details, more information, other services, and bank information to the user information page.
* Add a submit and reset button.
* Add validation to firstname, lastname, email, sort code, and account number on the user information page.

![alt text](/images/image-8.png)

### Payment Confirmation Page

* Given a user has submitted the user information form, then navigate the customer to the payment confirmation page.

![alt text](/images/image-9.png)

## Testing

* I can confirm this page works in Chrome and Microsoft Edge.
* I can confirm the form on the user information page works.
* I can confirm the navigation links work and the pages are responsive.

## Validator Testing
No errors were returned when validating through the [W3C Validator](https://validator.w3.org/).

## Accessibility
Accessibility was verified and passed using Lighthouse in DevTools.

- **Homepage**
- **About Us Page**
- **Book Appointment Page**

## Unfixed Bug
No unfixed bugs reported.

## Deployment
The site was deployed to GitHub Pages. Follow these steps for deployment:

1. Navigate to the **Settings** on the repository.
2. Click on **Pages** and select **main** as the branch.
3. Save the settings and click on the generated link.

The live site can be accessed here: [https://adebolafisayo.github.io/HeadMaster/](https://adebolafisayo.github.io/HeadMaster/)

## Credits
Most of the images and links were sourced from Google.

## Bugs

* When I was working on other pages, I noticed the CSS was not applied.
* I resolved this by using the link tag below:

```html
<link rel="stylesheet" href="assets/css/style.css">

