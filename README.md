# The Monkees' Major Project

### Site Address: 

https://ewanlockwood.github.io/the-monkees-major-project-01/

-----

## Table of Contents

1. [Overview](#overview)

2. [UX Design Procedure](#ux)
    - [Strategy Plane](#strategy-plane)
    - [Scope Plane](#scope-plane)

3. [Features](#features)
    - [Existing Features](#existing-features)
    - [Features Left to Implement](#features-left-to-implement)
    
4. [Technologies Used](#technologies-used)

5. [Testing](#testing)

6. [Deployment](#deployment)

7. [Credits](#credits)

-----

## Overview

In this project I was assigned to make a website for the Pop-Band "The Monkees'". I chose to follow-up with the suggested band and not decide on a project myself as I wanted to experience a real-life work situation where clients would say what they wanted to be displayed on their webiste.

This website displays content through visual and audible stimuluses such as: picture and videos and also audio files aswell. You can find infomation about each band member, the band availability and also tour dates in the UK. Additionally, there is an "Archives" page where viewers can look at their Discography and also listen to selected songs.
 
-----


## UX
 
 My method for the UX Design was to use the software Sketch (https://www.sketchapp.com/) to help me plan and design better. 
 
### Strategy Plane
 
This website is intended to be used by fans and potential fans. Therefore, there should be an abundance of media from the monkess that that veiwer can see or hear. Additionally, as it is a pop-band group the website needs to be basic and less tech savy as young people may want to access the website and therefore, the navigation should be easy to follow.

As I think it will be for younger audience (as the point is the monkees are at there prime) bootstrap would be a good libary to use as it is good mobile-first-approach. Moreover, as I am creating a B2C website there should be little text possible and more media should be used.

### Scope Plane

I wanted to included a page where there was a photo of the band, or individual photos, and when the user clicked a band memeber infomation about that band member would show. I thought this would create a more emotinal attachment because it shows their history and likes/dislikes.

Additionally, there would be an archive page showing all the band's discography so fans and potential fans can look up all their music with also a few songs free on their website so potential fans can decide whether or not they enjot the music.

Futhermore, I wanted to make a page to show the availablity of the group so people can book them out. Also, the dates or where and when they are peforming with a "Book Now" button will be made.
 
 ## Structure Plane
 
 For the structure plane I want to achieve the goal of making sure each piece of content is organised and placed correctly for the site's purpose and audience culture. Therefore, a easily usable navigation in the expected place and also accessibility points will be included for screen readers and images.
 
 ### Interaction Design
 
 <img src="assets/wireframes.png">
 
 The image above shows the structure of the website. Users will firstly load into the index.html page then directed to back stage where they can find a navigation in the following order: the logo used as a home button - Meet The Band - Monkee's Archive - Band Availability
 
 <img src="assets/tree-site.png">
 
As shown abovem a standard tree structure is implemented. It will be 3 levels but however will ensure the 3-click-rule is available with the index.html page being a page just for users to land on and will never be able to get to unless they revisit the website.

## Surface Plane

### Development

#### IDE

Cloud9 IDE was the Integrated development enviroment for this website.

#### Version Control

Git Hub was the version control station for this website which was used to manage and store versions of the source code.

-----
## Features
### Existing Features

1. Landing Page - I used the concept of having a full-width image of the band with a button to enter the website stating "Come Backstage!" to add a more user-friendly experience.

2. Backstage - I thought it was a good idea to have a "Backstage" of the website as when bands go on stage there is a chance for some  fans to go backstage and meet the band. This has an exclusive feeling about it and creates a more real-life experience. It also shows a video of them performing a song and is the only piece of content as I wanted the backstage just to be a place where viewers can go where ever they want from there.

3. Meet The Band - This page is where fans or potential fans can know more about each band member. I used pictures of each band member and created a hover effect so when they hovered of the face it shows their name and when clicked it directs them to another page with more indepth infomation about them. This was to make it look more visually satisfying rather than having text about each one on the same page. On those pages will be general infomation about them (Birthday, Birth-place and insturments they play), Likes/Dislikes, History and also social media links.

4. Archives - A place where viewers can listen to the most popular songs, look at the whole Discography of the Monkee's and see when new songs are released.

5. Band Availability - This is where fans can see where and when The Monkees' will be performing with a button to be linked to a place where they can purchase tickets. Futhermore, It has a Band Availability where people can book out The Monkees' for weddings etc.

### Features Left to Implement

I was going to make a live social media feed of each band member so when they post on either facebook, twitter or instagram it posts automatically on the website.

-----

## Technologies Used


### HTML
To provide the structure of the webiste.

### CSS
To make the website look better visually.

### Bootstrap
(https://getbootstrap.com/)
 To use their responsive grid system and also their sass variables where certain variables have an established design to it already.
 
-----

## Testing

When testing my website I wrote down all the links within the website and checked if they work correctly.

Index.html -> line 12 = "Come Backstage" directs the user to backstage.html in the same tab.

backstage.html / mtb.html / dj_page.html
md_page.html / mn_page.html / pt_page.html
archives.html / availability.html -> line 11 = Image of Monkees which directs the user to backstage.html / line 12 = button which expands the nav bar and is only displayed when the Navigation bar becomes collapsed / line 17 - 19 = 3 anchor tags that take the user to the corresponding page in the same tab.

mtb.html -> line 33 = anchor tage that directs users to dj_page.html in the same tab / 
            line 39 = anchor tage that directs users to pt_page.html in the same tab /
            line 45 = anchor tage that directs users to mn_page.html in the same tab / 
            line 51 = anchor tage that directs users to md_page.html in the same tab /
            
Inside each band member's page there are their social links which directs the user to a page outside the website and onto a new tab.

-----

## Deployment

The version control and deployment of this project is based on Git Hub. After every session I push the local code within Cloud9 into my GIT HUB repository.

This is my procedure: 

After I have finished working on the files in my IDE I would open the terminal and do the following commands to push the updated files across to the repository on GitHub

``` $git add . ```

```$git commit -m "describe the stage I am at"```

```git push -u origin master```

I would now ```$git status``` to check if everything is finished and then look at the repository to see there aswell.

-----

## Credits
### Content
History of each band member can be found on their wiki page:
- https://en.wikipedia.org/wiki/Micky_Dolenz - Mickly Dolenz
- https://en.wikipedia.org/wiki/Michael_Nesmith - Michael Nesmith
- https://en.wikipedia.org/wiki/Davy_Jones_(musician) - Davy Jones
- https://en.wikipedia.org/wiki/Peter_Tork - Peter Tork

The following webpages were used for debuging code and to attain pre-set css in some cases.

- https://www.w3schools.com
- https://css-tricks.com
- https://developer.mozilla.org/en-US
 
### Media
All peices of conent (photos, videos, audio) that were used in this site were obtained from the project assets given to me.
