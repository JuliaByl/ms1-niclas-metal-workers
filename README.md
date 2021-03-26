*work in progress*

# Niclas Metal Workers

## Why am I making this?

Niclas Metal Workers is, while built for a fictional company in north Dublin, based on real requests from my dad, who has a very outdated website with code that doesn't work like it used to. 
In short: it doesn't mirror his company's professionalism and needs an update. You can find a link to his current website [here](http://plat-niclas.com/).
Please note that permission has been given to share his website in the README.

<hr>
<hr>

### User Stories

#### As an owner of the website, I want to...

1. Make it **clear** to the users what my website is about
2. Mirror my company's **proffesionalism** through smart color picks and a sleek but inviting design 
3. Show off my **versatility** through many images as well as informational text showing the different kinds of services I offer
4. Make sure customers know they can **contact the company with any ideas**, even if it's not mentioned as a service on the page, through multiple call to action buttons and a contact form
5. Target a wide audience, **through smart UX**

<hr>

#### As an external user, I want to...

1. Understand from the start what the company offers through a **good introduction** on main page
2. Feel like it's not a hassle to find information, through **easy and clear navigation**
3. Feel like I can **trust** the contractor through a good first impression
4. Find proof that the company can handle smaller **private customers as well as big companies and cooperate with other contractors**, through documentation of previous works and access to reviews. 

<hr>
<hr>

### Features of the website
*This is the initial plan, if any changes occur to the design and layout, that will be put further down*

Across the entire page, everything is going to be styled using thirds, which is inspired by the Resume lesson from Code Insitiute.
Everything inside the header and body will be adhering to this as much as possible on big, medium and small screens. 
When not possible, they will be placed underneath each other instead.
This description is for a big screen layout. Please see wireframes for different screen size variations.
The short description of the layout is presented from top to bottom. 
Unless anything else is mentioned, it can be assumed that the content will be centered.
New row means it ends up under previous item. Any items described with a / between them is supposed to be placed next to each other.

<hr>

#### Header 

* Logo (1/3) / menu (2/3)

<hr>

#### Home (index.html)

* hero image
* Who are we
* What do we specialize in / image / What areas do we serve (1/3 each) 
* reviews (if there is time)

<hr>

#### Services (services.html)

* hero image
* header
* short disclaimer that they do all kinds of metal work + link to contact form
* images (3-grid) representing each service + text and short description about service over an opaque background horizontally stretching over half of the image
* services: tailored solutions / renovations / rent skylift / service work / metal roofing / welding 

<hr>

#### Gallery (gallery.html) 

* hero image
* header
* sub-header for each specific project / service that they have done
* 3-grid image gallery under each sub-header
* sub-headers: church roofs / welding / bigger projects

<hr>

#### Contact (contact.html)

* hero image 
* header
* text section for contact details (1/3) / contact form (2/3)
* google maps (stretched horizontally across entire section above)

<hr>

#### footer 

* copyright / linkedin / facebook / trustpilot / glassdoor / Contact us to get a **free quote** + link to contact form

<hr>

#### Initial wireframes

You can find the wireframes [here](https://github.com/JuliaByl/ms1-niclas-metal-workers/blob/master/images/wireframes-nmw.png) or go to my images folder and open wireframes-nmw.png.

<hr>
<hr>

### Changes, Bugs + solutions

#### Social media links in footer
I only found facebook and linkedin icons for the social media links on fontawesome,cwhich was the library I had planned to use.
I will add those two for now but might be changing to a different icon library so that I can link glassdoor and trustpilot too. If not, I will have to leave them out.

<hr>

#### ~~Hero image not responsive~~

I did not immediately notice that the hero image was not covering the entire screen horizontally on screens bigger than the one that I have been using. I will make it more responsive. 
![screenshot of hero image not filling up the entire right side of the page](assets/images/README-img/hero-image-issue.png)

*Fixed issue by adding **min-width: 100%;** to img element in the hero image section.*

<hr>

#### Responsiveness in .row classes across page

I have been adding more .row classes than what is neccessary, which have been affecting the responsivenes of the page. It currently does not look good when changing to smaller screen sizes.
*example image to be added soon*

*index.html + gallery.html partially done. Work on services.html next time.*

<hr>
<hr>

### Links, inspiration and creds (if too big to mention together with the code)

* Help with general issues: https://stackoverflow.com/
* Help with general reminders of how things work: https://www.w3schools.com/
* Website used for creating logo: https://www.freelogodesign.org/
* Website used for all other images: https://unsplash.com/
* Website used for finding the correct colors: https://color.adobe.com/create/color-wheel
* https://fontawesome.com/



