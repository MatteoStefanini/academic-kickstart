---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "CaMEL: Mean Teacher Learning for Image Captioning"
authors: [Manuele Barraco, Matteo Stefanini, Marcella Cornia, Silvia Cascianelli, Lorenzo Baraldi, Rita Cucchiara]
date: 2022-04-16T13:54:07+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-04-16T13:54:07+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Pattern Recognition - ICPR 2022"
publication_short: " ICPR 2022"

abstract: "Describing images in natural language is a fundamental step towards the automatic modeling of connections between the visual and textual modalities. In this paper we present CaMEL, a novel Transformer-based architecture for image captioning. Our proposed approach leverages the interaction of two interconnected language models that learn from each other during the training phase. The interplay between the two language models follows a mean teacher learning paradigm with knowledge distillation. Experimentally, we assess the effectiveness of the proposed solution on the COCO dataset and in conjunction with different visual feature extractors. When comparing with existing proposals, we demonstrate that our model provides state-of-the-art caption quality with a significantly reduced number of parameters. According to the CIDEr metric, we obtain a new state of the art on COCO when training without using external data. The source code and trained models are publicly available."

# Summary. An optional shortened abstract.
summary: "*International Conference on Pattern Recognition* - ICPR 2022"

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2202.10492.pdf
url_code: https://github.com/aimagelab/camel
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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

#### Model in details:

![CaMEL](/img/camel.jpg)

#### Qualitative examples:

![m2results](/img/camel_qualitatives.jpg)

## Full Paper: [pdf](https://arxiv.org/pdf/2202.10492.pdf)

## Code: [github](https://github.com/aimagelab/camel)

## Please cite with the following BibTeX:

```
@inproceedings{manuele2022camel,
  title={CaMEL: Mean Teacher Learning for Image Captioning},
  author={Manuele, Barraco and Stefanini, Matteo and Cornia, Marcella and Cascianelli, Silvia and Baraldi, Lorenzo and Cucchiara, Rita},
  booktitle={International Conference on Pattern Recognition},
  year={2022}
}
```
    
