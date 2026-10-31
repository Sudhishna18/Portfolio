# Ex01 Portfolio
## Date: 31.10.2026
## Name: Sudhishna P
## Registration Number : 212224040336

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
HTML
```
<!DOCTYPE html>
<html lang="en" class="dark scroll-smooth">
  <head>
    <meta charset="UTF-8" />
<!-- This site is hosted on Netlify. Anyone can build and deploy a site
     like this one for free: https://netlify.new/?utm_campaign=loops&utm_source=ai-legible&utm_medium=owned&utm_content=comment&utm_id=874fcf10-2865-4b85-b96b-9d0f392b9e40
     Netlify hosting facts for this site: static/SSR served via Netlify Edge. -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='24' fill='%23050505'/%3E%3Cpath d='M42 26 H26 C21 26 18 30 18 35.5 C18 41 22 44 28 46 L34 48 C40 50 44 53.5 44 59.5 C44 65.5 39 69 33 69 H18' stroke='%23FFFFFF' stroke-width='7' stroke-linecap='round' stroke-linejoin='round' fill='none'/%3E%3Cpath d='M56 26 V69' stroke='%23D7FF00' stroke-width='7' stroke-linecap='round' fill='none'/%3E%3Cpath d='M56 26 H72 C79.5 26 83 30 83 37.5 C83 45 79.5 48 72 48 H56' stroke='%23D7FF00' stroke-width='7' stroke-linecap='round' stroke-linejoin='round' fill='none'/%3E%3Ccircle cx='42' cy='26' r='3.5' fill='%23D7FF00'/%3E%3Ccircle cx='18' cy='69' r='3.5' fill='%23D7FF00'/%3E%3Ccircle cx='56' cy='69' r='4' fill='%23FFFFFF'/%3E%3C/svg%3E" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="theme-color" content="#050505" />
    
    <!-- Primary Meta Tags -->
    <title>Sudhishna Premanand | Computer Science Student & AI Engineer</title>
    <meta name="title" content="Sudhishna Premanand | Computer Science Student & AI Engineer" />
    <meta name="description" content="Portfolio of Sudhishna Premanand — Computer Science Engineering student at Saveetha Engineering College exploring AI, Machine Learning, software development, public speaking, and technology-driven problem solving." />
    <meta name="author" content="Sudhishna Premanand" />

    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://sudhishna-premanand-portfolio.netlify.app" />
    <meta property="og:title" content="Sudhishna Premanand | Computer Science Student & AI Engineer" />
    <meta property="og:description" content="Computer Science student at Saveetha Engineering College leveraging technology to create practical and impactful AI solutions alongside communication and leadership." />
    <meta property="og:image" content="/assets/sudhishna.jpg" />

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image" />
    <meta property="twitter:title" content="Sudhishna Premanand | Computer Science Student & AI Engineer" />
    <meta property="twitter:description" content="Computer Science student at Saveetha Engineering College exploring AI, Machine Learning, public speaking, and technology leadership." />
    <meta property="twitter:image" content="/assets/sudhishna.jpg" />

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500;600&family=Outfit:wght@400;500;600;700;800;900&family=Sora:wght@400;500;600;700;800&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script type="module" crossorigin src="/assets/index-9GMAs2KV.js"></script>
    <link rel="stylesheet" crossorigin href="/assets/index-D_tzj5_I.css">
  </head>
  <body class="bg-[#050505] text-white font-sans selection:bg-[#D7FF00]/30 selection:text-[#D7FF00] antialiased overflow-x-hidden">
    <div id="root"></div>
  </body>
</html>
``` 
CSS
```
/*! tailwindcss v4.3.3 | MIT License | https://tailwindcss.com */
@layer properties {
    @supports (((-webkit-hyphens: none)) and (not (margin-trim:inline))) or ((-moz-orient:inline) and (not (color:rgb(from red r g b)))) {
        *,:before,:after,::backdrop {
            --tw-translate-x:0;
            --tw-translate-y: 0;
            --tw-translate-z: 0;
            --tw-scale-x: 1;
            --tw-scale-y: 1;
            --tw-scale-z: 1;
            --tw-rotate-x: initial;
            --tw-rotate-y: initial;
            --tw-rotate-z: initial;
            --tw-skew-x: initial;
            --tw-skew-y: initial;
            --tw-space-y-reverse: 0;
            --tw-border-style: solid;
            --tw-gradient-position: initial;
            --tw-gradient-from: #0000;
            --tw-gradient-via: #0000;
            --tw-gradient-to: #0000;
            --tw-gradient-stops: initial;
            --tw-gradient-via-stops: initial;
            --tw-gradient-from-position: 0%;
            --tw-gradient-via-position: 50%;
            --tw-gradient-to-position: 100%;
            --tw-leading: initial;
            --tw-font-weight: initial;
            --tw-tracking: initial;
            --tw-shadow: 0 0 #0000;
            --tw-shadow-color: initial;
            --tw-shadow-alpha: 100%;
            --tw-inset-shadow: 0 0 #0000;
            --tw-inset-shadow-color: initial;
            --tw-inset-shadow-alpha: 100%;
            --tw-ring-color: initial;
            --tw-ring-shadow: 0 0 #0000;
            --tw-inset-ring-color: initial;
            --tw-inset-ring-shadow: 0 0 #0000;
            --tw-ring-inset: initial;
            --tw-ring-offset-width: 0px;
            --tw-ring-offset-color: #fff;
            --tw-ring-offset-shadow: 0 0 #0000;
            --tw-blur: initial;
            --tw-brightness: initial;
            --tw-contrast: initial;
            --tw-grayscale: initial;
            --tw-hue-rotate: initial;
            --tw-invert: initial;
            --tw-opacity: initial;
            --tw-saturate: initial;
            --tw-sepia: initial;
            --tw-drop-shadow: initial;
            --tw-drop-shadow-color: initial;
            --tw-drop-shadow-alpha: 100%;
            --tw-drop-shadow-size: initial;
            --tw-backdrop-blur: initial;
            --tw-backdrop-brightness: initial;
            --tw-backdrop-contrast: initial;
            --tw-backdrop-grayscale: initial;
            --tw-backdrop-hue-rotate: initial;
            --tw-backdrop-invert: initial;
            --tw-backdrop-opacity: initial;
            --tw-backdrop-saturate: initial;
            --tw-backdrop-sepia: initial;
            --tw-duration: initial;
            --tw-ease: initial
        }
    }
}

@layer theme {
    :root,:host {
        --font-sans: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", "Noto Sans", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
        --font-mono: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
        --color-red-500: oklch(63.7% .237 25.331);
        --color-yellow-500: oklch(79.5% .184 86.047);
        --color-green-500: oklch(72.3% .219 149.579);
        --color-emerald-400: oklch(76.5% .177 163.223);
        --color-zinc-200: oklch(92% .004 286.32);
        --color-zinc-300: oklch(87.1% .006 286.286);
        --color-zinc-400: oklch(70.5% .015 286.067);
        --color-zinc-500: oklch(55.2% .016 285.938);
        --color-zinc-600: oklch(44.2% .017 285.786);
        --color-zinc-700: oklch(37% .013 285.805);
        --color-zinc-800: oklch(27.4% .006 286.033);
        --color-zinc-900: oklch(21% .006 285.885);
        --color-white: #fff;
        --spacing: .25rem;
        --container-md: 28rem;
        --container-lg: 32rem;
        --container-xl: 36rem;
        --container-2xl: 42rem;
        --container-3xl: 48rem;
        --container-5xl: 64rem;
        --container-7xl: 80rem;
        --text-xs: .75rem;
        --text-xs--line-height: calc(1 / .75);
        --text-sm: .875rem;
        --text-sm--line-height: calc(1.25 / .875);
        --text-base: 1rem;
        --text-base--line-height: 1.5 ;
        --text-lg: 1.125rem;
        --text-lg--line-height: calc(1.75 / 1.125);
        --text-xl: 1.25rem;
        --text-xl--line-height: calc(1.75 / 1.25);
        --text-2xl: 1.5rem;
        --text-2xl--line-height: calc(2 / 1.5);
        --text-3xl: 1.875rem;
        --text-3xl--line-height: 1.2 ;
        --text-4xl: 2.25rem;
        --text-4xl--line-height: calc(2.5 / 2.25);
        --text-5xl: 3rem;
        --text-5xl--line-height: 1;
        --text-6xl: 3.75rem;
        --text-6xl--line-height: 1;
        --text-7xl: 4.5rem;
        --text-7xl--line-height: 1;
        --font-weight-medium: 500;
        --font-weight-semibold: 600;
        --font-weight-bold: 700;
        --font-weight-extrabold: 800;
        --font-weight-black: 900;
        --tracking-tight: -.025em;
        --tracking-wider: .05em;
        --leading-tight: 1.25;
        --leading-snug: 1.375;
        --leading-relaxed: 1.625;
        --radius-xl: .75rem;
        --radius-2xl: 1rem;
        --radius-3xl: 1.5rem;
        --ease-out: cubic-bezier(0, 0, .2, 1);
        --animate-ping: ping 1s cubic-bezier(0, 0, .2, 1) infinite;
        --animate-pulse: pulse 2s cubic-bezier(.4, 0, .6, 1) infinite;
        --blur-md: 12px;
        --blur-xl: 24px;
        --blur-2xl: 40px;
        --blur-3xl: 64px;
        --default-transition-duration: .15s;
        --default-transition-timing-function: cubic-bezier(.4, 0, .2, 1);
        --default-font-family: var(--font-sans);
        --default-mono-font-family: var(--font-mono)
    }
}

@layer base {
    *,:after,:before,::backdrop {
        box-sizing: border-box;
        border: 0 solid;
        margin: 0;
        padding: 0
    }

    ::file-selector-button {
        box-sizing: border-box;
        border: 0 solid;
        margin: 0;
        padding: 0
    }

    html,: host {
        -webkit-text-size-adjust:100%;
        -moz-tab-size: 4;
        tab-size: 4;
        line-height: 1.5;
        font-family: var(--default-font-family,-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", "Noto Sans", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji");
        font-feature-settings: var(--default-font-feature-settings,normal);
        font-variation-settings: var(--default-font-variation-settings,normal);
        -webkit-tap-highlight-color: transparent
    }

    hr {
        height: 0;
        color: inherit;
        border-top-width: 1px
    }

    abbr: where([title]) {
        -webkit-text-decoration:underline dotted;
        text-decoration: underline dotted
    }

    h1,h2,h3,h4,h5,h6 {
        font-size: inherit;
        font-weight: inherit
    }

    a {
        color: inherit;
        -webkit-text-decoration: inherit;
        text-decoration: inherit
    }

    b,strong {
        font-weight: bolder
    }

    code,kbd,samp,pre {
        font-family: var(--default-mono-font-family,ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace);
        font-feature-settings: var(--default-mono-font-feature-settings,normal);
        font-variation-settings: var(--default-mono-font-variation-settings,normal);
        font-size: 1em
    }

    small {
        font-size: 80%
    }

    sub,sup {
        vertical-align: baseline;
        font-size: 75%;
        line-height: 0;
        position: relative
    }

    sub {
        bottom: -.25em
    }

    sup {
        top: -.5em
    }

    table {
        text-indent: 0;
        border-color: inherit;
        border-collapse: collapse
    }

    :-moz-focusring:where(:not(iframe)) {
        outline: auto
    }

    progress {
        vertical-align: baseline
    }

    summary {
        display: list-item
    }

    ol,ul,menu {
        list-style: none
    }

    img,svg,video,canvas,audio,iframe,embed,object {
        vertical-align: middle;
        display: block
    }

    img,video {
        max-width: 100%;
        height: auto
    }

    button,input,select,optgroup,textarea {
        font: inherit;
        font-feature-settings: inherit;
        font-variation-settings: inherit;
        letter-spacing: inherit;
        color: inherit;
        opacity: 1;
        background-color: #0000;
        border-radius: 0
    }

    ::file-selector-button {
        font: inherit;
        font-feature-settings: inherit;
        font-variation-settings: inherit;
        letter-spacing: inherit;
        color: inherit;
        opacity: 1;
        background-color: #0000;
        border-radius: 0
    }

    :where(select: is([multiple],[size])) optgroup {
        font-weight:bolder
    }

    :where(select: is([multiple],[size])) optgroup option {
        padding-inline-start:20px
    }

    ::file-selector-button {
        margin-inline-end:4px}

    ::placeholder {
        opacity: 1
    }

    @supports (not ((-webkit-appearance: -apple-pay-button))) or (contain-intrinsic-size:1px) {
        ::placeholder {
            color:currentColor
        }

        @supports (color: color-mix(in lab,red,red)) {
            ::placeholder {
                color:color-mix(in oklab,currentcolor 50%,transparent)
            }
        }
    }

    textarea {
        resize: vertical
    }

    ::-webkit-search-decoration {
        -webkit-appearance: none
    }

    ::-webkit-date-and-time-value {
        min-height: 1lh;
        text-align: inherit
    }

    ::-webkit-datetime-edit {
        display: inline-flex
    }

    ::-webkit-datetime-edit-fields-wrapper {
        padding: 0
    }

    ::-webkit-datetime-edit {
        padding-block:0}

    ::-webkit-datetime-edit-year-field {
        padding-block:0}

    ::-webkit-datetime-edit-month-field {
        padding-block:0}

    ::-webkit-datetime-edit-day-field {
        padding-block:0}

    ::-webkit-datetime-edit-hour-field {
        padding-block:0}

    ::-webkit-datetime-edit-minute-field {
        padding-block:0}

    ::-webkit-datetime-edit-second-field {
        padding-block:0}

    ::-webkit-datetime-edit-millisecond-field {
        padding-block:0}

    ::-webkit-datetime-edit-meridiem-field {
        padding-block:0}

    ::-webkit-calendar-picker-indicator {
        line-height: 1
    }

    :-moz-ui-invalid {
        box-shadow: none
    }

    button,input: where([type=button],[type=reset],[type=submit]) {
        -webkit-appearance:button;
        -moz-appearance: button;
        appearance: button
    }

    ::file-selector-button {
        -webkit-appearance: button;
        -moz-appearance: button;
        appearance: button
    }

    ::-webkit-inner-spin-button {
        height: auto
    }

    ::-webkit-outer-spin-button {
        height: auto
    }

    [hidden]: where(:not([hidden=until-found])) {
        display:none!important
    }

    :root {
        --font-sans: "Inter", sans-serif;
        --font-grotesk: "Space Grotesk", sans-serif;
        --font-outfit: "Outfit", sans-serif;
        --font-sora: "Sora", sans-serif;
        --font-mono: "JetBrains Mono", monospace;
        --bg-primary: #050505;
        --bg-secondary: #080808;
        --bg-card: #0d0d0d;
        --bg-card-elevated: #101010;
        --accent-lime: #d7ff00;
        --accent-lime-glow: #d7ff0066;
        --border-lime: #d7ff001f
    }

    body {
        font-family: var(--font-sans);
        color: #fff;
        background-color: #050505
    }

    h1,h2,h3,h4,h5,h6 {
        font-family: var(--font-outfit)
    }
}

@layer components;@layer utilities {
    .pointer-events-none {
        pointer-events: none
    }

    .absolute {
        position: absolute
    }

    .fixed {
        position: fixed
    }

    .relative {
        position: relative
    }

    .-inset-1\.5 {
        inset: calc(var(--spacing) * -1.5)
    }

    .inset-0 {
        top: 0;
        right: 0;
        bottom: 0;
        left: 0
    }

    .-top-24 {
        top: calc(var(--spacing) * -24)
    }

    .top-0 {
        top: 0
    }

    .top-1\/2 {
        top: 50%
    }

    .top-1\/3 {
        top: 33.3333%
    }

    .top-1\/4 {
        top: 25%
    }

    .top-2 {
        top: calc(var(--spacing) * 2)
    }

    .top-4 {
        top: calc(var(--spacing) * 4)
    }

    .top-6 {
        top: calc(var(--spacing) * 6)
    }

    .-right-24 {
        right: calc(var(--spacing) * -24)
    }

    .right-0 {
        right: 0
    }

    .right-4 {
        right: calc(var(--spacing) * 4)
    }

    .right-6 {
        right: calc(var(--spacing) * 6)
    }

    .bottom-4 {
        bottom: calc(var(--spacing) * 4)
    }

    .-left-\[32px\] {
        left: -32px
    }

    .left-0 {
        left: 0
    }

    .left-1\/2 {
        left: 50%
    }

    .left-4 {
        left: calc(var(--spacing) * 4)
    }

    .z-0 {
        z-index: 0
    }

    .z-10 {
        z-index: 10
    }

    .z-20 {
        z-index: 20
    }

    .z-30 {
        z-index: 30
    }

    .z-40 {
        z-index: 40
    }

    .z-50 {
        z-index: 50
    }

    .mx-auto {
        margin-inline:auto}

    .my-auto {
        margin-block:auto}

    .mt-0\.5 {
        margin-top: calc(var(--spacing) * .5)
    }

    .mt-1 {
        margin-top: var(--spacing)
    }

    .mt-2 {
        margin-top: calc(var(--spacing) * 2)
    }

    .mt-3 {
        margin-top: calc(var(--spacing) * 3)
    }

    .mt-6 {
        margin-top: calc(var(--spacing) * 6)
    }

    .mt-8 {
        margin-top: calc(var(--spacing) * 8)
    }

    .mt-16 {
        margin-top: calc(var(--spacing) * 16)
    }

    .mb-1 {
        margin-bottom: var(--spacing)
    }

    .mb-1\.5 {
        margin-bottom: calc(var(--spacing) * 1.5)
    }

    .mb-2 {
        margin-bottom: calc(var(--spacing) * 2)
    }

    .mb-3 {
        margin-bottom: calc(var(--spacing) * 3)
    }

    .mb-4 {
        margin-bottom: calc(var(--spacing) * 4)
    }

    .mb-6 {
        margin-bottom: calc(var(--spacing) * 6)
    }

    .mb-8 {
        margin-bottom: calc(var(--spacing) * 8)
    }

    .mb-10 {
        margin-bottom: calc(var(--spacing) * 10)
    }

    .mb-16 {
        margin-bottom: calc(var(--spacing) * 16)
    }

    .ml-0 {
        margin-left: 0
    }

    .ml-2 {
        margin-left: calc(var(--spacing) * 2)
    }

    .ml-4 {
        margin-left: calc(var(--spacing) * 4)
    }

    .block {
        display: block
    }

    .flex {
        display: flex
    }

    .grid {
        display: grid
    }

    .hidden {
        display: none
    }

    .inline-block {
        display: inline-block
    }

    .inline-flex {
        display: inline-flex
    }

    .aspect-\[4\/5\] {
        aspect-ratio: 4/5
    }

    .h-1\.5 {
        height: calc(var(--spacing) * 1.5)
    }

    .h-2 {
        height: calc(var(--spacing) * 2)
    }

    .h-2\.5 {
        height: calc(var(--spacing) * 2.5)
    }

    .h-3 {
        height: calc(var(--spacing) * 3)
    }

    .h-3\.5 {
        height: calc(var(--spacing) * 3.5)
    }

    .h-4 {
        height: calc(var(--spacing) * 4)
    }

    .h-6 {
        height: calc(var(--spacing) * 6)
    }

    .h-8 {
        height: calc(var(--spacing) * 8)
    }

    .h-9 {
        height: calc(var(--spacing) * 9)
    }

    .h-10 {
        height: calc(var(--spacing) * 10)
    }

    .h-12 {
        height: calc(var(--spacing) * 12)
    }

    .h-14 {
        height: calc(var(--spacing) * 14)
    }

    .h-24 {
        height: calc(var(--spacing) * 24)
    }

    .h-32 {
        height: calc(var(--spacing) * 32)
    }

    .h-48 {
        height: calc(var(--spacing) * 48)
    }

    .h-72 {
        height: calc(var(--spacing) * 72)
    }

    .h-80 {
        height: calc(var(--spacing) * 80)
    }

    .h-96 {
        height: calc(var(--spacing) * 96)
    }

    .h-\[380px\] {
        height: 380px
    }

    .h-\[600px\] {
        height: 600px
    }

    .h-\[650px\] {
        height: 650px
    }

    .h-\[700px\] {
        height: 700px
    }

    .h-full {
        height: 100%
    }

    .min-h-\[220px\] {
        min-height: 220px
    }

    .min-h-\[420px\] {
        min-height: 420px
    }

    .min-h-screen {
        min-height: 100vh
    }

    .w-1 {
        width: var(--spacing)
    }

    .w-1\.5 {
        width: calc(var(--spacing) * 1.5)
    }

    .w-1\/2 {
        width: 50%
    }

    .w-2 {
        width: calc(var(--spacing) * 2)
    }

    .w-2\.5 {
        width: calc(var(--spacing) * 2.5)
    }

    .w-3 {
        width: calc(var(--spacing) * 3)
    }

    .w-3\.5 {
        width: calc(var(--spacing) * 3.5)
    }

    .w-4 {
        width: calc(var(--spacing) * 4)
    }

    .w-5 {
        width: calc(var(--spacing) * 5)
    }

    .w-6 {
        width: calc(var(--spacing) * 6)
    }

    .w-10 {
        width: calc(var(--spacing) * 10)
    }

    .w-12 {
        width: calc(var(--spacing) * 12)
    }

    .w-14 {
        width: calc(var(--spacing) * 14)
    }

    .w-24 {
        width: calc(var(--spacing) * 24)
    }

    .w-32 {
        width: calc(var(--spacing) * 32)
    }

    .w-48 {
        width: calc(var(--spacing) * 48)
    }

    .w-72 {
        width: calc(var(--spacing) * 72)
    }

    .w-96 {
        width: calc(var(--spacing) * 96)
    }

    .w-\[600px\] {
        width: 600px
    }

    .w-\[650px\] {
        width: 650px
    }

    .w-\[700px\] {
        width: 700px
    }

    .w-fit {
        width: fit-content
    }

    .w-full {
        width: 100%
    }

    .w-px {
        width: 1px
    }

    .max-w-2xl {
        max-width: var(--container-2xl)
    }

    .max-w-3xl {
        max-width: var(--container-3xl)
    }

    .max-w-5xl {
        max-width: var(--container-5xl)
    }

    .max-w-7xl {
        max-width: var(--container-7xl)
    }

    .max-w-lg {
        max-width: var(--container-lg)
    }

    .max-w-md {
        max-width: var(--container-md)
    }

    .max-w-xl {
        max-width: var(--container-xl)
    }

    .shrink-0 {
        flex-shrink: 0
    }

    .-translate-x-1\/2 {
        --tw-translate-x: -50% ;
        translate: var(--tw-translate-x) var(--tw-translate-y)
    }

    .-translate-y-1\/2 {
        --tw-translate-y: -50% ;
        translate: var(--tw-translate-x) var(--tw-translate-y)
    }

    .scale-110 {
        --tw-scale-x: 110%;
        --tw-scale-y: 110%;
        --tw-scale-z: 110%;
        scale: var(--tw-scale-x) var(--tw-scale-y)
    }

    .skew-x-12 {
        --tw-skew-x: skewX(12deg);
        transform: var(--tw-rotate-x,) var(--tw-rotate-y,) var(--tw-rotate-z,) var(--tw-skew-x,) var(--tw-skew-y,)
    }

    .animate-ping {
        animation: var(--animate-ping)
    }

    .animate-pulse {
        animation: var(--animate-pulse)
    }

    .cursor-default {
        cursor: default
    }

    .cursor-grab {
        cursor: grab
    }

    .cursor-pointer {
        cursor: pointer
    }

    .resize {
        resize: both
    }

    .resize-none {
        resize: none
    }

    .grid-cols-1 {
        grid-template-columns: repeat(1,minmax(0,1fr))
    }

    .grid-cols-2 {
        grid-template-columns: repeat(2,minmax(0,1fr))
    }

    .flex-col {
        flex-direction: column
    }

    .flex-wrap {
        flex-wrap: wrap
    }

    .items-baseline {
        align-items: baseline
    }

    .items-center {
        align-items: center
    }

    .items-end {
        align-items: flex-end
    }

    .items-start {
        align-items: flex-start
    }

    .justify-between {
        justify-content: space-between
    }

    .justify-center {
        justify-content: center
    }

    .gap-0\.5 {
        gap: calc(var(--spacing) * .5)
    }

    .gap-1 {
        gap: var(--spacing)
    }

    .gap-1\.5 {
        gap: calc(var(--spacing) * 1.5)
    }

    .gap-2 {
        gap: calc(var(--spacing) * 2)
    }

    .gap-2\.5 {
        gap: calc(var(--spacing) * 2.5)
    }

    .gap-3 {
        gap: calc(var(--spacing) * 3)
    }

    .gap-4 {
        gap: calc(var(--spacing) * 4)
    }

    .gap-6 {
        gap: calc(var(--spacing) * 6)
    }

    .gap-8 {
        gap: calc(var(--spacing) * 8)
    }

    .gap-10 {
        gap: calc(var(--spacing) * 10)
    }

    .gap-12 {
        gap: calc(var(--spacing) * 12)
    }

    :where(.space-y-12>:not(:last-child)) {
        --tw-space-y-reverse: 0;
        margin-block-start:calc(calc(var(--spacing) * 12) * var(--tw-space-y-reverse));margin-block-end: calc(calc(var(--spacing) * 12) * calc(1 - var(--tw-space-y-reverse)))
    }

    .overflow-hidden {
        overflow: hidden
    }

    .overflow-x-hidden {
        overflow-x: hidden
    }

    .scroll-smooth {
        scroll-behavior: smooth
    }

    .rounded-2xl {
        border-radius: var(--radius-2xl)
    }

    .rounded-3xl {
        border-radius: var(--radius-3xl)
    }

    .rounded-full {
        border-radius: 3.40282e38px
    }

    .rounded-xl {
        border-radius: var(--radius-xl)
    }

    .border {
        border-style: var(--tw-border-style);
        border-width: 1px
    }

    .border-2 {
        border-style: var(--tw-border-style);
        border-width: 2px
    }

    .border-t {
        border-top-style: var(--tw-border-style);
        border-top-width: 1px
    }

    .border-t-2 {
        border-top-style: var(--tw-border-style);
        border-top-width: 2px
    }

    .border-r-2 {
        border-right-style: var(--tw-border-style);
        border-right-width: 2px
    }

    .border-b {
        border-bottom-style: var(--tw-border-style);
        border-bottom-width: 1px
    }

    .border-b-2 {
        border-bottom-style: var(--tw-border-style);
        border-bottom-width: 2px
    }

    .border-l-2 {
        border-left-style: var(--tw-border-style);
        border-left-width: 2px
    }

    .border-\[\#D7FF00\] {
        border-color: #d7ff00
    }

    .border-\[\#D7FF00\]\/20 {
        border-color: #d7ff0033
    }

    .border-\[\#D7FF00\]\/25 {
        border-color: #d7ff0040
    }

    .border-\[\#D7FF00\]\/30 {
        border-color: #d7ff004d
    }

    .border-\[\#D7FF00\]\/40 {
        border-color: #d7ff0066
    }

    .border-\[\#D7FF00\]\/60 {
        border-color: #d7ff0099
    }

    .border-zinc-700\/80 {
        border-color: #3f3f46cc
    }

    @supports (color: color-mix(in lab,red,red)) {
        .border-zinc-700\/80 {
            border-color:color-mix(in oklab,var(--color-zinc-700) 80%,transparent)
        }
    }

    .border-zinc-800 {
        border-color: var(--color-zinc-800)
    }

    .border-zinc-800\/60 {
        border-color: #27272a99
    }

    @supports (color: color-mix(in lab,red,red)) {
        .border-zinc-800\/60 {
            border-color:color-mix(in oklab,var(--color-zinc-800) 60%,transparent)
        }
    }

    .border-zinc-800\/80 {
        border-color: #27272acc
    }

    @supports (color: color-mix(in lab,red,red)) {
        .border-zinc-800\/80 {
            border-color:color-mix(in oklab,var(--color-zinc-800) 80%,transparent)
        }
    }

    .border-zinc-900 {
        border-color: var(--color-zinc-900)
    }

    .bg-\[\#0D0D0D\] {
        background-color: #0d0d0d
    }

    .bg-\[\#0D0D0D\]\/60 {
        background-color: #0d0d0d99
    }

    .bg-\[\#050505\] {
        background-color: #050505
    }

    .bg-\[\#050505\]\/85 {
        background-color: #050505d9
    }

    .bg-\[\#050505\]\/90 {
        background-color: #050505e6
    }

    .bg-\[\#050505\]\/95 {
        background-color: #050505f2
    }

    .bg-\[\#080808\] {
        background-color: #080808
    }

    .bg-\[\#080808\]\/90 {
        background-color: #080808e6
    }

    .bg-\[\#D7FF00\] {
        background-color: #d7ff00
    }

    .bg-\[\#D7FF00\]\/5 {
        background-color: #d7ff000d
    }

    .bg-\[\#D7FF00\]\/10 {
        background-color: #d7ff001a
    }

    .bg-green-500\/80 {
        background-color: #00c758cc
    }

    @supports (color: color-mix(in lab,red,red)) {
        .bg-green-500\/80 {
            background-color:color-mix(in oklab,var(--color-green-500) 80%,transparent)
        }
    }

    .bg-red-500\/80 {
        background-color: #fb2c36cc
    }

    @supports (color: color-mix(in lab,red,red)) {
        .bg-red-500\/80 {
            background-color:color-mix(in oklab,var(--color-red-500) 80%,transparent)
        }
    }

    .bg-white {
        background-color: var(--color-white)
    }

    .bg-yellow-500\/80 {
        background-color: #edb200cc
    }

    @supports (color: color-mix(in lab,red,red)) {
        .bg-yellow-500\/80 {
            background-color:color-mix(in oklab,var(--color-yellow-500) 80%,transparent)
        }
    }

    .bg-zinc-700 {
        background-color: var(--color-zinc-700)
    }

    .bg-zinc-800 {
        background-color: var(--color-zinc-800)
    }

    .bg-gradient-to-r {
        --tw-gradient-position: to right in oklab;
        background-image: linear-gradient(var(--tw-gradient-stops))
    }

    .bg-gradient-to-t {
        --tw-gradient-position: to top in oklab;
        background-image: linear-gradient(var(--tw-gradient-stops))
    }

    .bg-\[radial-gradient\(circle\,_rgba\(215\,255\,0\,0\.08\)_0\%\,_transparent_70\%\)\] {
        background-image: radial-gradient(circle,#d7ff0014,#0000 70%)
    }

    .bg-\[radial-gradient\(circle_at_center\,_rgba\(215\,255\,0\,0\.06\)_0\%\,_transparent_70\%\)\] {
        background-image: radial-gradient(circle,#d7ff000f,#0000 70%)
    }

    .from-\[\#050505\] {
        --tw-gradient-from: #050505;
        --tw-gradient-stops: var(--tw-gradient-via-stops,var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position))
    }

    .from-\[\#D7FF00\]\/40 {
        --tw-gradient-from: oklab(93.8086% -.113731 .192904/.4);
        --tw-gradient-stops: var(--tw-gradient-via-stops,var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position))
    }

    .from-transparent {
        --tw-gradient-from: transparent;
        --tw-gradient-stops: var(--tw-gradient-via-stops,var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position))
    }

    .via-\[\#050505\]\/20 {
        --tw-gradient-via: oklab(11.4918% 7.45058e-9 7.45058e-9/.2);
        --tw-gradient-via-stops: var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-via) var(--tw-gradient-via-position), var(--tw-gradient-to) var(--tw-gradient-to-position);
        --tw-gradient-stops: var(--tw-gradient-via-stops)
    }

    .via-\[\#D7FF00\]\/25 {
        --tw-gradient-via: oklab(93.8086% -.113731 .192904/.25);
        --tw-gradient-via-stops: var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-via) var(--tw-gradient-via-position), var(--tw-gradient-to) var(--tw-gradient-to-position);
        --tw-gradient-stops: var(--tw-gradient-via-stops)
    }

    .via-white\/20 {
        --tw-gradient-via: #fff3
    }

    @supports (color: color-mix(in lab,red,red)) {
        .via-white\/20 {
            --tw-gradient-via:color-mix(in oklab, var(--color-white) 20%, transparent)
        }
    }

    .via-white\/20 {
        --tw-gradient-via-stops: var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-via) var(--tw-gradient-via-position), var(--tw-gradient-to) var(--tw-gradient-to-position);
        --tw-gradient-stops: var(--tw-gradient-via-stops)
    }

    .to-\[\#D7FF00\]\/30 {
        --tw-gradient-to: oklab(93.8086% -.113731 .192904/.3);
        --tw-gradient-stops: var(--tw-gradient-via-stops,var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position))
    }

    .to-transparent {
        --tw-gradient-to: transparent;
        --tw-gradient-stops: var(--tw-gradient-via-stops,var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position))
    }

    .object-cover {
        object-fit: cover
    }

    .object-center {
        object-position: center
    }

    .p-0\.5 {
        padding: calc(var(--spacing) * .5)
    }

    .p-1 {
        padding: var(--spacing)
    }

    .p-1\.5 {
        padding: calc(var(--spacing) * 1.5)
    }

    .p-2 {
        padding: calc(var(--spacing) * 2)
    }

    .p-2\.5 {
        padding: calc(var(--spacing) * 2.5)
    }

    .p-3 {
        padding: calc(var(--spacing) * 3)
    }

    .p-3\.5 {
        padding: calc(var(--spacing) * 3.5)
    }

    .p-4 {
        padding: calc(var(--spacing) * 4)
    }

    .p-5 {
        padding: calc(var(--spacing) * 5)
    }

    .p-6 {
        padding: calc(var(--spacing) * 6)
    }

    .p-8 {
        padding: calc(var(--spacing) * 8)
    }

    .px-2 {
        padding-inline:calc(var(--spacing) * 2)}

    .px-2\.5 {
        padding-inline: calc(var(--spacing) * 2.5)
    }

    .px-3 {
        padding-inline:calc(var(--spacing) * 3)}

    .px-3\.5 {
        padding-inline: calc(var(--spacing) * 3.5)
    }

    .px-4 {
        padding-inline:calc(var(--spacing) * 4)}

    .px-5 {
        padding-inline: calc(var(--spacing) * 5)
    }

    .px-6 {
        padding-inline:calc(var(--spacing) * 6)}

    .px-7 {
        padding-inline: calc(var(--spacing) * 7)
    }

    .py-0\.5 {
        padding-block: calc(var(--spacing) * .5)
    }

    .py-1 {
        padding-block:var(--spacing)}

    .py-1\.5 {
        padding-block: calc(var(--spacing) * 1.5)
    }

    .py-2 {
        padding-block:calc(var(--spacing) * 2)}

    .py-2\.5 {
        padding-block: calc(var(--spacing) * 2.5)
    }

    .py-3 {
        padding-block:calc(var(--spacing) * 3)}

    .py-3\.5 {
        padding-block: calc(var(--spacing) * 3.5)
    }

    .py-4 {
        padding-block:calc(var(--spacing) * 4)}

    .py-12 {
        padding-block: calc(var(--spacing) * 12)
    }

    .py-24 {
        padding-block:calc(var(--spacing) * 24)}

    .pt-2 {
        padding-top: calc(var(--spacing) * 2)
    }

    .pt-4 {
        padding-top: calc(var(--spacing) * 4)
    }

    .pt-5 {
        padding-top: calc(var(--spacing) * 5)
    }

    .pt-6 {
        padding-top: calc(var(--spacing) * 6)
    }

    .pt-24 {
        padding-top: calc(var(--spacing) * 24)
    }

    .pt-28 {
        padding-top: calc(var(--spacing) * 28)
    }

    .pb-3 {
        padding-bottom: calc(var(--spacing) * 3)
    }

    .pb-8 {
        padding-bottom: calc(var(--spacing) * 8)
    }

    .pb-16 {
        padding-bottom: calc(var(--spacing) * 16)
    }

    .pl-6 {
        padding-left: calc(var(--spacing) * 6)
    }

    .text-center {
        text-align: center
    }

    .text-left {
        text-align: left
    }

    .font-mono {
        font-family: var(--font-mono)
    }

    .font-sans {
        font-family: var(--font-sans)
    }

    .text-2xl {
        font-size: var(--text-2xl);
        line-height: var(--tw-leading,var(--text-2xl--line-height))
    }

    .text-3xl {
        font-size: var(--text-3xl);
        line-height: var(--tw-leading,var(--text-3xl--line-height))
    }

    .text-4xl {
        font-size: var(--text-4xl);
        line-height: var(--tw-leading,var(--text-4xl--line-height))
    }

    .text-base {
        font-size: var(--text-base);
        line-height: var(--tw-leading,var(--text-base--line-height))
    }

    .text-lg {
        font-size: var(--text-lg);
        line-height: var(--tw-leading,var(--text-lg--line-height))
    }

    .text-sm {
        font-size: var(--text-sm);
        line-height: var(--tw-leading,var(--text-sm--line-height))
    }

    .text-xl {
        font-size: var(--text-xl);
        line-height: var(--tw-leading,var(--text-xl--line-height))
    }

    .text-xs {
        font-size: var(--text-xs);
        line-height: var(--tw-leading,var(--text-xs--line-height))
    }

    .text-\[9px\] {
        font-size: 9px
    }

    .text-\[10px\] {
        font-size: 10px
    }

    .text-\[11px\] {
        font-size: 11px
    }

    .leading-\[1\.08\] {
        --tw-leading: 1.08;
        line-height: 1.08
    }

    .leading-relaxed {
        --tw-leading: var(--leading-relaxed);
        line-height: var(--leading-relaxed)
    }

    .leading-snug {
        --tw-leading: var(--leading-snug);
        line-height: var(--leading-snug)
    }

    .leading-tight {
        --tw-leading: var(--leading-tight);
        line-height: var(--leading-tight)
    }

    .font-black {
        --tw-font-weight: var(--font-weight-black);
        font-weight: var(--font-weight-black)
    }

    .font-bold {
        --tw-font-weight: var(--font-weight-bold);
        font-weight: var(--font-weight-bold)
    }

    .font-extrabold {
        --tw-font-weight: var(--font-weight-extrabold);
        font-weight: var(--font-weight-extrabold)
    }

    .font-medium {
        --tw-font-weight: var(--font-weight-medium);
        font-weight: var(--font-weight-medium)
    }

    .font-semibold {
        --tw-font-weight: var(--font-weight-semibold);
        font-weight: var(--font-weight-semibold)
    }

    .tracking-\[0\.2em\] {
        --tw-tracking: .2em;
        letter-spacing: .2em
    }

    .tracking-\[0\.3em\] {
        --tw-tracking: .3em;
        letter-spacing: .3em
    }

    .tracking-\[0\.25em\] {
        --tw-tracking: .25em;
        letter-spacing: .25em
    }

    .tracking-tight {
        --tw-tracking: var(--tracking-tight);
        letter-spacing: var(--tracking-tight)
    }

    .tracking-wider {
        --tw-tracking: var(--tracking-wider);
        letter-spacing: var(--tracking-wider)
    }

    .text-\[\#050505\] {
        color: #050505
    }

    .text-\[\#D7FF00\] {
        color: #d7ff00
    }

    .text-\[\#D7FF00\]\/10 {
        color: #d7ff001a
    }

    .text-emerald-400 {
        color: var(--color-emerald-400)
    }

    .text-white {
        color: var(--color-white)
    }

    .text-zinc-200 {
        color: var(--color-zinc-200)
    }

    .text-zinc-300 {
        color: var(--color-zinc-300)
    }

    .text-zinc-400 {
        color: var(--color-zinc-400)
    }

    .text-zinc-500 {
        color: var(--color-zinc-500)
    }

    .text-zinc-600 {
        color: var(--color-zinc-600)
    }

    .uppercase {
        text-transform: uppercase
    }

    .antialiased {
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale
    }

    .opacity-30 {
        opacity: .3
    }

    .opacity-70 {
        opacity: .7
    }

    .opacity-75 {
        opacity: .75
    }

    .opacity-85 {
        opacity: .85
    }

    .shadow-2xl {
        --tw-shadow: 0 25px 50px -12px var(--tw-shadow-color,#00000040);
        box-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
    }

    .shadow-\[0_0_8px_\#ffffff\] {
        --tw-shadow: 0 0 8px var(--tw-shadow-color,#fff);
        box-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
    }

    .shadow-\[0_0_10px_\#D7FF00\] {
        --tw-shadow: 0 0 10px var(--tw-shadow-color,#d7ff00);
        box-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
    }

    .shadow-\[0_0_20px_\#D7FF00\] {
        --tw-shadow: 0 0 20px var(--tw-shadow-color,#d7ff00);
        box-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
    }

    .shadow-\[0_0_30px_rgba\(215\,255\,0\,0\.35\)\] {
        --tw-shadow: 0 0 30px var(--tw-shadow-color,#d7ff0059);
        box-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
    }

    .shadow-\[0_0_45px_rgba\(215\,255\,0\,0\.3\)\] {
        --tw-shadow: 0 0 45px var(--tw-shadow-color,#d7ff004d);
        box-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
    }

    .shadow-lg {
        --tw-shadow: 0 10px 15px -3px var(--tw-shadow-color,#0000001a), 0 4px 6px -4px var(--tw-shadow-color,#0000001a);
        box-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
    }

    .shadow-md {
        --tw-shadow: 0 4px 6px -1px var(--tw-shadow-color,#0000001a), 0 2px 4px -2px var(--tw-shadow-color,#0000001a);
        box-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
    }

    .shadow-xl {
        --tw-shadow: 0 20px 25px -5px var(--tw-shadow-color,#0000001a), 0 8px 10px -6px var(--tw-shadow-color,#0000001a);
        box-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
    }

    .shadow-\[rgba\(215\,255\,0\,0\.2\)\] {
        --tw-shadow-color: #d7ff0033
    }

    @supports (color: color-mix(in lab,red,red)) {
        .shadow-\[rgba\(215\,255\,0\,0\.2\)\] {
            --tw-shadow-color:color-mix(in oklab, #d7ff0033 var(--tw-shadow-alpha), transparent)
        }
    }

    .shadow-\[rgba\(215\,255\,0\,0\.4\)\] {
        --tw-shadow-color: #d7ff0066
    }

    @supports (color: color-mix(in lab,red,red)) {
        .shadow-\[rgba\(215\,255\,0\,0\.4\)\] {
            --tw-shadow-color:color-mix(in oklab, #d7ff0066 var(--tw-shadow-alpha), transparent)
        }
    }

    .shadow-\[rgba\(215\,255\,0\,0\.25\)\] {
        --tw-shadow-color: #d7ff0040
    }

    @supports (color: color-mix(in lab,red,red)) {
        .shadow-\[rgba\(215\,255\,0\,0\.25\)\] {
            --tw-shadow-color:color-mix(in oklab, #d7ff0040 var(--tw-shadow-alpha), transparent)
        }
    }

    .blur {
        --tw-blur: blur(8px);
        filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
    }

    .blur-2xl {
        --tw-blur: blur(var(--blur-2xl));
        filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
    }

    .blur-3xl {
        --tw-blur: blur(var(--blur-3xl));
        filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
    }

    .blur-\[90px\] {
        --tw-blur: blur(90px);
        filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
    }

    .blur-\[130px\] {
        --tw-blur: blur(130px);
        filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
    }

    .blur-\[140px\] {
        --tw-blur: blur(140px);
        filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
    }

    .blur-xl {
        --tw-blur: blur(var(--blur-xl));
        filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
    }

    .drop-shadow-\[0_0_20px_rgba\(215\,255\,0\,0\.35\)\] {
        --tw-drop-shadow-size: drop-shadow(0 0 20px var(--tw-drop-shadow-color,#d7ff0059));
        --tw-drop-shadow: var(--tw-drop-shadow-size);
        filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
    }

    .drop-shadow-\[0_0_25px_rgba\(215\,255\,0\,0\.4\)\] {
        --tw-drop-shadow-size: drop-shadow(0 0 25px var(--tw-drop-shadow-color,#d7ff0066));
        --tw-drop-shadow: var(--tw-drop-shadow-size);
        filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
    }

    .filter {
        filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
    }

    .backdrop-blur-2xl {
        --tw-backdrop-blur: blur(var(--blur-2xl));
        -webkit-backdrop-filter: var(--tw-backdrop-blur,) var(--tw-backdrop-brightness,) var(--tw-backdrop-contrast,) var(--tw-backdrop-grayscale,) var(--tw-backdrop-hue-rotate,) var(--tw-backdrop-invert,) var(--tw-backdrop-opacity,) var(--tw-backdrop-saturate,) var(--tw-backdrop-sepia,);
        backdrop-filter: var(--tw-backdrop-blur,) var(--tw-backdrop-brightness,) var(--tw-backdrop-contrast,) var(--tw-backdrop-grayscale,) var(--tw-backdrop-hue-rotate,) var(--tw-backdrop-invert,) var(--tw-backdrop-opacity,) var(--tw-backdrop-saturate,) var(--tw-backdrop-sepia,)
    }

    .backdrop-blur-\[2px\] {
        --tw-backdrop-blur: blur(2px);
        -webkit-backdrop-filter: var(--tw-backdrop-blur,) var(--tw-backdrop-brightness,) var(--tw-backdrop-contrast,) var(--tw-backdrop-grayscale,) var(--tw-backdrop-hue-rotate,) var(--tw-backdrop-invert,) var(--tw-backdrop-opacity,) var(--tw-backdrop-saturate,) var(--tw-backdrop-sepia,);
        backdrop-filter: var(--tw-backdrop-blur,) var(--tw-backdrop-brightness,) var(--tw-backdrop-contrast,) var(--tw-backdrop-grayscale,) var(--tw-backdrop-hue-rotate,) var(--tw-backdrop-invert,) var(--tw-backdrop-opacity,) var(--tw-backdrop-saturate,) var(--tw-backdrop-sepia,)
    }

    .backdrop-blur-md {
        --tw-backdrop-blur: blur(var(--blur-md));
        -webkit-backdrop-filter: var(--tw-backdrop-blur,) var(--tw-backdrop-brightness,) var(--tw-backdrop-contrast,) var(--tw-backdrop-grayscale,) var(--tw-backdrop-hue-rotate,) var(--tw-backdrop-invert,) var(--tw-backdrop-opacity,) var(--tw-backdrop-saturate,) var(--tw-backdrop-sepia,);
        backdrop-filter: var(--tw-backdrop-blur,) var(--tw-backdrop-brightness,) var(--tw-backdrop-contrast,) var(--tw-backdrop-grayscale,) var(--tw-backdrop-hue-rotate,) var(--tw-backdrop-invert,) var(--tw-backdrop-opacity,) var(--tw-backdrop-saturate,) var(--tw-backdrop-sepia,)
    }

    .backdrop-blur-xl {
        --tw-backdrop-blur: blur(var(--blur-xl));
        -webkit-backdrop-filter: var(--tw-backdrop-blur,) var(--tw-backdrop-brightness,) var(--tw-backdrop-contrast,) var(--tw-backdrop-grayscale,) var(--tw-backdrop-hue-rotate,) var(--tw-backdrop-invert,) var(--tw-backdrop-opacity,) var(--tw-backdrop-saturate,) var(--tw-backdrop-sepia,);
        backdrop-filter: var(--tw-backdrop-blur,) var(--tw-backdrop-brightness,) var(--tw-backdrop-contrast,) var(--tw-backdrop-grayscale,) var(--tw-backdrop-hue-rotate,) var(--tw-backdrop-invert,) var(--tw-backdrop-opacity,) var(--tw-backdrop-saturate,) var(--tw-backdrop-sepia,)
    }

    .transition {
        transition-property: color,background-color,border-color,outline-color,text-decoration-color,fill,stroke,--tw-gradient-from,--tw-gradient-via,--tw-gradient-to,opacity,box-shadow,transform,translate,scale,rotate,filter,-webkit-backdrop-filter,backdrop-filter,display,content-visibility,overlay,pointer-events;
        transition-timing-function: var(--tw-ease,var(--default-transition-timing-function));
        transition-duration: var(--tw-duration,var(--default-transition-duration))
    }

    .transition-all {
        transition-property: all;
        transition-timing-function: var(--tw-ease,var(--default-transition-timing-function));
        transition-duration: var(--tw-duration,var(--default-transition-duration))
    }

    .transition-colors {
        transition-property: color,background-color,border-color,outline-color,text-decoration-color,fill,stroke,--tw-gradient-from,--tw-gradient-via,--tw-gradient-to;
        transition-timing-function: var(--tw-ease,var(--default-transition-timing-function));
        transition-duration: var(--tw-duration,var(--default-transition-duration))
    }

    .transition-transform {
        transition-property: transform,translate,scale,rotate;
        transition-timing-function: var(--tw-ease,var(--default-transition-timing-function));
        transition-duration: var(--tw-duration,var(--default-transition-duration))
    }

    .duration-200 {
        --tw-duration: .2s;
        transition-duration: .2s
    }

    .duration-300 {
        --tw-duration: .3s;
        transition-duration: .3s
    }

    .duration-500 {
        --tw-duration: .5s;
        transition-duration: .5s
    }

    .ease-out {
        --tw-ease: var(--ease-out);
        transition-timing-function: var(--ease-out)
    }

    .select-none {
        -webkit-user-select: none;
        user-select: none
    }

    @media(hover: hover) {
        .group-hover\:translate-x-1:is(:where(.group):hover *) {
            --tw-translate-x:var(--spacing);
            translate: var(--tw-translate-x) var(--tw-translate-y)
        }

        .group-hover\:-translate-y-1:is(:where(.group):hover *) {
            --tw-translate-y: calc(var(--spacing) * -1);
            translate: var(--tw-translate-x) var(--tw-translate-y)
        }

        .group-hover\:scale-105:is(:where(.group):hover *) {
            --tw-scale-x: 105%;
            --tw-scale-y: 105%;
            --tw-scale-z: 105%;
            scale: var(--tw-scale-x) var(--tw-scale-y)
        }

        .group-hover\:scale-125:is(:where(.group):hover *) {
            --tw-scale-x: 125%;
            --tw-scale-y: 125%;
            --tw-scale-z: 125%;
            scale: var(--tw-scale-x) var(--tw-scale-y)
        }

        .group-hover\:border-\[\#D7FF00\]:is(:where(.group):hover *) {
            border-color: #d7ff00
        }

        .group-hover\:border-\[\#D7FF00\]\/50:is(:where(.group):hover *) {
            border-color: #d7ff0080
        }

        .group-hover\:bg-\[\#D7FF00\]\/20:is(:where(.group):hover *) {
            background-color: #d7ff0033
        }

        .group-hover\:text-\[\#D7FF00\]:is(:where(.group):hover *) {
            color: #d7ff00
        }

        .group-hover\:opacity-60:is(:where(.group):hover *) {
            opacity: .6
        }

        .group-hover\:shadow-\[0_0_15px_\#D7FF00\]:is(:where(.group):hover *) {
            --tw-shadow: 0 0 15px var(--tw-shadow-color,#d7ff00);
            box-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
        }
    }

    .selection\: bg-\[\#D7FF00\]\/30 ::selection {
        background-color:#d7ff004d
    }

    .selection\: bg-\[\#D7FF00\]\/30::selection {
        background-color:#d7ff004d
    }

    .selection\: text-\[\#D7FF00\] ::selection {
        color:#d7ff00
    }

    .selection\: text-\[\#D7FF00\]::selection {
        color:#d7ff00
    }

    @media(hover: hover) {
        .hover\:-translate-y-1:hover {
            --tw-translate-y:calc(var(--spacing) * -1);
            translate: var(--tw-translate-x) var(--tw-translate-y)
        }

        .hover\:border-\[\#D7FF00\]:hover {
            border-color: #d7ff00
        }

        .hover\:border-\[\#D7FF00\]\/40:hover {
            border-color: #d7ff0066
        }

        .hover\:border-\[\#D7FF00\]\/50:hover {
            border-color: #d7ff0080
        }

        .hover\:bg-\[\#0D0D0D\]:hover {
            background-color: #0d0d0d
        }

        .hover\:bg-\[\#e4ff33\]:hover {
            background-color: #e4ff33
        }

        .hover\:bg-zinc-800\/60:hover {
            background-color: #27272a99
        }

        @supports (color: color-mix(in lab,red,red)) {
            .hover\:bg-zinc-800\/60:hover {
                background-color:color-mix(in oklab,var(--color-zinc-800) 60%,transparent)
            }
        }

        .hover\:text-\[\#D7FF00\]:hover {
            color: #d7ff00
        }

        .hover\:text-white:hover {
            color: var(--color-white)
        }
    }

    .focus\: border-\[\#D7FF00\]:focus {
        border-color:#d7ff00
    }

    .focus\: outline-none:focus {
        --tw-outline-style:none;
        outline-style: none
    }

    .active\: cursor-grabbing:active {
        cursor:grabbing
    }

    @media(min-width: 40rem) {
        .sm\:-left-\[49px\] {
            left:-49px
        }

        .sm\:ml-2 {
            margin-left: calc(var(--spacing) * 2)
        }

        .sm\:ml-8 {
            margin-left: calc(var(--spacing) * 8)
        }

        .sm\:flex {
            display: flex
        }

        .sm\:h-12 {
            height: calc(var(--spacing) * 12)
        }

        .sm\:h-\[440px\] {
            height: 440px
        }

        .sm\:w-auto {
            width: auto
        }

        .sm\:grid-cols-2 {
            grid-template-columns: repeat(2,minmax(0,1fr))
        }

        .sm\:grid-cols-3 {
            grid-template-columns: repeat(3,minmax(0,1fr))
        }

        .sm\:p-12 {
            padding: calc(var(--spacing) * 12)
        }

        .sm\:px-6 {
            padding-inline:calc(var(--spacing) * 6)}

        .sm\: pt-0 {
            padding-top:0
        }

        .sm\:pl-10 {
            padding-left: calc(var(--spacing) * 10)
        }

        .sm\:text-2xl {
            font-size: var(--text-2xl);
            line-height: var(--tw-leading,var(--text-2xl--line-height))
        }

        .sm\:text-3xl {
            font-size: var(--text-3xl);
            line-height: var(--tw-leading,var(--text-3xl--line-height))
        }

        .sm\:text-4xl {
            font-size: var(--text-4xl);
            line-height: var(--tw-leading,var(--text-4xl--line-height))
        }

        .sm\:text-5xl {
            font-size: var(--text-5xl);
            line-height: var(--tw-leading,var(--text-5xl--line-height))
        }

        .sm\:text-6xl {
            font-size: var(--text-6xl);
            line-height: var(--tw-leading,var(--text-6xl--line-height))
        }

        .sm\:text-base {
            font-size: var(--text-base);
            line-height: var(--tw-leading,var(--text-base--line-height))
        }

        .sm\:text-lg {
            font-size: var(--text-lg);
            line-height: var(--tw-leading,var(--text-lg--line-height))
        }

        .sm\:text-sm {
            font-size: var(--text-sm);
            line-height: var(--tw-leading,var(--text-sm--line-height))
        }
    }

    @media(min-width: 48rem) {
        .md\:grid-cols-2 {
            grid-template-columns:repeat(2,minmax(0,1fr))
        }

        .md\:grid-cols-4 {
            grid-template-columns: repeat(4,minmax(0,1fr))
        }

        .md\:flex-row {
            flex-direction: row
        }
    }

    @media(min-width: 64rem) {
        .lg\:col-span-5 {
            grid-column:span 5/span 5
        }

        .lg\:col-span-7 {
            grid-column: span 7/span 7
        }

        .lg\:flex {
            display: flex
        }

        .lg\:hidden {
            display: none
        }

        .lg\:grid-cols-4 {
            grid-template-columns: repeat(4,minmax(0,1fr))
        }

        .lg\:grid-cols-12 {
            grid-template-columns: repeat(12,minmax(0,1fr))
        }

        .lg\:flex-row {
            flex-direction: row
        }

        .lg\:gap-8 {
            gap: calc(var(--spacing) * 8)
        }

        .lg\:text-7xl {
            font-size: var(--text-7xl);
            line-height: var(--tw-leading,var(--text-7xl--line-height))
        }
    }
}

.font-outfit {
    font-family: var(--font-outfit)
}

.font-grotesk {
    font-family: var(--font-grotesk)
}

.font-sora {
    font-family: var(--font-sora)
}

.bg-noise {
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noiseFilter'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noiseFilter)' opacity='0.025'/%3E%3C/svg%3E")
}

.glass-panel {
    -webkit-backdrop-filter: blur(16px);
    background: #0d0d0dbf;
    border: 1px solid #d7ff001a
}

.glass-panel-hover {
    transition: all .4s cubic-bezier(.16,1,.3,1)
}

.glass-panel-hover:hover {
    background: #101010e6;
    border-color: #d7ff0059;
    transform: translateY(-3px);
    box-shadow: 0 10px 30px -10px #d7ff0026,0 0 20px -5px #d7ff001a
}

.lime-glow {
    box-shadow: 0 0 25px #d7ff004d
}

.lime-border-glow {
    border-color: #d7ff0066;
    box-shadow: 0 0 15px #d7ff0033
}

.text-lime {
    color: #d7ff00
}

.text-gradient-lime {
    -webkit-text-fill-color: transparent;
    background: linear-gradient(135deg,#fff,#d7ff00);
    -webkit-background-clip: text
}

::-webkit-scrollbar {
    width: 8px
}

::-webkit-scrollbar-track {
    background: #050505
}

::-webkit-scrollbar-thumb {
    background: #1a1a1a;
    border: 1px solid #d7ff0026;
    border-radius: 4px
}

::-webkit-scrollbar-thumb:hover {
    background: #d7ff00
}

.no-scrollbar::-webkit-scrollbar {
    display: none
}

.no-scrollbar {
    -ms-overflow-style: none;
    scrollbar-width: none
}

@media(prefers-reduced-motion:reduce) {
    *,:before,:after {
        scroll-behavior: auto!important;
        transition-duration: .01ms!important;
        animation-duration: .01ms!important;
        animation-iteration-count: 1!important
    }
}

@property --tw-translate-x {
    syntax: "*";
    inherits: false;
    initial-value: 0
}

@property --tw-translate-y {
    syntax: "*";
    inherits: false;
    initial-value: 0
}

@property --tw-translate-z {
    syntax: "*";
    inherits: false;
    initial-value: 0
}

@property --tw-scale-x {
    syntax: "*";
    inherits: false;
    initial-value: 1
}

@property --tw-scale-y {
    syntax: "*";
    inherits: false;
    initial-value: 1
}

@property --tw-scale-z {
    syntax: "*";
    inherits: false;
    initial-value: 1
}

@property --tw-rotate-x {
    syntax: "*";
    inherits: false
}

@property --tw-rotate-y {
    syntax: "*";
    inherits: false
}

@property --tw-rotate-z {
    syntax: "*";
    inherits: false
}

@property --tw-skew-x {
    syntax: "*";
    inherits: false
}

@property --tw-skew-y {
    syntax: "*";
    inherits: false
}

@property --tw-space-y-reverse {
    syntax: "*";
    inherits: false;
    initial-value: 0
}

@property --tw-border-style {
    syntax: "*";
    inherits: false;
    initial-value: solid
}

@property --tw-gradient-position {
    syntax: "*";
    inherits: false
}

@property --tw-gradient-from {
    syntax: "<color>";
    inherits: false;
    initial-value: #0000
}

@property --tw-gradient-via {
    syntax: "<color>";
    inherits: false;
    initial-value: #0000
}

@property --tw-gradient-to {
    syntax: "<color>";
    inherits: false;
    initial-value: #0000
}

@property --tw-gradient-stops {
    syntax: "*";
    inherits: false
}

@property --tw-gradient-via-stops {
    syntax: "*";
    inherits: false
}

@property --tw-gradient-from-position {
    syntax: "<length-percentage>";
    inherits: false;
    initial-value: 0%
}

@property --tw-gradient-via-position {
    syntax: "<length-percentage>";
    inherits: false;
    initial-value: 50%
}

@property --tw-gradient-to-position {
    syntax: "<length-percentage>";
    inherits: false;
    initial-value: 100%
}

@property --tw-leading {
    syntax: "*";
    inherits: false
}

@property --tw-font-weight {
    syntax: "*";
    inherits: false
}

@property --tw-tracking {
    syntax: "*";
    inherits: false
}

@property --tw-shadow {
    syntax: "*";
    inherits: false;
    initial-value: 0 0 #0000
}

@property --tw-shadow-color {
    syntax: "*";
    inherits: false
}

@property --tw-shadow-alpha {
    syntax: "<percentage>";
    inherits: false;
    initial-value: 100%
}

@property --tw-inset-shadow {
    syntax: "*";
    inherits: false;
    initial-value: 0 0 #0000
}

@property --tw-inset-shadow-color {
    syntax: "*";
    inherits: false
}

@property --tw-inset-shadow-alpha {
    syntax: "<percentage>";
    inherits: false;
    initial-value: 100%
}

@property --tw-ring-color {
    syntax: "*";
    inherits: false
}

@property --tw-ring-shadow {
    syntax: "*";
    inherits: false;
    initial-value: 0 0 #0000
}

@property --tw-inset-ring-color {
    syntax: "*";
    inherits: false
}

@property --tw-inset-ring-shadow {
    syntax: "*";
    inherits: false;
    initial-value: 0 0 #0000
}

@property --tw-ring-inset {
    syntax: "*";
    inherits: false
}

@property --tw-ring-offset-width {
    syntax: "<length>";
    inherits: false;
    initial-value: 0
}

@property --tw-ring-offset-color {
    syntax: "*";
    inherits: false;
    initial-value: #fff
}

@property --tw-ring-offset-shadow {
    syntax: "*";
    inherits: false;
    initial-value: 0 0 #0000
}

@property --tw-blur {
    syntax: "*";
    inherits: false
}

@property --tw-brightness {
    syntax: "*";
    inherits: false
}

@property --tw-contrast {
    syntax: "*";
    inherits: false
}

@property --tw-grayscale {
    syntax: "*";
    inherits: false
}

@property --tw-hue-rotate {
    syntax: "*";
    inherits: false
}

@property --tw-invert {
    syntax: "*";
    inherits: false
}

@property --tw-opacity {
    syntax: "*";
    inherits: false
}

@property --tw-saturate {
    syntax: "*";
    inherits: false
}

@property --tw-sepia {
    syntax: "*";
    inherits: false
}

@property --tw-drop-shadow {
    syntax: "*";
    inherits: false
}

@property --tw-drop-shadow-color {
    syntax: "*";
    inherits: false
}

@property --tw-drop-shadow-alpha {
    syntax: "<percentage>";
    inherits: false;
    initial-value: 100%
}

@property --tw-drop-shadow-size {
    syntax: "*";
    inherits: false
}

@property --tw-backdrop-blur {
    syntax: "*";
    inherits: false
}

@property --tw-backdrop-brightness {
    syntax: "*";
    inherits: false
}

@property --tw-backdrop-contrast {
    syntax: "*";
    inherits: false
}

@property --tw-backdrop-grayscale {
    syntax: "*";
    inherits: false
}

@property --tw-backdrop-hue-rotate {
    syntax: "*";
    inherits: false
}

@property --tw-backdrop-invert {
    syntax: "*";
    inherits: false
}

@property --tw-backdrop-opacity {
    syntax: "*";
    inherits: false
}

@property --tw-backdrop-saturate {
    syntax: "*";
    inherits: false
}

@property --tw-backdrop-sepia {
    syntax: "*";
    inherits: false
}

@property --tw-duration {
    syntax: "*";
    inherits: false
}

@property --tw-ease {
    syntax: "*";
    inherits: false
}

@keyframes ping {
    75%,to {
        opacity: 0;
        transform: scale(2)
    }
}

@keyframes pulse {
    50% {
        opacity: .5
    }
}
```
## OUTPUT
<img width="1906" height="1032" alt="Screenshot 2026-10-31 110227" src="https://github.com/user-attachments/assets/87437420-163a-4cd5-a6a5-42bea449f5be" />
<img width="1886" height="1028" alt="Screenshot 2026-10-31 110308" src="https://github.com/user-attachments/assets/f68859dc-0ac1-4618-97c2-84703ef5800a" />
<img width="1907" height="1027" alt="Screenshot 2026-10-31 110400" src="https://github.com/user-attachments/assets/e7e5d892-b474-4ab7-b4ab-f0138a2b8ae0" />
<img width="1877" height="1006" alt="Screenshot 2026-10-31 110502" src="https://github.com/user-attachments/assets/32fdbfe0-3468-48f3-82e9-31ff60831809" />
<img width="1917" height="1017" alt="Screenshot 2026-10-31 110528" src="https://github.com/user-attachments/assets/e94a0bc4-6d35-4fe5-8da5-7376bde3032c" />
<img width="1908" height="1011" alt="Screenshot 2026-10-31 110554" src="https://github.com/user-attachments/assets/278a1c11-65c9-4a65-be2b-efe655e131d5" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
