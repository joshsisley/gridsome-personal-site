<template>
  <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="about">
    <div class="w-100">
      <h1 class="mb-0">
        Joshua
        <span class="text-primary">Sisley</span>
      </h1>
      <div class="subheading mb-5">
        Real Estate Broker · Raleigh/Durham North Carolina ·
        <a
          href="mailto:name@email.com"
        >josh@joshuasisley.com</a>
      </div>
      <p
        class="lead mb-5"
      >With a background in software development, I use my experience to leverage innovative technology along with in-depth market knowledge and stellar customer service, to find you the right home.</p>
      <p class="lead mb-5">
        If you're looking to buy, sell or invest, 
        <a href="mailto:josh@joshuasisley.com">let's get in touch</a>!
      </p>
      <div class="social-icons">
        <!-- <a href="https://linkedin.com/in/joshua-sisley" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'linkedin']"/>
        </a> -->
        <!-- <a href="https://github.com/joshsisley" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'github']"/>
        </a> -->
        <a href="https://facebook.com/joshsisleyrealestate" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'facebook']"/>
        </a>
        <a href="https://twitter.com/joshsisley" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'twitter']"/>
        </a>
        <a href="https://www.instagram.com/joshuasisley" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'instagram']"/>
        </a>
        <!-- <a href="https://loke.dev" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fas', 'rss']"/>
        </a> -->
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.social-icons a {
  cursor: pointer;
  display: inline-block;
  height: 3.5rem;
  width: 3.5rem;
  background-color: var(--secondary);
  color: #fff !important;
  border-radius: 100%;
  text-align: center;
  font-size: 1.5rem;
  line-height: 3.5rem;
  margin-right: 1rem;

  @media (max-width: 380px) {
    margin-right: 0.5rem;
  }

  @media (max-width: 350px) {
    margin-right: 0.2rem;
  }
}

.social-icons a:last-child {
  margin-right: 0;
}

.social-icons a:hover {
  background-color: var(--primary);
}
</style>
