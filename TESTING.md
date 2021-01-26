# Testing

## 1. Automated Testing

### Validation Testing 

Validation testing was undertaken for HTML and CSS

For HTML validation the [W3C Markup Validation](https://validator.w3.org/#validate_by_input) was used. It yielded the following results:

<img src="https://github.com/Ciaranwbrady/MS1_Fresh_Market/blob/master/assets/docs/Testing1.png?raw=true" style="margin: 0;">

With these inital results I set about fixing the returning errors. Once this was complete I retested and the following results were returned

<img src="https://github.com/Ciaranwbrady/MS1_Fresh_Market/blob/master/assets/docs/testing2.png?raw=true" style="margin: 0;">

At this stage I was happy with the HTML Validation as it returned no errors. 


For CSS validation the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) was used by direct input. It yielded the following results:

<img src="https://github.com/Ciaranwbrady/MS1_Fresh_Market/blob/master/assets/docs/CSS%20Validation.png?raw=true" style="margin: 0;">

The CSS yielded no errors and I was happy to procede with further testing at this stage. 



### Lighthouse testing

For some further insight insight I tested the page with [Google Lighthouse](https://developers.google.com/web/tools/lighthouse)

<img src="https://github.com/Ciaranwbrady/MS1_Fresh_Market/blob/master/assets/docs/lighthousetesting.png?raw=true" style="margin:0;">

Steps taken to improve on these performance and accesibility results

-   Added title to iframe attribute 

-   Changed Navbar colour to meet accesibility guidlines and pass each test on the [Webaim Contrast Checker](https://webaim.org/resources/contrastchecker/)

- Set height and width for item that this was not set for. 

<img src="https://github.com/Ciaranwbrady/MS1_Fresh_Market/blob/master/assets/docs/lighthouse2.png?raw=true" style="margin:0;">

- The accesibility still needs to be improved but this is something that would require a bit more time from me and is a little beyond my learning currently. The default form elements used from the bootstrap documenation are returning high accesibility errors. As these forms are just for a static page this is okay. This would definetely need to be addressed on a real site.  

- Finally Aria label elements were added to all link elements. 

This resulted with a marked imrpovement in accesibility that is just below 90. With further insight and time I believe I could improve this further. Given this is my first project I am happy to learn from it. 

<img src="https://github.com/Ciaranwbrady/MS1_Fresh_Market/blob/master/assets/docs/accesibiltyimprovent.png?raw=true" style="margin:0;">

## Responsiveness and Compatibility

To check responsiveness for the site [Google Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools) were used which provide the following results 

<img src="https://github.com/Ciaranwbrady/MS1_Fresh_Market/blob/master/assets/docs/Responsive%20Breakpoints.png?raw=true" style="margin:0;">

## Devices and Browsers

I was unable to find a way to test my site on Internet Explorer as I did not have access to it. This is something I hope to rectify and work on after submission. 

The galaxy fold was the only device that had some display issues. The didn't overlay effect the usage of the website. However, I would like to improve it in portrait mode.

<img src="https://github.com/Ciaranwbrady/MS1_Fresh_Market/blob/master/assets/docs/Device%20Testing.png?raw=true" style="margin:0;">

<img src="https://github.com/Ciaranwbrady/MS1_Fresh_Market/blob/master/assets/docs/Browser%20Testing.png?raw=true" style="margin:0;">



## Code Institute Peer Code Review

I submitted my project for feedback on the Peer code review channel of the Code Institutes Slack. With the feedback I gained from this I was able to implement some fixes and changes.

- The Navbar brand Hover state was forcing the text and navbar to expand. I changed the hover properties for navbar.brand and this stopped the menu from expanding.

- I also changed the display properties for the mailing list to display differently on devices smaller than lg. This dropped it down to it's own section and was more visually appealling. 

- As a result of sharing my project I was also able to figure out something that was broken in the About us section. The About Us text was overfollowing and presnting issues with horizontal scroll. This was due to a spelling error for a Container item. Without the slack channel I may not have spotted this. 

## Performance Testing 
- Some Additonal performance testing was carried out on [WebPageTest](https://www.webpagetest.org/) with the page scoring very well on every section bar security. This is something I'm sure I will learn to improve on as I progress on the course

<img src="https://github.com/Ciaranwbrady/MS1_Fresh_Market/blob/master/assets/docs/webperformancetest.png?raw=true" style="margin:0;">

## Further Responsive Testing

Some additonal visual testing was done on the following websites to see how the webpage looked on different devices together.

- [Responsive Design Checker](https://www.responsivedesignchecker.com/)

- [Am I Responsive](http://ami.responsivedesign.is/)

## User Stories 


## Bugs 