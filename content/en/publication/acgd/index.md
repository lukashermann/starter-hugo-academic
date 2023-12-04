---
title: 'Adaptive Curriculum Generation from Demonstrations for Sim-To-Real Visuomotor Control'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - lukas
  - Max Argus
  - Andreas Eitel
  - Artemij Amiranashvili 
  - Wolfram Burgard 
  - Thomas Brox

# Author notes (optional)

date: '2020-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2020)*
publication_short: In *IROS 2020*

abstract: We propose Adaptive Curriculum Generation from Demonstrations (ACGD) for reinforcement learning in the presence of sparse rewards. Rather than designing shaped reward functions, ACGD adaptively sets the appropriate task difficulty for the learner by controlling where to sample from the demonstration trajectories and which set of simulation parameters to use. We show that training vision-based control policies in simulation while gradually increasing the difficulty of the task via ACGD improves the policy transfer to the real world. The degree of domain randomization is also gradually increased through the task difficulty. We demonstrate zeroshot transfer for two real-world manipulation tasks, pick-andstow and block stacking. A video showing the results can be found at https://lmb.informatik.uni-freiburg.de/projects/curriculum/  

# Summary. An optional shortened abstract.
summary: IROS 2020

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1910.07972.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://lmb.informatik.uni-freiburg.de/projects/curriculum/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=WRH2bH2CJco'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
