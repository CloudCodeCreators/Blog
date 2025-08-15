---
title: 'Home'
date: 2023-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Cloud Code Creators
      text: Microsoft 365 Desired State Configuration | Modern Workplace | Automation | Cybersecurity
      primary_action:
        text: Learn More
        url: /about/
        icon: rocket-launch
      secondary_action:
        text: Contact Us
        url: /contact/
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"
      background:
        color: "navy"
        image:
          filename: bg-triangles.svg
          filters:
            brightness: 0.5

  - block: features
    id: features
    content:
      title: Expertise
      text: We help organizations automate, secure, and govern Microsoft 365 and hybrid environments.
      items:
        - name: M365DSC & Automation
          icon: code-bracket
          description: Predictable, scalable, compliant M365 environments using Infrastructure as Code with M365DSC and Azure DevOps.
        - name: Cybersecurity & Compliance
          icon: shield-check
          description: Security by design with compliance frameworks including BIO2, NIS, ISO 27001, SOC2, CIS.
        - name: Complex Exchange Migrations
          icon: arrows-right-left
          description: End-to-end migrations from on-premises Exchange to Exchange Online, ensuring security and compliance at each step.
        - name: Hybrid Infrastructure
          icon: cloud
          description: Deep experience in VMware, Hyper-V, Citrix, and Microsoft Stack to deliver seamless hybrid solutions.
        - name: Governance & Risk Management
          icon: scale
          description: Helping organizations meet governance and risk requirements with measurable, auditable controls.
        - name: Strategic IT Consulting
          icon: light-bulb
          description: Bridging the gap between technical complexity and business objectives for maximum impact.
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"

  - block: cta-card
    content:
      title: Ready to transform your Modern Workplace?
      text: Automate, secure, and govern your Microsoft 365 and hybrid environments with proven expertise.
      button:
        text: Contact Us
        url: /contact/
    design:
      card:
        css_class: "bg-primary-700"
---
