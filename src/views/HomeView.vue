<template>
  <div class="global-wrap">
    <div class="global-content">
      <header class="header-section">
        <div class="header-wrap">
          <div class="header-logo">
            <h1 class="is-image">
              <RouterLink to="/">
                <img
                  src="https://renge.fueko.net/content/images/2020/07/renge.svg"
                  alt="Renge"
                />
              </RouterLink>
            </h1>
          </div>
          <div class="header-nav">
            <input id="toggle" class="header-checkbox" type="checkbox" />
            <label class="header-toggle" for="toggle">
              <span>
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
              </span>
            </label>
            <nav class="is-search">
              <ul>
                <li>
                  <a href="https://renge.fueko.net/" class="is-active">Home</a>
                </li>
                <li>
                  <a href="https://renge.fueko.net/membership/">Membership</a>
                </li>
                <li>
                  <a href="https://renge.fueko.net/style-guide/">Style Guide</a>
                </li>
                <li class="header-nav-dropdown">
                  <svg
                    role="img"
                    viewBox="0 0 20 4"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M2 4A2 2 0 102.001.001 2 2 0 002 4zm8 0a2 2 0 10.001-3.999A2 2 0 0010 4zm8 0a2 2 0 10.001-3.999A2 2 0 0018 4z"
                    />
                  </svg>
                  <ul>
                    <li>
                      <a href="https://renge.fueko.net/features/">Features</a>
                    </li>
                    <li>
                      <a href="https://renge.fueko.net/authors/">Authors</a>
                    </li>
                    <li><a href="https://renge.fueko.net/tags/">Tags</a></li>
                    <li>
                      <a href="https://renge.fueko.net/subscribe/">Subscribe</a>
                    </li>
                    <li>
                      <a href="https://renge.fueko.net/contact/">Contact</a>
                    </li>
                    <li><a href="https://renge.fueko.net/demos/">Demos</a></li>
                    <li>
                      <a
                        href="https://themeforest.net/item/renge-creative-ghost-blog-theme/27597084"
                        >Get Theme</a
                      >
                    </li>
                  </ul>
                </li>
              </ul>
              <ul>
                <li class="signup global-button">
                  <RouterLink to="/about">Register for free</RouterLink>
                </li>
                <li class="signin">
                  <RouterLink to="/about">Sign in</RouterLink>
                </li>
                <li id="search-open" class="header-search">
                  <span>Search</span
                  ><svg
                    role="img"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M19.063 16.384l4.325 4.323c.391.392.63.924.611 1.475-.032.926-.646 1.649-1.68 1.736-.551.046-1.086-.22-1.476-.61l-4.325-4.325c-1.706 1.131-4.034 1.895-6.08 1.893C4.673 20.875 0 16.202 0 10.438 0 4.673 4.673 0 10.438 0c5.764 0 10.437 4.673 10.437 10.438 0 2.127-.718 4.294-1.812 5.945v.001zm-8.625 1.032c3.839 0 6.997-3.161 6.997-7 0-3.84-3.16-7-6.999-7-3.84 0-7.001 3.16-7.001 7 0 3.839 3.161 6.998 7.001 6.998l.002.002z"
                    />
                  </svg>
                </li>
              </ul>
            </nav>
          </div>
        </div>
      </header>
      <main class="global-main">
        <div class="loop-section">
          <div class="loop-wrap">
            <article
              class="item is-hero is-first is-image post tag-story tag-art tag-creative tag-hash-post-card-raspberry"
            >
              <div class="item-container global-color">
                <a
                  href="/now-were-getting-somewhere/"
                  class="item-image global-image global-color"
                >
                  <img
                    srcset="
                      /images/arcana_main.png  500w,
                      /images/arcana_main.png  800w,
                      /images/arcana_main.png 1100w
                    "
                    sizes="(max-width:480px) 240px, (max-width:768px) 200px, (max-width:1024px) 290px, 350px"
                    src="/images/arcana_main.png"
                    alt="Now we’re getting somewhere"
                  />
                </a>
                <div class="item-content">
                  <div class="global-meta">
                    <time datetime="2020-03-05">3 years ago</time>
                    by
                    <a href="/author/megan/">Megan Anderson</a> &
                    <a href="/author/victoria/">Victoria West</a>
                    <span class="global-reading"> — 3 min read </span>
                  </div>
                  <h2 class="item-title">
                    <a
                      href="/now-were-getting-somewhere/"
                      class="global-underline"
                      >Descubre la Telaraña</a
                    >
                  </h2>
                  <p class="item-excerpt">
                    Quae quo sunt excelsiores, eo dant clariora indicia naturae.
                    Sed haec quidem liberius ab eo dicuntur et saepius. Et ille
                    ridens video, inquit, quid agas tum ille timide vel potius
                    verecunde.
                  </p>
                  <div class="global-tags">
                    <a href="/tag/story/" class="global-tags-hash-sign"
                      >story</a
                    >
                    <a href="/tag/art/" class="global-tags-hash-sign">art</a>
                    <a href="/tag/creative/" class="global-tags-hash-sign"
                      >creative</a
                    >
                  </div>
                </div>
              </div>
            </article>
            <article
              class="item is-even is-image post tag-story tag-illustration tag-hash-post-card-apricot featured"
            >
              <div class="item-container">
                <div class="item-content">
                  <a
                    href="/everything-has-beauty-but-not-everyone-sees-it/"
                    class="item-image global-image global-color"
                  >
                    <img
                      src="/content/images/size/w260/2020/06/photo-1506567859980-33c9c423649f.jpeg"
                      loading="lazy"
                      alt="Everything has beauty, but not everyone sees it"
                    />
                  </a>
                  <h2 class="item-title">
                    <a
                      href="/everything-has-beauty-but-not-everyone-sees-it/"
                      class="global-underline"
                      >Everything has beauty, but not everyone sees it</a
                    >
                  </h2>
                  <div class="global-meta">
                    <a href="/author/charles/">Charles Barrett</a>
                    and others
                    <span class="global-reading"> — 3 min read </span>
                  </div>
                  <p class="item-excerpt">
                    Utilitatis causa amicitia est quaesita. Quae quo sunt
                    excelsiores, eo dant clariora indicia naturae. Sed haec
                    quidem liberius ab eo dicuntur et...
                  </p>
                  <div class="global-tags">
                    <a href="/tag/story/" class="global-tags-hash-sign"
                      >story</a
                    >
                    <a href="/tag/illustration/" class="global-tags-hash-sign"
                      >illustration</a
                    >
                  </div>
                </div>
              </div>
            </article>
            <article
              class="item is-odd is-image post tag-creative tag-product tag-hash-post-card-amber featured"
            >
              <div class="item-container">
                <div class="item-content">
                  <a
                    href="/design-is-a-mirror-reflecting-the-culture/"
                    class="item-image global-image global-color"
                  >
                    <img
                      src="/content/images/size/w260/2020/06/photo-1588612005960-a382b1eca714.jpeg"
                      loading="lazy"
                      alt="Design is a mirror, reflecting the culture"
                    />
                  </a>
                  <h2 class="item-title">
                    <a
                      href="/design-is-a-mirror-reflecting-the-culture/"
                      class="global-underline"
                      >Design is a mirror, reflecting the culture</a
                    >
                  </h2>
                  <div class="global-meta">
                    <a href="/author/victoria/">Victoria West</a> &
                    <a href="/author/david/">David Cole</a>
                    <span class="global-reading"> — 2 min read </span>
                  </div>
                  <p class="item-excerpt">
                    Tertium autem omnibus aut maximis rebus iis, quae secundum
                    naturam sint, fruentem vivere. Materiam vero rerum et copiam
                    apud hos exilem, apud illos uberrimam reperiemus. Atque his
                    de rebus et splendida est eorum et illustris oratio.
                  </p>
                  <div class="global-tags">
                    <a href="/tag/creative/" class="global-tags-hash-sign"
                      >creative</a
                    >
                    <a href="/tag/product/" class="global-tags-hash-sign"
                      >product</a
                    >
                  </div>
                </div>
              </div>
            </article>
            <article
              class="item is-even is-image post tag-creative tag-review tag-story tag-hash-post-card-aqua"
            >
              <div class="item-container">
                <div class="item-content">
                  <a
                    href="/anyone-can-hold-the-helm-when-the-sea-is-calm/"
                    class="item-image global-image global-color"
                  >
                    <img
                      src="/content/images/size/w260/2020/06/photo-1515096788709-a3cf4ce0a4a6.jpeg"
                      loading="lazy"
                      alt="Anyone can hold the helm when the sea is calm"
                    />
                  </a>
                  <h2 class="item-title">
                    <a
                      href="/anyone-can-hold-the-helm-when-the-sea-is-calm/"
                      class="global-underline"
                      >Anyone can hold the helm when the sea is calm</a
                    >
                  </h2>
                  <div class="global-meta">
                    <a href="/author/megan/">Megan Anderson</a> &
                    <a href="/author/charles/">Charles Barrett</a>
                    <span class="global-reading"> — 2 min read </span>
                  </div>
                  <p class="item-excerpt">
                    Audio equidem philosophi vocem, Epicure, sed quid tibi
                    dicendum sit oblitus es. Haec et tu ita posuisti, et verba
                    vestra sunt. Contemnit...
                  </p>
                  <div class="global-tags">
                    <a href="/tag/creative/" class="global-tags-hash-sign"
                      >creative</a
                    >
                    <a href="/tag/review/" class="global-tags-hash-sign"
                      >review</a
                    >
                    <a href="/tag/story/" class="global-tags-hash-sign"
                      >story</a
                    >
                  </div>
                </div>
              </div>
            </article>
            <article
              class="item is-odd post tag-review tag-story tag-hash-post-card-amber no-image"
            >
              <div class="item-container">
                <span class="global-members-label"> Members </span>
                <div class="item-content">
                  <h2 class="item-title">
                    <a
                      href="/being-unique-is-better-than-being-perfect/"
                      class="global-underline"
                      >Being unique is better than being perfect</a
                    >
                  </h2>
                  <div class="global-meta">
                    <a href="/author/megan/">Megan Anderson</a>
                    <span class="global-reading"> — 2 min read </span>
                  </div>
                  <p class="item-excerpt">
                    Quae in controversiam veniunt, de iis, si placet,
                    disseramus. Iam quae corporis sunt, ea nec auctoritatem cum
                    animi partibus, comparandam et cognitionem habent
                    faciliorem.
                  </p>
                  <div class="global-tags">
                    <a href="/tag/review/" class="global-tags-hash-sign"
                      >review</a
                    >
                    <a href="/tag/story/" class="global-tags-hash-sign"
                      >story</a
                    >
                  </div>
                </div>
              </div>
            </article>
          </div>
        </div>
        <div class="pagination-section">
          <div class="pagination-wrap">
            <a href="/page/2/" id="next-page"></a>
            <button class="load-more" aria-label="Load more"></button>
          </div>
        </div>
        <div class="subscribe-section">
          <div class="subscribe-wrap">
            <h3>Subscribe to new posts.</h3>
            <form data-members-form="subscribe" class="subscribe-form">
              <input
                data-members-email
                type="email"
                placeholder="Your email address"
                aria-label="Your email address"
                required
              />
              <button class="global-button" type="submit">Subscribe</button>
              <div class="subscribe-alert">
                <small class="alert-loading">Processing your application</small>
                <small class="alert-success"
                  >Great! Check your inbox and confirm your subscription</small
                >
                <small class="alert-error"
                  >There was an error sending the email</small
                >
              </div>
            </form>
          </div>
        </div>
      </main>
      <footer class="footer-section global-footer">
        <div class="footer-wrap">
          <div class="footer-data">
            <div class="footer-logo">
              <a href="https://renge.fueko.net" class="is-image"
                ><img
                  src="https://renge.fueko.net/content/images/2020/07/renge.svg"
                  alt="Renge"
              /></a>
            </div>
            <p class="footer-description">
              A minimal, functional theme for running a paid-membership
              publication on Ghost.
            </p>
            <div class="footer-icons">
              <a
                href="https://twitter.com/fuekothemes"
                aria-label="link Twitter"
                ><svg
                  role="img"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M23.954 4.569c-.885.389-1.83.654-2.825.775 1.014-.611 1.794-1.574 2.163-2.723-.951.555-2.005.959-3.127 1.184-.896-.959-2.173-1.559-3.591-1.559-2.717 0-4.92 2.203-4.92 4.917 0 .39.045.765.127 1.124C7.691 8.094 4.066 6.13 1.64 3.161c-.427.722-.666 1.561-.666 2.475 0 1.71.87 3.213 2.188 4.096-.807-.026-1.566-.248-2.228-.616v.061c0 2.385 1.693 4.374 3.946 4.827-.413.111-.849.171-1.296.171-.314 0-.615-.03-.916-.086.631 1.953 2.445 3.377 4.604 3.417-1.68 1.319-3.809 2.105-6.102 2.105-.39 0-.779-.023-1.17-.067 2.189 1.394 4.768 2.209 7.557 2.209 9.054 0 13.999-7.496 13.999-13.986 0-.209 0-.42-.015-.63.961-.689 1.8-1.56 2.46-2.548l-.047-.02z"
                  /></svg
              ></a>

              <a href="#" aria-label="link Bitbucket"
                ><svg
                  role="img"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M.778 1.211c-.424-.006-.772.334-.778.758 0 .045.002.09.01.134l3.263 19.811c.084.499.515.867 1.022.872H19.95c.382.004.708-.271.77-.646l3.27-20.03c.068-.418-.216-.813-.635-.881-.045-.008-.089-.011-.133-.01L.778 1.211zM14.52 15.528H9.522L8.17 8.464h7.561l-1.211 7.064z"
                  /></svg
              ></a>
              <a href="#" aria-label="link GitHub"
                ><svg
                  role="img"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"
                  /></svg
              ></a>
              <a href="#" aria-label="link Kickstarter"
                ><svg
                  role="img"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M7.168 0c-3.2 0-5.797 2.579-5.797 5.758v12.484C1.371 21.42 3.968 24 7.168 24c1.981 0 3.716-.978 4.768-2.479l.794.79c2.26 2.245 5.943 2.245 8.203 0a5.724 5.724 0 001.696-4.075 5.724 5.724 0 00-1.696-4.074l-2.182-2.168 2.182-2.156a5.724 5.724 0 001.696-4.074 5.724 5.724 0 00-1.696-4.074c-2.26-2.246-5.942-2.246-8.203 0l-.794.789A5.797 5.797 0 007.168 0Z"
                  /></svg
              ></a>
              <a href="#" aria-label="link Reddit"
                ><svg
                  role="img"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M12 0A12 12 0 0 0 0 12a12 12 0 0 0 12 12 12 12 0 0 0 12-12A12 12 0 0 0 12 0zm5.01 4.744c.688 0 1.25.561 1.25 1.249a1.25 1.25 0 0 1-2.498.056l-2.597-.547-.8 3.747c1.824.07 3.48.632 4.674 1.488.308-.309.73-.491 1.207-.491.968 0 1.754.786 1.754 1.754 0 .716-.435 1.333-1.01 1.614a3.111 3.111 0 0 1 .042.52c0 2.694-3.13 4.87-7.004 4.87-3.874 0-7.004-2.176-7.004-4.87 0-.183.015-.366.043-.534A1.748 1.748 0 0 1 4.028 12c0-.968.786-1.754 1.754-1.754.463 0 .898.196 1.207.49 1.207-.883 2.878-1.43 4.744-1.487l.885-4.182a.342.342 0 0 1 .14-.197.35.35 0 0 1 .238-.042l2.906.617a1.214 1.214 0 0 1 1.108-.701zM9.25 12C8.561 12 8 12.562 8 13.25c0 .687.561 1.248 1.25 1.248.687 0 1.248-.561 1.248-1.249 0-.688-.561-1.249-1.249-1.249zm5.5 0c-.687 0-1.248.561-1.248 1.25 0 .687.561 1.248 1.249 1.248.688 0 1.249-.561 1.249-1.249 0-.687-.562-1.249-1.25-1.249zm-5.466 3.99a.327.327 0 0 0-.231.094.33.33 0 0 0 0 .463c.842.842 2.484.913 2.961.913.477 0 2.105-.056 2.961-.913a.361.361 0 0 0 .029-.463.33.33 0 0 0-.464 0c-.547.533-1.684.73-2.512.73-.828 0-1.979-.196-2.512-.73a.326.326 0 0 0-.232-.095z"
                  /></svg
              ></a>
              <a href="#" aria-label="link Unsplash"
                ><svg
                  role="img"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M7.5 6.75V0h9v6.75h-9zm9 3.75H24V24H0V10.5h7.5v6.75h9V10.5z"
                  /></svg
              ></a>
              <a href="#" aria-label="link Vimeo"
                ><svg
                  role="img"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M23.977 6.416c-.105 2.338-1.739 5.543-4.894 9.609-3.268 4.247-6.026 6.37-8.29 6.37-1.409 0-2.578-1.294-3.553-3.881L5.322 11.4C4.603 8.816 3.834 7.522 3.01 7.522c-.179 0-.806.378-1.881 1.132L0 7.197c1.185-1.044 2.351-2.084 3.501-3.128C5.08 2.701 6.266 1.984 7.055 1.91c1.867-.18 3.016 1.1 3.447 3.838.465 2.953.789 4.789.971 5.507.539 2.45 1.131 3.674 1.776 3.674.502 0 1.256-.796 2.265-2.385 1.004-1.589 1.54-2.797 1.612-3.628.144-1.371-.395-2.061-1.614-2.061-.574 0-1.167.121-1.777.391 1.186-3.868 3.434-5.757 6.762-5.637 2.473.06 3.628 1.664 3.493 4.797l-.013.01z"
                  /></svg
              ></a>
            </div>
          </div>
          <div class="footer-nav">
            <div class="footer-nav-column">
              <ul>
                <li>
                  <a href="https://renge.fueko.net/features/">Features</a>
                </li>
                <li>
                  <a href="https://renge.fueko.net/style-guide/">Style Guide</a>
                </li>
                <li><a href="https://renge.fueko.net/contact/">Contact</a></li>
                <li>
                  <a
                    href="https://themeforest.net/item/renge-creative-ghost-blog-theme/27597084"
                    >Get Theme</a
                  >
                </li>
              </ul>
            </div>

            <div class="footer-nav-column">
              <ul>
                <li><a href="https://renge.fueko.net/tags/">Tags</a></li>
                <li><a href="https://renge.fueko.net/authors/">Authors</a></li>
                <li>
                  <a href="https://renge.fueko.net/subscribe/">Subscribe</a>
                </li>
                <li><a href="https://renge.fueko.net/404/">404</a></li>
              </ul>
            </div>

            <div class="footer-nav-column">
              <ul>
                <li>
                  <a href="https://renge.fueko.net/tag/creative/">Tag page</a>
                </li>
                <li>
                  <a href="https://renge.fueko.net/author/megan/"
                    >Author page</a
                  >
                </li>
                <li><a href="https://renge.fueko.net/">Light version</a></li>
                <li>
                  <a href="https://renge-dark.fueko.net/">Dark version</a>
                </li>
              </ul>
            </div>

            <div class="footer-nav-column">
              <ul>
                <li>
                  <a href="https://renge.fueko.net/membership/">Membership</a>
                </li>
                <li>
                  <a href="https://renge.fueko.net/demo-account-paid-member/"
                    >Account page</a
                  >
                </li>
                <li><a href="https://renge.fueko.net/signin/">Sign In</a></li>
                <li><a href="https://renge.fueko.net/signup/">Sign Up</a></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="footer-copyright">
          Renge &copy; 2022. All Right Reserved. Published with
          <a href="https://ghost.org" target="_blank" rel="noopener noreferrer"
            >Ghost</a
          >
          &
          <a href="https://fueko.net" target="_blank" rel="noopener noreferrer"
            >Renge</a
          >.
        </div>
      </footer>
    </div>
  </div>
  <div id="notifications" class="global-notification">
    <div class="subscribe">You’ve successfully subscribed to Renge</div>
    <div class="signin">Welcome back! You’ve successfully signed in.</div>
    <div class="signup">Great! You’ve successfully signed up.</div>
    <div class="expired">Your link has expired</div>
    <div class="checkout-success">
      Success! Check your email for magic link to sign-in.
    </div>
  </div>
  <div id="search-section" class="search-section">
    <span id="search-close" class="search-close"
      ><svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M12 8.242L20.242 0 24 3.76 15.758 12 24 20.242 20.242 24 12 15.758 3.759 24 0 20.242 8.242 12 0 3.759 3.76 0 12 8.242z"
        /></svg
    ></span>
    <div id="search-content" class="search-content">
      <form class="search-form" onsubmit="return false">
        <input id="search-input" type="text" placeholder="Type your keywords" />
        <div class="search-meta">
          <span id="search-info">Please enter at least 3 characters</span>
          <span id="search-counter" class="is-hide">
            <span id="search-counter-results">0</span>
            Results for your search</span
          >
        </div>
      </form>
      <div id="search-results" class="search-results"></div>
    </div>
    <div id="search-overlay" class="search-overlay"></div>
  </div>
</template>
