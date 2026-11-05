# Gramsaarthi — Rural Development App Prototype

A responsive, front-end prototype inspired by the supplied dashboard reference. It runs locally in a modern browser and does not require Node.js or installation.

## Run it
1. Extract `Gramsaarthi_Prototype.zip`.
2. Open the extracted `Gramsaarthi_Prototype` folder.
3. Double-click `index.html` to open it in Chrome, Edge, or Firefox.
4. Choose a language and click Continue.
5. Sign in with any 10-digit mobile number and use demo OTP `123456`, or create a demo account.
6. Choose a role to see its personalized dashboard.

## Included
- Welcome screen and language selector: English, Hindi, Marathi.
- Mobile login flow with a clearly labelled simulated OTP.
- Registration: name, mobile number, age, role.
- Eight role-based dashboards: Farmer, Rural Woman, Landless Labourer, Livestock Rearer, Rural Entrepreneur, Artisan/Craftsperson, Fisherman/Pond Owner, Student/Dropout.
- Farmer farm-map simulation, current-vs-ideal comparison, crop advice tabs, sowing window and irrigation schedule.
- Fisheries pond readings, fish growth and feeding schedule.
- Entrepreneur revenue/expenses/profit and product performance examples.
- Artisan product catalogue and order management examples.
- Labour job listings and work/scheme status examples.
- Livestock overview, care reminders and milk production.
- Rural women business ideas, earnings and skills.
- Student course progress and scholarship/course suggestions.
- Government schemes directory, demo market prices, community feed, nearby services, opportunities, alerts, and demo assistant.
- Responsive desktop and mobile layout.

## Important prototype limits
- The OTP is simulated. No SMS is sent.
- No real account is created, and data is not securely stored or synced.
- Market prices, service distances, weather, farm map, water readings, financial figures and opportunities are illustrative sample data.
- The map is a visual simulation, not satellite imagery, GIS analysis or live location.
- Government scheme information is only an introductory summary. Always verify current rules and eligibility on official government portals.
- The assistant is a rule-based demo, not an AI service.
- Google Fonts requires an internet connection; the rest of the interface is local.
- This is a front-end prototype, not a deployed public website. To publish it publicly, upload the folder to a static host such as GitHub Pages, Netlify or Vercel. Real SMS OTP, authentication, databases, live APIs, location services, moderation and security need a backend and provider setup.

## Files
- `index.html` — page structure
- `style.css` — responsive styling
- `app.js` — demo interactions and role-specific views
- `README.md` — instructions and limitations


## Updated prototype features
- My profile page lets users edit name, mobile number, age, role, district, interests and reminder preference. Saving updates the role-specific dashboard for the current session.
- Nearby Services includes a draggable demo map with clickable, labelled sample locations and a reset control. Places and distances are fictional placeholders.
- Market price search is directly below the Mandi prices heading. Community post composer places the writing box beside the heading on wide screens and stacks neatly on mobile.
- OTP and preferred-language controls use fixed-width, non-rotated layout rules to prevent the layout issue shown in the supplied screenshots.
- Assistant replies to a wider set of role-specific questions and displays separate user/assistant chat bubbles. It is a local rule-based demo, not a connected generative-AI service.

## Important limitations
The OTP is fixed at `123456`; no SMS is sent. Profile changes are held in the browser session only. Map points, weather, market prices, scheme information, job listings and dashboard metrics are examples and are not live or verified. A production launch requires a secure backend, database, real SMS OTP provider, authenticated AI service, verified APIs and privacy/security review.

## Latest UI updates
- Added a top-right Light/Dark theme toggle with coordinated dashboard, cards, tables, form controls and assistant colours.
- Replaced the mandi search field with tidy clickable filters: All crops, Prices rising and Prices falling.
- Added four selectable farmer field layers: Current field, Ideal plan, Soil moisture and Crop health. Each selection changes the colour-coded simulated plot view.
- Straightened and constrained form controls so fields remain horizontal and inside their cards on desktop and mobile.
- Preserved eight role-based dashboards and their demo actions. All figures and locations remain sample data; this is a local front-end prototype.


## Saved demo profiles
- Registration and profile edits are saved in the browser's local storage, keyed by mobile number.
- On the same browser/device, signing in again with that mobile number and demo OTP `123456` restores the saved name, age, role, preferences, language and theme.
- Data remains on that browser/device; it is not synced across devices and is not protected like a production account. Do not enter sensitive personal or financial information. Clearing browser site data will remove these demo profiles.
- The login card now centers the leaf mark, account label and welcome heading while keeping the Back link aligned at the top.
