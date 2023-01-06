Testing base:
# QUALITY ASSURANCE Website Development Checklist

# UI and Design Testing #
- First impressions matter! Designing a website that expresses the brand’s identity and is enjoyable for visitors is no small feat.

## [ ] Visual coherence and ease of navigation:
 ### [ ] Text consistent across all pages
#### [ ] Fonts
#### [ ] Paragraph, headers, and other text sizes
#### [ ] Color
#### [ ] Icon style
#### [ ] Brand

### [ ] Links’ behavior and color are consistent for all states(Unvisited, visited, hovered, active, disabled, etc.)

### [ ] Buttons(Double-check colors for CTAs, disable vs enable, etc.)

### [ ] Alignment and spacing are consistent throughout the site

### [ ] Images, animations, and visuals:
#### [ ] Proper dimensions
#### [ ] All visuals are in the right place
#### [ ] SVG format used where possible
#### [ ] Favicon is properly scaled

### [ ] CSS has passed validation
### [ ] HTML has passed validation

#  Content testing #
- Sites riddled with spelling errors or poor structure will put off potentially valuable users.

## [ ] Correct all grammatical/spelling errors:
### [ ] Headers
### [ ] Paragraphs
### [ ] Navigation(Don't forget hamburger menus and other hidden navigation)
### [ ] Media(Check text inside of images and videos with extra care)
### [ ] Page metadata(Title, description, URL)

## [ ] Remove all placeholders
## [ ] Blog posts must have an author
## [ ] Include copyright statement in footer
## [ ] Add a 404 page
## [ ] No duplicate pages
## [ ] Content is unique(Use a plagiarism checker like Grammarly)

# Functional testing #
- Are your site's features working as expected? You don’t want to give out the idea that “not even the website works properly”. Double-check that every feature can be interacted with.

## [ ] Ensure link validity:
### [ ] Remove broken links(Use the "Link Checker" extension to do this faster)
### [ ] Verify links destination(Remove or fix links pointing to nowhere, too)
### [ ] Remove hidden links(You will only find those with a crawler tool like Screaming Frog)
### [ ] External links open in a new tab
### [ ] In-page link anchors: make sure scrolling works properly
### [ ] Use relative internal links rather than absolute
### [ ] Ensure every page has at least one link pointing to it(Pages without links are harder for search engines to find)

## [ ] All elements can be interacted with:
### [ ] Drop-downs
### [ ] Buttons
### [ ] Text fields
### [ ] Tables
### [ ] Search
### [ ] Checkboxes
### [ ] Tabs

## [ ] All forms work properly:
### [ ] Data validation (in all states - whole range of correct & incorrect data)
### [ ] Form submission and confirmation(Use the “Fake Filler” Chrome extension to do this faster)
### [ ] Data collection

## [ ] Media:
### [ ] All videos are playable
### [ ] WebP or SVG format used where possible


# Accessibility testing #
- Is your website usable by people with disabilities? About 15% of the world lives with some form of disability (hearing, visual impairment…). Make sure they can use your website, too.

## [ ] Provide audio/visual alternatives:
### [ ] Add alt text attributes for images(This is also important for SEO)
### [ ] Site is usable while zoomed in
### [ ] Forms have labels
### [ ] Links are recognizable
### [ ] Add captions to videos
### [ ] Provide an alternative for users with Javascript disabled
### [ ] Clear color contrast for colorblind people
### [ ] Use a logical structure(The “WAVE” Chrome extension helps a lot with this and other accessibility warnings)


# SEO testing #
- Is your website ready for search engines? Do all pages have clear titles, URLs, and meta descriptions? Do basic optimizations from the get-go and have your website indexed by all major search engines.

## [ ] On-page optimization:
### [ ] Page title is relevant and optimized for target keyword(Keep it under 60 characters to avoid truncation)
### [ ] URL contains target keyword


 # Responsive & cross-browser testing # 
 - Does your site work on all devices and operating systems? Your site should be easy to navigate on any device: desktop computer, laptop, phone, and other mobile devices. You should also take this opportunity to verify browser compatibility.

## [ ] Cross-device testing:
### [ ] Content is readable
### [ ] Navigation is functional
### [ ] Forms are easy to fill
### [ ] Alignment and spacing are responsive

## [ ] Cross-browser testing:
### [ ] Firefox
### [ ] Chrome
### [ ] Safari

## [ ] Cross-system testing:
### [ ] Windows
### [ ] Mac
### [ ] Android
### [ ] iOS

# Security testing #
- Is your website secure? Are there any blatant vulnerabilities? Make your visitors feel at ease and prevent website attacks.

## [ ] Privacy policy.
## [ ] Log in/register screens, password pages(Ensure you give the proper response message in case of errors).

## Unit-Testing
## E2E-Testing
