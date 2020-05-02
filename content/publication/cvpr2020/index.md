---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Meshed-Memory Transformer for Image Captioning"
authors: [Marcella Cornia, Matteo Stefanini, Lorenzo Baraldi, Rita Cucchiara]
date: 2020-06-07T18:08:23+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-04-07T18:08:23+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/CVF Conference on Computer Vision and Pattern Recognition - CVPR 2020"
publication_short: "CVPR 2020"

abstract: "Transformer-based architectures represent the state of the art in sequence modeling tasks like machine translation and language understanding. Their applicability to multi-modal contexts like image captioning, however, is still largely under-explored. With the aim of filling this gap, we present a Meshed Transformer with Memory for Image Captioning. The architecture improves both the image encoding and the language generation steps: it learns a multi-level representation of the relationships between image regions integrating learned a priori knowledge, and uses a mesh-like connectivity at decoding stage to exploit low-and high-level features. Experimentally, we investigate the performance of the M Transformer and different fully-attentive models in comparison with recurrent ones. When tested on COCO, our proposal achieves a new state of the art in single-model and ensemble configurations on the Karpathy test split and on the online test server. We also assess its performances when describing objects unseen in the training set."

# Summary. An optional shortened abstract.
summary: "*IEEE/CVF Conference on Computer Vision and Pattern Recognition* - CVPR 2020"

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/1912.08226.pdf
url_code: https://github.com/aimagelab/meshed-memory-transformer
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
  caption: "Meshed-Memory Transformer"
  focal_point: "Top"
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
#### Qualitative examples:

![m2results](/img/m2results.png)

## Results:

Meshed-Memory Transformer has been state-of-the-art model on the COCO test server [Leaderboard](https://competitions.codalab.org/competitions/3221#results) for several months:
![COCOLeaderboard](/img/CocoLeaderboard.PNG)

## Full Paper: [pdf](https://arxiv.org/pdf/1912.08226.pdf)

## Code: [github](https://github.com/aimagelab/meshed-memory-transformer)

## Please cite with the following BibTeX:

```
@article{cornia2019m,
  title={M $\^{} 2$: Meshed-Memory Transformer for Image Captioning},
  author={Cornia, Marcella and Stefanini, Matteo and Baraldi, Lorenzo and Cucchiara, Rita},
  journal={arXiv preprint arXiv:1912.08226},
  year={2019}
}
```
