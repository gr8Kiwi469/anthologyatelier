## Set-Content -Path content\_index.md -Value @"

## title: "Anthology Atelier"

"@

---

title: "Anthology Atelier"

layout: "home"

\---



<section class="hero">

&#x20; <h1>Curated Intelligence, Crafted for Clarity</h1>

&#x20; <p>Insights, previews, and upcoming releases from the Anthology Atelier ecosystem.</p>

&#x20; <a class="cta" href="/anthology4tech">Explore Anthology4Tech</a>

</section>



<section class="promos">

&#x20; <h2>Featured Promos</h2>

&#x20; <div class="promo-list">

&#x20;   <article>

&#x20;     <h3>The Architecture of Modern Workflows</h3>

&#x20;     <p>A preview of the upcoming release exploring how systems shape productivity.</p>

&#x20;     <a href="/promo/workflows">Read Preview</a>

&#x20;   </article>



&#x20;   <article>

&#x20;     <h3>Why Systems Thinking Still Wins</h3>

&#x20;     <p>An editorial insight into the frameworks behind effective decision-making.</p>

&#x20;     <a href="/promo/systems-thinking">Read Preview</a>

&#x20;   </article>



&#x20;   <article>

&#x20;     <h3>How Articles Are Crafted</h3>

&#x20;     <p>A behind-the-scenes look at the Anthology creation process.</p>

&#x20;     <a href="/promo/craft">Read Preview</a>

&#x20;   </article>

&#x20; </div>

</section>



<section class="about">

&#x20; <h2>About the Ecosystem</h2>

&#x20; <p>

&#x20;   Anthology Atelier is the curated gateway into a growing library of structured, practical insight.

&#x20;   Explore previews, follow upcoming drops, and discover the work happening across the Anthology4Tech platform.

&#x20; </p>

</section>



<section class="drops">

&#x20; <h2>Upcoming Drops</h2>

&#x20; <ul>

&#x20;   <li><strong>Drop #12:</strong> The Value Layer — Aug 2026</li>

&#x20;   <li><strong>Drop #13:</strong> The Hidden Architecture of Teams — Sept 2026</li>

&#x20;   <li><strong>Drop #14:</strong> The Systems Map — Oct 2026</li>

&#x20; </ul>

&#x20; <a href="/anthology4tech/drops">View Full Drop Calendar</a>

</section>



<section class="blog">

&#x20; <h2>Latest Posts</h2>

&#x20; {{ range first 3 (where .Site.RegularPages "Section" "blog") }}

&#x20;   <article>

&#x20;     <h3><a href="{{ .RelPermalink }}">{{ .Title }}</a></h3>

&#x20;     <p>{{ .Summary }}</p>

&#x20;   </article>

&#x20; {{ end }}

</section>



