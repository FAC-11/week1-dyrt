[dyrt developers Readme]

## dyrt developers website

The dyrt website is a place for any client looking to hire a team of developers to learn about the dyrt dev team and contact them. The project also facilitated the learning of the development team.


### Publishing

The website URL is:
https://fac-11.github.io/week1-dyrt/


## Features



The user stories this website fulfils are:

As a client looking to hire a team of developers...

- I want to visit your site and immediately see a headline about your team
So that I get a concise description of what you have to offer me.

- I want to visit your site and see a navigation link for 'About, Team, and Contact'
so I can quickly navigate to the areas of the site I'd like to visit.

- I want to be able to contact the developers by filling out and submitting a form by providing my name, email and message information
So that the team have sufficient information to contact me afterwards

- I want to click on a navigation link and a corresponding section be made visible in the browser window on the same page
So that I can quickly navigate around the site without having to wait for new pages to be loaded.

- I want to easily view the site when browsing on my mobile, tablet or desktop
so that I can understand the sites content easily on whatever device I choose to view it in.

As a visually impaired client...

- I would like to easily read and understand the text on your site
so I can understand the information available
As a blind client...

- I would like to easily understand how to navigate the site after my screen reader reads me the content of the site
so I can understand the information available.
As a client with JavaScript disabled in their browser for security reasons

- I would like to visit your site and get a similar experience to viewing your site on a modern browser with JavaScript enabled
so that I don't feel like I'm completely in the stone age.


## How - Our Journey to (Almost) Completion

1. We sketched out a wireframe for our website.  
 As a team we agreed a rough layout and design.

2. We created issues to describe what we wanted to include in our site.  
   We tried to create issues that were independent of each other so that each
   team could work on them without causing too many merge conflicts!

3. Splitting into pairs we chose the most important issues to solve in order to
   get a basic version of our site up and running.

4. Once we had a basic version, we focussed more on details and design.  
 We mostly followed two workflows where one half of a pair new a lot more about
 a subject than the other we used pair programming (towards the end we found we ended up
 working more independently due to the time pressure, with one person doing
 more research while the other continued working on agreed tasks!)

5. We aimed to design in a mobile-first way.  
 In practice we did tend to think about larger screens first and then sort out
 our media queries to work on smaller screens - but we did have mobile in mind
 throughout rather than adding it in at the end.

 6. We created the site without Javascript with the idea of adding Javascript
    features towards the end to ensure it would work well with Javascript
    disabled.  


## Contributing


If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome. The link to clone is:
https://github.com/FAC-11/week1-dyrt.git



## Credits

Credit for all code in the project is due to:

@rachaelcodes
@dangerdak
@morkeltry
@bowssy88

## Learning milestones



 - Dak - Learned About:
   *  Git and github: Make frequent small commits
   * Dont merge your own pull requests
   * I learnt about the css unit `vh` which allows you to size elements relative to the viewport height
   * I learnt that you can set up forms without having a backend
using eg formspree or a google script

- Tom - Learned:
  * I learned that git is to be feared and respected.
Specifically:
  * Get somebody not working on it to review your pull requests.
  * Create new branches for each new feature and delete the old ones.
  * Do not rely on atom working its clever magic behind the scenes. If your branch seems to be misbehaving, closing and restarting atom may help.
  * I learned how useful the 'Computed' section in the Inspector is for debugging styles (in conjunction with 'Pick element' - its logo is the mouse pointer on a tiny box).
  * I learned that, when you have a lot of nested tags, they'll will need most of their margins setting to zero! (margin: none doesn't always work)
  * I learned that the 20/20/20 rule places a time boundary around your stress!

 - Rachael - Learned about:
   * css `font-weight:` can be normal; bold; or if you want it to be bolder 800; or even 900;. If you’re using Google Fonts, make sure you request the 700, 800 or 900 options for the bolder weights
   * to carry over styling from parent div, try `margin: inherit`; `padding: inherit`;
   * for a child with `position:relative` , the parent must be ‘positioned’: so the parent should have the tag `position:absolute`
   * to test on different screen sizes, try this http://cybercrab.com/screencheck/
   * check the different pairs are on different branches

 - Yahia - Learned:
   * Cemented use of git on the terminal . Learnt some new commands including:
	`git commit -am "message"` adds and commits in one command.
   `git branch -a` command lists all branches including hidden ones.
   * Learned that serif means fonts with flicks on the ends and sans serif is without this.
   * Use of Flexbox: Learned more on how to use it, in particular with its use on containers. Learned that whenever you have multiple lines of flex, use flex-wrap to move the lines down.
   * CSS selectors and semantic html - Learned more about the semantics of html websites, and how to structure them. Learned about the space selector for child elements. .
   * Learned about creating readme's, and about lisences. In short: GPL - The entire purpose of this license is to make it impossible for someone who uses the code to make changes that they do not then make available freely and openly. The software a person produces must also be open source. BSD and MIT are permissive lisences that have been tested in court.  They are the most 'open source' and require little effort to comply with. To comply with these licenses, the person or organisation using the code simply has to reproduce the license and copyright notice. Otherwise, they may do as they wish with the code, including bundling it up and selling it as-is.




## Licensing

The code in this project is licensed under MIT license.
