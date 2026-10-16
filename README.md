# Biel Batllori | CV project notes

I am a third-year Computer Engineering student at the University of Girona. Alongside my studies, I have experience as a waiter and in coordinating service from the kitchen. This website brings those parts of my background together with a personal project: a bot intended to generate and publish videos after receiving the type of video to create.

The page was prepared for the Multimedia and User Interfaces course. Its content is in English, and its implementation uses HTML, one CSS file and my portrait.

**Figma design:** [CV Biel Batllori](https://www.figma.com/design/UPK1KRds4TlUTJZ2zVilxD/CV-Biel-Batllori?node-id=1-2&t=xzVIfu3sy3nJvoQF-1)

**Live website:** [CV Biel Batllori](https://u6103254.github.io/CV-Biel-Batllori/)

## Project analysis: user profile

### A visitor I designed for

**Marc Riera, 31, lead developer in a small digital studio in Girona.** Marc is a fictional persona created for this analysis, not an interviewed user or a real contact.

His studio builds websites and content tools for local businesses. He is looking through student profiles for a possible placement and receives a link to my CV. He opens it on his phone, then returns to it on his laptop when preparing a shortlist.

Marc wants to know my current study level, what responsibilities I have had at work and whether I can explain a technical idea clearly. The video bot gives him a specific topic to discuss with me: taking a repeated content task and trying to automate its generation and publication. My hospitality experience also matters to him because service coordination involves communication with other people during a shared task.

His main difficulty is working out what a student has actually done when a CV contains broad skill claims. For this reason, the page names my studies, describes my service responsibilities and presents the bot through its objective. The project description does not claim a finished implementation. Marc can read those details in sequence, jump to the project from the introduction or use the email link to follow up.

## Project analysis: information architecture

I arranged the CV around the information I would want someone to remember after a first visit: my name, my current studies, my working background and the automation project I want to develop. All of this fits into one page. Keeping the sections in the same document lets a visitor connect my practical experience with my technical interests during a continuous reading session.

The opening section combines my name, photograph and third-year student status. The short introduction mentions both Computer Engineering and hospitality, so the two parts of my background are visible immediately. The link labelled “Explore my project” gives the visitor an early route to the video bot. The navigation also offers Profile, Education, Experience, Project and Contact as direct destinations.

Education starts with the degree I am currently taking at the University of Girona. Batxillerat, ESO and primary education follow in that order. Experience then groups waiter work and coordination from the kitchen under one hospitality heading. The short list underneath makes the service responsibilities easier to scan without adding employer names or dates that have not been supplied.

The project occupies its own block because it needs more explanation than an education entry. Its description identifies the input, the requested video type, and the intended output, videos published to YouTube, TikTok and Reels. Three numbered steps make that sequence visible: Define, Generate and Publish. They describe the project goal; the CV itself does not run the bot.

Skills follows the supporting information and separates service experience from the HTML and CSS practices used in this coursework. Contact closes the page with my email and telephone number. A final “Back to top” link supports another pass through the CV. On a smaller screen, the columns stack while preserving this order and the same internal navigation targets.

## Project analysis: visual design

I used the layout of a personal document as the starting point. The large name on the left and the portrait panel on the right establish the introduction before the visitor reaches the detailed entries. The photograph is the image I supplied for the project. It keeps its original proportions and is displayed inside the burgundy panel with a maximum width of 230 pixels. The image file has not been retouched or cropped.

The palette has a warm background, `#f6f3ec`, and dark main text, `#242420`. Burgundy, `#6b2d36`, appears in the portrait panel, section labels, borders and the project link. This repetition connects the different parts of the page. Supporting text uses `#64645d`, while the project area uses a slightly darker neutral background, `#e9e4da`, to give the bot description its own space.

Georgia is used for my name and the larger headings. Arial is used for the introduction, entries, lists and navigation. The contrast between these two families helps distinguish section openings from the information inside them. Body text is 16 pixels with a line height of 1.6. The name is larger on desktop and reduced on mobile so that it remains within the available width. Both font families have fallbacks and require no external download.

The main container occupies 90 percent of the available width, up to 1120 pixels. Section borders and repeated spacing separate education, experience and skills. Flexbox places the section heading beside its content on larger screens. At 800 pixels and below, those arrangements become vertical. The project steps also become a single column. These changes use the responsive approach shown in the supplied layout exercise.

The project link has a border and changes colour on hover. Ordinary internal links handle navigation, with smooth scrolling added at my request. The resulting presentation uses typography, spacing, colour and my photograph to support the CV's content.

## Smooth scrolling

The page uses `scroll-behavior: smooth` to make movement between sections gradual when following the navigation links. This property was added for the requested scrolling effect and does not appear in the supplied course examples.

## Files and viewing instructions

```text
cv-biel-batllori/
├── index.html
├── styles.css
├── README.md
└── assets/
    └── biel-batllori.png
```

Open `index.html` in a browser. Keep the stylesheet and the `assets` folder in these relative locations. There is no installation or build step. The photograph is local, and the page does not load a framework, a script or a remote font.

The contact section uses `u6103254@campus.udg.edu` as an email link and displays `+34 067676767` as plain text. Both values reproduce the supplied details. Exact study dates, school names, employers and the bot's implementation status can be added when those details are available.
