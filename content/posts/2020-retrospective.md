---
title: "Zero to $50000 in six months: growing Ritza, a technical publishing company, as a productized service"
date: 2020-12-31T12:52:16+02:00
draft: false
---

For more background, you can find previous retrospectives for
[<u>2019</u>](https://sixhobbits.github.io/hugoblog/posts/2019-retrospective/),
[<u>Q1
2020</u>](https://sixhobbits.github.io/hugoblog/posts/2020-q1-retrospective/),
[<u>April
2020</u>](https://sixhobbits.github.io/hugoblog/posts/2020-04-retrospective/),
and [<u>May
2020</u>](https://sixhobbits.github.io/hugoblog/posts/2020-05-retrospective/).

In July, I founded Ritza - a technical publishing company that offers
(very) technical content marketing, developer advocacy as a service, and
a bunch of related publishing services. What does that mean exactly? We
publish ebooks, documentation, and blog articles, usually with the goal
of helping developers or technical managers in some way. For example, we
did [<u>https://codewithrepl.it</u>](https://codewithrepl.it) as a
companion website for [<u>Repl.it</u>](https://repl.it/). We offer this
content on a subscription basis

The title is clickbait: I’ve been working on Ritza for quite a bit
longer than 6 months, but it only became ‘real’ in July this year as a
registered business which I was devoting 100% of my time to, and -- from
what I’ve seen in Maker circles -- writing about how you got your
initial revenue is the best way to 2x your revenue, so the title is also
an experiment in some ways.

I’ve gained a lot by reading about
[<u>other</u>](https://www.coryzue.com/open/)
[<u>people’s</u>](https://twitter.com/SahinKevin/status/1334142235051520000)
[<u>transparent</u>](https://themakingof.carrd.co)
[<u>revenues</u>](https://nomadlist.com/open). That said, talking about
money is still weird for me, and I think it’s harder to be fully
transparent when offering services instead of a SaaS - there is more
customized pricing both in charging for work and paying contractors and
talking money is a sure way to get emotions up and make people feel like
they got a bad deal.

Here are some high level figures for the last 6 months to get it out of
the way.

Revenue
-------

Ritza made between $6000 and $14000 revenue each month between July and
December, with a total revenue of around $58000 for the last two
quarters of 2020.

This was below my target of hitting $20000/month in 2020, but --
especially given circumstances -- this was way better than my worst case
predictions. There was no clear overall trend, but a definite drop off
in November and December, with July and October being our best
performing months.

All of our contracts are month-to-month and one client went quiet in
October. While most of our revenue comes from recurring contracts, we
also did some one-off work in July through October, but none in November
or December.

Nearly all of our costs are from paying writers, editors, and designers.
We additionally spent money on office space that we don’t use (over
$500/month for coworking space that is tied to my ‘visa facilitation’,
which is a requirement for my visa in the Netherlands, and accounting
costs. We pay a few dollars a month for various online services, such as
GSuite and various domains, and we have credits on DigitalOcean and AWS
which take care of all of our hosting for now. We also recently picked
up a subscription to [<u>SemRush</u>](https://www.semrush.com/) - a tool
that I think is overpriced and slightly shady, but which has proven its use
in better understanding what people are searching for.

Overall, this revenue allows me to pay myself a ‘salary’ that pays rent
in Europe, with more cash than my previous job as Head of Technology for
a South African EdTech startup.

That said, my plan B after quitting my previous role was to find a full
time job remotely or in Europe. I shopped around a bit and did some
interviews for roles that were offering $150k-$200k/year + benefits so
in terms of opportunity cost I am still ‘losing’ for now and it remains
to be seen how far Ritza can scale with its current business model.

Experiments and content
-----------------------

Our bread-and-butter service is producing technical content: writing
[<u>tutorials</u>](https://codewithrepl.it) and
[<u>blog</u>](https://datarevenue.com/en-blog)
[<u>content</u>](https://virtasant.com/blog/data-lake-vs-data-warehouse/).
While our mission is to unlock marketing budgets “for good” by making
this content available for free, we have also helped companies produce
and improve internal proprietary content that they then sell.

On the side, I have been playing around with the idea of building online
tools to help with producing and publishing content. None of these got
the attention they needed to get off the ground, but they remain on the
back burner as ideas I’d still like to work on. They included

* **[<u>‘vs’ Graphs</u>](https://vsgraphs.ritza.co/) -** a tool
     inspired by [<u>this
     article</u>](https://medium.com/applied-data-science/the-google-vs-trick-618c8fd5359f).
     I built this because I needed it - especially for writing articles
     about ‘hot’ spaces like MLOps and DevOps, it’s easy to get
     overwhelmed by the sheer number of tools, products, and services.
     This visualisation makes it easy to explore a new area and find
     the most popular products, as well as to find out how a specific
     product ‘fits in’ (“Oh X plays in the same space as SageMaker”).
     This is also useful to write ‘[<u>x vs y vs
     z</u>](https://datarevenue.com/en-blog/data-dashboarding-streamlit-vs-dash-vs-shiny-vs-voila)’
     articles, which turn out to be very low hanging fruit in terms of
     ranking well on Google. If you’ve ever tried to find out how two
     products or services compare and found yourself frustrated at all
     the low quality ‘alternativeTo-like’ pages you’ll know why these
     articles are useful, and I ended up also building a [<u>related
     tool</u>](http://versus.ritza.co) to outline these articles
     automatically. The fun part about this was that I built it in a
     single train ride using only my iPad and repl.it, which felt like
     a big step in the direction of being able to code as a nomad.

* **[<u>Rate my Copy</u>](https://ratemycopy.ritza.co/)** - Also while
     researching products and services, I got annoyed at how cliched
     most landing page copy is, and even more annoyed by how
     uninformative it is. I scraped over 20000 landing pages for online
     products and services and built a database of the most commonly
     used cliches.

* **[<u>Opinionated tutorial
     Publisher</u>](https://ritza.co/experiments/opinionated-tutorial-publisher.html)** -
     while most of our clients have their own systems already in place
     to host the content we produce, I was frustrated at how hard it
     was to generate a lightweight, good looking page with writing,
     code samples, and images. There’s a long way to go on the design
     still, but some of the other pieces are in place.

I won’t link to all the content we produced in 2020, but some highlights
are

* **[<u>CodeWithRepl.it</u>](https://www.codewithrepl.it/) -** a set
     of tutorials, also in book form. This was very well received on
     reddit and continues to rank well for a variety of search terms. I
     am strongly against most kinds of tracking, but caved at the end
     of the year and installed Plausible Analytics on it, which also
     makes it easy to share publicly everything we track:
     [<u>https://plausible.io/codewithrepl.it</u>](https://plausible.io/codewithrepl.it).
     Traffic has died off a lot at the end of the year (based on some
     server logs analytics I did), but rankings continue to improve and
     I think the content is in pretty good shape now (we’ve done
     several sets of updates since initially publishing it).

* **[<u>DataRevenue Blog</u>](https://datarevenue.com/en-blog)** -
     This is the project I’ve personally learned the most from this
     year, writing about everything from general machine learning
     through BioTech (I didn’t even know what Metabolomics was in 2019,
     so there was a steep learning curve to write some of the articles
     about that).

Growing a team
--------------

While we initially mainly worked ad-hoc with contractors on various
projects, towards the end of the year Ritza started feeling like a real
company with a core team. [<u>Eugene
Dorfling</u>](https://dev.to/eugenedorfling/technical-writing-internship-it-can-only-get-better-from-here-10ma)
joined in October for a full time internship and is continuing in 2021
as an Associate Developer Advocate. Several other freelancers have
regularly worked on projects throughout the year. I’m still trying to
figure out if the next full time hire should be a senior writer (to take
over some of the writing I am doing), or a managing editor (to help out
with client feedback and all the nitty-gritty but super important
aspects of getting from ‘first draft’ to ‘production’), but I’m leaning
more towards the latter.

What IS Ritza?
--------------

Friends and family still don’t really understand what Ritza is. I get a
lot of “uh, so you make IT manuals, right? Isn’t that just telling
people to turn stuff off and on again until it works?”

Ritza is probably closest to a ‘content marketing agency’ at this stage.
But I really dislike most content marketing agencies. Not to name and
shame, but there’s definitely decent demand for very low cost content
such as
[<u>https://contentfly.com/blog/tag/content-sample/</u>](https://contentfly.com/blog/tag/content-sample/),
and I honestly can’t see how that adds any value to the world at all, so
I want to avoid being pulled in that direction or associated with
content like that.

My initial response to this was to try to move towards “Developer
Advocacy as a Service”, but it doesn’t really role off the tongue, and
I’m not sure that “Developer Advocacy” is actually a job that will
survive the Tech Bubble I’m convinced we’re in.

Towards the end of the year, it became clear that Ritza is simply a
publishing company (or at least the very beginnings of one). We are
slowly becoming experts in the entire publishing pipeline, from sourcing
high quality writing, through editing, designing, publishing, and
distributing. While we have started out with a strong focus on technical
content, there’s no reason that that has to remain a core focus forever.
I’ve had pretty mediocre experiences with technical publishing companies
like PacktPub and I believe non-tech publishers that have existed for
decades or centuries are even more in need of a bit of modernization.

I previously helped my Dad publish his first book of (hilarious)
[<u>memoirs as a Doctor in Africa</u>](http://leanpub.com/doctor) and
during the slower period between Christmas and New Year now I spent some
time tweaking the landing page, making a sample available, and doing
some marketing. So far, all I’ve done is burn $50 on Reddit ads that led
to zero sales, but I think with some experimentation with different
distribution channels there’s more potential. Stay tuned.


