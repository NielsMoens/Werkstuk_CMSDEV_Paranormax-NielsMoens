<h1>Paranormax CMS theme site </h1>

<h2>ScreenRecording</h2>
<a href="https://vimeo.com/667284010">Click here to see the screenRecordinge of the CMSthemeSite</a>

<h2>Links to source code</h2>
<a href="https://github.com/NielsMoens/Werkstuk_CMSDEV_Paranormax-NielsMoens"> CMS Theme Website </a><br>
<a href="https://github.com/NielsMoens/Werkstuk_CMSDEV_ParanormaxApp-NielsMoens"> Web App </a><br>
(incase the webApp gives you DNS errors use this <a href="https://hardcore-swanson-20ef3a.netlify.app/"> LINK</a>)

<h1>About the project</h1>

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```
Wegens het grote succes en nationale bekendheid van Paranormax werd intern beslist om een uitzendbureau te starten.
Er is immers nood aan een vertrouwelijke en veilige organisatie waar je pro mediums kan vinden.

Je kan het eigenlijk als een sociaal netwerk zien, dat paranormale activiteiten / enthousiastelingen / slachtoffers met elkaar verbindt.

Het werkstuk is tweeledig. Het volledige werkstuk wordt beheerd via een centraal CMS (Wordpress / Drupal / Craft CMS).

Er is een App (web / native) en er is een Site (theme in cms).

CMS (Enkel toegankelijk voor admins)

Admins = paranormax medewerkers
Beheer van alle content & gebruikers in de site
Beheer van vragen
Kunnen via het admin panel vragen goedkeuren of afkeuren.
Categoriseren goedgekeurde vragen en vullen verdere info aan.
(bv. categorie ‘geestoproeping’ of ‘duiveluitdrijving’)

(Goedgekeurde vragen verschijnen als opdracht op de website.)

Hebben een overzicht van alle opdrachten en hun status.
Statussen:
draft:
De vraag is ingediend en wacht op goedkeuring of afkeuring.
searching:
De vraag staat openbaar op de website en mediums kunnen zich kandidaat stellen.
pending:
Er zijn mediums die zich kandidaat gesteld hebben (mediums kunnen annuleren voor de deadline, status terug naar searching)
accepted
er is een match tussen medium & opdrachtgever.
deadline speelt geen rol meer
success:
de opdracht werd succesvol uitgevoerd.
Wordt door een opdrachtgever en medium aangeduid.
failed:
de deadline is verstreken en de opdracht mislukte.
of de deadline is verstreken alvorens mediums zich hebben kandidaat gesteld.


Site (theme in CMS)

Public Content
Informatie over het uitzendbureau/soc. netwerk
Recente opdrachten & status (vb de laatste 20)
Oplijsting van de mediums + profiel
Widgets / content blocks
Statistieken (hoeveel cases, hoeveel geregistreerde mediums, ...)
Partners (evt. als widget of content block)
Getuigenissen (evt. als widget of content block)
Contact
Publiciteit & link naar de app
Privacy Policy
Private Content (enkel voor geregistreerde gebruikers)
Paranormale Verhalen
VIP-content (normax-xxl):
Videokanaal (youtube / vimeo)
Registratie als normaxxer (member)
wordt vip-member
met betalingssysteem
Mollie / Ingenico / Stripe / Paypal / ...
beheer van eigen accountgegevens

