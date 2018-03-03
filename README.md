# How to Make an Inaccessible Website

Everyone is **different**. Everyone thinks and behaves **differently**. That's what makes us unique. Web accessibility is about making the web for everyone, being inclusive and providing access for all.

To do that it is important to recognise the different areas, skills and roles that impact on accessibility. It's not just content that affects how a website is perceived, operable and understood but it is also influenced by design, development, performance and security amongst other things.

It's hard to purposely make an inaccessible website as you must recondition your brain - throwing standards, values and principles out of the window. So why do a lot of websites still have accessibility issues?  Well, a lot of it comes down to awareness & understanding, organisation culture and working styles.

For this document we are not talking about the broader inclusive design definition, which there are many overlaps with **modern day accessibility**, this is more a look at the themes and issues that can occur - being proactive rather than reactive.

The following is a common **incomplete** checklist on what is involved in making an inaccessible website. We welcome contributions.

## Table of Contents

- [Business](#business)
- [Users](#users)
- [Design](#design)
- [Development](#development)
- [Content](#content)
  - [Language](#language)
  - [Page Title](#page-title)
  - [Page Layout](#page-layout)
  - [Navigation](#navigation)
  - [Headings](#headings)
  - [Colour and Contrast](#colour-and-contrast)
  - [Images](#images)
  - [Links](#links)
  - [Multimedia](#multimedia)
  - [Typography](#typography)
  - [Tables](#tables)
  - [Forms](#forms)
  - [Buttons](#buttons)
  - [Keyboard Access](#keyboard-access)
  - [Frames](#frames)
  - [Focus, Behaviour and States](#states-behaviour-and-focus)
  - [Time Based](#time-based)
  - [HTML](#html)
  - [CSS](#css)
  - [JS](#js)
- [Testing](#testing)
- [Security](#security)
- [Performance](#performance)
- [Digital Marketing](#digital-marketing)
- [Support](#support)
- [General](#general)
- [Credits](#credits)
- [Resources](#resources)

---

## Business

This is generally the business owners, sometimes it's marketing or whoever controls the budget depending on the organisation size, type and sector.

List of Dos: ✔️

- [ ] Do use and stay with third-party legacy enterprise <abbr title="Content Management System">CMS</abbr>.
- [ ] Do use and stay with third-party legacy <abbr title="Learning Management System">LMS</abbr>.
- [ ] Do register overly long and hard to remember *domain names* - keyboard users especially love that.
- [ ] Do develop your own user agent for your audience - we could always do with another web browser.
- [ ] Do limit opportunities to increase your bottom line.

List of Don'ts: ❌

- [ ] Don't make a business case for latest software.
- [ ] Don't make a business case for latest devices.
- [ ] Don't make a business case for latest firmware.
- [ ] Don't make a business case for any assistive technologies not already available.
- [ ] Don't comply with legislation.
- [ ] Don't comply with national or international standards.
- [ ] Don't have any existing policies, processes or frameworks in place.
- [ ] Don't do any user research - assume each web project has the same users and outputs, saves on cost.
- [ ] Don't use any online tools that promote cross team collaboration and agile ways of working.
- [ ] Don't use a shortened domain name that redirects to that overly long one.
- [ ] Don't be concerned about your brand or reputation.

[back to top](#table-of-contents)

---

## Users

Everyone should be virtual stakeholder and have an invested interest. However, you'll find this is often not the case.

List of Dos: ✔️

- [ ] Do keep legacy client-supplier relationship models (externally).
- [ ] Do keep inter team / department working silos (internally).
- [ ] Do assume that the project manager, or business owner, represents multiple different user types.
- [ ] Do assume that the project manager is a <abbr title="User Experience">UX</abbr> and accessibility expert.

List of Don'ts: ❌

- [ ] Don't involve or get any input from other business teams.
- [ ] Don't involve or get any input from real users.
- [ ] Don't involve or get any input from any blind or low vision impaired users.
- [ ] Don't involve or get any input from any deaf users.
- [ ] Don't involve or get any input from users with multiple disabilities.
- [ ] Don't involve or get any input from users with invisible disabilities.
- [ ] Don't involve or get any input from users with learning difficulties or disabilities.
- [ ] Don't involve or get any input from elderly users.
- [ ] Don't involve or get any input from young users.
- [ ] Don't involve or get any input from users with differing education levels.
- [ ] Don't involve or get any input from <abbr title="English for Speakers of Other Languages">ESOL</abbr> users.
- [ ] Don't involve or get any input from users with differing computer literacy skills.
- [ ] Don't safeguard vulnerable individuals and social groups.
- [ ] Don't involve any UX consultants.
- [ ] Don't involve any accessibility consultants.

[back to top](#table-of-contents)

---

## Design

Normally contained within the design activities again this depends on the organisation, structure and size as some can bleed into development function.

List of Dos: ✔️

- [ ] Do assume there is only one user journey through the site.
- [ ] Do assume there is only one user persona.
- [ ] Do design for one vendor and a particular release at that.
- [ ] Do design for one orientation - no one uses portrait apparently.
- [ ] Do change the design based on the time of day - don't need to inform users in advance of any major changes.
- [ ] Do assume that users only access your website from their office, never from home - they will be on super duper ultrafast fibre extreme unlimited hardcore weapon X broadband connections.
- [ ] Do use parallax designs - reports that they are overwhelming and can cause ill effects like motion sickness, dizziness and confusion are untrue.
- [ ] Do assume usability and accessibility are the same thing.
- [ ] Do assume accessibility can only be addressed by development alone.

List of Don'ts: ❌

- [ ] Don't offer any customisation pre-login - assume all users have the same level of digital skills and computer literacy.
- [ ] Don't offer any theme switcher - low vision, eye fatigue, emotional condition and hangovers are not real things.
- [ ] Don't use proven design patterns - be bold, create something new and different.
- [ ] Don't design for print, ensure the website looks the same when printed out.
- [ ] Don't do mock-ups, wireframes, prototypes and/or storyboarding - keep users and business owners in suspense.
- [ ] Don't follow latest trends or techniques - it's good to stay in the dark.
- [ ] Don't ever revisit a design after going live - assume it is right first time, tada!
- [ ] Don't cater for inclusive design - it's a myth like self-driving cars.
- [ ] Don't ensure primary calls to action, especially above the fold, are obvious.
- [ ] Don't do any logical content sort or information architecture.

[back to top](#table-of-contents)

---

## Development

Tasks and activities normally assigned to front end or back end development of the web application. Also, with no coding standards, or methodologies, used then the results for other developers (as well as the end user) can be unexpected. #codebaselivesmatter.

List of Dos: ✔️

- [ ] Do use legacy <abbr title="Integrated Development Environment">IDE</abbr> or code editors - HotDog anyone??
- [ ] Do use legacy authoring tools - upgrade costs are unnecessary.
- [ ] Do <abbr title="Write Everything Twice">WET</abbr> yourself often.
- [ ] Do <abbr title="Do Repeat in Places">DRIP</abbr>.
- [ ] Do <abbr title="Garbage In, Garbage Out">GIGO</abbr> - the user agent will fix any mistakes you make, that's their job.
- [ ] Do overly depend on CMS third party plugins to make sites accessible - contrast switcher? Yep, the site is now fully accessible. Yay.
- [ ] Do install as many CMS plugins as possible - no requirement for the backend to be accessible or understandable (a developer is not a user).
- [ ] Do install and use as many JavaScript frameworks as possible - this will have no adverse impact at all.
- [ ] Do render block scripts and styles.
- [ ] Do browser sniff - you'll *always* get accurate results that way.
- [ ] Do use <abbr title="Internet Explorer">IE</abbr> conditional statements.
- [ ] Do assume accessibility can only be addressed by design alone.

List of Don'ts: ❌

- [ ] Don't use any <abbr title="Cascading Style Sheets">CSS</abbr> methodologies.
- [ ] Don't use any <abbr title="JavaScript">JS</abbr> methodologies.
- [ ] Don't use any <abbr title="Hypertext Markup Language">HTML</abbr> preprocessors.
- [ ] Don't use any CSS preprocessors.
- [ ] Don't use any JS preprocessors.
- [ ] Don't use feature detection.
- [ ] Don't use a tag manager - instead have multiple <abbr title="Hypertext Transfer Protocol">HTTP</abbr> requests and scripts, plus marketing <abbr title="Request for Change">RFC</abbr> with development <abbr title="Service-level Agreement">SLA</abbr> is guaranteed to always run smoothly.
- [ ] Don't use web standards - go with proprietary software that has a long shelf life '#flash2020'.
- [ ] Don't use lints in development mode.
- [ ] Don't debug code - assume it will work first time.
- [ ] Don't use code validation tools.
- [ ] Don't refactor code.
- [ ] Don't <abbr title="Keep It Simple, Stupid">KISS</abbr>.
- [ ] Don't leave code comments for complex functions - other developers enjoy figuring out what is going on.
- [ ] Don't use task runners, module bundler or package managers - you have plenty of time to do things your way, what sprints?
- [ ] Don't use any proven web scaffold project - keep on reinventing the wheel and code from scratch, trust your code.
- [ ] Don't use open source over proprietary software.
- [ ] Don't use templating - making things look and feel consistent is so 10 years ago.
- [ ] Don't clean, trim (whitespaces) or treat user generated web content.
- [ ] Don't strip (or encode) HTML elements out of user generated content outputted to screen.
- [ ] Don't keep frameworks updated.
- [ ] Don't use lean methodologies - include all the framework, you never know when you may need it in the future.
- [ ] Don't use any caching - always best to get everything fresh from the server every time.
- [ ] Don't use <abbr title="Authoring Tools Accessibility Guidelines">ATAG</abbr> compliant CMS's.
- [ ] Don't use mainstream UTAG compliant user agents.
- [ ] Don't use `.webmanifest` format, with correct mime types, for different device home screens.
- [ ] Don't use relevant server config file (for URL rewrite, redirection, custom error pages, TLS, proxy server, etc., etc.).

[back to top](#table-of-contents)

---

## Content

The crux. Content owners can stretch across an entire organisation including externally such as suppliers, or partners, if they are also providing content for extranet, intranet or public facing sites.

List of Dos: ✔️

- [ ] Do use (Adobe) Flash movies for animation and slideshow features.
- [ ] Do create content in non-standard web format as such served as '.txt' files.
- [ ] Do use content identified by location - Marco...
- [ ] Do use 'under construction' pages and message in production environments - perfectly acceptable, will boost user confidence as well.
- [ ] Do use **lorem ipsum** or dummy text in completed content ready tasks.
- [ ] Do use multiple non-breaking spaces `&nbsp;` in content copy.
- [ ] Do display content that is in a different reading order in source code.

List of Don'ts: ❌

- [ ] Don't create any style and/or user guides.
- [ ] Don't adhere to any style guides - it just stifles creativity, override CMS template CSS with content CSS.
- [ ] Don't provide 'terms of use' content - let the user assume your site *operates* the same as everyone else's.
- [ ] Don't provide 'privacy or cookies' content - if you don't tell them, you can do what you want with their data.
- [ ] Don't provide an 'accessibility' content - certainly don't state what guidance and level the site conforms with, when it was last tested, enhancements and/or points of contact if there are issues.
- [ ] Don't spell check copy - assume the user makes the same spelling mistakes as you do.
- [ ] Don't check grammar - your welcome (yes, I know it's spelt *you're*).
- [ ] Don't proof read - assume the user knows how you think.
- [ ] Don't expand the first instance of abbreviations, acronyms and initialisms with `<abbr>` element.
- [ ] Don't show file sizes or file types when needed to link to non-standard web formats such as '.pdf', '.docx', or '.zip'.
- [ ] Don't show how long an article or blog post content type takes to read.

[back to top](#table-of-contents)

---

### Language

Lugha ya kumbukumbu na lugha ya maudhui.

List of Dos: ✔️

- [ ] Do interchange British English and American English spelling variations such as 'centre' / 'center', 'colour' / 'colour', 'behaviour' / 'behavior', etc., etc.
- [ ] Do use technobabble.
- [ ] Do use slang words.
- [ ] Do use specific regional language.
- [ ] Do overly rely on automated translation services to convert page into another language.

List of Don'ts: ❌

- [ ] Don't properly identify the language of the page `<html lang="[ISO 639-1 code]">`.
- [ ] Don't properly identify the language change within portions of the page `lang="[ISO 639-1 code]"`.
- [ ] Don't consider other audiences or content flow - everyone, everywhere reads left to right.
- [ ] Don't offer 'glossary of items' if nature of site and content is technical or profession based.
- [ ] Don't use established HTML Editors like TinyMCE or CKEditor to produce compliant user generated web content.
- [ ] Don't use a native speaker to help translate content into other said languages.
- [ ] Don't consider providing other languages especially for public funded web projects - e.g. UK project, provide English and Welsh as standard.

[back to top](#table-of-contents)

---

### Page Title

Page titles helps define the title of document, giving it meaning and purpose.

List of Dos: ✔️

- [ ] Do remember there is no recommended minimum length for page titles - can leave it blank as no one saves, bookmarks or shortcuts these days.
- [ ] Do remember there is no recommended maximum length for page titles - the longer the better.
- [ ] Do remember that page titles can be duplicated for other pages - saves you thinking of unique and meaningful titles.
- [ ] Do stuff page titles with keywords - stuff it I say.
- [ ] Do omit the `<title>` element entirely.

List of Don'ts: ❌

- [ ] Don't use good descriptive `<title>` elements.
- [ ] Don't optimise `<title>` element for 7-8 words or 50-60 characters.

[back to top](#table-of-contents)

---

### Page Layout

A bit to the left. More. A bit more. A little bit more. More. Okay, stop. Hmm... Move to the right instead. More. A bit more. A bit more. A little bit more. More. Hmm... You know what? It was fine where it was.

List of Dos: ✔️

- [ ] Do use complex layouts.
- [ ] Do use plenty of large irregular whitespace gaps in layouts.
- [ ] Do use spacer images for layout.
- [ ] Do use tables for layout.
- [ ] Do change layouts from page to page regards of section, article or content type.
- [ ] Do blend main content copy into secondary content.
- [ ] Do implement scrolling on content list items within a page.
- [ ] Do remember that horizontal scrolling is way cooler and modern than vertical scrolling.
- [ ] Do implement scrollbars that are over 100% viewpoint width.
- [ ] Do use cookies notification layouts that obstruct basic content and site functionality.
- [ ] Do place ads that are disruptive to basic content and functionality.
- [ ] Do use obtrusive ad block detectors.
- [ ] Do assume all third party served content such as ads, cookies, API integration will be accessible and customisable - no testing or thought required.
- [ ] Do make sure each browser has a different user experience.

List of Don'ts: ❌

- [ ] Don't offer clean and consistent layouts that don't cause confusion and hard to remember.
- [ ] Don't offer any visual cues to close modals or inline pop-ups with mouse.
- [ ] Don't offer any visual cues to close modals or inline pop-ups with keyboard access or touch controls - tab / tap background should have expected results.
- [ ] Don't support 'pinch zoom' gestures on mobile devices.
- [ ] Don't support motion detection control features with hybrid web apps.
- [ ] Don't offer the same content and/or functionality on mobile devices.

[back to top](#table-of-contents)

---

### Navigation

☝️ ☝ 👇 👇 👈 👉 👈 👉 🅱 ️🅰️

List of Dos: ✔️

- [ ] Do make clickable targets teeny weeny.
- [ ] Do ignore human psychology patterns and display multiple visible options on the navigation bar - at least 10-12 options available on the primary navigation works well.
- [ ] Do make users dependent on the user agent navigation buttons (back and forward) for site navigation.
- [ ] Do state which browser the site is best supported on.
- [ ] Do state what resolution the site is best viewed on.
- [ ] Do bury content more than 4 levels deep.
- [ ] Do change menu ordering after selection.
- [ ] Do load next content page automatically when scrolling to bottom of current content page.

List of Don'ts: ❌

- [ ] Don't use breadcrumb navigation on complex or content heavy sites.
- [ ] Don't offer pagination for multiple records or results.
- [ ] Don't highlight current page when using pagination.
- [ ] Don't offer filtering for multiple categorised search results such as date, author or content type.
- [ ] Don't offer different views for search results such as grid and list.
- [ ] Don't highlight where in the user journey you are - keep users guessing where in the site you are.
- [ ] Don't provide a skip link (bypass block) for content rich sites or that use complex navigation.
- [ ] Don't use table of contents for multiple sections and content hierarchy - ignore what this document does.
- [ ] Don't provide alternative means to find content such as HTML sitemap or simplified site search feature - make users depend on main navigation as primary route for content.
- [ ] Don't offer advanced search for large quantity of differing content types.

[back to top](#table-of-contents)

---

### Headings

Refers to `<h1>` all the way through to `<h6>` elements.

List of Dos: ✔️

- [ ] Do skip headings order, jumping from `<h1>` to `<h3>` elements are quite common.
- [ ] Do use empty heading elements.
- [ ] Do omit `<h1>` element altogether.
- [ ] Do use faux headings with style formatting `<div class="heading">`, `<span class="heading">` and `<p class="heading">` elements are common ones to do this on - visually it's fine.
- [ ] Do use multiple `<h1>` elements on a standard content page without sectioning elements.

List of Don'ts: ❌

- [ ] Don't use headings that start new sections of content.
- [ ] Don't use headings to structure content.
- [ ] Don't use headings in hierarchical order - `<h2>` elements can come after `<h3>` elements.
- [ ] Don't use one `<h1>` per page.

[back to top](#table-of-contents)

---

### Colour and Contrast

Colour is key but not for the reasons you think.

List of Dos: ✔️

- [ ] Do use colour to convey content and instructions alone.
- [ ] Do use colours that are hard to focus on - lime background works exceptionally well, concentration wise it's awesome.
- [ ] Do use the same text colour as link colour for main body content.
- [ ] Do remember that black and white are *colours*.
- [ ] Do remember that color is spelt with a 'u'. - c-o-l-o-u-r
- [ ] Do assume that chosen colours have the same meaning worldwide in every culture.
- [ ] Do use colour gradients on body text.
- [ ] Do make colours fluid on elements.
- [ ] Do make clickable targets rotate colours.

List of Don'ts: ❌

- [ ] Don't ensure text sizes are within acceptable contrast ratio thresholds.
- [ ] Don't ensure text (foreground) and backgrounds colours are within acceptable contrast ratio thresholds.
- [ ] Don't make focus elements distinguishable when tabbing.
- [ ] Don't offer high contrast modes or themes.
- [ ] Don't use fixed colour states.

[back to top](#table-of-contents)

---

### Images

Images can also refer to SVG, canvas drawn, button images and style sourced background images not just those derived from `<img>` element.

List of Dos: ✔️

- [ ] Do use both `alt` and `title` attributes for `<img>` elements.
- [ ] Do use large uncompressed raster images - render size on fly.
- [ ] Do duplicate images for multiple purposes.
- [ ] Do use images that have no relevant context or meaning to text copy.
- [ ] Do store the filename of the image in `alt` attribute.
- [ ] Do use obtrusive watermark images supporting main content copy.
- [ ] Do use generic popular stock photos.
- [ ] Do link `src` to third party hosted images that you have no control over.
- [ ] Do hotswap images.
- [ ] Do use background images to support main content.
- [ ] Do ensure image map clickable areas `<map>` overlap.
- [ ] Do provide hidden areas on image maps `<map>`.
- [ ] Do embed text into raster images.

List of Don'ts: ❌

- [ ] Don't provide a text alternative for infographics based images.
- [ ] Don't use 'PNG' fallback for legacy browsers if using 'SVG' - users should be upgrading their browsers.
- [ ] Don't use `srcset` attribute to target multiple devices.
- [ ] Don't apply `alt=""` or `aria-hidden="true"` attributes to decorative images.
- [ ] Don't use `alt` attribute on `<map>` elements
- [ ] Don't make images responsive.
- [ ] Don't place large collection of images over 'CDN' i.e. product catalogue, asset library or stock photos.
- [ ] Don't supply good descriptive `<figcaption>` elements with `<figure>` element.

[back to top](#table-of-contents)

---

### Links

20 GOTO 10.

List of Dos: ✔️

- [ ] Do use multiple links to the same location - increases the chances of a user selecting it.
- [ ] Do use links that can be taken out of context - 'click here', 'read more', 'show more' or 'go here', vagueness is great, adds to the suspense.
- [ ] Do open links in external pop-up windows.
- [ ] Do use inline JavaScript on links `<a>` element `href` attribute itself.
- [ ] Do make links do more than standard behaviour, i.e. open two new tabs and download a file with one click.
- [ ] Do use `title` attribute on links.
- [ ] Do use broken links - it's a test to see if the people actually use the site.

List of Don'ts: ❌

- [ ] Don't warn users that links may open in a new or pop-up window - unexpected behaviours are great.
- [ ] Don't warn users that links take them offsite - assume that third-party sites are designed the same as yours therefore same user experience.
- [ ] Don't make links behave like links.
- [ ] Don't make links easily identifiable.
- [ ] Don't notify users that links do not go to another HTML document e.g. links go to an actual image or a downloadable file or opens a third-party software application and/or setting on your device.
- [ ] Don't ensure that image only links (no text) have appropriate alternative text set (`alt` attribute used).

[back to top](#table-of-contents)

---

### Multimedia

And action.

List of Dos: ✔️

- [ ] Do use short but multiple framed animated gifs on infinite loops.
- [ ] Do provide meaningless animation.
- [ ] Do auto play / auto start video without offering any controls.
- [ ] Do embed video content with missing text alternative.
- [ ] Do ensure talking heads have a heavy / thick accent.
- [ ] Do ensure talking heads mouth movements are visually hidden.
- [ ] Do try and film in raw camcorder footage.
- [ ] Do use low quality and jerky movement.
- [ ] Do provide fluctuating volume in video audio.
- [ ] Do provide meaningless video content.
- [ ] Do auto play / auto start audio without offering any controls - works so well when sitting in Costa with no headphones plugged in.
- [ ] Do embed audio content with missing text alternative.
- [ ] Do provide fluctuating volume in audio sound.
- [ ] Do provide meaningless audio content.

List of Don'ts: ❌

- [ ] Don't provide player controls for complex animation.
- [ ] Don't provide a mechanism to stop any user triggered animation.
- [ ] Don't provide a warning for videos showing flickering or strobing lighting effects.
- [ ] Don't provide a warning for videos showing jump scares.
- [ ] Don't provide a warning for videos showing graphical content.
- [ ] Don't provide captions or transcript for pre-recorded videos content.
- [ ] Don't provide transcripts for live (scripted) video.
- [ ] Don't auto generate captions for live streaming video.
- [ ] Don't provide sign language for videos.
- [ ] Don't consider video duration for content purpose - 5 mins or 30 mins? attention span and availability.
- [ ] Don't provide player controls for video content.
- [ ] Don't offer different video quality - high, medium, low
- [ ] Don't offer different video playback speed - half, x.75, normal, x1.25, x1.75, double.
- [ ] Don't offer other navigation mechanisms in video playback - intervals of 10 or 30 seconds, back or forward.
- [ ] Don't provide player controls for third party video content such as YouTube or Vimeo.
- [ ] Don't provide transcripts or text alternative for pre-recorded audio content.
- [ ] Don't provide player controls for audio content.

[back to top](#table-of-contents)

---

### Typography

FONT FACES AND APPEARANCES AND STYLES - OH MY. <- Oops, caps lock.

List of Dos: ✔️

- [ ] Do justify body text - what river effect?
- [ ] Do use any display fonts.
- [ ] Do make paragraphs as large as possible - no limitations or impact.
- [ ] Do use bold (`<strong>` element) on complete paragraphs.
- [ ] Do use italics (`<em>` element) on complete paragraphs.
- [ ] Do use all caps text on complete paragraphs. - scream your point across.
- [ ] Do use fixed font size values.
- [ ] Do change font sizes during a paragraph.
- [ ] Do use with all your might to have two spaces after a period.
- [ ] Do use overly lightweight or thin font faces.
- [ ] Do use font faces that can cause confusion - distinguishing between capital letter 'I', lowercase letter 'l' and numeric digit '1' is fun.

List of Don'ts: ❌

- [ ] Don't use text sizes that are scalable.
- [ ] Don't use adequate `line-height` property values, consider font face and use default user agent as baseline.
- [ ] Don't use adequate `letter-height` property values, consider font face and use default user agent as baseline.
- [ ] Don't use adequate body text size, consider font face and use default user agent as baseline.
- [ ] Don't break up paragraphs into manageable chunks.
- [ ] Don't use fall backs for third party web fonts - for offline purposes or when Google Fonts went down that time.
- [ ] Don't use family fonts - user font corruption never happens.
- [ ] Don't offer adjustable body text feature - rely on user agent to offer 'Reader view' mode instead.
- [ ] Don't use standard icons and symbols - create your own (no, that doesn't look like a location glyph - looks more like fish).

[back to top](#table-of-contents)

---

### Tables

Golf. Really no good at word association games.

List of Dos: ✔️

- [ ] Do use deprecated `bgcolor` attribute on `<table>` element.
- [ ] Do use deprecated `border` attribute on `<table>` element.
- [ ] Do use deprecated `width` attribute on `<table>` element.
- [ ] Do use deprecated `cellpadding` attribute on `<table>` element.
- [ ] Do use deprecated `cellspacing` attribute on `<table>` element.
- [ ] Do remember table data `<td>` element can be omitted for missing data.
- [ ] Do use `<table>` elements for page layout.

List of Don'ts: ❌

- [ ] Don't use `<caption>` element to summarise the data table.
- [ ] Don't use `<caption>` element directly after `<table>` element.
- [ ] Don't use `<thead>` element for header information.
- [ ] Don't use `<tbody>` element for main data.
- [ ] Don't make data table responsive.

[back to top](#table-of-contents)

---

### Forms

Sign here.

List of Dos: ✔️

- [ ] Do use autofocus on forms - override document focus.
- [ ] Do apply autofocus to multiple form controls.
- [ ] Do use empty `<legend>` elements.
- [ ] Do use empty `<label>` elements.
- [ ] Do use `<fieldset>` elements without a `<legend>` element defined.
- [ ] Do use red asterisk content to mark which form controls are mandatory.
- [ ] Do use `tabindex` attribute on dynamic forms and routing.
- [ ] Do leave `<textarea>` element `resize` property values undeclared.
- [ ] Do ensure resizing of `<textarea>` element disrupts and changes the page layout unexpectedly.
- [ ] Do use `placeholder` attribute if form `label` display the same information.
- [ ] Do use `placeholder` attribute unstyled - default contrast is fine.
- [ ] Do use `title` attribute on form controls rather than `<label>` element.
- [ ] Do use `aria-label` or `aria-labelledby` attributes on form controls instead of `<label>` element.
- [ ] Do use associate labels implicitly with form controls as a general rule over explicit labels.
- [ ] Do use `<input>` element over `<button>` element for button functionality, using `type="submit"` and `type="button"` attributes.

List of Don'ts: ❌

- [ ] Don't use `id` attribute over `name` attribute for form controls.
- [ ] Don't make `id` attribute values unique.
- [ ] Don't offer instructions or examples for input solutions to complex regex `pattern` attributes.
- [ ] Don't use appropriate text to communicate which form controls are mandatory, e.g. 'Name (required)'.
- [ ] Don't split long form across accordion sections or across screens.
- [ ] Don't use step headings, progress bars or percent indicators on split forms, i.e. checkout process (sign up > check basket > delivery address > payment information > confirm or stage 1 of 5).
- [ ] Don't offer form navigation to review or amend previous entries before final submission.
- [ ] Don't capture minimal form data for registration process.
- [ ] Don't offer autocomplete features like address postcode finder, employee/staff directory or business listing services.
- [ ] Don't set `<textarea>` element `resize` property values to `vertical` or `none` only.
- [ ] Don't use ARIA attributes on dynamic changing forms.
- [ ] Don't group similar related form controls together using `<fieldset>` elements.
- [ ] Don't always use `<label>` elements with form controls.
- [ ] Don't use `<label>` element for challenge responses.
- [ ] Don't ensure `<label>` elements match the corresponding correct form controls.
- [ ] Don't ensure `checkbox` input elements has a unique `label` assigned.
- [ ] Don't ensure each `checkbox` input elements has a unique `id` attribute value.
- [ ] Don't ensure `radiobox` input elements has a unique `label` assigned.
- [ ] Don't ensure each `radiobox` input elements has a unique `id` attribute value.
- [ ] Don't ensure visually hidden `<label>` elements are still available to screen readers.

[back to top](#table-of-contents)

---

### Buttons

He's behind you.

List of Dos: ✔️

- [ ] Do use empty `<button>` elements.
- [ ] Do omit or use empty `alt` attribute on image buttons using `<input>` elements.
- [ ] Do intermix `<input>` elements and `<button>` elements for button functionality.

List of Don'ts: ❌

- [ ] Don't have good descriptive `<button>` element values.
- [ ] Don't have good descriptive `alt` attributes set for image buttons using `<input>` elements.
- [ ] Don't use `<button>` elements over `<input type="submit">` or `<input type="button">` elements.
- [ ] Don't ensure that text links styled to look like buttons, do operate similar to buttons. Default behaviour specifically focus, hover, active and clickable.
- [ ] Don't ensure all buttons have a functional purpose.
- [ ] Don't ensure image buttons, or styled buttons, are within acceptable contrast ratio thresholds.

[back to top](#table-of-contents)

---

### Keyboard Access

Tabbity, tab-tab.

List of Dos: ✔️

- [ ] Do use `accesskey` attributes - they are a recognised government standard (back in 2005) and do not interfere with browser or screen readers at all.
- [ ] Do use `tabindex` attributes - override organic ordering.
- [ ] Do remove `outline` property value for keyboard focusable targets.
- [ ] Do overwrite standard keyboard scrolling behaviour with 'spacebar' and 'directional arrows keys'.
- [ ] Do present keyboard traps leaving users unable to navigate to or from page elements via a keyboard only input.

List of Don'ts: ❌

- [ ] Don't ensure all clickable targets have suitable focus when keyboard tabbed.
- [ ] Don't ensure triggered focus targets have clear and distinguish visual cues.
- [ ] Don't ensure all page functionality is available using the keyboard.

[back to top](#table-of-contents)

---

### Frames

Say cheese.

List of Dos: ✔️

- [ ] Do use deprecated `<frameset>` elements.
- [ ] Do use deprecated `<frame>` elements.
- [ ] Do use `<iframe>` element with missing a title attribute.

List of Don'ts: ❌

- [ ] Don't set `<iframe>` element to be responsive.
- [ ] Don't use good descriptive `<iframe>` element title attributes.
- [ ] Don't consider that third-party sourced `<iframe>` element to stop serving content, implement clickjacking and/or introduce strict cross origin policies.
- [ ] Don't cater for fall back use of iframe for legacy user agents.

[back to top](#table-of-contents)

---

### Focus, Behaviour and States

What just happened?

List of Dos: ✔️

- [ ] Do overwrite natural user agent behaviours.
- [ ] Do use ARIA `role="menu"` attribute on `<nav>` elements.
- [ ] Do use ARIA `role="grid"` attribute on data `<table>` elements.
- [ ] Do use ARIA `aria-required` attribute in conjunction with form control `required` attribute.
- [ ] Do use ARIA `role="alert"` attribute to hidden elements.
- [ ] Do use multiple system alerts on hidden elements for all message types e.g. on success, on error, on warning, on information, etc., etc.
- [ ] Do use ARIA `role="button"` attribute on links.

List of Don'ts: ❌

- [ ] Don't make it obvious where the error lies.
- [ ] Don't link error message or hints to relevant form controls.
- [ ] Don't provide any help or visual cues to help with form completion and submission.
- [ ] Don't use ARIA `aria-expanded` attribute on content held within an accordion.
- [ ] Don't use ARIA `aria-invalid`, `aria-checked`, `aria-disabled` attributes to improve web forms.
- [ ] Don't use ARIA `aria-haspopup` attribute on pop-up menu, modals or lightboxes.
- [ ] Don't use ARIA `aria-busy` attribute for content ready and processing states.
- [ ] Don't use ARIA `aria-atomic` attribute to read new live changes only.
- [ ] Don't use ARIA live regions techniques for any SPA functionality.

[back to top](#table-of-contents)

---

### Time Based

3, 2, 1.

List of Dos: ✔️

- [ ] Do set idle timeout to less than 10 minutes.
- [ ] Do set live chat to log out after 5 minutes of inactivity.
- [ ] Do auto fade important messages - chances are users have read it first time.
- [ ] Do use third party sign in methods (OAuth) that offer different user experiences.
- [ ] Do log out users after unreasonable of time - 10 minutes.

List of Don'ts: ❌

- [ ] Don't provide manual mechanism to remove of key system messages or instructions.
- [ ] Don't suitably notify the user how time remains on a time bound task - e.g. releasing seats when booking online tickets.
- [ ] Don't let users defined reasonable time out ranges.
- [ ] Don't display a warning to the user prior to logging out that data will be lost.
- [ ] Don't display ARIA `role="timer"` supported countdown feature to session expiry.

[back to top](#table-of-contents)

---

### HTML

Web standard. Nuff said.

List of Dos: ✔️

- [ ] Do use duplicate `id` attributes - troubleshooting is half the fun and life is at the console.
- [ ] Do use mix up `id` and `class` attributes.
- [ ] Do use empty paragraph `<p>` elements.
- [ ] Do use deprecated `<center>` element.
- [ ] Do use deprecated `<font>` element.
- [ ] Do use deprecated `<blink>` element.
- [ ] Do use deprecated `<marquee>` element.
- [ ] Do use invalid ARIA `role` attribute names.
- [ ] Do use redundant ARIA `role` attributes with semantic HTML elements.
- [ ] Do interchange your `doctype` between HTML5, HTML4 strict and transitional.
- [ ] Do use `<pre>` for formatting and layout.
- [ ] Do design page layouts with data tables - no one uses CSS any more.
- [ ] Do use div elements to replace existing semantic structure - 'divitis' is back in fashion for 2018, it never really left.
- [ ] Do provide key web content and functionality in unnecessary non-standard formats such as forms in Microsoft Word.

List of Don'ts: ❌

- [ ] Don't declare `doctype` for your document - it's not needed.
- [ ] Don't use landmark elements `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>` and `<footer>`.
- [ ] Don't use semantic HTML to correctly structure a web document.
- [ ] Don't place all scripts prior to the closing of the `</body>` element.
- [ ] Don't add ending slash to sef-close elements `<br />`, `<img />`, `<input />`, `<meta />` - it's optional in HTML5 and has noooooo effect anywhere whatsoever.
- [ ] Don't ensure all elements are weighed correctly.
- [ ] Don't ensure all elements are well balanced, all have correct start and end tags.
- [ ] Don't clean up HTML comments.
- [ ] Don't prepare content copy directly within the CMS - use Microsoft Word.
- [ ] Don't use CMS HTML parser to strip out all non-standard HTML tags and styled. e.g. `charset=windows-1252` and `class="MsoNormal"`.

[back to top](#table-of-contents)

---

### CSS

Does my font look big in this?

List of Dos: ✔️

- [ ] Do ignore rules for specificity - plus go nuts with `!important`
- [ ] Do use vendor prefixes - no tools available to do that for you or target certain versions.
- [ ] Do provide important and key content via `content` property values.
- [ ] Do ensure when increasing text, it impacts on layout and functionality.
- [ ] Do ensure visually hide content is also hidden to screen readers.
- [ ] Do override the natural `cursor` property values and behaviours - be creative, change links to show an image instead of a pointer.
- [ ] Do use styles to visually describe document structure and meaning.

List of Don'ts: ❌

- [ ] Don't normalise CSS - user agents all work the same.
- [ ] Don't reset CSS - browser support is good.
- [ ] Don't separate presentation from mark-up - use inline styles.
- [ ] Don't honour Reduced Motion media query `prefers-reduced-motion` - it's not fully supported yet so there's that old argument.
- [ ] Don't cater for visually hidden content rule set that is still available for screen readers.
- [ ] Don't provide a simplified print version - make sure all page furniture is available on print.
- [ ] Don't use media queries for responsive design.

[back to top](#table-of-contents)

---

### JS

A *little* bit of ECMAScript in your life.

List of Dos: ✔️

- [ ] Do overwrite standard user agent behaviour like disable right click context menu.
- [ ] Do disable the entire site / page when scripts are disabled.
- [ ] Do leave `console.log` in production code.
- [ ] Do target the latest ecosystem like ES2018 - the browser will catch up next week.
- [ ] Do use obtrusive JavaScript - add handlers and functions directly to mark-up elements.
- [ ] Do use internal inline rather external JavaScript.

List of Don'ts: ❌

- [ ] Don't overwrite user browser settings - i.e. take control of the volume levels.
- [ ] Don't honour <abbr title="Do Not Track">DNT</abbr> - not fully supported yet old adage.
- [ ] Don't cater for basic navigation if scripts are disabled.
- [ ] Don't cater for basic content if scripts are disabled.
- [ ] Don't alert user if scripts are required for enhanced experience using `<noscript>` element.
- [ ] Don't lazy load images.
- [ ] Don't use ARIA for SPA applications like real time chat, shopping basket, store finder and other similar features.
- [ ] Don't use ARIA for SPA frameworks.
- [ ] Don't allow live chat transcripts to be save, emailed or printed.

[back to top](#table-of-contents)

---

## Testing

Sometimes covered with development team but let's face it in most cases it's not real proper testing or as objective certainly not to the same degree.

List of Dos: ✔️

- [ ] Do over dependent on one testing tool and one device.
- [ ] Do remember that if you can use it fine then hey everyone else can too.
- [ ] Do one round of testing - no one pays attention to concurrent users and load issues.
- [ ] Do rely on automated accessibility testing tools to pick up on every issue - manual testing or input is not required.

List of Don'ts: ❌

- [ ] Don't use A/B Testing.
- [ ] Don't use multiple testing tools.
- [ ] Don't use any testing scripts for user journey.
- [ ] Don't use code validation tools.
- [ ] Don't use iterative testing.
- [ ] Don't use mobile devices.
- [ ] Don't use browser dev tools.
- [ ] Don't use any automated accessibility tools.
- [ ] Don't test with just the keyboard.
- [ ] Don't use assistive technology such as screen readers or magnifiers.
- [ ] Don't use third party screen readers.
- [ ] Don't use native operating system screen readers like Voice Over on MacOS and iOS or Narrator on Windows.

[back to top](#table-of-contents)

---

## Security

From some businesses point of view developers are apparently security experts as well.

List of Dos: ✔️

- [ ] Do leave redundant code or functions commented out - <abbr title="Document Object Model">DOM</abbr> manipulation is so much fun.
- [ ] Do use CAPTCHAs provided by CMS.
- [ ] Do use CAPTCHAs that offer arithmetic challenges to answers.
- [ ] Do use CAPTCHAs that provide only one challenge type.
- [ ] Do set CAPTCHAs to expire quickly - they snooze, they lose.
- [ ] Do use as many third-party plugins or frameworks as possible - the more, the better.
- [ ] Do host scripts plugins or frameworks from GitHub repos - even better.

List of Don'ts: ❌

- [ ] Don't use any <abbr title="Uniform Resource Locator">URL</abbr> rewrite - use hard to remember paths and querystrings.
- [ ] Don't use any custom error pages - the site will never throw any errors, user will be fine with the experience.
- [ ] Don't use custom error pages - external sites, search engines, bookmarks / favourites will have to update their links.
- [ ] Don't cater for 404 not found custom error page.
- [ ] Don't cater for 500 and/or application custom error page.
- [ ] Don't prevent clickjacking, impact on automated testing.
- [ ] Don't use TLS on server.
- [ ] Don't use invisible CAPTCHA - i.e. reCaptcha.
- [ ] Don't allow option to show password when signing up - user memories are fine.
- [ ] Don't show informative password strength checker.
- [ ] Don't allow passwords to be auto generate by the user.
- [ ] Don't have HTTP headers information set correctly - server, XPB, RP, XFO, XXSSP, XCTO, STS, ECT, CSP, SRI.
- [ ] Don't have cookies set correctly - HTTPS, Secure, SameSite.

[back to top](#table-of-contents)

---

## Performance

Again, development might do this as well, then again might also be Ops.

List of Dos: ✔️

- [ ] Do have as large page assets as possible - people on slow connection, poor reception or limited bandwidth have plenty of time to wait.
- [ ] Do have as many page assets as possible.
- [ ] Do use limited bandwidth and resources hosting plans.
- [ ] Do host on data centres no one near your country.

List of Don'ts: ❌

- [ ] Don't minify the HTML.
- [ ] Don't minify the CSS.
- [ ] Don't minify the JS.
- [ ] Don't concatenate / bundle CSS.
- [ ] Don't concatenate / bundle JS.
- [ ] Don't optimise raster images.
- [ ] Don't optimise vector images like SVG.
- [ ] Don't remove comments from SVG - always useful to know if it was created in Illustrator or Sketch.
- [ ] Don't use server compression / gzip assets.
- [ ] Don't cache anything or anywhere.
- [ ] Don't drop favicon.ico in root path - error logs and alerts are fun to review.
- [ ] Don't load balance - what concurrent requests?
- [ ] Don't use CDN.
- [ ] Don't use DNS Prefetch.
- [ ] Don't ensure web apps are scalable.
- [ ] Don't ensure hosting platforms support scalable web apps.

[back to top](#table-of-contents)

---

## Digital Marketing

Accessibility has an impact on SEO which in turns leads to better usability, then ROI and increase bottom line. Also, your analytics can be quite telling.

List of Dos: ✔️

- [ ] Do use inviso text (same colour text foreground and background colour) for marketing purposes - screen readers love finding hidden gems and you definitely won't get penalised anymore.
- [ ] Do omit site and content from search engines / consoles.
- [ ] Do omit site and content from directory services.
- [ ] Do use the same body content for `<meta>` descriptions.
- [ ] Do click bait often.

List of Don'ts: ❌

- [ ] Don't use and analyse analytics on your site.
- [ ] Don't use SEO techniques on your site - users only navigate one way.
- [ ] Don't use marketing toolkits like SEMrush.
- [ ] Don't use data structure tools.
- [ ] Don't use enhanced meta data Schema.org.
- [ ] Don't use enhanced meta data OpenGraph.
- [ ] Don't use enhanced meta data Twitter Card.
- [ ] Don't ensure each page has a unique and relevant content image.
- [ ] Don't use enhanced features like Open Search.
- [ ] Don't use enhanced browser and OS support like Windows Tile & Notifications.
- [ ] Don't use and submit sitemap.xml.
- [ ] Don't use social media to promote site.
- [ ] Don't integrate or share content with social and professional networks.
- [ ] Don't allow customisable integrated user commenting services.
- [ ] Don't write teaser content on external (reputable) blogs or forums to signpost back to your site.

[back to top](#table-of-contents)

---

## Support

A website is never finished so what are the communication channels? What happens to the users between original go live and the next release? If there is one.

List of Dos: ✔️

- [ ] Do assume your website is perfect and that there will be no need for users to reach out.
- [ ] Do offer only one support route - you know, from the goodness of your heart.
- [ ] Do only offer support between core hours - no one uses your site before 10:00 AM and after 3:30 PM.
- [ ] Do remember when you eat, your users eat - no one uses your site between 12:00 PM and 2:00 PM.
- [ ] Do assume all users are on the same time zone - it's called *Universal Time* for a reason.
- [ ] Do ensure that your service support agent speaks a different native language to what your core site has been developed in - helps with bonding and socialising.
- [ ] Do ensure support staff on social media know that 'accessibility' only means 'service availability' - generating at least 10 back and forth exchanges is a necessary prerequisite to this.

List of Don'ts: ❌

- [ ] Don't provide multiple means of support for users who may come across issues - your time is more important than your brand or reputation.
- [ ] Don't train staff about possible supporting offline services (e.g. you offer a large print version).
- [ ] Don't train support staff about user accessibility needs and requirements.
- [ ] Don't use support staff that know the system or have <abbr title="Network Operations Centre">NOC</abbr> access - too costly to use good support staff.
- [ ] Don't have a real time system status page if providing critical services - <abbr title="Software as a Service">SaaS</abbr>.
- [ ] Don't believe the myth that the user is always right - always assume they are wrong until proven otherwise.
- [ ] Don't offer cross teams any training, workshops or meetups for accessibility awareness.
- [ ] Don't **intentional secret placeholder**.

[back to top](#table-of-contents)

---

## General

A few thoughts not yet categorised properly.

List of Dos: ✔️

- [ ] Do assume this checklist is final and relevant.

List of Don'ts: ❌

- [ ] Don't assume that this checklist will be out of date as soon as it is published.
- [ ] Don't collaborate internally - pay no attention to working with other teams or sharing ideas, knowledge and experiences.
- [ ] Don't collaborate externally - techniques and standards never change, be the bubble.
- [ ] Don't do project lessons learnt or continuous improvement.
- [ ] Don't pay any attention to this checklist.

[back to top](#table-of-contents)

---

## License

[MIT](https://raw.githubusercontent.com/wshu/how-to-make-an-inaccessible-website/master/LICENSE)

---

## Credits

[![William Shu](https://wshu.github.io/me.png "yep, that's me")](https://williamshu.com)


[back to top](#table-of-contents)

---

## Resources

Some basic but key resources that support and give guidance on why web accessibility is important. Certainly not exhausted but does need adding to at some point including (probably) citing real world examples of the dos and don'ts in action. Maybe.

### Standards and Guidelines

- [World Wide Consortium (W3C)](https://www.w3.org/ "Opens in new window")
- [Web Accessibility Initiative (WAI)](https://www.w3.org/WAI/ "Opens in new window")
- [Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/TR/WCAG20/ "Opens in new window")
- [Web Content Accessibility Guidelines (WCAG) 2.1](https://w3c.github.io/wcag21/guidelines/ "Opens in new window")
- [Accessible Rich Internet Applications (ARIA)](https://www.w3.org/TR/wai-aria-1.1/ "Opens in new window")
- [Authoring Tool Accessibility Guidelines (ATAG)](https://www.w3.org/TR/ATAG20/ "Opens in new window")
- [User Agent Accessibility Guidelines (UAAG)](https://www.w3.org/TR/UAAG20/ "Opens in new window")
- [ISO/IEC 40500:2012 (W3C)](https://www.iso.org/standard/58625.html "Opens in new window")
- [BS 8878:2010 Web accessibility. Code of practice](https://shop.bsigroup.com/ProductDetail/?pid=000000000030180388 "Opens in new window")

### Legislation

- <abbr title="United Kingdom">UK</abbr> - [Equality Act 2010](http://www.legislation.gov.uk/ukpga/2010/15 "Opens in new window")
- <abbr title="Australia">AU</abbr> - [Disability Discrimination Act (DDA) 1992](https://www.legislation.gov.au/Details/C2017C00339 "Opens in new window")
- <abbr title="United States of America">US</abbr> - [Section 508 of the US Rehabilitation Act of 1973](https://www.section508.gov/ "Opens in new window")
- Canada - [Canadian Human Rights Act 1985](http://laws-lois.justice.gc.ca/eng/acts/h-6/FullText.html "Opens in new window")

[back to top](#table-of-contents)