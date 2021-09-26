---
layout: post
title: "Wrapping Up"
date: 2021-09-25 22:00:00 -0400
categories: blueOcean
---
### Straightforward Bells and Whistles
The practice of adding sparkle to CSS is feeling more and more second nature. It is more of something to naturally do than of new vistas to explore. Mixing and matching Flexbox and Grid gives the power to control just about anything on the page as long as one is willing to commit the time.

### The Cool New Thing
What really knocked my socks off this week was finishing the process of producing a rank for a single username, based on the db spontaneously generating that rank. I figured out last week that I needed to write the query as a function and that upon running the function, I could run it "with ordinality." But the syntax for doing such a thing was still a mystery. This week the fog cleared, and all that it really took was taking a second glance at the Postgres docs (https://www.postgresql.org/docs/9.1/sql-createfunction.html). One pice that I found really strange, and seemed contrary to older random Postgres articles around writing functions, was that in the function, the query is inserted within two dollar signs which act as parentheses. It looks funny, but it works. In the end, between the function and the ensuing query, it didn't end up being too many lines of code. But the world of functions has been opened up. And a new day has dawned! 