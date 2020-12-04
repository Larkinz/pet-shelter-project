# Testing

View live version of the website [here](https://larkinz.github.io/pet-shelter-project/).

Milestone Project 1: User-Centric Front-end Development – [Code Institute](https://codeinstitute.net/)

In this document you will find information about the testing procedures that I have used to make sure the website displays and functions correctly.

---

## Contents

- [**Browser compatibility**](#browser-compatibility)

  - Tested browsers and devices
  - What I tested
  - Browser compatibility testing results

- [**Mobile responsiveness**](#mobile-responsiveness)

- [**Lighthouse**](#lighthouse)

- [**Code validators**](#code-validators)

  - W3C - Markup Validation Service
  - W3C - CSS Validation Service

- [**Test cases**](#test-cases)

- [**Testing user stories**](#testing-user-stories)

- [**Bugs**](#bugs)

  - Solved bugs
  - Known bugs

---

## Browser compatibility

### Tested browsers and devices

I tested these browser versions on these devices:

**Desktop PC (64-bit, Windows 10):**

- Google Chrome Version 87.0.4280.88 (Official Build) (64-bit)
- Firefox Version 83.0 (64-bit)
- Microsoft Edge Version 87.0.664.55 (Official build) (64-bit)
- Safari (via https://www.browserstack.com/)

**Dell E7240 laptop (64-bit, Windows 10):**

- Internet Explorer Version 11.1139.18362.0 (64-bit)
- Opera Version 72.0.3815.400 (64-bit)

**Samsung Galaxy S7 (Android Version 8.0.0):**

- Samsung internet Version 9.2.00.70
- Brave Browser Version 1.13.87, Chromium 85.0.4183.102

### What I tested

List of things that I tested:

- If things display in the correct order
- If things display in the correct size
- If media displays and works correctly
- If all internal links work
- If hover effects work
- If pop-ups work and display correctly

### Browser compatibility testing results

**Internet Explorer Version 11.1139.18362.0 (64-bit):**

Website is not displaying correctly, everything is out of place and element and text sizings seem completely random. Grid and Flexbox don't seem to be supported either.
The links in the navigation bar work, but other than that I can't test anything since the footer is pretty much invisible. To see some screenshots just click on [example 1](testing-screenshots/IE-homepage.png) and [example 2](testing-screenshots/IE-contact.png).

**Opera Version 72.0.3815.400 (64-bit):**

Everything is working and displaying as intended.

**Safari (via https://www.browserstack.com/):**

I don't have any capability to properly test Safari myself, since I don't own any Apple devices and the Windows version was discontinued in September 2018. After a quick search on the internet I found the
website https://www.browserstack.com/ that lets you test other peoples' devices for a limited amount of time. From my limited testing capabilities what I found was that everything seemed to work and display
correctly on Safari Version 13.1 mac devices ([see screenshot](testing-screenshots/safari-mac.png)). On the one phone that had Safari Version 10 there were some spacing issues between elements ([see screenshot](testing-screenshots/safari-10.png)) and the hamburger
menu seemed to be broken since nothing happened when I tapped it. On all phones I tested that had Safari Version 11 or higher the hamburger menu worked ([see screenshot](testing-screenshots/safari-latest.png)), but the spacing issues between elements
on the homepage was still there. So in conclusion, if you're using the newest version of Safari everything seems okay except for some spacing issues on the homepage.

**Microsoft Edge Version 87.0.664.55 (Official build) (64-bit):**

Everything is working and displaying as intended.

**Firefox Version 83.0 (64-bit):**

Everything is working and displaying as intended.

**Google Chrome Version 87.0.4280.88 (Official Build) (64-bit):**

Everything is working and displaying as intended.

**Samsung Internet Version 9.2.00.70:**

The same spacing issues on the homepage that I encountered when testing Safari on iPhones seem to be present here ([see screenshot](testing-screenshots/SI-homepage.jpg)), other than that everything is working and displaying as intended ([screenshot of footer](testing-screenshots/SI-footer.jpg)).

**Brave Browser Version 1.13.87, Chromium 85.0.4183.102:**

Everything is working and displaying as intended, no spacing issues on the homepage here unlike the other mobile browsers ([see screenshot](testing-screenshots/brave-homepage.jpg)).

**_[Back to top](#contents)_**

---

## Mobile responsiveness

To test the website for mobile responsiveness I've been using the [Google Chrome devtools](testing-screenshots/chrome-devtools.png) throughout the coding of the media queries. I manually used the sliders to go through different screen sizes. I've also used all of the [pre-configured screen sizes](testing-screenshots/devtools-phones.png) in the devtools to test if things looked okay. The only issue that I found is that for some phone screen sizes the landscape mode is kind of zoomed in or sub-optimal looking, while on other phone screen sizes it looks perfectly fine.

**_[Back to top](#contents)_**

---

## Lighthouse

In the Google Chrome devtools is also a [Lighthouse feature](testing-screenshots/google-lighthouse.png) which gives you some performance, accessibility, best practices and SEO indicators for your website. I recorded some before and after scores from several pages. I managed to improve the performance score on pages (although this metric seemed somewhat unreliable, since scores deviated without changes to the website) by putting my images through compression on the https://tinyjpg.com/ website. I also improved accessibility scores by adding an aria-label in the HTML code to the hamburger menu button and on the frontpage I added a title to the embedded YouTube video in the HTML code. The SEO score was simply improved by adding meta tags in the HTML with a description of the website and keywords, I did this for all pages. Below you can see some of the before and after scores.

![Homepage desktop lighthouse](testing-screenshots/homepage-desktop-LH.png)

![Homepage mobile lighthouse](testing-screenshots/homepage-mobile-LH.png)

![Adopt page desktop lighthouse](testing-screenshots/adopt-desktop-LH.png)

![Adopt page mobile lighthouse](testing-screenshots/adopt-mobile-LH.png)

![Gallery page desktop lighthouse](testing-screenshots/gallery-desktop-LH.png)

![Gallery page mobile lighthouse](testing-screenshots/gallery-mobile-LH.png)

**_[Back to top](#contents)_**

---

## Code validators

### W3C - Markup Validation Service

I've put the HTML code for all pages through the [W3C markup validator](https://validator.w3.org/) and got no errors, just some harmless warnings. On the index.html page I got the following 2 warnings:

![HTML validator index page warnings](testing-screenshots/HTML-validator-index.png)

For the let go, about us and contact pages I got the same H1 warning that I got for the index.html page:

![HTML validator let go page warning](testing-screenshots/HTML-validator-letgo.png)

Weirdly enough I didn't get this warning on the adopt, dog gallery, cat gallery and pet gallery pages, even though I'm using the same code in there:

![HTML validator pass](testing-screenshots/HTML-validator-pass.png)

### W3C - CSS Validation Service

I've put the CSS code from my style.css file through the [W3C CSS validator](https://jigsaw.w3.org/css-validator/) and got no errors:

![CSS validator pass](testing-screenshots/CSS-validator-pass.png)

**_[Back to top](#contents)_**

---

## Test cases

placeholder text

**_[Back to top](#contents)_**

---

## Testing user stories

placeholder text

**_[Back to top](#contents)_**

---

## Bugs

### Solved bugs

placeholder text

### Known bugs

placeholder text

**_[Back to top](#contents)_**

---