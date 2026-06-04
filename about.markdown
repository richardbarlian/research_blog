---
layout: page
title: About
permalink: /about/
---

<style>
.about-intro {
  display: flex;
  align-items: flex-start;
  gap: 2rem;
  margin-bottom: 1rem;
}

.about-intro img {
  width: 300px;
  max-width: 100%;
  height: auto;
  object-fit: cover;
  flex-shrink: 0;
}

.about-contact {
  display: flex;
  align-items: center;
  gap: 3rem;
  margin-top: 1rem;
}

.about-contact .social-media-list {
  margin: 0;
}

.about-contact img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  margin-left: auto;
  margin-top: -1rem;
}

/* Mobile */
@media (max-width: 768px) {
  .about-intro {
    flex-direction: column;
  }

  .about-intro img {
    width: 100%;
    max-width: 300px;
    margin: 0 auto;
  }

  .about-contact {
    flex-direction: column;
    gap: 1.5rem;
    align-items: center;
    text-align: center;
  }

  .about-contact img {
    margin: 0;
    width: 160px;
    height: 160px;
  }

  .social-media-list {
    width: 100%;
  }
}
</style>

<div class="about-intro">
  <img src="{{ '/assets/me.jpeg' | relative_url }}" alt="Richard Barlian">

  <div>
    <p>Ralph Waldo Emerson once wrote "Trust thyself: every heart vibrates to that iron string".</p>

    <p>I don't fully trust myself in implementing these architectures correctly -- I've had my fair share of patching sketchy code with sketchier fixes, slapping on a tighter gradient clip and praying training magically goes smooth.</p>

    <p>Neither does everyone know what I'm doing. People either think I'm Jimmy Neutron himself or a 16 year old who spends their entire day messing around prompting ChatGPT to do my homework.</p>

    <p>But I think the message is still important. So this blog is me trusting myself anyway, with all the shape errors and mid-training brutal Kullback-Leiber divergence blow-ups. I hope you can learn something useful from my journey too.</p>

  </div>
</div>

### Reach Out

<div class="about-contact">
  <ul class="social-media-list">
    <li>
      <a href="https://github.com/richardbarlian">
        <svg class="svg-icon">
          <use xlink:href="{{ '/assets/minima-social-icons.svg#github' | relative_url }}"></use>
        </svg>
        <span class="username">richardbarlian</span>
      </a>
    </li>

    <li>
      <a href="https://www.linkedin.com/in/richard-henry-barlian-76b044361">
        <svg class="svg-icon">
          <use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use>
        </svg>
        <span class="username">richard-henry-barlian-76b044361</span>
      </a>
    </li>

    <li>
      <a href="mailto:richard.barlian@gmail.com">
        <i class="fa-solid fa-envelope svg-icon" style="color: #828282;"></i>
        <span class="username">richard.barlian@gmail.com</span>
      </a>
    </li>

  </ul>

  <img src="{{ '/assets/me2.jpg' | relative_url }}" alt="Richard Barlian">
</div>
