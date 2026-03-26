---
layout: default
title: ClarityFlow - Decision Tracker & Subscription Manager for iOS
---

<div class="hero animate-fade-in-up">
  <h1 class="text-gradient">Think Clearly.<br>Decide Confidently.</h1>
  <p class="mb-xl">Stop making decisions you'll regret. ClarityFlow helps you beat impulse buying, track every subscription, and capture decisions before they cost you money.</p>
  <p class="mb-2xl" style="color: var(--color-text-secondary); max-width: 680px; margin-left: auto; margin-right: auto;">No account needed. All your data stays private on your device. Free to download.</p>

  <div style="display: flex; justify-content: center; margin-bottom: var(--spacing-4xl);">
    <a href="{{ site.appstore_link | default: '#' }}" class="btn btn-primary btn-large">
      <i class="fab fa-apple"></i>
      Download on the App Store
    </a>
  </div>
</div>

<section class="features">
  <div class="text-center mb-2xl">
    <h2>Everything you need to decide smarter</h2>
    <p>ClarityFlow combines a cooling-off timer, subscription tracker, and AI import in one clean, private app.</p>
  </div>

  <div class="grid grid-3">
    {% for feature in site.features %}
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-{{ feature.fontawesome_icon_name }}"></i>
      </div>
      <h3>{{ feature.title }}</h3>
      <p>{{ feature.description }}</p>
    </div>
    {% endfor %}
  </div>
</section>

<section class="features">
  <div class="text-center mb-2xl">
    <h2>How ClarityFlow Works</h2>
    <p>Capture a decision in seconds. Let ClarityFlow do the rest.</p>
  </div>

  <div class="grid grid-2">
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-snowflake"></i>
      </div>
      <h3>Capture & Cool Off</h3>
      <p>Tap "Should I buy this?" and set a waiting period. ClarityFlow reminds you when time is up so you can decide with a clear head — not in the heat of the moment.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-sync-alt"></i>
      </div>
      <h3>Track Every Subscription</h3>
      <p>Add your recurring charges and see your total monthly burn at a glance. Get reminded before renewals so you're never surprised by a charge you forgot about.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-comments"></i>
      </div>
      <h3>Import from AI Chat</h3>
      <p>Already talked through a decision with ChatGPT or Claude? Paste the conversation and ClarityFlow extracts the key details — name, cost, and interval — automatically.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-chart-bar"></i>
      </div>
      <h3>See Your Progress</h3>
      <p>Track how much you've saved by pausing before spending. See your subscription costs, decisions made, and patterns over time — all in one Finance view.</p>
    </div>
  </div>
</section>

<section class="features">
  <div class="text-center mb-2xl">
    <h2>Built for iPhone</h2>
    <p>Native iOS app. Fast, clean, and always private.</p>
  </div>

  <div class="grid grid-3">
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-mobile-alt"></i>
      </div>
      <h3>iOS 18+ Optimized</h3>
      <p>Built with SwiftUI for smooth 60 FPS performance and a beautiful interface that feels at home on any iPhone.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-moon"></i>
      </div>
      <h3>Light & Dark Mode</h3>
      <p>Looks great in both light and dark mode. Switch automatically with your system or choose your preferred theme in Settings.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-shield-alt"></i>
      </div>
      <h3>Zero Data Collection</h3>
      <p>No account, no server, no tracking. Everything lives on your device. ClarityFlow will never see your decisions — they're yours.</p>
    </div>
  </div>
</section>
