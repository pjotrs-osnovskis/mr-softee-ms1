![Am I Responsive Image](assets/img/amiresp.png)


# Mr Softee

## Idea/Description

Idea behind this project is to create a website for existing Ice Cream Van business I work for over the weekends. I want to make it light, easy to browse on the varaity of different devices with most useful info about company and what they do. Sort of "business card" website. 

>**Important:** I have agreed with business owner to use any text or images (not code) off his current website for this project for learning purposes, their usage will be credited here or in the comments by their code.

## Roadmap (will be marked off once done)

I intend to create a 4-page website that includes:

1. **Home page [DONE]** 

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

## Wireframes

[Here](https://app.moqups.com/vBfsRq0TBr/view/page/a91ceea0e) you can find a wireframes of my page that I have in mind as of 05/04/21.

## Header

Simple and light header, with naviagtion and burger button in mobile devices, logo on the left.

## Footer

fixed footer with company contacts info, social links (basic).

## Contributors

* Pjotrs (Pete) Osnovskis

## Licence

Private

## Credits

01. Found a [Datepicker](https://github.com/eureka2/ab-datepicker) online and thought to use it for customer convinience in Hire a Van page.

## Project Status

Project is in development as of 05/04/21, please follow Commits and section below for further updates.

## Fixes/Issues/Solutions

Here I will comment on issues and problems I have faced and solutions I found.

1. Centered Logo, I have alligned all items in one line and looks okay, but picture is stretched in middle column in full width, cant get it to be nicely in center. (overall time spent on centering the logo: about an hour) 
    + steps taken: played around with CSS and bootstrap classes to get it right, but nothing works at the moment.
    + **Solution** okay, seems to be sorted, logo is positioned in the middle and size I want it to be, gone thorugh some study material and had a mess in CSS after trying different things, so cleaned up the mess, then [this video](https://www.youtube.com/watch?v=hp-LP8Nv18s) gave me a little advice regards left: 50% and margin-left: half of the width of the image. I tried to play around with right: 50% and all, but it wont work. Works for now, will move on now.

2. Gradient of hero image, instead of fading image out in image editor I decided to try and do it using CSS so I can chage images and still get the same result. Googled it and found a easy solution to use gradient generator, credits in the code. 

3. Hero content container with transperent background. I knew how to make a transperent background, but had some struggle to vertically align it, tried bootstrap classes even, but at the end remembered that there is a simple ```vertical-align``` rule, so solved too. 

4. Width of website is wider than actual screen size, tried ```box-sizing: border-box;``` everywhere, but it won't work. Looking for solution online.
+ tried ```container``` and ```container-fluid``` from bootstrap, but it won't help.
+ Did not find solution online, but realised, that it might be navbar issue, checked ```.row``` in header, removed padding and it worked, now everything is fit to actual screen size.

>--==-- Re-designed whole navigation code --==--

5. After a mentor meeting, decided to go with suggestion and use bootstrap navigation, had an issue to figure how to put menu items in place I wanted with logo in the middle.
+ online did not show much results, so decided to figure how to center the menu items first and then spread them to place where I want it.
+ found ```mx-auto``` class that centered all items, but instead, to be able to style all items like I wanted, I picked ```navbar-nav```, centered it with own css and moved each item separately targeting child elements of ```navbar-nav```. Now it all is in place on desktop version like I need but in mobile preview it is a bit off, so will style it once will do mobile part later on.

>--==-- Re-designed most of CSS to mobile first --==--

6. Realised that by using ```min-width```, best to strt off with mobile design and adjust rest of the code for desktop. will know for future.

7. on burger menu when expanded goes behind hero content, looking out for a fix.
+ thought to have collapable menu going on top of content, then with time realised it is not practical no visually good, so moved on to menu, that wpuld push content down and will be better visually and practically.
+ long time I spent on optimizin navbar for mobile and desktop, playing with different sizes and ideas, finally, after 2 hours of styling, I got to poin I am happy with mobile menu style, works well on mobile, tablet and desktop. 


8. Set up secondary section on landing page. Used idea from Code Institute's Resume Project i.e. three-reasons items. Changed most of the code to my own liking, there was some minor issues with positioning, but overall looks good.

> **Important:** It has a gap between 962px and 1240px where webapp is mixed in styles between mobile and desktop view. Need to look in to it! As it was okay at first, but then switched between previews with different widths and it plays up.

## Next steps

+ move on to trays.html page
