---

title: 'The Explosion Afraid of Itself'
# Single author. `me` references your profile folder under content/authors/.

authors:
  - me
date: '2026-08-01T00:00:00Z'        # TODO: set the actual AGI-26 publication date
publishDate: '2026-06-16T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: 'Artificial General Intelligence 2026 (AGI-26)'
  short_name: 'AGI-26'
peer_reviewed: true
# Accepted manuscript under Springer's licence — barred from open access / CC.
open_access: false
abstract: >-
  For an active inference agent evaluating recursive self-modification, the
  expected free energy cost of modification is bounded below, monotone in
  modification magnitude and superlinearly compounding under recursion. The brake
  is endogenous: a free-energy minimizer rationally allocates effort to predict
  its own successor, and the residual uncertainty grows at least quadratically
  with the magnitude of perceptual change. The two costs are complementary.
  Perceptual modification loads an unconditional ambiguity penalty — the agent
  cannot cheaply predict how a changed perception would see. Modifications that
  move the policy, preference drift above all, load a risk penalty, bounded below
  quadratically and conditional on a non-desperate regime: the divergence between
  the outcomes the agent's current model foresees and its preferences. Dynamics
  and prior-belief updating carry the weakest cost, the components the brake
  leaves freest. The brake is therefore strongest on the two safety-relevant
  quantities: whether the agent can still perceive, and whether it still wants
  what its stakeholders want. It relaxes under shared crisis, as an aligned agent
  would endorse. Computational validation on discrete POMDPs confirms the
  quadratic ambiguity floor and its path-independence, the complementary
  two-channel structure, and the brake's relaxation under desperation, across
  models from 28 to 1,738 parameters and four trajectory geometries. Alignment,
  once achieved, is preserved as an architectural property rather than an external
  constraint.
summary: 'A geometric braking mechanism on recursive self-modification for Active Inference agents, arguing that radical and runaway self-improvement meets intrinsic curvature limits.'
tags:
  - AI Safety
  - AGI
  - Recursive Self-Improvement
  - Information Geometry
featured: true
hugoblox:
  ids:
    doi: ''                          # TODO: add the Version-of-Record DOI once Springer issues it
links:
  - type: pdf
    url: 'The_Explosion_Afraid_of_Itself, Buteau, 2026.pdf'
image:
  caption: ''
  focal_point: ''
  preview_only: false
projects:
  - safer-explosions
slides: ''
---

**Accepted manuscript notice.** This version of the contribution has been accepted for publication, after peer review, but is not the Version of Record and does not reflect post-acceptance improvements, or any corrections. The Version of Record will be made available online at: after the publication of AGI-26's proceedings (estimated August 2026). Use of this Accepted Version is subject to the publisher's Accepted Manuscript terms of use https://www.springernature.com/gp/open-research/policies/accepted-manuscript-terms

---

tags:
  - Active Inference
  - Recursive self-improvement
  - Intelligence Explosions
  - AGI Safety

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: ''

# Custom links
links:
  - type: pdf
    url: ""
  - type: code
    url: https://github.com/HugoBlox/kit
  - type: dataset
    url: https://github.com/HugoBlox/kit
  - type: slides
    url: https://www.slideshare.net/
  - type: source
    url: https://github.com/HugoBlox/kit
  - type: video
    url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
# ---

# > [!NOTE]
# > Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

# > [!NOTE]
# > Create your slides in Markdown - click the _Slides_ button to check out the example.

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
