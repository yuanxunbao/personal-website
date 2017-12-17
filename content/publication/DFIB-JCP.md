+++
title = "An Immersed Boundary Method with Divergence-Free Velocity Interpolation and Force Spreading"
date = "2017-10-15"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Y. Bao**", "A. Donev", "B. E. Griffith", "D. M. McQueen", "C. S. Peskin"]

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
publication = "In *Journal of Computational Physics*."
publication_short = "In *J. Comput. Phys.*"

# Abstract and optional shortened version.
abstract = "The Immersed Boundary (IB) method is a mathematical framework for constructing robust numerical methods to study fluid–structure interaction in problems involving an elastic structure immersed in a viscous fluid. The IB formulation uses an Eulerian representation of the fluid and a Lagrangian representation of the structure. The Lagrangian and Eulerian frames are coupled by integral transforms with delta function kernels. The discretized IB equations use approximations to these transforms with regularized delta function kernels to interpolate the fluid velocity to the structure, and to spread structural forces to the fluid. It is well-known that the conventional IB method can suffer from poor volume conservation since the interpolated Lagrangian velocity field is not generally divergence-free, and so this can cause spurious volume changes. In practice, the lack of volume conservation is especially pronounced for cases where there are large pressure differences across thin structural boundaries. The aim of this paper is to greatly reduce the volume error of the IB method by introducing velocity-interpolation and force-spreading schemes with the properties that the interpolated velocity field in which the structure moves is at least and satisfies a continuous divergence-free condition, and that the force-spreading operator is the adjoint of the velocity-interpolation operator. We confirm through numerical experiments in two and three spatial dimensions that this new IB method is able to achieve substantial improvement in volume conservation compared to other existing IB methods, at the expense of a modest increase in the computational cost. Further, the new method provides smoother Lagrangian forces (tractions) than traditional IB methods. The method presented here is restricted to periodic computational domains. Its generalization to non-periodic domains is important future work."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_custom = [{name = "Journal", url = "https://doi.org/10.1016/j.jcp.2017.06.041"}]
url_pdf = "https://arxiv.org/pdf/1701.07169.pdf"
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
# caption = "My caption :smile:"

+++

