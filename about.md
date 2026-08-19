---
layout: default
title: About
permalink: /about/
---

<style>

/* =========================
   GLOBAL
========================= */

html {
  background: #080808;
}

body {
  background: #080808 !important;
  color: #f5f5f5 !important;
}

.page-content {
  background: #080808 !important;
}

.wrapper {
  max-width: 1150px;
}

/* =========================
   MINIMA HEADER
========================= */

.site-header {
  background: rgba(8, 8, 8, 0.95) !important;
  border-bottom: 1px solid #242424 !important;
}

.site-title,
.site-title:visited {
  color: #ffffff !important;
  font-weight: 700;
}

.site-nav {
  background: #080808 !important;
}

.site-nav .page-link {
  color: #aaaaaa !important;
}

.site-nav .page-link:hover {
  color: #7cff6b !important;
  text-decoration: none;
}

/* =========================
   FOOTER
========================= */

.site-footer {
  background: #080808 !important;
  border-top: 1px solid #242424 !important;
  color: #777777 !important;
}

.site-footer a {
  color: #aaaaaa !important;
}

/* =========================
   ABOUT HERO
========================= */

.about-hero {
  padding: 110px 0 90px;
}

.about-label {
  color: #7cff6b;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 4px;
  margin-bottom: 20px;
}

.about-hero h1 {
  color: #ffffff;
  font-size: clamp(48px, 7vw, 78px);
  line-height: 1.05;
  letter-spacing: -3px;
  margin: 0 0 30px;
}

.about-hero h1 span {
  color: #666666;
}

.about-intro {
  max-width: 850px;
  color: #aaaaaa;
  font-size: 18px;
  line-height: 1.9;
}

.about-intro strong {
  color: #ffffff;
}

/* =========================
   SECTIONS
========================= */

.about-section {
  padding: 80px 0;
  border-top: 1px solid #222222;
}

.section-heading {
  display: flex;
  align-items: center;
  gap: 14px;
  margin-bottom: 35px;
}

.section-number {
  color: #7cff6b;
  font-size: 12px;
  font-weight: 700;
}

.section-heading h2 {
  color: #ffffff;
  font-size: 29px;
  margin: 0;
  letter-spacing: -1px;
}

/* =========================
   SKILL CARDS
========================= */

.skill-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 14px;
}

.skill-card {
  background: #111111;
  border: 1px solid #242424;
  border-radius: 12px;
  padding: 24px 26px;
  transition: 0.25s;
}

.skill-card:hover {
  background: #161616;
  border-color: #444444;
  transform: translateY(-3px);
}

.skill-card span {
  color: #7cff6b;
  font-size: 11px;
  font-weight: 700;
}

.skill-card h3 {
  color: #ffffff;
  margin: 8px 0 0;
  font-size: 17px;
}

/* =========================
   EXPLORING
========================= */

.explore-list {
  border-top: 1px solid #222222;
}

.explore-item {
  display: grid;
  grid-template-columns: 60px 1fr;
  padding: 22px 10px;
  border-bottom: 1px solid #222222;
}

.explore-number {
  color: #666666;
  font-size: 12px;
}

.explore-item p {
  color: #dddddd;
  margin: 0;
}

/* =========================
   APPROACH
========================= */

.approach-flow {
  margin: 35px 0;
  padding: 30px;

  background: #111111;
  border: 1px solid #242424;
  border-radius: 12px;

  color: #ffffff;

  font-size: clamp(16px, 2vw, 21px);
  font-weight: 600;
  text-align: center;

  letter-spacing: 0.3px;
}

.approach-flow span {
  color: #7cff6b;
  margin: 0 8px;
}

.about-text {
  max-width: 850px;
  color: #aaaaaa;
  font-size: 16px;
  line-height: 1.9;
}

.about-text strong {
  color: #ffffff;
}

/* =========================
   TOPICS
========================= */

.topic-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 30px;
}

.topic-tags span {
  background: #111111;
  border: 1px solid #303030;
  border-radius: 20px;
  padding: 7px 13px;

  color: #aaaaaa;
  font-size: 12px;
}

/* =========================
   PROFILE FOOTER
========================= */

.profile-footer {
  padding: 80px 0 110px;
  border-top: 1px solid #222222;
}

.profile-footer-label {
  color: #7cff6b;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 3px;
}

.profile-footer h2 {
  color: #ffffff;
  font-size: 35px;
  margin: 10px 0 25px;
}

.profile-links {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
}

.profile-button {
  display: inline-block;

  padding: 12px 20px;

  border: 1px solid #333333;
  border-radius: 7px;

  background: #111111;

  color: #ffffff !important;
  text-decoration: none !important;

  transition: 0.2s;
}

.profile-button:hover {
  background: #181818;
  border-color: #7cff6b;
}

/* =========================
   MOBILE
========================= */

@media (max-width: 800px) {

  .about-hero {
    padding: 70px 0;
  }

  .about-hero h1 {
    font-size: 46px;
    letter-spacing: -2px;
  }

  .about-intro {
    font-size: 16px;
  }

  .skill-grid {
    grid-template-columns: 1fr;
  }

  .about-section {
    padding: 60px 0;
  }

  .explore-item {
    grid-template-columns: 40px 1fr;
  }

}

</style>


<!-- =========================
     HERO
========================= -->

<section class="about-hero">

  <div class="about-label">
    ABOUT ME
  </div>

  <h1>
    Network Engineer.<br>
    <span>Analyze. Validate. Improve.</span>
  </h1>

  <div class="about-intro">

    Hi, I’m <strong>Jaewoong Wang</strong>, a Network Engineer
    based in South Korea with around 10 years of experience
    working with enterprise, data center, and service provider networks.

    <br><br>

    My main focus is not only on configuring networks,
    but also on understanding how they behave during
    <strong>failures, changes, and unexpected conditions.</strong>

    <br><br>

    I analyze network issues by separating them into routing,
    switching, redundancy, physical connectivity, and service impact,
    and I use lab environments to reproduce and verify behavior
    before applying changes to production networks.

  </div>

</section>


<!-- =========================
     WHAT I WORK WITH
========================= -->

<section class="about-section">

  <div class="section-heading">
    <span class="section-number">01</span>
    <h2>What I Work With</h2>
  </div>

  <div class="skill-grid">

    <div class="skill-card">
      <span>NETWORK</span>
      <h3>Data Center & Service Provider Networks</h3>
    </div>

    <div class="skill-card">
      <span>ROUTING</span>
      <h3>BGP / OSPF / EIGRP</h3>
    </div>

    <div class="skill-card">
      <span>PLATFORM</span>
      <h3>Cisco Nexus / Catalyst</h3>
    </div>

    <div class="skill-card">
      <span>TROUBLESHOOTING</span>
      <h3>Network Troubleshooting & Verification</h3>
    </div>

    <div class="skill-card">
      <span>AUTOMATION</span>
      <h3>Python / REST API</h3>
    </div>

    <div class="skill-card">
      <span>OBSERVABILITY</span>
      <h3>Prometheus / Grafana / Telemetry</h3>
    </div>

  </div>

</section>


<!-- =========================
     CURRENTLY EXPLORING
========================= -->

<section class="about-section">

  <div class="section-heading">
    <span class="section-number">02</span>
    <h2>What I’m Currently Exploring</h2>
  </div>

  <div class="explore-list">

    <div class="explore-item">
      <span class="explore-number">01</span>
      <p>VXLAN EVPN architecture and Multi-Site design</p>
    </div>

    <div class="explore-item">
      <span class="explore-number">02</span>
      <p>Network automation using Python</p>
    </div>

    <div class="explore-item">
      <span class="explore-number">03</span>
      <p>API-based network tools</p>
    </div>

    <div class="explore-item">
      <span class="explore-number">04</span>
      <p>Infrastructure monitoring and telemetry</p>
    </div>

    <div class="explore-item">
      <span class="explore-number">05</span>
      <p>Automated pre/post network change validation</p>
    </div>

  </div>

</section>


<!-- =========================
     APPROACH
========================= -->

<section class="about-section">

  <div class="section-heading">
    <span class="section-number">03</span>
    <h2>How I Approach Network Engineering</h2>
  </div>

  <div class="approach-flow">
    Analyze
    <span>→</span>
    Hypothesize
    <span>→</span>
    Reproduce
    <span>→</span>
    Compare
    <span>→</span>
    Isolate
    <span>→</span>
    Validate
    <span>→</span>
    Apply
  </div>

  <div class="about-text">

    Rather than assuming a single cause,
    I try to isolate variables and verify each part
    of the network step by step.

    <br><br>

    For network changes, I prefer to define the
    <strong>expected behavior and failure conditions first</strong>,
    validate them in a lab whenever possible,
    and then apply the change to production
    with a clear rollback plan.

  </div>

</section>


<!-- =========================
     THIS SITE
========================= -->

<section class="about-section">

  <div class="section-heading">
    <span class="section-number">04</span>
    <h2>This Site</h2>
  </div>

  <div class="about-text">

    This site is where I document what I learn and verify
    through hands-on labs and real-world network engineering experience.

    <br><br>

    Rather than simply documenting commands,
    I try to record <strong>why a network behaves the way it does</strong>,
    how it can fail, and how that behavior can be verified.

  </div>

  <div class="topic-tags">

    <span>Routing & Switching</span>
    <span>Data Center</span>
    <span>SDN</span>
    <span>Network Automation</span>
    <span>Monitoring & Telemetry</span>
    <span>Network Design</span>
    <span>Verification</span>

  </div>

</section>


<!-- =========================
     PROFILE FOOTER
========================= -->

<section class="profile-footer">

  <div class="profile-footer-label">
    CERTIFICATION
  </div>

  <h2>
    CCIE Enterprise Infrastructure
  </h2>

  <div class="profile-links">

    <a href="https://github.com/w2jay"
       target="_blank"
       rel="noopener noreferrer"
       class="profile-button">
      GitHub ↗
    </a>

    <a href="{{ '/projects/' | relative_url }}"
       class="profile-button">
      View Projects →
    </a>

  </div>

</section>
