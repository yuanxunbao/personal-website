+++
title = "A Fluctuating Boundary Integral Method for Brownian Suspensions"
date = "2017-11-06"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Y. Bao**", "M. Rachh", "E. E. Keaveny", "L. Greengard", "A. Donev"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Submitted to *Journal of Computational Physics*."
publication_short = "Submitted to *J. Comput. Phys.*"

# Abstract and optional shortened version.
abstract = "We present a fluctuating boundary integral method (FBIM) for Brownian Dynamics of suspensions of rigid particles of complex shape immersed in a Stokes fluid. We develop a linear-scaling algorithm to generate, together, both the deterministic (mean) component of the particle linear and angular velocities that arise in response to the applied forces and torques, as well as the stochastic (fluctuating) Brownian displacements that arise in response to the thermal fluctuations in the fluid. In this work we restrict our attention to two-dimensional periodic domains, however, our key ideas can be extended to three dimensions and confined suspensions. Our approach relies on a first-kind boundary integral formulation of a Stochastic Stokes Boundary Value Problem (SSBVP) in which a random surface velocity is prescribed on the particle surface. This random surface velocity has zero mean and covariance proportional to the Green's function for the Stokes flow (Stokeslet). We demonstrate that the Brownian displacements generated by solving this SSBVP obey the fluctuation-dissipation balance relation. Furthermore, we demonstrate that discretizing the first-kind formulation using standard boundary integral techniques leads to an efficient numerical method that strictly preserves discrete fluctuation-dissipation balance (DFDB). Near-field contributions to the Brownian displacements are efficiently approximated by iterative methods in real space, while far-field contributions are rapidly generated by fast Fourier-space methods based on fluctuating hydrodynamics. FBIM provides the key ingredient for time integration of the overdamped Langevin equations for Brownian suspensions of rigid particles. We demonstrate that FBIM obeys DFDB by performing equilibrium BD simulations of suspensions of starfish-shaped bodies using a random finite difference temporal integrator."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1709.01480.pdf"
url_preprint = "https://arxiv.org/abs/1709.01480"
# url_code = "#"
# url_dataset = "#"
# url_project = "#"
# url_slides = "#"
# url_video = "#"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.