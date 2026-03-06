---
title: 'iPlaces'
date: 2024-01-01
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Discover Amazing Places Around the World
      text: Your gateway to extraordinary destinations, hidden gems, and unforgettable experiences.
      primary_action:
        text: Start Exploring
        url: /#discover
        icon: rocket-launch
      secondary_action:
        text: Learn More
        url: /#features
      announcement:
        text: "New: AI-powered place recommendations are here."
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "#0f4c3a"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "50K+"
          description: |
            Places discovered
            worldwide
        - statistic: "120+"
          description: |
            Countries
            covered
        - statistic: "10K+"
          description: |
            Active explorers
            in our community
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Why iPlaces?
      text: Everything you need to find and share the world's best places.
      items:
        - name: Smart Discovery
          icon: magnifying-glass
          description: Our intelligent search helps you find the perfect places based on your interests, travel style, and preferences.
        - name: Curated Collections
          icon: rectangle-group
          description: Browse expertly curated collections of places organized by theme, region, and experience type.
        - name: Community Reviews
          icon: star
          description: Read authentic reviews and tips from fellow travelers who have actually been there.
        - name: Interactive Maps
          icon: map-pin
          description: Explore destinations with beautiful, interactive maps that make planning your trip a breeze.
        - name: Offline Access
          icon: bolt
          description: Save your favorite places for offline access so you're never lost, even without internet.
        - name: Trip Planning
          icon: sparkles
          description: Create personalized itineraries with our AI-powered trip planner that optimizes your route and schedule.
  - block: cta-image-paragraph
    id: discover
    content:
      items:
        - title: Explore Hidden Gems Everywhere
          text: From secret beaches to mountain retreats, discover places you won't find in typical travel guides.
          feature_icon: check
          features:
            - "Verified locations with photos and directions"
            - "Local insider tips from the community"
            - "Real-time availability and crowd information"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Start Exploring
            url: /#features
        - title: Join a Global Community of Explorers
          text: Connect with like-minded travelers, share your discoveries, and get inspired for your next adventure.
          feature_icon: bolt
          features:
            - "Share your favorite places with the world"
            - "Follow other explorers and get notified of new finds"
            - "Participate in challenges and earn explorer badges"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Join the Community
            url: /#features
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    id: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Sarah Chen"
          role: "Travel Blogger & Explorer"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "iPlaces completely changed how I discover new destinations. The community-driven recommendations led me to places I never would have found on my own!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Start Your Next Adventure with iPlaces
      text: Join thousands of explorers discovering amazing places every day.
      button:
        text: Get Started for Free
        url: /#features
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
