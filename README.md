Embassy Electricals: Brand Guide
This is the single source of truth for the Embassy Electricals brand. Use it to build a design system. Values marked Fixed were decided with the owner. Values marked Defined were set while building the Home screen and are the system's working defaults.

Company name: Embassy Electricals
Signature line: #TheEngineeringCompany (always written exactly like this, with capital T, E and C and no spaces)
Direction: Fair Line
Product: Embassy Electricals Request Portal, a website where property owners send an electrical request in minutes, and urgent problems are handled before planned projects.
1. Brand concept
Mission
To make getting electrical engineering help simple and fair for everyone. Every request is logged, urgent faults are handled first, and every customer is treated by the same rules, wherever they are.

Primary audience
Property owners and managers who need electrical engineering work, either because something has failed (power down, a safety risk) or because they are planning a project (a new block to wire). They are most often commercial and industrial clients, apartment block managers and landlords. They value a documented, favour-free process because they have been burned by contractors who answer to whoever knows them best.

Positioning against competitors
Most competitors fall into two groups: informal contractors who work through phone calls, personal contacts and favours, and large firms that are slow, paper-heavy and hard to reach. Embassy Electricals sits between them. It is as quick and easy to reach as a local contractor, and as orderly and accountable as an institution. The proof is concrete: a reference number for every request, urgent first and then planned in the order received, and a hotline that is always easy to find. #TheEngineeringCompany is the confidence line on top of that proof. It says the company honours its services.

Brand pillars
Fair. The same rules apply to every customer. No favours, no queue-jumping, no side deals.
Transparent. Every request gets a reference number and a clear statement of what happens next.
Fast. Urgent problems come first, and sending a request takes minutes from anywhere in the world.
Visual feel
Embassy Electricals looks like a trusted institution that has learned to be fast: official without being stiff. Newsreader gives headlines the weight of a formal record, and Public Sans keeps forms and body text plain and easy to read on any screen. The base palette is calm and document-like: deep ink-navy, clean off-white paper and quiet grey rules. One signal colour, amber, is saved for the hotline and the urgent state so the most important thing is always the easiest to find. Layouts are orderly and well spaced, with strong alignment, generous margins and clearly labelled steps, so a page feels like a well-run front desk. Photography is real work in real buildings, never stock lightning bolts.

2. Product context
Users

Customer (no login): opens the site, fills in a form and sends it.
Staff or admin (login required): sees all incoming requests with urgent ones at the top, views customer details, and marks each request Received, In progress or Completed.
Core action: the customer sends a request form, either "Report a problem" (urgent) or "New customer" (planned).

Screens

Home: who we are, the hotline and other contact options, one line on how requests are handled (urgent first, then planned, in the order received), and two buttons: "Report a problem" and "New customer".
Service form: displays types of services that are available for the customer.
Request form: the problem form or the new customer form, depending on the button chosen.
Confirmation: reference number, whether the request is marked urgent or planned, a "what happens next" message, and the hotline.
Staff view (login): list of requests showing reference number, urgent or planned, customer details and status.
Report a problem form fields: full name, phone, email, building location, what happened, damage level (choose one: Partial power loss, Total power loss, Safety risk), optional photo.

New customer form fields: full name, phone, email, site location, building type (choose one: House, Apartment block, Commercial, Industrial), description of work needed, optional preferred start date.

Out of scope: customer accounts and request tracking, About us or blog pages, online payments or quotes, live chat.

Rule for the hotline: it must always be easy to find. It sits in a sticky header on every page.

Placeholders : hotline no: +254 707463607, email@xyz.com.

3. Typography (Fixed: fonts. Defined: scale)
Both fonts are free on Google Fonts. Neither Inter, Roboto, Poppins nor Montserrat is used.

Role	Font	Weights	Use
Headlines	Newsreader	500, 600	Headings, card titles, the logo text. Gives the weight of a formal record.
Body and UI	Public Sans	400, 500, 600	Body copy, forms, buttons, labels, status chips, captions. Built for plain-language clarity.
Google Fonts link

https://fonts.googleapis.com/css2?family=Newsreader:opsz,wght@6..72,500;6..72,600&family=Public+Sans:wght@400;500;600&display=swap

Fallback stacks

Headlines: "Newsreader", Georgia, serif
Body: "Public Sans", system-ui, -apple-system, "Segoe UI", sans-serif
Type scale (base 16px, sizes in rem)

Token	Font	Weight	Size	Line height	Use
Display	Newsreader	600	clamp(2rem, 5.2vw, 3.2rem)	1.1	Home hero headline
H1	Newsreader	600	1.9rem	1.15	Page titles
H2	Newsreader	600	1.35rem	1.2	Card and section titles
Body	Public Sans	400	1.05rem	1.6	Main copy
Body small	Public Sans	400	0.92rem	1.5	Helper text, contact labels, footer
Label	Public Sans	600	1rem	1.3	Buttons, form labels, hotline
Chip	Public Sans	600	0.85rem	1.2	Status chips
Rules

Headlines are never all caps. Maximum headline width about 18ch for the hero.
Body line length stays between 56ch and 64ch.
Use curly typographic punctuation in all visible text: ’ for apostrophes and “ ” for quotation marks.
Headlines use the primary navy #12304F on light backgrounds and #D6E6F7 on dark backgrounds.
4. Colour palette: Ink and Amber (Fixed)
Role	Hex	Use
Primary	#12304F	Nav bar, headlines, the "New customer" button, logo tile
Accent	#F2A900	The hotline and the urgent state only. Always used as a background, never as text.
Background	#F6F8FA	Page and form surfaces
Text	#14212E	Body copy and labels
Success	#1B6E43	Completed status
Warning	#8A5300	In progress status, damage notices
Error	#B3261E	Form errors, Safety risk
Supporting tokens (Defined, light mode)

Token	Hex	Use
Card	#FFFFFF	Cards and form panels
Line	#D3DAE1	Borders and dividers
Muted text	#3F4F5E	Secondary copy
Text on accent	#14212E	Text placed on amber
Text on primary	#FFFFFF	Text placed on navy
Dark mode tokens (Defined)

Token	Hex
Background	#0E1923
Card	#16222E
Line	#2B3947
Text	#EEF2F6
Muted text	#A9B8C6
Headings	#D6E6F7
Secondary button	#2A5382
Header bar	#12304F (unchanged)
Accent	#F2A900 (unchanged)
CSS custom properties

:root {
  --primary: #12304F;
  --accent: #F2A900;
  --bg: #F6F8FA;
  --text: #14212E;
  --success: #1B6E43;
  --warning: #8A5300;
  --error: #B3261E;
  --card: #FFFFFF;
  --line: #D3DAE1;
  --muted: #3F4F5E;
  --head: #12304F;
  --btn2: #12304F;
}
@media (prefers-color-scheme: dark) {
  :root {
    --bg: #0E1923; --text: #EEF2F6; --head: #D6E6F7;
    --card: #16222E; --line: #2B3947; --btn2: #2A5382; --muted: #A9B8C6;
  }
}

WCAG AA contrast (needs 4.5:1 for body text). All pass.

Pairing	Ratio
Text on background (#14212E on #F6F8FA)	15.3:1
Text on card (#14212E on #FFFFFF)	16.3:1
Muted text on background	7.9:1
Primary on background	12.6:1
White on primary	13.4:1
Text on accent (#14212E on #F2A900)	8.1:1
Success on background	5.9:1
Warning on background	5.9:1
Error on background	6.1:1
Dark mode text on dark background	15.8:1
Dark mode muted on dark background	8.8:1
Dark mode headings on dark background	14.0:1
White on dark mode secondary button	7.9:1
Cream on navy (logo text on dark)	12.6:1
Colour rules

Amber on the light background is only 1.9:1. Never use amber for text or thin lines on light backgrounds. It is a fill colour with dark text on top.
Amber is reserved for the hotline, "Report a problem", the urgent badge, and the amber bar in the logo. Do not use it for decoration.
Status colours are never the only signal. Always pair them with a text label (Received, In progress, Completed).
No gradients, no drop shadows on brand elements.
5. Logo (Fixed)
Final logo files
File	Use
embassy-stacked-light.svg	Full logo on light backgrounds
embassy-stacked-dark.svg	Full logo on dark backgrounds
embassy-tile-light.svg	App tile alone, on light backgrounds
embassy-tile-dark.svg	App tile alone, on dark backgrounds (adds a thin light border)
embassy-stamp.svg	Clean official stamp
embassy-stamp-inked.svg	Official stamp with rubber-ink texture
Construction
Tile: a 200 by 200 rounded square, corner radius 44, filled #12304F.
Symbol: a power ring in cream #F6F8FA (stroke 20, radius 50, centred, with a gap of 32° each side of the top, round caps), and a vertical amber #F2A900 bar through the gap (stroke 20, round caps, running from the top of the ring down towards the centre).
Dark version of the tile: the same, with a 6-unit cream #F6F8FA border inside the tile edge so the shape holds on dark backgrounds.
Stacked logo: tile on the left, with "Embassy" above "Electricals" on the right. Both lines are Newsreader. "Embassy" is weight 600 and "Electricals" is weight 500. Text colour is navy #12304F on light and cream #F6F8FA on dark. The tile is about 120 px tall in a 130 px high lockup.
Usage rules
Minimum size: the stacked logo is never narrower than 160 px (about 40 mm in print). Below that, use the tile alone. The tile reads clearly down to 32 px wide.
Clear space: keep a margin equal to one quarter of the tile's height on all sides. Nothing else enters it.
Light and dark: use the -light files on light backgrounds and the -dark files on dark backgrounds. Never put a light file on a dark background or the reverse.
Do not recolour any part, especially the amber bar. Do not stretch, rotate or skew the logo. Do not add shadows, outlines, glows or gradients. Do not rebuild it in another typeface. Do not put it on busy photography without a solid panel behind it.
Do not use any earlier logo versions (shield, seal, gate, outlet, hex nut, wordmark-only). They were rejected.
Text in the files is live Newsreader. Convert text to outlines before sending the files to a printer or sign-maker. The tile has no text.
Where the logo goes
Website header: the stacked logo (dark version, at least 160 px wide, about 56 px tall) on the navy bar on the left, with the hotline button on the right. On screens narrower than 520 px the header uses the tile alone (dark version, 40 px) so the logo never falls below its minimum size.
Favicon, app icon, social profile image: the tile alone.
Documents and vehicles: stacked logo, with the signature line #TheEngineeringCompany set below or beside it in Public Sans 600.
Official stamp
Design: a double ring in navy #12304F (outer ring stroke 6, thin ring stroke 1.5, inner ring stroke 2). "EMBASSY ELECTRICALS" is arched across the top in Newsreader 600 with letter-spacing 2.5. "THE ENGINEERING COMPANY" is arched across the bottom in Public Sans 600 with letter-spacing 3. A small diamond sits at the left and right. The Power ring symbol with its amber bar is in the centre, and "OFFICIAL RECORD" in Public Sans 600 sits beneath it.
Use: certificates, request confirmations, letterheads and the confirmation screen, beside the reference number.
Minimum size: 160 px wide, so the arched text stays legible.
Inked version: tilted slightly (−5°) with a worn texture. Use it only where a hand-stamped feel is wanted, never for small UI.
Note: this is a brand mark. Real legal or government stamps follow local rules, so check the requirements if it must carry legal weight.
6. Voice and tone (Fixed)
Voice
Plain, steady and direct, like a calm official who is on your side. Short sentences, active verbs, no jargon. In an urgent moment the tone is calm and reassuring. For planned work it is clear and professional. We say what we will do, and then we do it.

Five words we always use
Logged, Order, Clear, Same, Confirmed

Five words we never use
Favour, Connections, VIP, Fast-track, Cutting, I can pay

Examples
Hero headline: "Every request logged. Every customer treated the same."
Confirmation: "Request logged. Your reference is on screen. Urgent faults are handled first."
Handling line: "Urgent problems first, then planned work, each in the order received."
Urgent card: "Something has failed. Power is down, a system has stopped, or there is a safety risk."
Planned card: "Planned electrical work. Wiring a new block, upgrading a site, or any project with a start date."
Tagline use
#TheEngineeringCompany is a signature line, not a headline. It appears in the footer, on social posts, vehicles and uniforms, and under the logo on documents. It assures the customer that the company is capable and honours its services. The headline does the persuading with specifics, and the hashtag adds confidence on top.

Writing rules
Always tell people what happens next.
Always give the reference number in plain text.
Never promise a time we cannot guarantee.
Never suggest any customer gets special treatment.
7. UI components (Defined, from the Home screen)
Layout: content max width 1080px, centred, 20px side padding. Spacing uses multiples of 4 and 8. Card radius 10px, button radius 6px, rule-bar radius 0 8px 8px 0.

Header: sticky, navy #12304F, white text. Logo on the left. The hotline button on the right: amber background, #14212E text, weight 600, padding 9px 16px, radius 6px, links to tel:.

Buttons

Urgent ("Report a problem"): amber #F2A900 background, #14212E text, Public Sans 600 1rem, padding 13px 20px, radius 6px.
Planned ("New customer"): navy #12304F background (dark mode #2A5382), white text, same size.
Visible focus outline: 3px in the heading colour, 3px offset.
Option cards: card background, 1px line border, radius 10px, padding 22px. An H2 title, one line of muted text, then the button at the bottom.

Handling rule bar: card background, 6px amber left border, padding 16px 20px, with the label in weight 600.

Status chips: pill shape, 1.5px border in the current text colour, text label always present.

Received: text colour
In progress: warning #8A5300
Completed: success #1B6E43
Error messages: #B3261E, weight 500, 0.9rem, placed directly under the field they refer to.

Contact list: three columns (Hotline, WhatsApp, Email), each with a 2px line on top, a muted label and a link in the heading colour.

Footer: top border in the line colour, company name in weight 600 on the left, #TheEngineeringCompany on the right.

Accessibility: meet WCAG AA, support light and dark modes, and respect safe-area insets on phones. Declare viewport-fit=cover.

8. Quick reference
Name: Embassy Electricals
Signature: #TheEngineeringCompany
Headline font: Newsreader 500 and 600
Body font: Public Sans 400, 500 and 600
Primary: #12304F
Accent: #F2A900 (fill only)
Background: #F6F8FA
Text: #14212E
Success: #1B6E43
Warning: #8A5300
Error: #B3261E
Words we use: Logged, Order, Clear, Same, Confirmed
Words we never use: Favour, Connections, VIP, Fast-track, I can pay