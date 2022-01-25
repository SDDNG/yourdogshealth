# Your Dog's Health
This project consists of a static website which gives people an easy overview of the elements required for a dog to be healthy. It considers three main elements - diet, exercise and enrichment (i.e. mental stimulation). There is also a form page where someone could enter their name and email in order to register for a Newsletter and to receive a free ebook on dog's health. There is also an 'About' page which explains the background of the authors. Images of each page appear below (Note: was not sure how to paste images so looked up and found YouTube video (https://www.youtube.com/watch?v=nvPOUdz5PL4) which advised to create issues and drop screen caputures in and then to grab code from there):


<img width="450" alt="IndexHtml" src="https://user-images.githubusercontent.com/70945839/150997287-40f9a218-26bc-44cc-aab7-be057e873f8f.PNG">

<img width="450" alt="Exercise" src="https://user-images.githubusercontent.com/70945839/150997155-d2a83cdf-30ba-41cf-8f6b-7864beafb03e.PNG">

<img width="450" alt="Diet" src="https://user-images.githubusercontent.com/70945839/150996962-cee7c5c5-18f9-4ea6-9776-6ea04feff466.PNG">

<img width="450" alt="Enrichment" src="https://user-images.githubusercontent.com/70945839/150997121-e8b61d33-06bd-48c5-b607-f9762889a24e.PNG">

<img width="450" alt="Download" src="https://user-images.githubusercontent.com/70945839/150997036-dbcac2ca-b0dc-41b5-be84-ec1c69be2867.PNG">

<img width="450" alt="About" src="https://user-images.githubusercontent.com/70945839/150996887-29e06e99-eca5-4903-8652-57028111887b.PNG">

## Existing Features
### Navigation Bar
Featured on all six pages, the full responsive navigation bar includes links to the Logo, Home page, Diet page, Exercise page, Enrichment page, Download page and the About page and is identical in each page to allow for easy navigation. This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. The page the user is currently residing on is given a grey background as is the one they hover over.

<img width="509" alt="Navigation" src="https://user-images.githubusercontent.com/70945839/150997350-e6dd5d0d-eaf2-4154-9263-7babaab92a7e.PNG">


### The Page images
Each page features two appropriate photographs or images e.g. in the case of the diet page, one of the images is a figure showing how the body condition score for a dog is judged, on the enrichment page, photos of dogs socialising are featured. 

<img width="450" alt="Images" src="https://user-images.githubusercontent.com/70945839/150999359-f5db2f94-799a-47e4-8b23-43b0265dba64.PNG">

### The Footer
The footer section includes links to the relevant social media sites for Your Dog's Health. The links will open to a new tab to allow easy navigation for the user.
The footer is valuable to the user as it encourages them to keep connected via social media.

<img width="960" alt="Footer" src="https://user-images.githubusercontent.com/70945839/150997225-e76514b4-fcc0-4b12-8007-3778e685b2b5.PNG">

### Download Guide
This page will allow the user to get signed up to Your Dog's Health to receive a newsletter and also to get a free download of an ebook with some advice on how to maintain their dog's health. The user will be asked to submit their first name, last name and email address.

<img width="490" alt="Form" src="https://user-images.githubusercontent.com/70945839/151000763-5c378459-b6a0-4450-8213-b1482a122310.PNG">

### Responsive Design
The website was implemented with various media queries which restructured the page depending on the size of device it was being viewed on. When the device size drops below a certain size the structure of the pages changes so that the menu items are stacked vertically rather than horizontally.

<img width="206" alt="VerticalMenu" src="https://user-images.githubusercontent.com/70945839/150997526-7aa6ef50-2d13-42ac-a241-a96351e24a90.PNG">

### Features Left to Implement
A food calculator for dogs based on various information such as age, current weight, breed, type of food and activity level would be a good addition to the site.

## Testing
The site was tested for navigation, appearance and responsiveness on different device sizes. Initially when it was ported to GitHub pages there were issues with some filepath names and one of the html file names ('index' had been renamed to 'home') and these were addressed. Chrome, Firefox and Edge were all tested.

### Validator Testing
HTML
On the initial run through the official W3C validator, errors in the html files were flagged because of 'alt' attributes on links, there were changed to 'aria-labels' and the files then passed. 
CSS
On the initial run throught the W3C CSS Validator, it flagged that there was an invalid ‘float:center’ on a number of attributes in the CSS file, these were removed and no difference in the pages was noted, so the intended effect was redundant.
### Unfixed Bugs
There are no known unfixed bugs.

## Deployment
The site was deployed to GitHub pages. The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab then choose the GitHub Pages link.
From the source section drop-down menu, select the Master Branch
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found here - https://sddng.github.io/yourdogshealth/

## Credits
### Content
The icons in the navigation menu and the footer were taken from Font Awesome.
The dog favicon for the web tab is from and https://favicon.io/emoji-favicons/dog/.
Google fonts are used throughout the website for heading and body content.

There are a number of information links featured on each page which include:
Index.html
"https://tinyurl.com/2s3azccx" - A shortened version of the Amazon url for 'The Forever Dog' a book explaining how to improve a dog's lifespan and healthspan.  
"https://www.dogzone.com/breeds/" - A link to a comprehensive list of dog breeds.
Exercise.html
"https://dogtime.com/" - A link to an information site about 'all things dog'.
"https://en.wikipedia.org/wiki/English_Springer_Spaniel" - A link to the Wikipedia listing for a Springer Spaniel.
"https://dogtime.com/dog-breeds/weimaraner#/slide/1" - A link to the Wikipedia listing for a Weimaraner.
"https://www.akc.org/expert-advice/health/how-much-exercise-does-dog-need/" - A link to the American Kennel Club's page advising on different kinds of exercise a dog will enjoy.
The text for the Home page was taken from Wikipedia Article A
Instructions on how to implement form validation on the Sign Up page was taken from Specific YouTube Tutorial
Diet.html
"https://www.purina.co.uk/articles/dogs/health/exercise/dog-body-condition-tool" - a link to Purina's guide to the body condition score system. Note there is also a figure on this page with an easy-to-understand graphic of this scoring system from •	https://www.vetfolio.com/learn/article/hills-body-condition-scoring-chart.
"https://dogsfirst.ie/" - a link to a guide to feeding dogs a raw diet and alternative medical treatement.
"https://www.bbc.com/news/education-48665618" - a link to a BBC story explaining how dogs evolved to evoke sympathy from humans through the use of facial expressions.
Enrichment.html
"https://en.wikipedia.org/wiki/Livestock_guardian_dog" - a link to a Wikpedia page explaining the demanding task Livestock Guardian Dogs were bred for.
"https://en.wikipedia.org/wiki/Hunting_dog" - a link to a Wikipedia page explaining how hunting dogs work.
"https://www.battersea.org.uk/fuelling-your-dogs-brain" - a link to a page from Battersea explaining ways to mentally stimulate a dog.
About.html
"https://www.independent.ie/irish-news/another-glimpse-of-misneach-president-michael-d-higgins-new-puppy-40165468.html" - a link to a story from the Irish Independent on the President of Ireland's Bernese Mountain Dogs. 

### Media
The photos used on all of the photos are from the personal collection of the website designer.The graphic in the Figure on the Diet page is from •	https://www.vetfolio.com/learn/article/hills-body-condition-scoring-chart and explains how to judge the body condition score system.
