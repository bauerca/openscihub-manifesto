
# Openscihub

This is an essay, whitepaper, whatever that rambles on about some (possibly
naive and misguided) ideas supporting a new online service for scientists we
call openscihub (or pursuescience, whichever one sounds cooler).

Contributors to this document:

- [Carl A. Bauer](https://github.com/bauerca)


## Summary

As scientific subdisciplines become more specialized, it becomes increasingly
difficult to connect with the public and educate newcomers
due to the accumulation of scientific jargon and concepts.
The proliferation of isolated journals with ever narrowing
scopes gives a fractured and disconnected feel to the science landscape. At the
same time, news outlets and discussion venues for more specialized communities
are required.

Journals are great and editors work very hard to find relevant reviewers and keep
the back-and-forth between reviewer and author respectful and constructive.
However, we wonder if it's possible for the peer review process to
manage itself. If peer review is openly viewable by the public and the
identities of the reviewers are exposed, will discussions moderate themselves
by virtue of the potential damage an ugly dispute could inflict on a scientist's
reputation?

Openscihub will be an online venue where scientific communities gather to
publish, discuss, and review their work. The primary goals of the project are
to define, organize, and consolidate focused lines of scientific research,
to bring expert scientific discussion to a public venue, and to increase interaction
between scientists and the general public.

The framework will be highly community-oriented. A major guiding principle
behind openscihub is the belief that an individual's or research group's scientific
work is only useful when it is relevant to some broader well-defined scientific
goal. Where there emerges a clear, worthwhile, and challenging scientific
pursuit, communities form.  We also believe that small communities with very
clear, targeted goals can have the greatest effect, which is why openscihub
will encourage the creation of small new communities and the subdivision of
popular communities into subcommunities with more refined goals.  Communities
will spawn, stagnate, subdivide, connect, and merge, creating a dynamic
graph of scientific inquiry.

Scientists will signup, join/create communities, and participate in communities by
submitting new scientific works and reviewing those contributed by others.
Communities will consist of articles, summaries, datasets, etc. and
discussion/peer review interfaces.
Moderators will keep discussions civil and relevant, resolve
disputes, and make decisions for the community.


## Background

### Scientific pursuits

All of scientific knowledge is, by definition, a giant set of ideas and
theories supported by an even larger set of facts, experiments, data, proofs,
etc. (i.e. evidence).  We will call each individual idea or theory a
*scientific pursuit* (for generality), and each bit of evidence that supports
or contributes to the pursuit a *contribution*.

Scientific pursuits come in many forms. They may be purely inquisitive (what
happened in the big bang?) or serve some technological purpose (let's build an
ultra-short-pulse x-ray laser).  They may be complete (the theory of classical
electrodynamics--barring magnetic monopoles :)) or in their infancy
(understanding the Higgs mechanism). They have widely-varying
scopes and efforts; building a multi-TeV supercollider is a massive scientific undertaking,
while developing a new time-stepping algorithm for plasma simulation can be a
one-group project.

### Communities

People form communities around scientific pursuits (or related pursuits),
and individuals feel like
members of a community when they make contributions or educate themselves
[(Glaser 2001)](http://www.tasa.org.au/docs/conferences/2001_01/031201%20Glaser.pdf).
The purpose of communities seems to derive from scientists' desire to promote
their work, network for job and funding opportunities, and stay up-to-date on the
latest research. By virtue of the subject matter, communities also inherently
provide checks on submitted ideas and conclusions, as research groups compete for
success and recognition in the field.

While some sociologists refute the existence of scientific communities
[(Knorr-Cetina
1982)](http://scholar.google.com/scholar?cluster=8069252351466314366), they
nevertheless manifest in the form of workshops, conferences, and journals (via
their networks of qualified peer reviewers).

### Relationships

#### Dependencies

Most new scientific pursuits depend on the discoveries made by other
pursuits, relying on technologies developed, theories confirmed, etc.
Identification of dependencies in a researcher's work establishes context and
builds credibility.
Currently, these dependencies are determined by the network
of citations in scientific publication.  Publication citations
are most often dependencies between *contributions*, not *pursuits*.

#### Contributors

Another relationship between pursuits is that of the contributor community.
There may be another way to describe this in terms of dependencies but here
goes.  A contributor community is like a sub-community. They are tackling a
specific problem relevant to another broader scientific pursuit.

You might say that the broader pursuit *depends* on the more specific,
contributing pursuit, but you might not. For example, a sub-pursuit might
be focused on building a single component of a giant machine (e.g.
steerer magnet systems for a particle accelerator). In this case, the dependency
concept fits. Alternatively,
the broader pursuit might simply be *interested* in the sub-pursuit
(the broader accelerator physics community is certainly interested in
plasma wakefield acceleration as a future technology); there is no explicit
dependency on plasma accelerator research to achieve immediate goals.

### A scientist's activities

- Attend conferences, present work
- Publish articles
- Interact with colleagues at institution
- Read papers
- Think about problems, write code, build apparatus
- Write grant proposals
- Review the work of peers
- Coffee and cookie breaks
- Colloquia
- Teaching

#### Grant proposals

PIs develop relationships with grant managers. Relationships must affect the distribution
of awards; it seems unlikely that grant managers can maintain objectivity toward all
submitted proposals.

#### Publishing

Choose a journal. The choice depends on the perceived impact of association with the
journal, likelihood of acceptance, and relevance to the purview of the journal.
Write the paper, in a format for that journal. Submit to a preprint
archive.

#### Reviewing

Review submitted journal articles as a duty to the practice. Reviewer gets to see
new work before it is published. Reviewer gets to exert influence over the presentation
of the new work.

One study showed no significant difference in the quality of
reviews between double-blind and open peer review scenarios.


## Online communities

We propose an
*online* manifestation of scientific communities.
They would serve the same purposes of promotion,
networking, news, and peer review just as journals, conferences, and workshops do today,
but with some possible advantages.

Online communities would capture important discussions that may otherwise occur only
behind the closed doors of double-blind peer review and conference/workshop
conversation. These discussions would become public record and possibly
fodder for some kind of reputation-building system.

Online communities might also serve as important organizational tools for related
scientific pursuits. Contributions would aggregate and persist in one central location
rather than scattered across institutional servers and journal archives. Researcher's
news sources would be community news feeds (although [search](scholar.google.com) and
[scientific social networks](https://researchgate.net) also provide excellent methods
of staying up-to-date).

Online communities could provide instant feedback on a researcher's latest
work through a publish-now, peer-review-and-revise-forever paradigm.

Online communities can be *small*. They can be small, because, once the
website infrastructure is built, a community just becomes a chunk of data on a
server, which is cheap. In contrast, traditional scientific communities defined by
conferences and journals with editors are expensive. Small communities
are important breeding grounds for new major discoveries. The more easily researchers
can gather and establish small communities around new ideas, the faster they can
iterate on those ideas and accrue outside interest.
Additionally, if a community's pursuit fails to attract interest or its goals prove
too lofty, there is a record of the attempt to guide future investigations.

Online communities would bring together researchers that might otherwise find each
other only if they stumble upon an article while browsing papers on Google Scholar.
When a bright idea strikes them, they can traverse the network of online communities
searching for those that are already toying with the same idea. Think of it as a
coarser pre-search for content. Once they find the community they're looking for,
they no longer have to search, just listen and participate.


### Relationships

As previously mentioned, relationships between ideas
in the current system are defined by
citations. Often times, a paper will stuff many citations into their introductions
to set the context for their new result. Unfortunately this means many relevant
references are left out, while bibliographies become overcrowded.
Using online communities, we would like to see a graph of higher-level
dependencies between scientific pursuits that sets context in a more helpful
way to the reader and author.

Explicit dependencies
between online communities could make the navigation of prior work a
more pleasant experience for both new and veteran researchers.
Authors place in their articles only those references to other articles
(contributions) that are truly
significant to new conclusions. And if more background knowledge is required,
a reader knows which more general pursuit they should study.

In the case of contributing, or sub-, communities, explicit hierarchical relationships
seem useful for attaching broader contexts to targeted scientific
pursuits that may appear esoteric to the newcomer. These types of relationships
could help
scientists avoid unnecessary repetition in their presentations. Instead of
long-winded introductions, there can be links to broader explanations
and bodies of work collected in higher-level communities.
Newcomers that are confused by jargon and common knowledge can
easily browse the hierarchy for information.
Of course, the opposing view values comprehensive articles that
summarize context and previous work before describing new findings.
Honestly, I'm a fan of both. Repetition of common knowledge is never a bad thing.

The figure below shows an example of a portion of the graph of science
openscihub would like to construct. Most connections in this example are
depicted as two-way (two arrow heads) since there is a give-and-take
relationship to most pairs. For example, the plasma accelerator community
bases much of its work on the fundamental concepts widely known to the
accelerator physics community. At the same time, the accelerator physics
community has recognized that plasma acceleration techniques may fundamentally
change the particle accelerator landscape. Mutual dependencies and interests
exist. On the other hand, plasma accelerators are founded on a basic understanding
of electrostatic (Langmuir) waves in plasmas. For the most part, conclusions
flow in one direction (although, work by the plasma accelerator community
may very well reveal new subtleties in the understanding of electrostatic
waves; in fact, we believe most relationships between credible scientific
communities are two-way).

![Plasma Acc](https://dl.dropbox.com/s/16n4uh7azjwlm55/plasma-acc.png)

In the above figure, the real work is happening in the *laser/beam-driven plasma
accelerator* communities, which are small and focused. The generic communities
(physics, science, plasma, accelerators, Langmuir waves) act more like news outlets
and historical (and *historic*!) communities
for all their connected (sub)communities. Occasionally, new
discoveries may impact fundamental principles, in which case, they should be
submitted to communities with broader impact.

## Relevant existing projects

Here is a (growing) list of projects pursuing open science:

- [Open Science Framework](https://osf.io/)
- [Authorea](https://authorea.com)
- [ResearchGate](https://researchgate.net)
- [Academia.edu](https://academia.edu)

It seems like social networks of scientists (a la ResearchGate and Academia.edu)
primarily provide a service for resume-building and networking. This is great,
but we wonder if a greater focus on communities rather than the individual would
spur more interaction and constructive competition.

The projects in the above list all provide interesting new tools for interaction
between scientists, but seem to neglect the community aspect. It is our goal to
determine if the online community model is something scientists want; the best
course of action may be to join one of these efforts.

<!--
For example, new researchers must learn the jargon and concepts of their
future research area. This can be accomplished by reading select articles
or books (suggested by advisors and senior group members), and having
discussions with the group. More often, though, a new researcher is plunged
into work (simulating, building, etc.) and only grasps important concepts
after years of information osmosis.

We would like to establish online communities that surround scientific pursuits
and provide a history of discoveries relevant to that pursuit. As discoveries
within the pursuit rise in importance, they become the community canon.
-->

## Openscihub model

So, to summarize, the core components of the openscihub model seem to be:

- Scientists
- Communities
- Membership by contribution
- Community relationships

Except for scientists, openscihub appears to rely on a generic model for exclusive,
connected, online communities.

### Scientists; the individual

We'll need a user account system, user pages, etc.

User contributions (articles, data, whatever) must be submitted to a community.

### Communities

Communities should be easy to create.
They should not be easily
destroyable, because that would delete from the scientific record.

Communities will need moderators to keep discussions civil.
We should look to StackOverflow and maybe
Reddit for advice on effective moderator tools.

Communities will have home pages, news feeds, and a ranked list of
contributions. In general, communities will need tools for organizing
contributions in ways that best help members, newcomers, and the general
public learn the community's goals and conclusions.

There should be a separation between public discussion of community work
and expert peer review. Only members will be allowed to review work.

### Membership

Contribution to and membership in an online community should be interdependent
to ensure the quality of work and discussions.
It follows that, to gain membership in a community, one must first contribute
and prove their value.
This mirrors the current process of joining a scientific community, where a
researcher (usually a graduate student),

1. joins a research group (optional)
   and produces some work (necessary),
2. submits that work to a journal or a conference,
3. gets published or attends the conference,

and thereby is (usually unofficially) accepted into the community.

Communities should have
their own definitions of a "contribution", which may include

- writing a summary article
- writing an article describing unique research
- reviewing an existing community work
- proof of participation in a relevant conference.

Communities may also wish to implement invitation systems.

Of course, exclusivity can lead to abuse of power. For example, community moderators
can deny membership by arguing a contribution "isn't good enough," even though
the majority may feel otherwise.
Since the actions of
communities will be in the open, we hope the watchful eye of the public will
provide some level of oversight. We may have to implement a voting system that
somehow provides a measure of the community's/public's discontent for certain
actions.

### Community relationships

Relationships should only be one-way, like the "following/followers" systems in
social networks. A community does not
necessarily endorse the communities that are following it, but certainly
endorses those it follows. Alternatively, we can consider relationships by
mutual consent only. Of course, that would open the door for abuse/collusion.

Relationships should be kept generic. Only a community knows whether a relationship
is of the sub-community or dependency (or some other) kind. Maybe there should be
a system for giving the community some control over defining the type of
relationship.

## Tools

We hope that online scientific communities on openscihub inspire open, timely,
and respectful
peer review and discussion on the newest results in science. What tools do scientists
need for such joyous interaction? The ability to:

- post scientific articles
- markup scientific articles during review
- discuss scientific topics in forums
- create communities

Seems pretty simple so far.

### Posting work

The vast majority of scientists continue to exchange papers in PDF format. Some
efforts are pushing to change this ([authorea](https://authorea.com),
[eLife](http://www.elifesciences.org/lens/)). While these approaches are quite cool,
we think the most important aspect of a scientific work is its conclusion, which
scientists should strive to explain with simplicity and clarity. If the majority of
scientists can
continue making their point through static media, we don't see the
necessity for change. Therefore, we should focus on the efficient display and
markup of the most common format, PDF, and support/encourage new
formats as they gain popularity.

## Public outreach

Openscihub will facilitate conversation between the general public and the researchers behind
the work. A general-public Q&A system will accompany every community and
publication. Community experts will vote up and respond to insightful and useful
questions from the public. These dialogues could produce efficient learning
material for interested parties or researchers aspiring to join and contribute to the
community.
