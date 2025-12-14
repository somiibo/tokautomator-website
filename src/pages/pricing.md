---
### ALL PAGES ###
layout: blueprint/pricing
permalink: /pricing

### PAGE CONFIG ###
# Pricing Section
pricing:
  price_per_unit:
    enabled: false
  definitions:
    - id: "modules"
      definition: "Modules are automation tasks that run simultaneously. More modules = faster growth."
    - id: "profiles"
      definition: "Profiles are separate TikTok accounts or browser sessions you can automate."
    - id: "runtime"
      definition: "How long the automation can run per session."
    - id: "settings"
      definition: "Access to advanced targeting and behavior customization options."
    - id: "proxies"
      definition: "Proxies protect your account by masking your IP address. Premium proxies are faster and more reliable."
    - id: "support"
      definition: "Get help when you need it through our support channels."
  plans:
    - id: "basic"
      name: "Basic"
      tagline: "best for getting started"
      url: "https://somiibo.com/download"
      pricing:
        monthly: 0
        annually: 0
      features:
        # Common features
        - id: "modules"
          name: "Concurrent modules"
          value: 2
          icon: "cubes"
        - id: "profiles"
          name: "Profiles"
          value: 3
          icon: "users"
        - id: "runtime"
          name: "Runtime"
          value: "30 min/session"
          icon: "clock"
        - id: "settings"
          name: "Module settings"
          value: "Most"
          icon: "sliders"
        - id: "proxies"
          name: "Proxies"
          value: "Basic rotating"
          icon: "shield"
        # Additional features
        - id: "support"
          name: "Support"
          value: "Discord"
          icon: "discord"

    - id: "starter"
      name: "Starter"
      tagline: "best for individuals"
      url: "https://somiibo.com/pricing?plan=starter"
      pricing:
        monthly: 15
        annually: 150
      features:
        # Common features
        - id: "modules"
          name: "Concurrent modules"
          value: 5
          icon: "cubes"
        - id: "profiles"
          name: "Profiles"
          value: 3
          icon: "users"
        - id: "runtime"
          name: "Runtime"
          value: "Unlimited"
          icon: "clock"
        - id: "settings"
          name: "Module settings"
          value: "All"
          icon: "sliders"
        - id: "proxies"
          name: "Proxies"
          value: "Basic rotating"
          icon: "shield"
        # Additional features
        - id: "ads"
          name: "Ads"
          value: "No ads"
          icon: "ban"
        - id: "support"
          name: "Support"
          value: "Email"
          icon: "envelope"

    - id: "pro"
      name: "Pro"
      tagline: "best for creators"
      url: "https://somiibo.com/pricing?plan=pro"
      popular: true
      pricing:
        monthly: 36
        annually: 360
      features:
        # Common features
        - id: "modules"
          name: "Concurrent modules"
          value: 10
          icon: "cubes"
        - id: "profiles"
          name: "Profiles"
          value: 5
          icon: "users"
        - id: "runtime"
          name: "Runtime"
          value: "Unlimited"
          icon: "clock"
        - id: "settings"
          name: "Module settings"
          value: "All"
          icon: "sliders"
        - id: "proxies"
          name: "Proxies"
          value: "Basic rotating"
          icon: "shield"

    - id: "max"
      name: "Max"
      tagline: "best for agencies"
      url: "https://somiibo.com/pricing?plan=max"
      pricing:
        monthly: 72
        annually: 720
      features:
        # Common features
        - id: "modules"
          name: "Concurrent modules"
          value: "Unlimited"
          icon: "cubes"
        - id: "profiles"
          name: "Profiles"
          value: "Unlimited"
          icon: "users"
        - id: "runtime"
          name: "Runtime"
          value: "Unlimited"
          icon: "clock"
        - id: "settings"
          name: "Module settings"
          value: "All"
          icon: "sliders"
        - id: "proxies"
          name: "Proxies"
          value: "Premium rotating"
          icon: "shield-halved"
        # Additional features
        - id: "support"
          name: "Support"
          value: "24/7 live chat"
          icon: "headset"

# Feature Comparison Section
feature_comparison:
  superheadline:
    icon: "table"
    text: "Compare"
  headline: "Compare all"
  headline_accent: "features"
  subheadline: "See exactly what's included in each plan"

# Social Proof Section
social_proof:
  items:
    - number: "500K+"
      label: "Active users"
      sublabel: "Worldwide"
    - number: "#1"
      label: "TikTok tool"
      sublabel: "2024"
    - number: "4.8"
      label: "User rating"
      show_stars: true
      star_color: "warning"
    - number: "50M+"
      label: "Followers gained"
      sublabel: "For users"

# CTA Section
cta:
  superheadline:
    icon: "comments"
    text: "Questions?"
  headline: "Need help choosing a"
  headline_accent: "plan?"
  subheadline: "Our team is here to help you find the perfect fit"
  button:
    text: "Contact us"
    icon: "envelope"
    href: "/contact"

# Testimonials Section
testimonials:
  superheadline:
    icon: "megaphone"
    text: "Testimonials"
  headline: "Users love"
  headline_accent: "{{ site.brand.name }}"
  subheadline: "See what our customers have to say"
  items:
    - quote: "The Pro plan is perfect for my needs. I've grown from 5K to 100K followers!"
      author: "Sarah Kim"
      role: "Dance Creator"
      company: "@sarahkim"
      initial: "S"
    - quote: "Best investment for my business. The automation saves me hours every day."
      author: "David Martinez"
      role: "E-commerce Owner"
      company: "@davidm"
      initial: "D"
    - quote: "Started with Basic, now on Max. The growth has been incredible!"
      author: "Emily Chen"
      role: "Lifestyle Influencer"
      company: "@emilychen"
      initial: "E"

# FAQs Section
faqs:
  superheadline:
    icon: "circle-question"
    text: "FAQs"
  headline: "Frequently asked"
  headline_accent: "questions"
  subheadline: "Everything you need to know about {{ site.brand.name }} pricing"
  items:
    - question: "Is there a free trial?"
      answer: "Yes! The Basic plan is completely free with no credit card required. You can use it forever to try out {{ site.brand.name }} before upgrading to a paid plan."
    - question: "Can I change plans anytime?"
      answer: "Absolutely! You can upgrade or downgrade your plan at any time. Changes take effect immediately, and we'll prorate any differences."
    - question: "What payment methods do you accept?"
      answer: "We accept all major credit cards (Visa, MasterCard, American Express), PayPal, and cryptocurrency payments."
    - question: "Is my TikTok account safe?"
      answer: "Yes! {{ site.brand.name }} uses human-like behavior patterns, smart rate limiting, and follows TikTok's guidelines. We've helped 500K+ users grow safely."
    - question: "What are modules and profiles?"
      answer: "Modules are automation tasks (like following, liking, commenting) that run simultaneously. Profiles are separate TikTok accounts you can manage. More modules = faster growth!"
    - question: "Do you offer refunds?"
      answer: "Yes, we offer a 7-day money-back guarantee on all paid plans. If you're not satisfied, contact us for a full refund."
---
