# Survivant-Digital-Hub
Official website and digital marketplace for Survivant Digital Hub
/* SURVIVANT DIGITAL HUB BRAND REFRESH */
:root {
  --navy: #171717;
  --gold: #FFC928;
  --gold2: #FFE27A;
  --ink: #191919;
  --muted: #626262;
  --paper: #F7F7F7;
  --sdh-red: #C8102E;
}

.header {
  background: #fff;
  border-bottom: 3px solid var(--sdh-red);
}

.brand b { color: var(--sdh-red); }

.mark {
  background: #171717;
  border: 2px solid var(--gold);
  color: #fff;
}

.hero { background: #171717; }

.hero:before {
  background: radial-gradient(
    circle at 80% 45%,
    #c8102e35,
    transparent 38%
  );
}

.eyebrow { color: var(--gold); }

h1 em, h2 em { color: var(--gold); }

.gold {
  background: var(--sdh-red);
  color: #fff;
}

.gold:hover { background: #a50c25; }

.poster {
  background: linear-gradient(145deg, #333, #111);
  border: 1px solid var(--gold);
}

.poster strong span { color: var(--sdh-red); }

.card:before { background: var(--sdh-red); }

.biz:before { background: var(--gold); }

.ai:before { background: #222; }

.icon {
  background: #fff0f1;
  color: var(--sdh-red);
}

.biz .icon {
  background: #fff8df;
  color: #9b7100;
}

.ai .icon {
  background: #ededed;
  color: #222;
}

.card small { color: var(--sdh-red); }

.card>a {
  color: var(--sdh-red);
  border-bottom-color: #e9b9c2;
}

.dark { background: #171717; }

.steps b { color: var(--gold); }

.seal {
  border-color: var(--sdh-red);
  background: #fff;
}

.seal strong { color: #171717; }

.seal small { color: var(--sdh-red); }

.contact-box {
  background: #171717;
  border-top: 4px solid var(--sdh-red);
}

footer { background: #101010; }

@media(max-width:640px) {
  .nav nav {
    background: #fff;
    border-top: 3px solid var(--sdh-red);
  }
}/* =====================================
   SURVIVANT DIGITAL HUB BRAND THEME
   BLACK | RED | YELLOW | WHITE
===================================== */

:root {
  --navy: #171717;
  --gold: #FFC928;
  --gold2: #FFD95C;
  --ink: #171717;
  --muted: #666666;
  --paper: #FFFFFF;
}

/* General */
body {
  background: #FFFFFF;
  color: #171717;
}

/* Header and navigation */
.header {
  background: #FFFFFF;
  border-bottom: 2px solid #C8102E;
}

.brand {
  color: #171717;
}

.brand b {
  color: #C8102E;
}

.mark {
  background: #171717;
  border: 2px solid #FFC928;
  color: #FFC928;
}

.nav nav {
  color: #171717;
}

.nav nav a:hover,
footer a:hover {
  color: #C8102E;
}

.navbutton {
  border: 1px solid #C8102E;
  color: #171717;
}

.toggle {
  color: #171717;
}

/* Hero section */
.hero,
.dark {
  background: #171717;
  color: #FFFFFF;
}

.hero:before {
  background: radial-gradient(
    circle at 80% 45%,
    #C8102E35,
    transparent 38%
  );
}

.eyebrow,
.eyebrow.dark {
  color: #FFC928;
}

h1 em,
h2 em {
  color: #FFC928;
}

/* Buttons */
.gold {
  background: #C8102E;
  color: #FFFFFF;
}

.gold:hover {
  background: #A50D25;
}

.outline {
  border: 1px solid #FFC928;
  color: #FFFFFF;
}

/* Hero artwork */
.poster {
  background: linear-gradient(145deg, #303030, #171717);
  border: 1px solid #FFC928;
}

.poster strong span {
  color: #C8102E;
}

.poster i {
  background: #FFC928;
}

.orbit {
  border-color: #FFC92855;
}

.float {
  background: #FFFFFF;
  color: #171717;
}

/* Information strip */
.strip {
  border-top: 1px solid #FFFFFF25;
}

.strip i {
  background: #C8102E;
}

/* Product department cards */
.card {
  background: #FFFFFF;
  border: 1px solid #E5E5E5;
}

.card:before,
.biz:before,
.ai:before {
  background: #C8102E;
}

.icon,
.biz .icon,
.ai .icon {
  background: #FFF4CC;
  color: #C8102E;
}

.card small,
.card > a {
  color: #C8102E;
}

.card > a {
  border-bottom: 1px solid #FFC928;
}

.launch span {
  background: #C8102E;
}

/* How it works */
.steps b {
  color: #FFC928;
}

/* About section */
.about {
  background: #FFFFFF !important;
}

.seal {
  border: 1px solid #C8102E;
  outline: 1px solid #FFC928;
  background: #FFFFFF;
}

.seal strong {
  color: #171717;
}

.seal small {
  color: #C8102E;
}

/* Contact section */
.contact {
  background: #F5F5F5;
}

.contact-box {
  background: #171717;
  color: #FFFFFF;
}

.contact-side span,
.contact-side small {
  color: #FFC928;
}

/* Footer */
footer {
  background: #111111;
  color: #FFFFFF;
}

.foot .brand {
  color: #FFFFFF;
}

.copyright {
  border-top: 1px solid #FFFFFF30;
  color: #BBBBBB;
}

/* Mobile navigation */
@media(max-width:640px) {
  .nav nav {
    background: #FFFFFF;
  }

  .contact-side {
    border-left: 0;
    border-top: 1px solid #FFFFFF40;
  }
}
