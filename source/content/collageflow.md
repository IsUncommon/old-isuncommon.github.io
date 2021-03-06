We all love pictures, single moments in time frozen and captured forever. They are our way of traveling through time, to experience important moments of our past and relive the glory days — of youth, achievement, joy, etc. One of the most classic and traditional way of using pictures is depicting pictures through collages. Collages are beautiful means of communicating multiple images and sometimes an entire experience in one single frame. 

At Uncommon photography is very dear to our heart and being the classic geeks that we are, we always tend to look for tools that will help us be better not only at the art of photography but also tools that will help us make the end products of photography better. In our search we used a lot of apps for creating collages but somehow we were never satisfied with any of them completely. We soon realised that we could not be the only ones unsatisfied by such apps. Therefore we simply decided to build an app from the ground-up, one that we would love to use. This was the inception of CollageFlow.

CollageFlow was build through multiple iterations of design supported by even more iterations in development. Design-wise it evolved from being a simple black and white interface to a rich, beautiful and colourful UI inspired from the base concepts of Material Design. The latest iteration in design showcases almost all concepts of Material Design such as Paper-Ink mentality, bold contrasting colour choices, authentic and original animations and much more. As far as development goes CollageFlow employs complex geometric algorithms, compressions techniques, caching algorithms, newly introduced widgets such as Recycler Views and last but not the least our own custom widgets which, at the risk of sounding boastful, shame the traditional widgets which provide the same functionality.


### First Major Iteration

To compete in an established market one needs to have a unique product or a unique aspect to the product. We realised this fact and embarked on the quest to add a new unique feature to our version of the app. Surprisingly we did not have to look far. The best part about collages is that they are extremely personal. It presents one’s perspective, a way for one to showcase their thoughts and their memories. However none of the apps that give the functionality to create collages provide a way to choose the way in which pictures would be added to the collage, their shapes and their placement, In short users have to select from a list of pre-existing templates most of which are not that great or obvious to create their collage and so had to compromise. We thought that it was really unintuitive not to be able to provide the users the ability to create their own templates and just like that we had our unique feature. Our first major iteration of the app completely revolved around the unique feature of users being able to create their own templates. 

#### Design Challenges
* Figuring out flows for creating new templates.
* Figuring out how users would draw the templates on the screen with their fingers, 
* Figuring out how they would save the templates 
* Figuring out how they could fill pictures inside it.

#### Dev Challenges
Setting up the complete geometric model for Points, Lines, Polygons and Polygon Canvases that would be required to facilitate users to draw their templates and also to provide abstraction over the model for filling pictures in the polygons.
Figuring out the best way in which we could save the templates and the best way to represent them.
Developing algorithms that deal with complex geometric calculations and also consider error boundaries as dealing with pixels in not always perfect.
Developing algorithms to be able to fill, scale, resize, rotate and work with images inside the collage while editing the collage and be able to reflect that scaled up versions of the collages while saving them for high resolutions.
Developing algorithms for compression and caching of images that need to be used to provide a fast and seamless experience of creating a collage and also incorporating the logic to get back to high res images from these compressed ones while saving the collage.

This iteration was the most major iteration as it laid the base framework which would speed up not only the development but also the design process as we now could gauge what was possible and what would be time intensive which helped in making complex and difficult design decisions and also decision based on what UI elements and widgets would need to be used. Above all this framework provided us with an app that helped us create our own templates. This capability helped us to be visually involved in creating the pre-existing templates that would be provided to the users. 


## Second Major Iteration

Now that we have our unique feature we needed to get back down to the basics. Focusing the app only on the unique feature would be wrong to the user as we first needed to figure out what would be the most intuitive way to create a collage. We realised that in the physical world we would never start making a collage by first deciding where to place the pictures and their shapes. We would always first chose the set of photos that we want to work with. And so even though our USP was creating templates we decided to move it to a later stage keeping the intuition of the user in mind. We mimicked our app flow to the real world process of creating collages. This was the most important design challenge of the second iteration.

This iteration coincided with the time when Google announced Material Design Principles for Android. Thoroughly inspired by the principles of Paper and Ink and material consistency we focused our design efforts in this iteration to match our flow with the material principles. As far as dev was concerned, this iteration dev was only done to implement the new design and flow that was inspired by material design and real world intuition of making collages.


## Third Major Iteration

Now that our flow was complete, it was time to polish the look and feel of the app and make decisions to add or reject features. We decided that our app did one thing and one thing only for the time being and that was to help users create beautiful and brilliant collages in the most user-friendly and quickest way possible. All other features like sharing created collages or editing them by adding filters, text etc would be delegated to apps on the users phone that were specifically designed for such purposes.

We decided to add a new feature in the app to include aspect ratios for the collages being created. We live in a world where we no longer mail images through post or gift them through presents. We share them on people’s Facebook Walls, Instagram, keep them as our profile pictures, our cover pictures and even Twitter header images or even use them for creating our wallpapers for phones, desktops, laptops, etc. All these uses require the base image size to conform to certain standard ratios. It would be inevitable for the user to use our app to create collages for one or more such uses and therefore we decided to give the user to simply chose which use case they want instead of creating a collage and then worrying about their faces being cropped off for not sticking to the use-case standards. Moreover inside the collage while initially placing the pictures for the user we even make sure that the aspect-ratio of the section in the collage matches the image that is being placed in it to prevent unnecessary and unwanted cropping of the beautiful images selected by the user.

A new colour theme was chosen for the app, elements were polished, traditional widgets were replaced with our own contextual, user-friendly more functional widgets. Finally the beta design of the app was ready and the dev work started.

### Design Challenges

* Making decisions on Sharing and Editing features
* Designing widgets for Colour Selection, Filter Selection & Aspect Ratio Selection from scratch.
* Making decisions on animations
* Deciding app themes and colour choices
* Polishing user interactions and experience

### Dev Challenges

* Implementing the new design with new themes and colour choices
* Implementing all collection views using Recycler View introduced for Android
* Implementing all the new custom widgets
* Including Aspect Ratios in pre-existing templates and also for user created templates.
* Making sure that user experience stays the same for Lollipop and Pre-Lollipop devices for Android which meant making animations and other features of Material Design to be implemented in a way that they worked with Pre-Lollipop Android versions too.

And so we landed on the version of the app that we were delighted to use and develop. We were satisfied with our work and it was finally time to let CollageFlow out into the wilderness of the Play Store. Our first in house project had seen the light of day and we had finally given ourselves the gift our creating beautiful and amazing collages.