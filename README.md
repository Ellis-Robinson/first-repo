# first-repo - A simple site linking to information about different web development tools. 

The site was created as part of a training course in front-end development. 
It has three pages of links that, via logos and names, take the user to the corresponding Wikipedia page, 
where they can gain more information on the specific development tool. 
There are six links per page, with some repeating on across pages. The reason for repeating the links 
was to practice where pieces of code can be copied and reused during a single project,  
allowing the whole process be more efficient while keeping a sense of uniformity across the site. 

 <img src="assets/images/page-screenshot.png" alt="screenshot of webpage">

# Technologies used 

### HTML5 (hyper-text markup language) 
HTML is a programming language used for structuring and presenting content on the world wide web. 
This was used for the bulk of the project. 

### CSS (Cascading Style Sheets) 
CSS is a style sheet language used for describing the presentation of a document 
written in a markup language such as HTML. 
This was used to make the site look more appealing for a better user experience via logos,  
colour and spacing etc. 

#### issues and fixes
-The images I used were different sizes, 
so I put them each in their own div, all with the same class name. 
Then using CSS, set the width and height of that class, then set width and height of images to 100%.
This gave me a strong starting position for getting a more uniform feel.

-Some images were streched one way or another so to fix this I gave certain images ID attributes,
 and adjusted their size accordingly in CSS. A few needed unique adjustments but I was able to group
 the majority together via a class attribute and change them with one rule.