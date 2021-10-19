# Thanet Gaming Club

Thanet Gaming Club is a site that advertises and informs people about a brand new gaming hobby club that has started in Westgate-on-sea, Thanet. The site is aimed at gamers of all ages and abilities and it offers an easy-to-access way of finding out how to join the group as well as the benefits of doing so. Not only does the site detail the times, dates and venue of the club, but it also offers information about the range of games and consoles on offer to play.
 
The site also offers a sign-up form and links to social media for anyone interested in connecting with the group.



![Responsive Mock-up](https://github.com/StevieMigan/thanet-gaming-club/blob/main/assets/images/responsive.png?raw=true)



## Features 

- __Navigation Bar__

  The Navigation bar appears on all three pages and features links to the "Home", "games" and "join us" sections. The Navbar has been styled with a color changing hover feature to highlight to the user which section they will be navigating to next.

  Featuring the Navigation bar on all three pages negates the need for the user to use the back button when navigating the site.

![Nav Bar](https://github.com/StevieMigan/thanet-gaming-club/blob/main/assets/images/navbar.png?raw=true)

- __The landing page image__

  The Landing features a bright and colourful feature image that captures the attention of the user immediately, coupled with a short, snappy overview of the purpose of the website and the club that it serves to advertise.

![Landing Page](https://github.com/StevieMigan/thanet-gaming-club/blob/main/assets/images/landing-image.png?raw=true)

- __What do we play? section__

 -The "What do we play?" section provides further details to the user of the kinds of activities that take place at the club as well as the range of hardware available to play.

  -The section is complimented by another eye-catching image, along with individual logos for the aforementioned games consoles that are available to play at the club.

![What do we play?](https://github.com/StevieMigan/thanet-gaming-club/blob/main/assets/images/what-do-we-play.png?raw=true)

- __When and where to find us? section__

  - This section serves to inform the user of the weekly meetup day and times for the group, as well as featuring the full address in an easy to read format. 

  - This section also includes a Google maps link that shows the user precisely where they can find the group.

![When and where to find us?](https://github.com/StevieMigan/thanet-gaming-club/blob/main/assets/images/where-to-find-us.png?raw=true)

- __The Footer__ 

  - The footer section provides the user with alternative ways to link in with and follow the group on their various social media pages - these include: Facebook, Twitter and Instagram.

![Footer](https://github.com/StevieMigan/thanet-gaming-club/blob/main/assets/images/footer.png?raw=true)

- __Games__

  - The games section provides an overview of some of the games available to play at the club. This serves to inform the user of what they can access whilst also offering some relatability as they should hopefully recognise one or two of the games.
  -Games have been selected based on a mixture of current popularity along with some retro classics thrown in to appeal to older audiences. 

![Games](https://github.com/StevieMigan/thanet-gaming-club/blob/main/assets/images/games-library.png?raw=true)

- __Join Us section__

  - This page allows a simple means of registering your interest in the club. It encourages users to leave their name and email address to allow a member of the team to send a follow-up email inviting them along to the club meet and/or to answer any further questions.

![Join us](https://github.com/StevieMigan/thanet-gaming-club/blob/main/assets/images/join.png?raw=true)

### Features Left to Implement

- Embed a Youtube video onto the homepage that showcases the group and what goes on there.
- Add Testimonials and feedback from people who already attend the group.

## Testing 

A number of testing methods have been used throughout the creation of Thanet Gaming Club. The navigation elements, both internal and external have been checked to ensure they lead to the right page and that all external links open in a new tab.

The Lighthouse feature of Chrome Dev tools has been used to ensure a consistently high score in all 4 areas of testing:

*Performance
*Accessibility
*Best Practices
*SEO

![Lighthouse](https://github.com/StevieMigan/thanet-gaming-club/blob/main/assets/images/lighthouse-score.png?raw=true)

Site colours and features have been chosen to compliment one another and text color has been chosen to contrast against backgrounds to maximise UX and accessibility. The Site has been tested on a range of Devices and on 3 different browsers to ensure a consistent performance.

-Chrome
-Firefox
-Edge

The relevant media queries have been implemented to ensure a smooth UX site-wide for all screen sizes. This has been tested using Chrome developer tools and finalised using - http://ami.responsivedesign.is/#

A few minor alterations were made for these media queries - The Hero-image does not appear on mobile devices, focusing instead on relaying information and using the high-score image as a background to provide an eye catching landing page. The background colours for the individual sections have also been removed to just be black on smaller screens, again to minimise overwhelming the user with too many colors and features.

## Bugs

A number of bugs were found during the construction of the project, both in the HTML and CSS files.

- Fixed bugs in file paths that were causing certain images not to load. I removed "/" before assets to fix this problem sitewide.

- Fixed potential issue in the footer social media links relating to security - as flagged by Lighthouse checks - Added rel="noreferrer" to fix this.

- Fixed a bug causing long load times on index.html and games.html by converting images from JPG and PNG format to webp, before compressing images to ensure the minimum file size.

- Fixed a bug in CSS code that was causing console pictures to be sized incorrectly and stretch outside their individual borders. Rectified this by adding "object-fit: cover;" and correcting the Width and Height elements.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator] (https://github.com/StevieMigan/thanet-gaming-club/blob/main/assets/images/w3-html-check.png?raw=true)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://github.com/StevieMigan/thanet-gaming-club/blob/main/assets/images/jigsaw-css-check.png?raw=true)

### Unfixed Bugs

None to report.

## Deployment

This site has been deployed to GitHub pages - Deployment steps are as follows:

- From the Github repository, navigate to the settings tab
- From the source section drop-down menu, select the "Master" branch
- Once this has been selected, the page will refresh with a ribbon display to indicate that the site has been deployed successfully.

The Live link can be found here - https://steviemigan.github.io/thanet-gaming-club/


## Credits 

### Content 

- Hero-image.webp and snes-contoller.webp have been sourced from https://www.pexels.com/
- The icons in the footer, as well as the Control pad icon used in the site logo were taken from https://fontawesome.com/
- Fonts - Roboto & Autowide have been sourced from https://fonts.google.com/
- Code for the Sign-up form was adapted from the CI "Love Running" walkthrough project. The Form destination still links to CI but the rest has been changed to fit with the site purpose and style.

### Media

- Hero-image.webp and snes-contoller.webp have been sourced from https://www.pexels.com/
- Console logo sources: 

PS5-Logo - https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRojY0hZpJtconMSSl-gXqhQfBs_cQ21ncapw&usqp=CAU

N64-Logo - https://1000logos.net/wp-content/uploads/2017/07/Emblem-N64.jpg

Xbox-series-x-logo - https://twinfinite.net/wp-content/uploads/2020/03/Xbox-Series-X-Logo-scaled.jpg

Megadrive-logo - https://image.pngaaa.com/521/4150521-middle.png

Sega-master-system-logo - https://www.logolynx.com/images/logolynx/6c/6ca781208326a18e1df470307bdeac15.jpeg

Sega-dreamcast-logo - https://i.pinimg.com/originals/80/1a/3e/801a3e3501cfb3c25a34d456dc3a3a1c.jpg

Snes-logo - https://logodix.com/logo/311006.png

Nintendo-switch-logo - https://sportshub.cbsistatic.com/i/2021/03/18/6b14bc50-dc21-4ae9-b73c-c1282b002e8a/nintendo-switch-logo-black-white-1216019.jpg

Nintendo-gamecube-logo - https://cdn.freebiesupply.com/logos/large/2x/nintendo-gamecube-logo-png-transparent.png


- Games gallery sources -

Castle-of-illusion-ps3 - https://images-na.ssl-images-amazon.com/images/I/81r0SDcqyNL.png

Fortnite-ps4 - https://www.cranbrookeducationcampus.org.uk/wp-content/uploads/2018/12/fortnite-2.jpg

Goldeneye-n64 - https://upload.wikimedia.org/wikipedia/en/3/36/GoldenEye007box.jpg

Halo-infinite-xbox - https://content.halocdn.com/media/Default/community/InfiniteCoverArt/halo_infinite_wallpaper-mobile_1080x1920-a49fb4f750fc4a4d9ae2cc9f58f4e366.jpg

Mario-kart-8-deluxe - https://assets.nintendo.eu/image/upload/f_auto,q_auto,t_product_tile_desktop/MNS/NOE/70010000000126/SQ_NSwitch_MarioKart8Deluxe

Minecraft-ps4 - https://ferncreekkids.files.wordpress.com/2015/08/minecraft-banner-3_3510581_3522898.jpg?w=640

Timesplitters-2-artwork - https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQRa_EZQXBhsF7BdI4FQXBXUshMRuBDRQliM6buSEhxWqdUsgwH-xk_Je13vqG9-9pLdSw&usqp=CAU

Sonic-2-megadrive - https://upload.wikimedia.org/wikipedia/en/0/0c/Sonic_2_US_Cover.jpg

Super-mario-world-snes - https://e.snmc.io/lk/o/x/c5c0fa491bb1ea4faf324b8f53aa1fcd/6735381

