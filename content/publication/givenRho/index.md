---
title: "An efficient algorithm for generating directed networks with predetermined assortativity measures (work in progress)"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tiandong Wang
- Jun Yan
- Yelie Yuan
- Panpan Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: Assortativity coefficients are important metrics to analyze both directed and undirected networks. In general, it is not guaranteed that the fitted model will always agree with the assortativity coefficients in the given network, and the structure of directed networks is more complicated than the undirected ones. Therefore, we provide a remedy by proposing a degree-preserving rewiring algorithm, called DiDPR, for generating directed networks with given directed assortativity coefficients. We construct the joint edge distribution of the target network by accounting for the four directed assortativity coefficients simultaneously, provided that they are attainable, and obtain the desired network by solving a convex optimization problem. Our algorithm also helps check the attainability of the given assortativity coefficients. We assess the performance of the proposed algorithm by simulation studies with focus on two different network models, namely Erdős–Rényi and preferential attachment random networks. We then apply the algorithm to a Facebook wall post network as a real data example. The codes for implementing our algorithm are publicly available in a [R package wdnet](../wdnet/).

# Summary. An optional shortened abstract.
summary: We provide a degree-preserving rewiring algorithm, called DiDPR, for generating directed networks with given directed assortativity coefficients.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
