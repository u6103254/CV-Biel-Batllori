# Biel Batllori — Online CV

A static, English-language CV website for the **Multimedia and User Interfaces** course at **Universitat de Girona**. It presents Biel's studies, hospitality experience, and personal interest in automating video creation and publication.

## Files and local use

```text
cv-biel-batllori/
├── index.html
├── styles.css
├── README.md
└── assets/
    └── biel-batllori.png
```

Extract the complete folder and open `index.html` in a web browser. Keep `styles.css` beside it and preserve the `assets` folder. The website uses plain HTML and CSS; no installation, build process, JavaScript, external fonts, or internet connection is required to view the page. The portrait is the original photograph supplied by Biel, stored locally without cropping, retouching or replacing its background.

## Confirmed content

- **Name:** Biel Batllori.
- **Education:** Primary education, compulsory secondary education (ESO), upper secondary education (Batxillerat), and currently the third year of GEINF at Universitat de Girona.
- **Experience:** Work as a waiter and coordination of service from the kitchen.
- **Personal project:** A bot intended to generate and publish videos to YouTube, TikTok, and Instagram Reels after the user specifies the type of video.
- **Email:** [u6103254@campus.udg.edu](mailto:u6103254@campus.udg.edu).
- **Telephone:** +34 067676767, reproduced as supplied and displayed as plain text.

Dates, school names, employer names, proficiency levels, and a completed or deployed status for the bot have not been invented. The project is described through its objective rather than unsupported implementation claims.

## Project analysis: user profile

### User persona

**Name:** Laura Serra. **Age:** 34. **Role:** Junior talent recruiter at a small software company in Girona. **Devices:** A laptop during candidate screening and a smartphone when opening a forwarded CV. **Digital confidence:** Comfortable with websites and recruitment tools, without needing technical implementation details.

Laura reviews several student profiles in a short period. She wants to identify Biel's current studies, understand what his previous work says about teamwork and responsibility, and find one concrete technology interest that could start an interview conversation. Her main task is deciding whether to contact him for an initial discussion about a student opportunity.

Her frustrations include long introductions, unclear section labels, exaggerated skill ratings, and contact details hidden behind forms. She needs readable text, a predictable structure, a direct email link and a visible telephone number. The website therefore places identity and student status first, gives education and work experience their own sections, explains the automation idea in plain language, and ends with a visible contact section. Navigation lets her move directly to relevant information.

This is a fictional design persona based on a plausible visitor scenario. It is an analysis tool, not a claim that user interviews or recruitment research were conducted.

## Project analysis: information architecture

The website uses a single-page structure because the available CV content is concise and closely connected. A visitor can read Biel's background in one continuous sequence or use the navigation to reach a particular section. The first screen introduces his name, current student status, and interest in technology. Its “Explore my project” link provides a direct route to the most distinctive personal idea without requiring the visitor to read the full CV first.

The main navigation contains five clear labels: Profile, Education, Experience, Project, and Contact. Each label links to a section in the same document. Profile introduces Biel in a short paragraph. Education follows with the current third year of GEINF at Universitat de Girona, then completed upper secondary, compulsory secondary, and primary education in that order. This gives a recruiter the current academic context while keeping the rest of the educational path available.

Experience describes waiter work and service coordination from the kitchen. These are kept together because they belong to the same hospitality background and explain responsibility, communication, and teamwork. Project then describes the intended automation workflow: specify a video type, generate content, and publish it to YouTube, TikTok, and Instagram Reels. The text presents an objective and does not imply that an unverified product is already operational. Skills provides a compact account of relevant interests and transferable abilities after the supporting context.

Contact appears at the end, where a visitor who has finished reviewing the profile can act immediately. The email is a direct link and the telephone number is displayed as plain text, with no form fields. The footer includes “Back to top” for returning to the beginning. The page uses a main heading and descriptive section headings, paragraphs, and lists to make the reading order explicit. The anchors are `#top`, `#profile`, `#education`, `#experience`, `#project`, `#skills`, and `#contact`. The same order is preserved on narrow screens, so the navigation and content remain predictable across devices.

## Project analysis: visual design

The visual design presents the CV as a clear personal document with a restrained academic character. Its background is warm ivory (`#f6f3ec`), the main text is dark ink (`#242420`), and burgundy (`#6b2d36`) provides a recognizable accent. Muted text (`#64645d`) supports secondary information, while a soft neutral surface (`#e9e4da`) separates selected areas without introducing many competing colors. The accent connects navigation, key labels, and calls to action, helping visitors recognize interactive elements consistently.

Typography uses two familiar font families already available on typical devices. Arial gives body text and interface labels a straightforward appearance, while Georgia gives major headings a more personal editorial tone. Differences in size, weight, and spacing establish hierarchy. The name is the strongest visual element, section headings are easy to scan, and paragraphs remain modest in length. Generous line spacing and a constrained content width help visitors read the details without losing their place.

The layout is centered with a maximum width of 1120 pixels. Flexbox supports the horizontal arrangements on larger screens, while a media query at 800 pixels reorganizes the content for smaller devices. Spacing and borders group related material, following the box model and layout approaches shown in the course examples. The reading sequence stays consistent as the layout changes. The identity panel contains Biel's supplied portrait, using an HTML image with descriptive alternative text. Its width is constrained with basic CSS dimensions while its natural proportions are preserved. No cropping, retouching or external image service is used.

The design keeps decorative effects limited so that the profile, education, experience, and project receive most of the attention. Links have visual feedback and keyboard focus remains visible. The user specifically requested smooth movement between sections, so CSS smooth scrolling makes anchor navigation feel continuous. This small scrolling enhancement is identified below as an extension beyond the supplied examples. The complete page remains a static HTML and CSS document with no JavaScript, remote visual assets or font downloads.

## Relationship to the supplied theory and examples

The implementation applies the supplied course material and auxiliary examples, with one explicitly requested scrolling extension. It is original project code built from those concepts, not a verbatim copy of a class example. The colour values, spacing, wording and fictional persona are project decisions; the personal facts and portrait come from Biel. The material was used as a reference for structure and techniques; unrelated example people, images, audio, and video are not included in the CV.

| Supplied material | How it informs this website |
| --- | --- |
| `01_IntroCourse_2627.pdf` | The static personal CV assignment, implemented mainly in HTML and CSS, and the course context. |
| `02_IntroToHTML.pdf` | Document structure, headings, paragraphs, lists, hyperlinks, linking a stylesheet, and images with alternative text (pp. 57-60). |
| `02_IntroToHTML+CSS.pdf` | The relationship between HTML content and CSS presentation. |
| `03_IntroCSS.pdf` | Selectors, text styling, colors, the box model, layout, link states, and responsive rules. |
| `ç.pdf` (Hypermedia system design) | User modeling, information architecture, navigation, visual hierarchy, and visual design analysis. |
| `04_IntroJavaScript1.pdf` | Reviewed as part of the supplied material; no JavaScript is needed for this static CV. |
| `Auxiliary files for session 2 HTML-20261016.zip` | Basic HTML template, lists, and hyperlink patterns. Media and form examples were reviewed but are not required by the chosen content. |
| `Auxiliary files for session 3 CSS-20261016.zip` | External stylesheets, selectors, text and box styling, list navigation, responsive rules, and simple interaction feedback. |
| `Session 2 Complementary files-20261016.zip` | The personal-page layout example, Flexbox, positioning, and the 800-pixel responsive layout pattern. |
| `Auxiliary files for session 4 JavaScript-20261016.zip` | Reviewed; no script, interactive form, or JavaScript dependency is included. |

**Requested extension:** `scroll-behavior: smooth` implements the user's explicit request for smooth anchor navigation. This property is absent from the supplied theory and examples and is the remaining addition beyond that material.

**Review correction:** The unsupported `lang` attribute, `tel:` telephone link and `prefers-reduced-motion` query from an earlier version were removed after a detailed source review. The content remains in English, the telephone remains visible, and the user's smooth-scrolling request is preserved. Standard variations of spacing and side borders apply the taught box-model concepts rather than copying every declaration literally.

**Course policy note:** Page 41 of `01_IntroCourse_2627.pdf` limits AI use to improving spelling, grammar, and text clarity. This AI-assisted package should be treated as study/reference material; its generation does not establish permission to submit it under that rule.

## Figma and public links

- **Figma project:** [ADD FIGMA PROJECT URL]
- **GitHub repository:** Not published.
- **Public website / GitHub Pages:** Not published.

No Figma URL was identified in the supplied project material. Add the actual project link here when available. The current instruction is to prepare downloadable files only, so neither a repository nor a public website has been created. Public links remain a separate requirement of the original assignment and are not fulfilled by a local ZIP file.

## Review before submission

Confirm the personal content and contact details, add the real Figma project URL, and review the course policy above. Open `index.html` after extraction and check navigation, the project link, “Back to top,” the portrait and the email link. Keep the three root files and the `assets` folder together when copying or uploading the website in the future.
