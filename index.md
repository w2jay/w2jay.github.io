---
layout: default
title: Home
---

<section class="hero">

  <div class="hero-badge">
    NETWORK ENGINEER
  </div>

  <h1>
    Building Reliable<br>
    <span>Network Infrastructure.</span>
  </h1>

  <p class="hero-description">
    Data Center · Service Provider · Network Automation
  </p>

  <p class="hero-text">
    Architecture, troubleshooting, validation and automation
    for modern network infrastructure.
  </p>

  <div class="hero-actions">
    <a href="/projects/" class="button primary">
      View Projects
    </a>

    <a href="https://github.com/w2jay"
       target="_blank"
       class="button secondary">
      GitHub
    </a>
  </div>

</section>


<section class="section">

  <div class="section-title">
    <span>01</span>
    <h2>Areas of Interest</h2>
  </div>

  <div class="cards">

    <div class="card">
      <div class="card-number">01</div>
      <h3>Routing & Switching</h3>
      <p>
        BGP, OSPF, STP, HSRP, VRRP and routing architecture.
      </p>
    </div>

    <div class="card">
      <div class="card-number">02</div>
      <h3>Data Center</h3>
      <p>
        Cisco Nexus, vPC, ACI and highly available
        data center architectures.
      </p>
    </div>

    <div class="card">
      <div class="card-number">03</div>
      <h3>VXLAN EVPN</h3>
      <p>
        BGP EVPN control plane, VXLAN Fabric
        and Multi-Site architecture.
      </p>
    </div>

    <div class="card">
      <div class="card-number">04</div>
      <h3>Automation</h3>
      <p>
        Python, REST API, NETCONF, RESTCONF
        and network automation.
      </p>
    </div>

    <div class="card">
      <div class="card-number">05</div>
      <h3>Observability</h3>
      <p>
        Telemetry, Prometheus, Grafana
        and infrastructure monitoring.
      </p>
    </div>

    <div class="card">
      <div class="card-number">06</div>
      <h3>Troubleshooting</h3>
      <p>
        Packet analysis, failure reproduction
        and root-cause analysis.
      </p>
    </div>

  </div>

</section>


<section class="section">

  <div class="section-title">
    <span>02</span>
    <h2>Selected Projects</h2>
  </div>

  <div class="projects">

    <a href="/posts/vxlan-evpn/" class="project">

      <div class="project-index">
        01
      </div>

      <div class="project-content">
        <h3>VXLAN EVPN Multi-Site</h3>

        <p>
          Architecture design and BGP EVPN
          control-plane validation.
        </p>

        <div class="tags">
          <span>VXLAN</span>
          <span>EVPN</span>
          <span>BGP</span>
          <span>Nexus</span>
        </div>
      </div>

      <div class="project-arrow">
        ↗
      </div>

    </a>


    <a href="/posts/vpc-lacp/" class="project">

      <div class="project-index">
        02
      </div>

      <div class="project-content">
        <h3>vPC / LACP Failure Analysis</h3>

        <p>
          Failure reproduction and analysis
          of LACP System-ID and timer behavior.
        </p>

        <div class="tags">
          <span>vPC</span>
          <span>LACP</span>
          <span>Troubleshooting</span>
        </div>
      </div>

      <div class="project-arrow">
        ↗
      </div>

    </a>


    <a href="/posts/network-monitoring/" class="project">

      <div class="project-index">
        03
      </div>

      <div class="project-content">
        <h3>Network Observability Stack</h3>

        <p>
          Monitoring network infrastructure using
          Telegraf, Prometheus and Grafana.
        </p>

        <div class="tags">
          <span>Telemetry</span>
          <span>Grafana</span>
          <span>Prometheus</span>
        </div>
      </div>

      <div class="project-arrow">
        ↗
      </div>

    </a>

  </div>

</section>


<section class="section">

  <div class="section-title">
    <span>03</span>
    <h2>Latest Articles</h2>
  </div>

  <div class="articles">

    {% for post in site.posts limit:5 %}

    <a href="{{ post.url | relative_url }}" class="article">

      <div>
        <span class="article-date">
          {{ post.date | date: "%Y.%m.%d" }}
        </span>

        <h3>
          {{ post.title }}
        </h3>
      </div>

      <span class="article-arrow">
        →
      </span>

    </a>

    {% endfor %}

  </div>

</section>
