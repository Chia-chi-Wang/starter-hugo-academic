---
title: Course Project of "Mechanical Vibration"
summary: Torque vibration analysis of steam turbine generator set.
tags:
  - Course Project
date: '2022-05-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:


links:

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---

As shown in the figure, the turbine and generator are connected by a reducer. When the generator is short-circuited, the short-circuit torque is too large, and the safety coupling is disconnected at this time to protect the generator. This paper first abstracts the system, simplifying the steam turbine and pump to shaft 2 (high-speed shaft), the generator to shaft 1 (low-speed shaft), and shaft 1, shaft 2, and reducer with a certain inertia and torsional stiffness instead. Second, since the speeds of the two axes are different, the two axes are equated to the same axis to obtain a multi-degree-of-freedom torsional vibration system. By solving the mass matrix, stiffness matrix, and damping matrix of the system, the differential equations of motion of the system can be obtained. Using mode shape analysis, the natural frequencies and mode shape vectors of each order can be obtained to decouple the problem. For the damping matrix, using the proportional damping model, set the damping matrix form as: $c = \alpha M+\beta K$, we can diagonally process the damping matrix. To simplify the calculation, mode shape truncation is taken and the first 12-order mode is used for discussion. For the solution of the transient response, you can first assume that the safety coupling is constantly open, find the torsional angle response of the response, and find the time point of disconnection according to the critical angle value at the time of disconnection. Starting from this time point, taking the displacement and velocity at that moment as the initial values, the re-solution obtains the response after the disconnection.
