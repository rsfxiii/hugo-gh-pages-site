---
title: "Ryan Ferguson"
# Profile settings
profileImage: "images/headshot.jpeg"        # path under static/
name: "Ryan Ferguson"
description: "DevOps, Cloud & Site Reliability Expert"
socials:
  # - url: "https://github.com/rsfxiii"
  #   icon: "fab fa-github"
  # - url: "https://linkedin.com/in/ryanshawferguson"
  #   icon: "fab fa-linkedin"

# Link cards
links:
  # - href: "https://raijinn.xyz"
  #   icon: "fas fa-globe"
  #   title: "Personal Website"
  #   description: "Check out my portfolio"
  - href: "https://raijinn.substack.com"
    icon: "fas fa-blog"
    title: "My Blog"
    description: "Read my latest articles on Substack"
  - href: "https://github.com/rsfxiii"
    icon: "fab fa-github"
    title: "GitHub"
    description: "Explore my open-source projects"
  - href: "https://linkedin.com/in/ryanshawferguson"
    icon: "fab fa-linkedin"
    title: "LinkedIn"
    description: "Browse my employment history"
  - href: "mailto:ryan@raijinn.xyz"
    icon: "fas fa-envelope"
    title: "Contact Me"
    description: "For recruitment, collaboration, or consultation"

# Messaging Etiquette. You can add new rules as per your needs.
messaging:
  title: "Messaging Etiquette"
  items:
    - icon: "fas fa-check-circle"
      color: "text-green-400"
      text: "Please include context about why you're reaching out and how I can help."
    - icon: "fas fa-check-circle"
      color: "text-green-400"
      text: "For collaboration requests, include details about the project scope and timeline."
    - icon: "fas fa-check-circle"
      color: "text-green-400"
      text: "I typically respond within 2-3 business days for professional inquiries."
    - icon: "fas fa-times-circle"
      color: "text-red-400"
      text: "Please don't send unsolicited sales pitches."


#  REMOVE "How to Customize This Page" section by removing the line "{{ partial "Instructions.html" . }}" in index.html file under layouts/


# About section (optional section)

about:
  title: "About Me"
  sections:
    - heading: "Professional Background"
      content: |
        I'm a seasoned Infrastructure Engineer with over six years of experience architecting secure, scalable, and cost-efficient cloud platforms. I specialize in Kubernetes (EKS), CI/CD automation, infrastructure as code, and cloud-native observability—enabling engineering teams to move faster without compromising reliability.
        <br><br>
        At Groundfloor Finance, I designed and governed a multi-tenant EKS environment serving over 25 namespaces with granular IAM and network policies. I built PR-driven Helm-based Kubernetes sandboxes, orchestrated via GitHub Actions and shell scripts, that emulate production environments in minutes. I’ve reduced cloud costs by up to 60% through proactive orphaned-resource cleanup, and modernized mobile CI/CD workflows from Jenkins to GitHub Actions on native macOS runners—cutting build times and improving maintainability.
        <br><br>
        Previously, at OpSourced, I led infrastructure standardization across 20+ customer environments, implemented disaster recovery automation for enterprise clients, and migrated critical systems to AWS-based containerized stacks. I've also contributed to microservice deployments, CDN automation, and support tooling during my tenure at Mailchimp.
        <br><br>
        Whether building resilient infrastructure, mentoring junior engineers, or bridging silos between ops and dev teams, I bring a pragmatic, automation-first approach to system reliability and delivery velocity.
    - heading: "Current Focus"
      content: "Currently building an online presence showcasing open-source tooling, technical deep-dives, and otherwise sharing things I've learned."
    - heading: "Personal Interests"
      content: "When not coding, I enjoy running guitar scales, reading critical analyses of <i>The Sopranos</i>, playing video games, and figuring out something interesting to code or write about."
---