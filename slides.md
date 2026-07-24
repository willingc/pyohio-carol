---
# try also 'default' to start simple
theme: default
# some information about your slides (markdown enabled)
title: Growing as a Python developer

# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable Comark Syntax: https://comark.dev/syntax/markdown
comark: true
# duration of the presentation
duration: 35min
# aspect ratio
aspectRatio: 16/9
layout: cover
background: '#f5f1e8'
class: title-slide

---

# Growing as a Python developer

*Resilience, Effort, Community*

## Carol Willing

PyOhio 2026 · July 25, 2026

<!--
Good morning. I want to share some lessons I've learned while building in Python and its community. Growing as a developer takes three core things: resilience, effort, and community
-->

---
class: how-slide
---

<div class="how-hero">
  <h1 class="how-q">How?</h1>
  <p class="how-sub">Growing as a Python developer &mdash; so many questions&hellip;</p>
</div>

<div class="how-options">
<v-clicks>

<span class="how-chip">📖 Learn the language</span>

<span class="how-chip">🧭 Follow a tutorial</span>

<span class="how-chip how-chip--ai">🤖 Ask Claude / ChatGPT / Gemini 👀</span>

</v-clicks>
</div>

---
layout: default
class: intro-slide
---

# Hi 😊 I'm Carol Willing

<div class="badges">
  <span class="badge">Python Core Team since 2017</span>
  <span class="badge">3× Python Steering Council</span>
  <span class="badge">PSF Fellow</span>
  <span class="badge">2× PSF Board member</span>
  <span class="badge">Jupyter Core Team</span>
  <span class="badge">ACM Software System Award</span>
  <span class="badge">PSF Community Service Award</span>
  <span class="badge">PSF Frank Willison Award</span>
</div>

<p class="tagline">Mentor, teacher, collaborator, and friend</p>

---
layout: image-overlay
image: /Varanus_komodoensis6.jpg
class: pos-dragon
---

# Thar be dragons

### Are they nice dragons or<br>do they breathe fire?

Today, let's go with nice.

<span class="attribution"><a href="http://creativecommons.org/licenses/by-sa/3.0/" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a> | <a href="https://commons.wikimedia.org/w/index.php?curid=529977">Link</a></span>

<!--
Thar be dragons. It’s a scary feeling when you are starting out or looking at uncharted territory.
-->

---
layout: image-overlay
image: /dragon-toddler.jpg
class: overlay-right
---

# Growing dragonfruits

<!--
 But I like to think Python devs are a lot like dragonfruit—unique, needing a little care to start, but capable of blooming beautifully if given the right environment."
-->

---
layout: image-overlay
image: /dragon-orchard-young.jpg
class: pos-nutrients
---

## Nutrients and water

---
layout: image-overlay
image: /dragon-care-day.jpg
class: pos-care
---

# Care

---
layout: image-overlay
image: /dragon-flowers-prebloom.jpg
---

# Starting to bloom

---
layout: image-overlay
image: /dragon-flower.jpg
image2: /dragon-flower-night.jpg
class: overlay-right
---

## Full bloom

The process isn't finished yet.

---
layout: image-overlay
image: /dragon-pollinate-night.jpg
---

# Cross-pollinating

---
layout: image-overlay
image: /dragon-fruit.jpg
class: pos-fruit
---

## Bearing fruit

---
layout: statement
---

## Python developers are like dragonfruits

---
layout: default
---

# My journey and the pedestal of doubt

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-year">1995</div>
    <div class="timeline-text"><strong>The long break from tech.</strong> Caregiving across 3,000 miles for a mom with Alzheimer's, raising two kids, and a husband traveling 50% of the time.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2010</div>
    <div class="timeline-text"><strong>The return.</strong> Facing the industry myth: "You wasted your MIT degree. You lost your technical skills. You have to start at the bottom as a junior."</div>
  </div>
</div>

<div class="pedestal-block">
  <h2 class="pedestal-title">The reverse pedestal</h2>
  <div class="pedestal-images">
    <img src="/screenshots/Gemini_Generated_Image_8tnxlj8tnxlj8tnx.png" alt="Falling off the 'brightest star' pedestal" />
    <img src="/screenshots/Gemini_Generated_Image_it1extit1extit1e.png" alt="Climbing back onto the pedestal" />
  </div>
</div>

<!--
In 1995, I took a long break from the tech industry. Life happened—I was raising two kids, managing a home alone half the time, and caring for my mom who was 3,000 miles away with Alzheimer's. I took some C and C++ classes in 2007 just to keep my brain moving, even though I didn't have a formal CS background. When I tried to return in 2010, people put me on a scary 'reverse pedestal'. They told me I'd wasted my degree, lost my skills, and had to start completely over from the bottom. It wasn't true."
-->
---
layout: default
class: anchors-slide
---

# Community Anchors & The Power of 5 Minutes

<div class="era-badge">2011 – 2014</div>

<div class="labeled-cards labeled-cards--grid">
  <div class="labeled-card">
    <div class="labeled-card__label">🫂 Local community</div>
    <div class="labeled-card__body">Geek in Residence at FabLab San Diego, San Diego Python and PyLadies.</div>
  </div>
  <div class="labeled-card">
    <div class="labeled-card__label">✉️ Invitation</div>
    <div class="labeled-card__body">AdaCamp, Shauna Gordon McKeon (OpenHatch / Django), Jessica McKellar (PyCon).</div>
  </div>
  <div class="labeled-card">
    <div class="labeled-card__label">🌟 Micro-Mentorship</div>
    <div class="labeled-card__body">Adrian Holovaty and Jacob Kaplan-Moss (PyCon Poster). Contributing to the Requests library (POST for JSON).</div>
  </div>
  <div class="labeled-card labeled-card--highlight">
    <div class="labeled-card__label">💡 The Turning Point</div>
    <div class="labeled-card__body">Fernando Perez, IPython and Jupyter, asking: <em>"What do you think?"</em></div>
  </div>
</div>

<!--
"Things changed when I found community anchors. I started helping people fabricate their dreams at FabLab San Diego. Then I hit AdaCamp and met Shauna Gordon McKeon—that's where the serious Python adventure began. Jessica McKellar asked me to join the PyCon program committee. When I was terrified to show a poster, Adrian Holovaty and Jacob Kaplan-Moss sat with me for 30 minutes to look at it. Someone took the time to help me add JSON posting to Requests. The magic moment was Fernando Perez asking me, 'What do you think?' That simple question pulled me straight into Jupyter."

-->

---
layout: default
class: gardening-slide
---

# Moving from Learning to Gardening

<div class="era-badge">2014 – Present</div>

<div class="labeled-cards">
  <div class="labeled-card">
    <div class="labeled-card__label">🎤 The Stage</div>
    <div class="labeled-card__body">My first PyCon talk — rehearsing with Selena Deckelman; asking a core dev to stand on stage with me.</div>
  </div>
  <div class="labeled-card">
    <div class="labeled-card__label">🏆 The Milestones</div>
    <div class="labeled-card__body">CPython Core Developer (2017), ACM Software System Award (2019), White House recognition (2014 FabLab, 2024 Project Jupyter).</div>
  </div>
  <div class="labeled-card">
    <div class="labeled-card__label">🌱 The Gentle Code Garden</div>
    <div class="labeled-card__body">San Diego Python Study Group, JupyterHub / Binder code and docs, CPython humane leadership, PyOpenSci outreach.</div>
  </div>
</div>

<p class="motto">Learn. Build. Share. — <em>Openly</em></p>

<!--
"I was so nervous giving my first PyCon talk that Selena Deckelman had to help me rehearse. I literally asked a core dev to stand on stage and hold my hand until I hit the slide showing my young son playing trombone outside on our patio in his bathrobe. Eventually, I became the second woman core developer for CPython, and our team won the ACM Software System Award. But my real work shifted to becoming a gardener. I wanted to build a Gentle Code Garden where people could learn, build, and share openly without fear."
-->

---
layout: default
class: reality-slide
---

# The Modern Reality <span class="subtitle-tag">a distributed system</span>

<div class="concept-cards">
  <div class="concept-card">
    <div class="concept-card__icon">🎲</div>
    <div class="concept-card__title">Unpredictability</div>
    <div class="concept-card__body">is a constant.</div>
  </div>
  <div class="concept-card">
    <div class="concept-card__icon">🌐</div>
    <div class="concept-card__title">Immense scale</div>
    <div class="concept-card__body">Information moves instantly, everywhere at once.</div>
  </div>
  <div class="concept-card">
    <div class="concept-card__icon">⚙️</div>
    <div class="concept-card__title">Complex system mirrors us</div>
    <div class="concept-card__body">Race conditions, latency, and shifting timelines.</div>
  </div>
</div>

<!--
"Today's world feels chaotic and unpredictable. The real shift isn't change itself—it's that we move information around the globe instantaneously at a massive scale. Software engineering mirrors distributed computing. We are constantly dealing with race conditions, latency, and changing timelines. Because of this, I have three simple rules: Adapt to change, Open doors, and Be humble."
-->

---
layout: section
---

## How to grow as a Python developer

---
layout: two-cols
class: who-slide
---

## Who is a Python developer?

<p class="who-lead"><strong>Anyone</strong> who creates&hellip;</p>

::right::

<div class="who-tags" v-click>
  <span class="who-tag">code</span>
  <span class="who-tag">tests</span>
  <span class="who-tag">documentation</span>
  <span class="who-tag">designs</span>
  <span class="who-tag">communities</span>
  <span class="who-tag">governance</span>
  <span class="who-tag">translations</span>
  <span class="who-tag">accessibility</span>
  <span class="who-tag">events</span>
  <span class="who-tag who-tag--more">&amp; much, much more…</span>
</div>

---
class: steps-slide
---

# Three steps to success

<div class="steps">
  <div class="step">
    <div class="step-num">1</div>
    <div class="step-icon">🌊</div>
    <div class="step-name">Adapting to change</div>
  </div>
  <div class="step">
    <div class="step-num">2</div>
    <div class="step-icon">🚪</div>
    <div class="step-name">Opening doors</div>
  </div>
  <div class="step">
    <div class="step-num">3</div>
    <div class="step-icon">🌿</div>
    <div class="step-name">Being humble</div>
  </div>
</div>

---
layout: section
---

# adapting to change

---
layout: two-cols
class: title-left
---

# 🐍 Python 🐍

*What you need, when you need it*

::right::

<div class="resource-groups">
  <div class="resource-group">
    <div class="resource-group__label">All</div>
    <a href="https://docs.python.org">docs.python.org</a>
    <a href="https://pypi.org">pypi.org</a>
  </div>
  <div class="resource-group">
    <div class="resource-group__label">Intermediate</div>
    <a href="https://devguide.python.org">devguide.python.org</a>
    <a href="https://peps.python.org">peps.python.org</a>
  </div>
  <div class="resource-group">
    <div class="resource-group__label">Advanced theory</div>
    <a href="https://web.mit.edu/6.001/6.037/sicp.pdf">SICP <span class="resource-note">(MIT 6.001)</span></a>
  </div>
</div>

---
layout: two-cols
class: title-left
---

<h1 class="owl-title"><span class="owl">🦉</span>Deconstructed<span class="owl">🦉</span></h1>

::right::

<div class="deconstruct-blocks">
  <div class="deconstruct-block" v-click>
    <div class="deconstruct-block__label"><span class="deconstruct-block__num">1</span> Primitives</div>
    <ul>
      <li>numbers and strings</li>
      <li>built-in operations</li>
      <li>names / variables</li>
    </ul>
  </div>
  <div class="deconstruct-block" v-click>
    <div class="deconstruct-block__label"><span class="deconstruct-block__num">2</span> Means of combination</div>
    <ul>
      <li>expressions (produce a value from operations)</li>
      <li>control flow (if, loops)</li>
      <li>data structures (list, dict)</li>
    </ul>
  </div>
  <div class="deconstruct-block" v-click>
    <div class="deconstruct-block__label"><span class="deconstruct-block__num">3</span> Means of abstraction</div>
    <ul>
      <li>functions</li>
      <li>data abstraction (interface, implementation)</li>
      <li>modularity (classes, modules)</li>
    </ul>
  </div>
</div>

---
layout: default
class: adapt-slide
---

# adapting to change

<div class="adapt-points">
  <div class="adapt-point" v-click>
    <span class="adapt-point__icon">🔁</span>
    <span>Failure and change are <strong>baseline rules</strong> in software systems.</span>
  </div>
  <div class="adapt-point" v-click>
    <span class="adapt-point__icon">🧪</span>
    <span>Move past technical myths — rely on continuous <strong>experimentation and exploration</strong>.</span>
  </div>
  <div class="adapt-point" v-click>
    <span class="adapt-point__icon">🤔</span>
    <span>An expert saying it — or a fancy system — <strong>doesn't make it correct</strong> or capture the full problem.</span>
  </div>
</div>

<div class="tides" v-click>
  <div class="tides__label">Follow the tides of your personal energy</div>
  <div class="tides__cycle">
    <span class="tide">🌙 Ebb</span>
    <span class="tide">😴 Rest</span>
    <span class="tide">🌊 Flow</span>
    <span class="tide">⚡ Recharge</span>
  </div>
</div>

<!--
"Rule one: Adapt to change. Change is a constant in software systems. Forget the technical myths—focus on experimentation and active exploration. And remember: just because an expert says it or builds a fancy system doesn't mean it's correct or captures the ground-reality of the problem. Gather information, make your own rules, and test the system yourself. Lastly, manage your own system latency. Follow the tides of your energy. Allow yourself the ebb and the rest so you can hit the flow state and truly recharge."
-->

---
layout: fact
---

# Time

is precious

---
layout: image-overlay
image: /door-scroll.jpg
---

# Open doors

### and invite people in

---
layout: default
class: adapt-slide
---

# open a door

<div class="adapt-points">
  <div class="adapt-point">
    <span class="adapt-point__icon">🌐</span>
    <span><strong>Grow networks and impact</strong>
      <span class="net-chips">
        <span class="net-chip">PyLadies</span>
        <span class="net-chip">Black Python Devs</span>
        <span class="net-chip">Djangonauts</span>
        <span class="net-chip">PyOhio</span>
      </span>
    </span>
  </div>
  <div class="adapt-point">
    <span class="adapt-point__icon">🧺</span>
    <span><strong>Have a picnic</strong> — a brilliant woman in Argentina who thought she was "just a junior DevOps dev," now on the PyCon Charlas stage.</span>
  </div>
  <div class="adapt-point">
    <span class="adapt-point__icon">🌱</span>
    <span><strong>Encourage gently</strong> — be a <a href="https://speakerdeck.com/willingc/be-a-slqar-micromentoring-for-all" class="slqar-link">SLQAR</a>:
      <span class="slqar">
        <span class="slqar__part"><b>S</b>how up</span>
        <span class="slqar__part"><b>L</b>isten</span>
        <span class="slqar__part"><b>Q</b>uestion</span>
        <span class="slqar__part"><b>A</b>ct</span>
        <span class="slqar__part"><b>R</b>echarge</span>
      </span>
    </span>
  </div>
</div>

<p class="lead-note">Stop gatekeeping</p>

<!--
"Rule two: Open doors. We have to stop gatekeeping, even the well-meaning kind that accidentally slams doors on beginners. Use networks like PyLadies, Black Python Devs, and Djangonauts to knock down stronger doors. I remember meeting a young woman at a picnic in Argentina. She told me she was 'just a junior DevOps dev,' but she knew an absolute ton about Kubernetes. We talked, encouraged her, and a year or two later she was on stage giving a talk at the PyCon Charlas track. Level up the people around you. It’s not about being self-serving; it's about making the space better so everyone can do more creative, challenging work."
-->

---
class: adapt-slide
---

# Make the room accessible

<div class="adapt-points">
  <div class="adapt-point">
    <span class="adapt-point__icon">📋</span>
    <span><strong>Formal program</strong> — Djangonaut Space</span>
  </div>
  <div class="adapt-point">
    <span class="adapt-point__icon">📍</span>
    <span><strong>Local gatherings</strong> — regional conferences and user groups</span>
  </div>
  <div class="adapt-point">
    <span class="adapt-point__icon">🍵</span>
    <span><strong>Conversation</strong> — have tea. Chat.</span>
  </div>
</div>

<p class="lead-note lead-note--strong">Create a safe space</p>

---

## Go beyond one-dimensional views and code

---
layout: iframe
url: https://www.drcathicks.com/podcast
---

## Dr. Cat Hicks

---
class: courage-slide
---

<div class="courage">
  <h1>Gather courage and enter the room</h1>
  <p class="courage__sub">when <strong>you</strong> feel ready</p>
</div>

---
layout: section
---

## Be humble

---
layout: default
class: adapt-slide
---

# Be humble

<div class="adapt-points">
  <div class="adapt-point">
    <span class="adapt-point__icon">💬</span>
    <span><strong>Honest phrases</strong>
      <span class="net-chips">
        <span class="net-chip">I don't know</span>
        <span class="net-chip">What do you think?</span>
        <span class="net-chip">Yes, and …</span>
      </span>
    </span>
  </div>
  <div class="adapt-point">
    <span class="adapt-point__icon">✈️</span>
    <span><strong>The flight crew</strong> — pilots, flight attendants, and maintenance crews all own safety equally.</span>
  </div>
  <div class="adapt-point">
    <span class="adapt-point__icon">💙</span>
    <span><strong>Kind code reviews</strong> — focus on the code, not the person.</span>
  </div>
  <div class="adapt-point">
    <span class="adapt-point__icon">✨</span>
    <span><strong>Foundational courtesy</strong>
      <span class="net-chips">
        <span class="net-chip">Please</span>
        <span class="net-chip">Thank you</span>
        <span class="net-chip">I appreciate your effort</span>
      </span>
    </span>
  </div>
</div>

<p class="lead-note">Drop the arrogance and jargon — it only creates friction.</p>

<!--
"Rule three: Be humble. Technical arrogance or jargon just creates unnecessary friction. Step off the pedestal. It is incredibly powerful to say, 'I don't know,' and immediately follow it up with, 'What do you think?' Think of software like a commercial flight crew. The pilots, the flight attendants, and the maintenance team all have completely different roles, but they are all entirely critical to safety. Bring that mindset into code reviews. Keep it to the technical issue, never the person. Use simple kindness: 'Please,' 'Thank you,' and 'I appreciate your effort.'"
-->

---

- look beyond snap judgments
- empathy
- humble data

---
layout: two-cols
---

## Anti-pattern alert: Technical and not technical

Remember the flight crew metaphor

::right::

Code for "you are not as valuable as me" or "code writing is more important"

Success skills

---

## Recap

- Adapt by testing assumptions and listening to your own energy flow.

- Open doors and invite people in

- Be humble, yet assertive

- Step beyond your comfort zone

<!--
"To wrap it up: Adapt to change by experimenting, open doors for others using the power of a quick five-minute interaction, and stay humble by treating tech like a team flight crew. I challenge you today to step completely out of your comfort zone, find your community anchor, and jump in."
-->

---
layout: iframe-right
url: https://www.satyrn.ai
---

## We can change the world together

• Dream big.

• Hope starts with your immediate, daily choices.

• Write impactful code and change your little corner of the world.


<!--
"Dream big. Hope and progress start right now with your own choices. Write impactful code, stay curious, and change your little corner of the world. The technology landscape might not always be perfect, but the people dedicated to building it definitely make this journey worth it. Thank you."
-->

---
layout: cover
class: title-slide
---

# Thank you

## Carol Willing

*Resilience, Effort, Community*
