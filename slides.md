name: inverse
layout: true
class: inverse

---
name: title
class: false
background-image: url(img/tim-gouw-1K9T5YiZ2WU-unsplash.jpg)
background-size: contain

.pull-right[# Death of a SPAlesman
## REST in peace
### Introducing HTMX
]

.footnote.text-right[Photo by <a href="https://unsplash.com/@punttim?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tim Gouw</a> on <a href="https://unsplash.com/photos/1K9T5YiZ2WU?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>]

???
- Let's talk about single page applications
- what is bad about SPAs
- why SPAs are dead
- how to avoid writing an SPA
---
.left-column[
## 2013-2019
]
.right-column[
Early years in web development as a SPA developer

Tried Angular, Ember, React

Notice these projects tend to not do very well

I choose to become pessimistic instead of blame

Maybe web development is a bit like being a lawyer

.footnote[[The surprising benefits of being a pessimist](https://theconversation.com/the-surprising-benefits-of-being-a-pessimist-91851)]]

???
Lawyers and developers can agree that more trouble means more work.
---
class: inverse, list-no-style

### Face up to the facts
Faced with dominant cultural preferences and limited alternatives, critiques of SPAs struggled to gain traction in recent years.
.pull-left.list-no-style[
- 🥸 "Emulates" browser + website
  - 📈 Tons of JavaScript

  - ♿️ Accessibility issues

  - 🔎 SEO Issues

  - 😲 [Surprising behaviour](https://web.dev/client-side-rendering-of-html-and-interactivity/)

- 👨‍💻 [Chasing developer experience](https://infrequently.org/2018/09/the-developer-experience-bait-and-switch/)

- 🫥 No [Progressive Enhancement](https://blog.logrocket.com/the-single-page-application-must-die/)
    
- ❤️‍🩹 Notoriously [Fragile](https://www.gov.uk/service-manual/technology/using-progressive-enhancement)

- 🥷 Require developer specialisation
]
.pull-right.list-no-style[
- 🤨 ["Optimisations"](https://macwright.com/2020/05/10/spa-fatigue)
  - 🥹 Server rendering

  - 😏 Bundle splitting

  - 🥳 JavaScript everywhere!

- 🤼‍♂️ "Independent" APIs
  - 🪢 Duplicate logic in UI

  - 🪓 BFF/GraphQL pattern

- 🥶 Small market for alternatives
]

???
Maybe these challenges are surmountable. After all, the big tech cos do it. Why can't I?
---
class: inverse

<h2>In denial of the modern web</h2>

<blockquote>It will take more than technological advancement to get the web there; it will take a cultural shift as well. But we certainly can't get there if we abandon our current trajectory. Which is exactly what Tom seems to be suggesting.</blockquote>

<blockquote>We can only get there by committing to the paradigm Tom critiques — the JavaScript-ish component framework server-rendered SPA.</blockquote>

&mdash;Rich Harris [In defense of the modern web](https://dev.to/richharris/in-defense-of-the-modern-web-2nia)

<blockquote>However, the more I tried to improve it, the harder things got... Ultimately, I decided to re-write most of it using frameworks that were more familiar to me.</blockquote>
<blockquote>I want to pause here and clarify: JHipster and Angular are not bad platforms. Far from it. I’d recommend them in heartbeat for the right project.</blockquote>
<blockquote>...When I say they were becoming a hindrance, what I really mean is that my lack of knowledge of the technologies had come back to bite me.</blockquote>

&mdash;Stack overflow blog [What I wish I had known about SPAs](https://stackoverflow.blog/2021/12/28/what-i-wish-i-had-known-about-single-page-applications/)

???
Denial takes many forms. Sometimes they blame you, sometimes they blame themselves.
---
class: inverse
background-image: url(/img/anti-js-js-club-lighter-small.jpg)
background-position: 50% 90%

.left-column[
## 2023
]
.right-column[
### RIP

<blockquote>SPAs were a zero interest rate phenomenon</blockquote>

&mdash;Guillermo Rauch [@rauchg](https://twitter.com/rauchg/status/1619492334961569792)

<blockquote>Unfortunately improving DX is all SPAs really did for us.</blockquote>

&mdash;Kent C Dodds [The Web’s Next Transition](https://www.epicweb.dev/the-webs-next-transition)
]

???

2023 was the year SPAs officially died, the way I see it

Rauch was actually referring to framework advancements, not to hard times experienced by tech companies or IT departments. funny

Alex Russell writes about browser performance on Infrequently Noted.

The market for lemons is an economic paper which concludes that a market where consumers have poor information inevitably shrinks.

---
.left-column[
## 2023
]
.right-column[
### Catharsis

<blockquote>SPAs make the entire web worse: ditch them</blockquote>

&mdash;Alex Russell [The Market For Lemons](https://infrequently.org/2023/02/the-market-for-lemons/)

&mdash;[React is holding me hostage!](https://emnudge.dev/blog/react-hostage)

&mdash;[I Almost Got Fired for Choosing React in Our Enterprise App](https://betterprogramming.pub/i-almost-got-fired-for-choosing-react-in-our-enterprise-app-846ea840841c)

<p class="text-right"><a href="https://www.youtube.com/watch?v=SuPFwIQ27kk">(YouTube reaction)</a></p>

&mdash;[Why does everyone "suddenly" hate single page apps](https://begin.com/blog/posts/2023-02-21-why-does-everyone-suddenly-hate-single-page-apps)
]
???
At the end of a tragedy, there is catharsis--an outpouring of grief that brings it all to a close.

Increasingly incendiary blog posts indicate that's happening now.
---
layout: inverse
class: inverse, center, vcenter
## RIP Single Page Apps
### 2013-2023

???
- JavaScript will be ok, it lives on in other projects
- But maybe there's a way to not write so much JavaScript
- Can we move on from JavaScript?
---
name: wrong
background-image: url(/img/restapi.png), url(img/7y4sa3.jpg)
background-position: left, right
background-size: 50% auto, contain

???
Where did we go wrong?

SPAs were a solution to larger trends that started a long time ago.
---
## How do we avoid making an SPA?
.pull-left.list-no-style[
### As an individual
- 🧑‍💻 Be a [humble developer](https://grugbrain.dev)

- 🏠 Respect the browser

- 💵 Have a [Complexity budget](https://htmx.org/essays/complexity-budget/)

- 🏙️ Enterprise tools are for enterprises
  
- 💍 Avoid client state management:
  
  - 🤼‍♂️ JSON + API docs

  - 💸 JS Rendering logic
]
.pull-right.list-no-style[
### Tool choice
- 🛠️ Follow UNIX philosophy

- 😎 [Progressive Enhancement](https://www.gov.uk/service-manual/technology/using-progressive-enhancement)

- 👨‍🚒 Beware arsonist fireman:
  - 🔥 take away native web features

  - 💧 resell them as "optimisations"

- 😤 [View Transition API](https://developer.chrome.com/docs/web-platform/view-transitions/)
- 🤩 [Native dialog element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog)
]
.footnote[Timeless advice: use the right tool for the job (even if it's an SPA)]

???
- UNIX philosophy
  - Do one thing well
  - Write programs that work together
  - Code to a universal interface
- Complexity Budget: Put complexity where it's needed, but nowhere else. An out of control SPA will consume your complexity budget.
- Many newer generation tools should meet these requirements, but they are likely javascript based.
- Employers are getting strict around accessibility, maybe progressive enhancement
---
background-image: url(img/7ye438.jpg)
background-position: right
background-size: 50%

.pull-left[
### REST: an old friend
Roy Fielding's dissertation gave us concepts like URIs, GET, PUT, POST, DELETE, etc.

[HTMX picks up where Rails left off](https://intercoolerjs.org/2016/01/18/rescuing-rest.html)

#### Hypermedia
Hypermedia is the normal language of the web. Think HTML and HTTP.

We get around with few hypermedia controls, but what if we had more?
```html
<form> <a>
```
*HTMX extends HTML, for modern apps*
]

.footnote[Book: http://hypermedia.systems/]

???
But what if there were more powerful Hypermedia controls? (HTMX!)
---
background-image: url(img/7y4ssl.jpg)
background-position: 10% 67%
background-size: 50%

## HATEOAS
.pull-left[
- Hypermedia from the server is your application state. 

- Minimal client state.

*HTMX and HATEOAS help each other*
]

.pull-right[
```html
<section>
  <img src="/cover.jpg">
  <dl>
    <dt>Title</dt>
    <dd>Hypermedia Systems</dd>
    <dt>Subject</dt>
    <dd>Web development</dd>
  </dl>
  <nav>
    <a href="/book/1/delete">Delete</a>
    <a href="/book/1/edit">Edit</a>
  </nav>
</section>
```
.footnote[Book: http://hypermedia.systems/]
]

???
JSON APIs, AKA "RPC" APIs, can't *really* support HATEOAS.
---
background-image: url(img/original.png)
background-size: contain
background-position: 0 85%

## HTMX is on a mission
- Reign in client state chaos with HATEOAS

- Give the browser Hypermedia superpowers

- Restore HTML to its RESTful place in the web

???
Early web was simple because we had simple tools.
Then things got crazy with client state management.
We can choose simplicity by using well designed tools like HTMX.
---
background-image: url(img/createdwith.jpeg)
background-position: 50% 65%

## Demo

https://replit.com/@rowinf/Rails-Demo

https://htmx.org/examples/

https://htmx.org/migration-guide-hotwire-turbo/

https://vanillaweather.com/


.footnote[Slideshow created using [remark](http://github.com/gnab/remark).]
---
## Thanks!