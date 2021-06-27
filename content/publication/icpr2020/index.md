---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Novel Attention-based Aggregation Function to Combine Vision and Language"
authors: [Matteo Stefanini, Marcella Cornia, Lorenzo Baraldi, Rita Cucchiara]
date: 2020-07-29T22:46:23+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-04-29T22:46:23+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Pattern Recognition - ICPR 2020"
publication_short: "ICPR 2020"

abstract: "The joint understanding of vision and language has been recently gaining a lot of attention in both the Computer Vision and Natural Language Processing communities, with the emergence of tasks such as image captioning, image-text matching, and visual question answering. As both images and text can be encoded as sets or sequences of elements -like regions and words- proper reduction functions are needed to transform a set of encoded elements into a single response, like a classification or similarity score. In this paper, we propose a novel fully-attentive reduction method for vision and language. Specifically, our approach computes a set of scores for each element of each modality employing a novel variant of cross-attention, and performs a learnable and cross-modal reduction, which can be used for both classification and ranking. We test our approach on image-text matching and visual question answering, building fair comparisons with other reduction choices, on both COCO and VQA 2.0 datasets. Experimentally, we demonstrate that our approach leads to a performance increase on both tasks. Further, we conduct ablation studies to validate the role of each component of the approach."

# Summary. An optional shortened abstract.
summary: "*International Conference on Pattern Recognition* - ICPR 2020"

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

url_pdf: https://arxiv.org/pdf/2004.13073.pdf
url_code:
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
  caption: "Attention-based Aggregation Function"
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

### An effective alternative to the CLS Token!

#### Model in details:

![pipeline](/img/aggregation_pipeline.png)

## Full Paper: [pdf](https://arxiv.org/pdf/2004.13073.pdf)

## Please cite with the following BibTeX:

```
@article{stefanini2020novel,
  title={A Novel Attention-based Aggregation Function to Combine Vision and Language},
  author={Stefanini, Matteo and Cornia, Marcella and Baraldi, Lorenzo and Cucchiara, Rita},
  journal={arXiv preprint arXiv:2004.13073},
  year={2020}
}
```
