![Konstantin Kudryashov running workshop](workshopping.jpeg)

Although I’ve written software for years, I realised only recently that writing
code was more about communicating with humans than computers. To become a
better engineer, I realised I needed to become a better communicator both
inside and outside the code to create a stronger connection between the code I
write and the people it helps.

As a technical consultant as well as an engineer, I spend as much time working
with business stakeholders and sticky notes as I do with fellow engineers and a
code editor. Bridging both worlds often means I have to find new ways of
communicating ideas and information and ensuring that nothing gets lost in
between. This blog documents my progress at improving communication between the
people caring about software products and the people building them. I hope you
find this blog a useful starting point for thinking about software development
as a talking, rather than writing, activity and would be interested to hear
your thoughts on the subjects discussed here.

## Posts

### [Maximum Feasible Miracle](posts/2019/6/maximum-feasible-miracle.md)

Current technological constraints heavily influence many of our product
decisions. When figuring out the minimum in your Minimum Viable Product takes
too much energy, consider temporarily discarding all of the constraints. Later,
incrementally reintroduce them back, monitoring the impact on the product.
Exploring product without constraints allows your team to reconnect with the
underlying customer behaviour and identify both smaller and better ways to
serve it — the ways hidden behind years of bad memories about intractable
problems.

### [Impactful Reports](posts/2019/6/impactful-reports.md)

Often, when building a software system, teams are asked to develop a series of
reports or even a generalized report builder. Every single requested report is
hiding a need, which it was devised to fulfill. Stating the need explicitly and
reworking specifications to better reflect it, makes it easier to plan,
prioritize and deliver the software that matters. Clearly stated objectives
allow teams to fundamentally challenge underlying assumptions and develop
reporting capabilities with a bigger impact.

### [Sharing Learning via Code](posts/2019/6/sharing-learning-via-code.md)

When you build a new feature as a team, and it requires much new learning, do
not hoard new knowledge in your head. Instead, incrementally commit each unit
of learning into working code. Committing and exposing the intermediate
learning through code helps to spread the knowledge within the team faster.
Problems get discovered early into implementation instead of much later.
Moreover, the need for comprehensive documentation decreases as knowledge
sharing through code and collaboration increases.

### [Valuable Products](posts/2016/3/valuable-products.md)

The problem with talking about the “value” of software is that it is often
perceived differently by people using it and people building it. Users
increasingly expect software to change. However, when building software
products, we (the creators) often fail to accommodate these expectations,
focusing instead on the elusive “finished” product. That creates a tension
between what users want and what we deliver.

### [The Innovation Slider](posts/2016/1/innovation-slider.md)

Every time I meet a client to discuss their new project plans, I encounter the
same question: "I want my software to be unique and different. How much will it
cost?”. The problem is that unique products and true innovation are difficult
to estimate, and even harder to accurately budget for. Helping a business find
the balance between the innovation they need, and the predictability they want
led me to create the Innovation Slider, a tool you can use to harmonise the
split between innovation and predictability in software projects.

### [Economy of Tests](posts/2015/1/economy-of-tests.md)

A common complaint with teams that first try their hand at automated testing,
is that it is hard, costly, and not worth the effort. On the other hand,
supporters say that it saves them time. In this post, we’ll try to add some
nuance to the discussion. We’ll take a look at how different levels of
automated testing affect the cost of development, both in the short and the
long term, for both greenfield and brownfield projects. Finally, we’ll look at
a simple strategy for introducing tests and migrating them across test levels,
in order to reduce maintenance costs.

### [Introducing Modelling by Example](posts/2014/10/introducing-modelling-by-example.md)

For the last year I have been experimenting with the new approach to a
Behaviour-Driven Development, which could be summarised as "Ubiquitous Language
is a thing again". The core premise of this approach is that if you take
Ubiquitous Language seriously and push for it in your scenarios, you open the
door to doing a Domain-Driven Design while you're doing Behaviour-Driven
Development's red-green-refactor cycle. By embedding Ubiquitous Language in
your scenarios, your scenarios naturally become your domain model, which you
can use to develop the most important part of your application - a core domain.
