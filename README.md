# Mr Softee

## Idea/Description

Idea behind this project is to create a website for existing Ice Cream Van business I work for over the weekends. I want to make it light, easy to browse on the varaity of different devices with most useful info about company and what they do. Sort of "business card" website. 

>**Important:** I have agreed with business owner to use any text or images (not code) off his current website for this project for learning purposes, their usage will be credited here or in the comments by their code.

## Roadmap (will be marked off once done)

I intend to create a 4-page website that includes:

1. **Home page**

    General information, why us, good hygene, friendly staff, maybe use some picture slides, book now button in the middle.

2. **Events (book now)**

    Contact form made for event booking/reservations/date request, information about general practice, pop up window after "submit" saying "we will be in touch soon”.

3. **About**

    General about page with short description, map and company address, contact details.

4th page ideas:

  * **Trays:** 

    Seasonal stuff, menu and information how and where to follow us to find out when we'll be in the area.

  * **Charity:** 

    in what charity events we participated lately or what charities we support, pictures, stories, etc.

## Mockup

[Here](https://app.moqups.com/vBfsRq0TBr/view/page/a91ceea0e) you can find a mockup of my page that I have in mind as of 05/04/21.


## Header

Simple and light header, with naviagtion and burger button in mobile devices, logo on the left.

## Footer

Fixed footer with company contacts info, social links (basic).

## Contributors

* Pjotrs (Pete) Osnovskis

## Licence

Private

## Project Status

Project is in development as of 05/04/21, please follow Commits and section below for further updates.

## Fixes/Issues/Solutions

Here I will comment on issues and problems I have faced and solutions I found.

1. Centered Logo, I have alligned all items in one line and looks okay, but picture is stretched in middle column in full width, cant get it to be nicely in center. (overall time spent on centering the logo: about an hour) 
    + steps taken: played around with CSS and bootstrap classes to get it right, but nothing works at the moment.
    + **Solution** okay, seems to be sorted, logo is positioned in the middle and size I want it to be, gone thorugh some study material and had a mess in CSS after trying different things, so cleaned up the mess, then [this video](https://www.youtube.com/watch?v=hp-LP8Nv18s) gave me a little advice regards left: 50% and margin-left: half of the width of the image. I tried to play around with right: 50% and all, but it wont work. Works for now, will move on now.

2. Gradient of hero image, instead of fading image out in image editor I decided to try and do it using CSS. so I can chage images and still get the same result. Googled it and found a easy solution to use gradient generator, credits in the code. 

3. Hero content container with transperent background. I knew how to make a transperent background, but had some struggle to vertically align it, tried bootstrap classes even, but at the end remembered that there is a simple "vertical-align" rule, so solved too. 

4. Width of website is 15 px wider than screen, tried box-sizing: border-box;, everywhere, but it won't work. Looking for solution online.

## Next step
> add google fonts and pick fonts for the web app, then move on to footer and mobile preview.