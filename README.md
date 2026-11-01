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
}
