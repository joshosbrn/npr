# Prototyping NPR.org
Jekyll powered prototyping kit for NPR.org :radio: :satellite: :100:

For NPR's 15th [Serendipity Day](http://www.niemanlab.org/2011/08/npr-tries-something-new-a-day-to-let-managers-step-away-and-developers-play/), I set out to create a tool to help our [designers](https://twitter.com/nprdesign/lists/dm-design) prototype new features for NPR.org quickly & easily. I've come up with a way of using the Jekyll templating/layout system to break structural elements of our site into includes & layout elements. Story content is fully powered by markdown, and metadata is pulled from the front-matter of each .md file.

## Getting Started
1. If you're unfamiliar with Jekyll, or need some help installing the gem on your machine, check out the [Jekyll repo](https://github.com/jekyll/jekyll).

2. Clone this repository on your machine & create a new branch using the name of your prototype.

3. Hack away!

## Open Questions:
* How might we keep this template up to date with the most recent code changes from our production code base?
* Is there a Markdown parser that can understand CSS classes? (We're currently using mark-UP in our mark-DOWN and that's no fun for anyone)
