---
layout: default
title: ClarityFlow - Smart Health Tracker for iOS
---

<div class="hero animate-fade-in-up">
  <h1 class="text-gradient">ClarityFlow<br>AI Memory for Your Body & Life</h1>
  <p class="mb-xl">Remember what works for YOUR body. ClarityFlow is the AI health tracker that finds patterns in your symptoms, treatments, and daily life—so you can finally understand your triggers.</p>
  <p class="mb-2xl" style="color: var(--color-text-secondary); max-width: 680px; margin-left: auto; margin-right: auto;">Perfect for chronic illness, migraines, headaches, and health optimization. All your data stays encrypted on your device—100% private.</p>

  <div style="display: flex; justify-content: center; margin-bottom: var(--spacing-4xl);">
    <a href="{{ site.appstore_link | default: '#' }}" class="btn btn-primary btn-large">
      <i class="fab fa-apple"></i>
      Download ClarityFlow on the App Store
    </a>
  </div>
</div>

<div class="screenshots">
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/03-onboarding.png' | relative_url }}" alt="ClarityFlow onboarding screen introducing smart pattern detection">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/04-main-page.png' | relative_url }}" alt="ClarityFlow home view with stats and top insights">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/05-entrries.png' | relative_url }}" alt="ClarityFlow entries view showing decision journeys with categories">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/06-patterns.png' | relative_url }}" alt="ClarityFlow pattern discovery showing symptom-treatment connections">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/07-quick-log.png' | relative_url }}" alt="ClarityFlow quick log with voice input and smart suggestions">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/08-ai-smart-splitting.png' | relative_url }}" alt="ClarityFlow AI automatically splitting entries into context, action, outcome">
  </div>
</div>

<section class="features">
  <div class="text-center mb-2xl">
    <h2>Track Smarter with ClarityFlow</h2>
    <p>AI-powered pattern detection, voice input, and privacy-first architecture help you understand what works for your body.</p>
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
    <h2>How It Works</h2>
    <p>From voice input to pattern discovery—ClarityFlow makes health tracking effortless.</p>
  </div>

  <div class="grid grid-2">
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-microphone-alt"></i>
      </div>
      <h3>Speak Naturally</h3>
      <p>Just say "Headache, took ibuprofen, felt better" and ClarityFlow's NLP automatically creates a complete decision journey with context, action, and outcome.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-project-diagram"></i>
      </div>
      <h3>Discover Patterns</h3>
      <p>AI analyzes your journeys to reveal what actually works. See which treatments help, which triggers to avoid, and make better health decisions.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-layer-group"></i>
      </div>
      <h3>Smart Categorization</h3>
      <p>Entries automatically categorize into Health, Work, Lifestyle, Relationships, or Financial—keeping everything organized without extra effort.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-shield-alt"></i>
      </div>
      <h3>Complete Privacy</h3>
      <p>All data encrypted on your device. No cloud uploads, no tracking, no third parties. Your health data is yours alone.</p>
    </div>
  </div>
</section>

<section class="features">
  <div class="text-center mb-2xl">
    <h2>Built for Apple Ecosystem</h2>
    <p>Native iOS app with modern Liquid Glass design and accessibility excellence.</p>
  </div>

  <div class="grid grid-3">
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-mobile-alt"></i>
      </div>
      <h3>iOS 18+ Optimized</h3>
      <p>Built with latest SwiftUI and iOS features for smooth 60 FPS performance.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-universal-access"></i>
      </div>
      <h3>Accessibility First</h3>
      <p>Full VoiceOver support, Dynamic Type, and WCAG 2.1 AA+ compliance built-in.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-moon"></i>
      </div>
      <h3>Dark Mode Ready</h3>
      <p>Beautiful in both light and dark mode with translucent Liquid Glass materials.</p>
    </div>
  </div>
</section>
