
:root {
  --bg: #081426;
  --panel: #10233d;
  --text: #f3f7ff;
  --muted: #9aabc2;
  --blue: #4da3ff;
  --cyan: #55d6e8;
  --line: rgba(158,190,226,.15);
  --font: 'DM Sans', sans-serif;
  --display: 'Space Grotesk', sans-serif;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: 90px;
}

body {
  font-family: var(--font);
  background: var(--bg);
  color: var(--text);
  line-height: 1.65;
  overflow-x: hidden;
}

a {
  color: inherit;
  text-decoration: none;
}

button {
  font: inherit;
}

.container {
  width: min(1120px, calc(100% - 48px));
  margin: auto;
}

.section {
  padding: 112px 0;
  position: relative;
}

.scroll-progress {
  position: fixed;
  top: 0;
  left: 0;
  height: 3px;
  width: 0;
  background: linear-gradient(90deg, var(--blue), var(--cyan));
  z-index: 1000;
}

/* NAVIGATION */

.site-header {
  height: 82px;
  position: sticky;
  top: 0;
  z-index: 100;
  background: rgba(8,20,38,.86);
  backdrop-filter: blur(18px);
  border-bottom: 1px solid var(--line);
}

.nav {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.brand {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  font-family: var(--display);
  font-weight: 700;
  letter-spacing: 1.3px;
  font-size: 14px;
}

.brand-mark {
  width: 34px;
  height: 34px;
  border-radius: 10px;
  background: linear-gradient(145deg,#55b8ff,#2875db);
  display: grid;
  place-items: center;
  color: #071529;
  font-size: 19px;
  box-shadow: 0 5px 22px #318ce94a;
}

.brand-dot {
  color: var(--cyan);
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 30px;
}

.nav-link {
  font-size: 12px;
  color: var(--muted);
  transition: .25s;
}

.nav-link:hover,
.nav-link.active {
  color: white;
}

.nav-contact {
  font-size: 12px;
  font-weight: 700;
  padding: 11px 17px;
  border: 1px solid #3c8fe7;
  border-radius: 7px;
  color: #b9dcff;
}

.menu-toggle {
  display: none;
  background: none;
  border: 0;
  color: white;
}

/* HERO */

.hero {
  min-height: 690px;
  display: flex;
  align-items: center;
  overflow: hidden;
  padding-top: 86px;
  padding-bottom: 105px;
  background:
    radial-gradient(ellipse at 76% 48%,#12345b50,transparent 42%),
    linear-gradient(180deg,#09172b,#081426);
}

.hero-grid {
  display: grid;
  grid-template-columns: 1.05fr .95fr;
  align-items: center;
  gap: 35px;
  position: relative;
  z-index: 2;
}

.availability {
  display: inline-flex;
  align-items: center;
  gap: 9px;
  border: 1px solid #4389bb55;
  background: #102b45a6;
  padding: 8px 13px;
  border-radius: 30px;
  color: #b8d8f3;
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 1.4px;
  margin-bottom: 36px;
}

.pulse {
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #5be0b2;
  box-shadow: 0 0 0 5px #5be0b21c;
  display: inline-block;
}

.eyebrow {
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 2.2px;
  color: var(--cyan);
  margin-bottom: 15px;
}

.hero h1 {
  font: 700 clamp(54px,7vw,86px)/.99 var(--display);
  letter-spacing: -4px;
}

.hero h1 span {
  color: var(--blue);
}

.hero-role {
  font: 500 20px var(--display);
  margin-top: 24px;
  color: #c9d7e8;
}

.hero-role span:first-child {
  color: var(--cyan);
}

.cursor {
  color: var(--cyan);
  animation: blink .8s infinite;
}

.hero-description {
  color: var(--muted);
  font-size: 14px;
  line-height: 1.9;
  max-width: 490px;
  margin-top: 17px;
}

.hero-actions {
  display: flex;
  gap: 12px;
  margin-top: 29px;
  flex-wrap: wrap;
}

.button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 17px;
  padding: 13px 19px;
  border-radius: 7px;
  font-size: 12px;
  font-weight: 700;
  transition: .25s;
}

.button:hover {
  transform: translateY(-3px);
}

.button-primary {
  background: linear-gradient(110deg,#3388eb,#42b9e9);
  color: #041426;
  box-shadow: 0 9px 25px #2788db30;
}

.button-ghost {
  border: 1px solid #607c9b66;
  color: #d7e4f4;
  background: #ffffff05;
}

.hero-social {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-top: 44px;
}

.hero-social > span {
  font-size: 9px;
  letter-spacing: 1.5px;
  color: #7288a2;
}

.hero-social a {
  width: 29px;
  height: 29px;
  border: 1px solid var(--line);
  border-radius: 50%;
  display: grid;
  place-items: center;
  font-size: 9px;
  color: #b8cce1;
}

/* CODE WINDOW */

.hero-art {
  height: 430px;
  position: relative;
  display: grid;
  place-items: center;
}

.hero-glow {
  position: absolute;
  border-radius: 50%;
  filter: blur(2px);
  pointer-events: none;
}

.glow-one {
  width: 350px;
  height: 350px;
  background: #1d75c51c;
  top: 20%;
  right: 8%;
}

.glow-two {
  width: 180px;
  height: 180px;
  background: #25c2d414;
  bottom: 4%;
  left: 10%;
}

.orbit {
  position: absolute;
  border: 1px solid #5bb7f51d;
  border-radius: 50%;
  transform: rotate(-25deg);
}

.orbit-a {
  width: 430px;
  height: 260px;
}

.orbit-b {
  width: 360px;
  height: 350px;
  transform: rotate(42deg);
}

.code-window {
  width: min(100%,440px);
  position: relative;
  z-index: 2;
  background: linear-gradient(145deg,#10233c,#0b1a2e);
  border: 1px solid #6ca8df3a;
  border-radius: 13px;
  box-shadow: 0 25px 80px #0007,0 0 55px #248cdb17;
  transform: perspective(900px) rotateY(-7deg) rotateX(3deg);
  overflow: hidden;
}

.window-top {
  height: 45px;
  border-bottom: 1px solid var(--line);
  display: flex;
  align-items: center;
  padding: 0 15px;
  gap: 13px;
  color: #8fa5bf;
  font-size: 10px;
}

.window-dots {
  display: flex;
  gap: 5px;
}

.window-dots i {
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #fa7373;
}

.window-dots i:nth-child(2) {
  background: #e9bd5e;
}

.window-dots i:nth-child(3) {
  background: #57cda1;
}

.window-lock {
  margin-left: auto;
}

.code-content {
  padding: 23px 16px 21px;
  font: 11px/2.05 monospace;
  color: #c4d3e6;
  white-space: nowrap;
}

.line-no {
  display: inline-block;
  width: 27px;
  color: #4f6885;
}

.code-purple { color: #d59bff; }
.code-blue { color: #6dbdff; }
.code-green { color: #8ee2bd; }

.window-footer {
  height: 31px;
  border-top: 1px solid var(--line);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 14px;
  color: #7790aa;
  font-size: 8px;
}

.floating-chip {
  position: absolute;
  z-index: 3;
  display: flex;
  align-items: center;
  gap: 8px;
  background: #142c49;
  border: 1px solid #6da8dc40;
  padding: 9px 12px;
  border-radius: 9px;
  box-shadow: 0 10px 30px #0005;
  font-size: 10px;
  color: #c8d8eb;
}

.floating-chip b {
  color: var(--cyan);
}

.chip-html { top: 52px; left: 2%; }
.chip-css { right: 0; top: 125px; }
.chip-js { bottom: 65px; left: 5%; }

.hero-art-caption {
  position: absolute;
  bottom: 4px;
  right: 0;
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 8px;
  letter-spacing: 1.5px;
  color: #6e8aa8;
}

.caption-line {
  width: 30px;
  height: 1px;
  background: var(--cyan);
}

.scroll-cue {
  position: absolute;
  bottom: 28px;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  align-items: center;
  gap: 10px;
  color: #6d829b;
  font-size: 8px;
  letter-spacing: 1.8px;
}

.mouse {
  width: 15px;
  height: 22px;
  border: 1px solid #6785a5;
  border-radius: 10px;
}

/* SECTION HEADINGS */

.section-heading {
  max-width: 640px;
  margin-bottom: 48px;
}

.section-heading h2 {
  font: 700 clamp(34px,5vw,48px)/1.15 var(--display);
  letter-spacing: -1.8px;
}

.section-heading h2 span {
  color: var(--blue);
}

.section-intro {
  color: var(--muted);
  font-size: 13px;
  line-height: 1.8;
  margin-top: 15px;
  max-width: 550px;
}

/* ABOUT */

.about-section,
.projects-section,
.contact-section {
  background: #0a192d;
}

.about-grid {
  display: grid;
  grid-template-columns: 1.1fr .9fr;
  gap: 25px;
}

.about-card {
  background: linear-gradient(145deg,#112641,#0e2037);
  border: 1px solid var(--line);
  padding: 34px;
  border-radius: 12px;
}

.about-icon {
  width: 40px;
  height: 40px;
  border-radius: 11px;
  background: #1d4770;
  color: var(--cyan);
  display: grid;
  place-items: center;
  font-size: 22px;
  margin-bottom: 24px;
}

.about-card p {
  color: var(--muted);
  font-size: 13px;
  line-height: 1.9;
  margin-bottom: 15px;
}

.about-card .about-lead {
  font: 500 19px/1.55 var(--display);
  color: #e3edf8;
}

.about-lead strong {
  color: var(--cyan);
}

.text-link {
  display: inline-flex;
  gap: 12px;
  color: #78baff;
  font-size: 12px;
  font-weight: 700;
}

.about-facts {
  display: grid;
  gap: 11px;
}

.fact-card {
  display: flex;
  gap: 17px;
  align-items: flex-start;
  padding: 17px 19px;
  background: #0e2036;
  border: 1px solid var(--line);
  border-radius: 9px;
}

.fact-number {
  font: 600 18px var(--display);
  color: var(--cyan);
}

.fact-card h3 {
  font: 600 14px var(--display);
}

.fact-card p {
  font-size: 11px;
  color: var(--muted);
}

.fact-note {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 13px 18px;
  border: 1px dashed #4d87b366;
  border-radius: 8px;
}

/* SKILLS */

.skills-grid {
  display: grid;
  grid-template-columns: repeat(4,1fr);
  gap: 13px;
}

.skill-card {
  position: relative;
  min-height: 165px;
  padding: 22px;
  background: linear-gradient(145deg,#102540,#0d1d32);
  border: 1px solid var(--line);
  border-radius: 10px;
  transition: .25s;
}

.skill-card:hover {
  transform: translateY(-6px);
  border-color: #4da3ff75;
}

.skill-symbol {
  width: 39px;
  height: 39px;
  display: grid;
  place-items: center;
  border-radius: 9px;
  background: #193c60;
  font: 700 17px var(--display);
  color: #7ccaff;
  margin-bottom: 17px;
}

.css-symbol { color: #a8a1ff; }
.js-symbol { color: #f3d76a; }
.python-symbol { color: #ffe08a; }
.c-symbol { color: #8bd9ed; }
.cpp-symbol { color: #8bd9ed; }

.skill-card h3 {
  font: 600 15px var(--display);
}

.skill-card p {
  font-size: 10px;
  color: var(--muted);
}

.skill-tag {
  position: absolute;
  right: 13px;
  top: 15px;
  font-size: 8px;
  letter-spacing: 1px;
  color: #7895b5;
}

.skills-footnote {
  margin-top: 24px;
  color: #91a9c4;
  font-size: 11px;
  display: flex;
  align-items: center;
  gap: 10px;
}

/* PROJECTS */

.project-filters {
  display: flex;
  gap: 9px;
  margin-bottom: 25px;
  flex-wrap: wrap;
}

.filter-btn {
  background: transparent;
  border: 1px solid var(--line);
  border-radius: 30px;
  padding: 8px 14px;
  color: #9aabc2;
  font-size: 10px;
  cursor: pointer;
}

.filter-btn:hover,
.filter-btn.active {
  background: #173554;
  border-color: #438ed0;
  color: #e7f3ff;
}

.projects-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
}

.project-card {
  background: #10233b;
  border: 1px solid var(--line);
  border-radius: 12px;
  overflow: hidden;
  transition: .25s;
}

.project-card:hover {
  transform: translateY(-5px);
}

.project-card.is-hidden {
  display: none;
}

.project-visual {
  height: 220px;
  position: relative;
  display: grid;
  place-items: center;
}

.bill-visual {
  background: radial-gradient(circle,#1a4d78,#10243d 68%);
}

.electric-visual {
  background: radial-gradient(circle,#174a5a,#10243d 70%);
}

.receipt {
  width: 190px;
  background: #eaf2f9;
  color: #1b334c;
  padding: 15px 16px 18px;
  position: relative;
  box-shadow: 0 15px 35px #0005;
  transform: rotate(-4deg);
  font-size: 9px;
}

.receipt-head,
.receipt-row,
.receipt-total {
  display: flex;
  justify-content: space-between;
}

.receipt-line {
  height: 1px;
  background: #9cabb9;
  margin: 10px 0;
}

.receipt-row {
  padding: 4px 0;
  color: #617487;
}

.receipt-stamp {
  position: absolute;
  right: -27px;
  bottom: 37px;
  border: 2px solid #1599bf;
  color: #1599bf;
  padding: 5px 7px;
  transform: rotate(-13deg);
}

.circuit-board {
  width: 235px;
  height: 130px;
  border: 1px solid #50c8d866;
  border-radius: 8px;
  background: #0c2639;
  position: relative;
  padding: 18px;
  box-shadow: 0 0 35px #37c8d51c;
}

.circuit-title {
  font: 700 16px var(--display);
  color: #d8f8ff;
}

.circuit-bottom {
  position: absolute;
  bottom: 10px;
  right: 13px;
  color: #70a9b5;
  font-size: 7px;
}

.visual-label {
  position: absolute;
  bottom: 15px;
  left: 17px;
  font-size: 8px;
  color: #a6c9e8;
}

.project-info {
  padding: 22px;
}

.project-topline {
  display: flex;
  justify-content: space-between;
  color: #78a6ce;
  font-size: 8px;
}

.project-info h3 {
  font: 600 20px var(--display);
  margin: 12px 0 8px;
}

.project-info p {
  font-size: 11px;
  color: var(--muted);
  line-height: 1.8;
}

.project-bottom {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-top: 1px solid var(--line);
  padding-top: 15px;
  margin-top: 15px;
}

.project-tech {
  display: flex;
  gap: 7px;
}

.project-tech span {
  padding: 5px 8px;
  border-radius: 4px;
  background: #1b3857;
  color: #9fc7e9;
  font-size: 8px;
}

.project-arrow {
  color: var(--cyan);
}

.project-disclaimer {
  font-size: 10px;
  color: #7188a3;
  margin-top: 18px;
}

/* EDUCATION */

.education-timeline {
  position: relative;
  max-width: 900px;
  margin: 0 auto;
  padding-left: 28px;
  display: grid;
  gap: 14px;
}

.education-timeline:before {
  content: "";
  position: absolute;
  left: 51px;
  top: 30px;
  bottom: 35px;
  width: 1px;
  background: linear-gradient(var(--cyan),#3c75a555);
}

.education-step {
  position: relative;
  display: grid;
  grid-template-columns: 48px 1fr 110px;
  gap: 22px;
  align-items: start;
  padding: 25px 28px;
  background: linear-gradient(110deg,#102641,#0d1e33);
  border: 1px solid var(--line);
  border-radius: 11px;
}

.timeline-marker {
  position: relative;
  z-index: 1;
  width: 46px;
  height: 46px;
  display: grid;
  place-items: center;
  border: 1px solid #4d9ed477;
  border-radius: 50%;
  background: #102b48;
  color: var(--cyan);
}

.education-step-content h3 {
  font: 600 19px var(--display);
  margin: 8px 0 4px;
}

.education-step-content p {
  font-size: 11px;
  color: var(--muted);
  line-height: 1.8;
  margin-top: 7px;
}

.education-step-content .education-level {
  color: #9bcfff;
  font-weight: 600;
}

.education-status {
  font-size: 8px;
  letter-spacing: 1.5px;
  color: #62d8b0;
}

.education-date {
  justify-self: end;
  color: #7795b5;
  font-size: 8px;
  letter-spacing: 1.4px;
}

.current-step {
  border-color: #4da3ff66;
  background: linear-gradient(110deg,#123052,#0d2139);
}

.current-step .timeline-marker {
  background: linear-gradient(145deg,#55b8ff,#2875db);
  color: #071529;
}

/* CONTACT */

.contact-section {
  padding-top: 90px;
  padding-bottom: 90px;
}

.contact-panel {
  min-height: 350px;
  position: relative;
  overflow: hidden;
  border: 1px solid #438ed044;
  border-radius: 15px;
  background: linear-gradient(115deg,#102d4c,#10213a 65%,#12354c);
  padding: 55px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.contact-content {
  position: relative;
  z-index: 2;
  max-width: 560px;
}

.contact-content h2 {
  font: 700 clamp(36px,5vw,54px)/1.1 var(--display);
  letter-spacing: -2px;
}

.contact-content h2 span {
  color: var(--cyan);
}

.contact-content > p:not(.eyebrow) {
  font-size: 12px;
  color: #a4b8ce;
  margin-top: 15px;
  line-height: 1.8;
}

.contact-actions {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  margin-top: 24px;
}

.contact-decoration {
  width: 230px;
  height: 230px;
  position: relative;
  display: grid;
  place-items: center;
}

.contact-orbit {
  position: absolute;
  inset: 10px;
  border: 1px solid #65c9ed5c;
  border-radius: 50%;
}

.contact-monogram {
  font: 700 53px var(--display);
  color: #d6efff;
}

.contact-monogram span {
  color: var(--cyan);
}

/* FOOTER */

.footer {
  background: #071222;
  border-top: 1px solid var(--line);
  padding: 27px 0 18px;
}

.footer-inner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 15px;
}

.footer-inner p {
  font-size: 10px;
  color: #8196af;
}

.back-top {
  font-size: 8px;
  letter-spacing: 1.4px;
  color: #91bce2;
}

.copyright {
  border-top: 1px solid var(--line);
  margin-top: 22px;
  padding-top: 15px;
  color: #617891;
  font-size: 9px;
}

/* ANIMATIONS */

.reveal {
  opacity: 0;
  transform: translateY(22px);
  transition: opacity .7s ease, transform .7s ease;
}

.reveal.visible {
  opacity: 1;
  transform: translateY(0);
}

@keyframes blink {
  50% { opacity: 0; }
}

/* RESPONSIVE DESIGN */

@media(max-width:900px) {
  .nav-links { gap: 18px; }
  .hero-grid { grid-template-columns: 1fr 1fr; gap: 10px; }
  .skills-grid { grid-template-columns: repeat(3,1fr); }
}

@media(max-width:680px) {
  .container {
    width: min(100% - 36px,520px);
  }

  .section { padding: 78px 0; }

  .site-header { height: 70px; }

  .menu-toggle {
    display: flex;
    flex-direction: column;
    gap: 5px;
    padding: 8px;
  }

  .menu-toggle span {
    display: block;
    width: 23px;
    height: 2px;
    background: #dcecff;
  }

  .nav-links {
    display: none;
    position: absolute;
    top: 69px;
    left: 0;
    right: 0;
    background: #0b1b30;
    padding: 20px 25px;
    flex-direction: column;
    align-items: stretch;
  }

  .nav-links.open { display: flex; }

  .nav-link {
    padding: 12px 0;
    border-bottom: 1px solid var(--line);
  }

  .nav-contact {
    margin-top: 15px;
    text-align: center;
  }

  .hero {
    min-height: auto;
    padding-top: 75px;
    padding-bottom: 75px;
  }

  .hero-grid {
    grid-template-columns: 1fr;
    gap: 40px;
  }

  .hero h1 { font-size: 62px; }

  .hero-art {
    height: 330px;
    margin: 0 -8px;
  }

  .code-window {
    width: min(100%,390px);
    transform: none;
  }

  .code-content {
    font-size: 9px;
    padding: 18px 10px;
  }

  .orbit-a { width: 340px; height: 230px; }
  .orbit-b { width: 290px; height: 300px; }

  .section-heading h2 { font-size: 36px; }

  .about-grid { grid-template-columns: 1fr; }

  .about-card { padding: 25px; }

  .skills-grid {
    grid-template-columns: repeat(2,1fr);
    gap: 10px;
  }

  .projects-grid { grid-template-columns: 1fr; }

  .project-visual { height: 205px; }

  .education-timeline { padding-left: 0; }

  .education-timeline:before { left: 22px; }

  .education-step {
    grid-template-columns: 44px 1fr;
    gap: 14px;
    padding: 20px 15px;
  }

  .timeline-marker {
    width: 42px;
    height: 42px;
  }

  .education-date {
    grid-column: 2;
    justify-self: start;
  }

  .contact-panel {
    padding: 32px 24px;
    min-height: 0;
  }

  .contact-decoration { display: none; }

  .contact-content h2 { font-size: 42px; }

  .contact-actions {
    flex-direction: column;
    align-items: stretch;
  }

  .footer-inner {
    flex-wrap: wrap;
  }

  .footer-inner p {
    order: 3;
    width: 100%;
  }

  .back-top { margin-left: auto; }
}

@media(prefers-reduced-motion:reduce) {
  html { scroll-behavior: auto; }
  *, *:before, *:after {
    animation-duration: .01ms !important;
    transition-duration: .01ms !important;
  }
  .reveal {
    opacity: 1;
    transform: none;
  }
}
