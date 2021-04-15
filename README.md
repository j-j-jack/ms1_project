# **Late night cakes website**

## **User Experience (UX)**

### **Strategy plane**

The strategy upon which the site is built is based on the business objectives and the user needs.

**The business objectives are as follows:**

* To allow online orders to increase revenue
* To move the company's wordpress blog to their own website
* To increase the number of customers in the cafe
* To improve the company's public profile
* To have a collection of reviews
* to improve public knowledge of the service and the company's history

**The user needs are as follows:**

* To be able to interact with the organisation
* To understand reasons why to choose the company
* To be able to order from the company online
* To provide feeback on goods services
* To view prices

Using the business goals and user needs a table of opportunities was created and their importance was compared with their viability to decide which opportunities to pursue.

| Opportunities                                                                                                  | Importance | Viability | in/out |
|----------------------------------------------------------------------------------------------------------------|------------|-----------|--------|
| Create a forum for reviews                                                                                     | 5          | 1         | out    |
| Supply information about the company history and services (feeds into reasons to choose the company for users) | 4          | 4         | in     |
| Increase traffic to cafe (develop a strategy to do this)                                                       | 4          | 1         | out    |
| Move blog to own website                                                                                       | 3          | 1         | out    |
| Provide a means for the public/other businesses to interact with company                                       | 3          | 5         | in     |
| Provide a means for user's to view company's previous work                                                     | 4          | 4         | in     |
| Allow customers to order online                                                                                | 5          | 5         | in     |
| Provide information about the cafe's opening hours and address                                                 | 4          | 5         | in     |

Another important consideration is that prices must be provided upfront as this is B2C website and this will support impulse buys.

### Scope plane

The features to be included in the site based on the tradeoffs from the strategy plane. They are as follows:

A form page - A form page will be developed to allow customers/other businesses to interact with the company. This form will also double up as an order form which customers will fill out information about what they want to buy and leave their email so that the company can follow up.

About pages - This will help the company provide the public with information about their history and services and will also give reasons to customers to choose the company. 

Social media links - This will allow potential customers to view the companys previous workand give them reasons to choose the company. Also the company's blog will be linked. This somewhat amends the fact that the blog will not be transferred to view on the site directly.

Gallery - Again so that potential customers can view previous work. This will give them reasons to choose the company.

Cafe-info - A google map, the cafe phone number and the opening hours - while this is not a strategy to increase numbers to the cafe, it may do so indirectly.

#### user stories

user stories were created to aid in the designing of the site and in testing later on. They are as follors:

* as somebody interested in buying cupcakes, I want to discover when the cafe is open to sample cupcakes.
* as a lorry driver in the area I want to find the location of the cafe
* as a person who wants to buy cupcakes I want to make an order
* as a particularly choosy individual I want to view the company's previous work before deciding whether or not to choose the company
* as a local politician I want to contact the company in relation to employment schemes
* As a potential bulk buy I want to see a list of prices

### Structural plane 

The structure of the site was designed in a consistant manner meeting user expectations. An example of this is to have a navbar on the top of the page.

The site uses contact hinting to encourage scrolling where necessary. ie. Information is partially visible before the fold of the page.

The site uses feedback such as buttons highlighting and the cursor changing to a pointer.

### Skeleton plane

With the features and structural considerations completed. Wireframes were drawn for all device sizes to show how these elements would be laid out. Below the wireframes are linked.

[about us pages on mobile](documents/wireframes/about-us-pages-cupcakes-mobile.png)
[about us pages on tablet](documents/wireframes/about-us-pages-cupcakes-tablet.png)
[about us pages on laptop](documents/wireframes/about-us-pages-cupcakes-laptop.png)
[about us pages on desktop](documents/wireframes/about-us-pages-cupcakes-desktop.png)
[form page on mobile](documents/wireframes/form-page-cupcakes-mobile.png)
[form page on tablet](documents/wireframes/form-page-cupcakes-tablet.png)
[form page on laptop](documents/wireframes/form-page-cupcakes-laptop.png)
[form page on desktop](documents/wireframes/form-page-cupcakes-desktop.png)
[galleries page on mobile](documents/wireframes/galleries-page-cupcakes-mobile.png)
[galleries page on tablet](documents/wireframes/galleries-page-cupcakes-tablet.png)
[galleries page on laptop](documents/wireframes/galleries-page-cupcakes-laptop.png)
[galleries page on desktop](documents/wireframes/galleries-page-cupcakes-desktop.png)
[home paghe on mobile](documents/wireframes/home-page-cupcakes-mobile.png)
[home page on tablet](documents/wireframes/home-page-cupcakes-tablet.png)
[home page on laptop](documents/wireframes/home-page-cupcakes-laptop.png)
[home page on desktop](documents/wireframes/home-page-cupcakes-desktop.png)

### Surface plane

The fonts and colors used are to mimic night clubs/venues that are open at night. The pages are designed to have good contrast and consistent patterns to create good readability.

## Technologies used

### Languages used

Html5
Css3

### Libraries, Frameworks and Programs used

Bootstrap 4.5 was used for the responsiveness and structure of the website as well as interactive components such as the navbar and modals.

jquery was used with bootstrap to allow the interactive elements to function correctly

font-awesome was used for the site's icons

google-fonts was used for the sarina and play fonts

gitpod was used to edit the pages and push the code to github

github pages were used to deploy the site

boxy-svg.com was used to create the company logo

balsamiq was used to create the wireframes for the project

## Testing

W3 markup validator was used to validate all of the site's pages - they now pass through with no errors.
W3 jigsaw css3 validator was used to validate the style sheet - it passes through without error.

### testing user stories

* as somebody interested in buying cupcakes, I want to discover when the cafe is open to sample cupcakes 
-on loading the site the user searches through the body of the home page. This is not a large amount of text and the user does not waste much time.
-the user then searches the footer as this is a common location of such information and finds the information easily.
[opening time for tasters found by customer](documents/testing/user-story-1.png)

* as a lorry driver in the area I want to find the location of the cafe
-on entering the site the map is clearly visible due to content hinting
-the lorry driver scrolls down to the map and finds the location
[map found by lorry driver](documents/testing/user-story-2.png)

* as a person who wants to buy cupcakes I want to make an order
-on entering the site the user clearly sees the order button on the home page as it stands out.
-they click this button and are directed to the order page where they place an order
[order button on home page](documents/testing/user-story-3.png)

* as a particularly choosy individual I want to view the company's previous work before deciding whether or not to choose the company
-on entering the site the user checks the navbar for links. one of the links is galleries which the user clicks assuming they will see they products
-this being an intuitive assumption they are proven correct and on the gallery page click the thumbnails which are shown to be clickable due to the cursor changing to a pointer and the thumnail darkening
-the gallery modal opens and the user scrolls through the pictures using the arrows
[user scrolling through gallery](documents/testing/user-story-4.png)

* as a local politician I want to contact the company in relation to employment schemes
-on entering the site the politician reads the navbar items. he finds the order/enquire button. he does not want to order but he wants to enquire
- on the next page the politician clicks the general enquiry radio button and uses the textarea to write his enquiry
[politician clicking enquiry radio button](documents/testing/user-story-5.png)

* As a potential bulk buy I want to see a list of prices
-on entering the site the user checks the navbar for a link to pricing. they do not see one
-the user searches the home page for prices. they do not find any. they look at the navbar again and assume that they can find prices on the order page
-the user opens the order page and sees the prices.
-although the user was successful, perhaps in a future build the prices can be accessed directly from the navbar.
[user unsure if order/enquire will lead them to prices](documents/testing/user-story-6.png)

## Deployment

The site is deployed on git pages 
[link to deployed site](https://j-j-jack.github.io/ms1_project/)

The site was deployed from the settings section on the github repository.
After accessing the setting the developer scrolled to github pages section.
The developer selected the master branch as a source.
The page refreshed and the developer recorded the link supplied.

## References

### Images

The references to the images used in the project are as follows

Photo by Rod Long on Unsplash - background
Photo by Fred Moon on Unsplash - Richie Mulligan
Photo by 99.films on Unsplash - cafe
Photo by Elle Hughes on Unsplash - ingredients

2018
Photo by Natalie Chaney on Unsplash - cupcake-1
Photo by Daniel Klein on Unsplash - cupcake-2
Photo by Sara Cervera on Unsplash - cupcake-3
Photo by Heather Mount on Unsplash - cupcake-4
Photo by Jr R on Unsplash - cupcake-5
Photo by Nickie Joseph on Unsplash - cupcake-6
Photo by Dessy Dimcheva on Unsplash - cupcake-7 
Photo by Olivia Herlambang-Tham on Unsplash - cupcake-8
Photo by Deva Williamson on Unsplash - cupcake-9
Photo by Meritt Thomas on Unsplash - cupcake-10

2019
Photo by Angèle Kamp on Unsplash - cupcake-1
Photo by Cristina Matos-Albers on Unsplash - cupcake-2
Photo by Cristina Matos-Albers on Unsplash - cupcake-3
Photo by Mia Cambriello on Unsplash - cupcake-4
Photo by Tai's Captures on Unsplash cupcake-5
Photo by Meritt Thomas on Unsplash - cupcake-6
Photo by Charisse Kenion on Unsplash - cupcake-7 
Photo by Brooke Lark on Unsplash - cupcake-8
Photo by atheer alghamdi on Unsplash - cupcake-9
Photo by Jamie Street on Unsplash - cupcake-10

2020
Photo by Jennie Brown on Unsplash - cupcake-1
Photo by Léo Roza on Unsplash - cupcake-2
Photo by Marta Muñoz on Unsplash - cupcake-3
Photo by Jen Theodore on Unsplash - cupcake-4
Photo by Katherine Chase on Unsplash - cupcake-5
Photo by ABHISHEK HAJARE on Unsplash - cupcake-6
Photo by OhTilly on Unsplash - cupcake-7
Photo by Jacob Boavista on Unsplash - cupcake-8
Photo by Siora Photography on Unsplash - cupcake-9
Photo by Aneta Voborilova on Unsplash - cupcake-10

### Other references

The code used for the neon text effect was modified from the w3 schools page Below

[link to page](https://www.w3schools.com/howto/howto_css_glowing_text.asp)










