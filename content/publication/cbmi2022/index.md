---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ALADIN: Distilling Fine-grained Alignment Scores for Efficient Image-Text Matching and Retrieval"
authors: [Nicola Messina, Matteo Stefanini, Marcella Cornia, Lorenzo Baraldi, Fabrizio Falchi, Giuseppe Amato, Rita Cucchiara]
date: 2022-09-14T12:59:46+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-14T12:59:46+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 19th International Conference on Content-based Multimedia Indexing"
publication_short: "CBMI2022"

abstract: "Image-text matching is gaining a leading role among tasks involving the joint understanding of vision and language. In literature, this task is often used as a pre-training objective to forge architectures able to jointly deal with images and texts. Nonetheless, it has a direct downstream application: cross-modal retrieval, which consists in finding images related to a given query text or vice-versa. Solving this task is of critical importance in cross-modal search engines. Many recent methods proposed effective solutions to the image-text matching problem, mostly using recent large vision-language (VL) Transformer networks. However, these models are often computationally expensive, especially at inference time. This prevents their adoption in large-scale cross-modal retrieval scenarios, where results should be provided to the user almost instantaneously. In this paper, we propose to fill in the gap between effectiveness and efficiency by proposing an ALign And DIstill Network (ALADIN). ALADIN first produces high-effective scores by aligning at fine-grained level images and texts. Then, it learns a shared embedding space -- where an efficient kNN search can be performed -- by distilling the relevance scores obtained from the fine-grained alignments. We obtained remarkable results on MS-COCO, showing that our method can compete with state-of-the-art VL Transformers while being almost 90 times faster. The code for reproducing our results is available."

# Summary. An optional shortened abstract.
summary: "Proceedings of the 19th *International Conference on Content-based Multimedia Indexing* - CBMI2022"

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

url_pdf: https://arxiv.org/pdf/2207.14757.pdf
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

## Full Paper: [pdf](https://arxiv.org/pdf/2207.14757.pdf)

## Please cite with the following BibTeX:

```
@inproceedings{messina2022aladin,
  title={ALADIN: Distilling Fine-grained Alignment Scores for Efficient Image-Text Matching and Retrieval},
  author={Messina, Nicola and Stefanini, Matteo and Cornia, Marcella and Baraldi, Lorenzo and Falchi, Fabrizio and Amato, Giuseppe and Cucchiara, Rita},
  booktitle={Proceedings of the 19th International Conference on Content-based Multimedia Indexing},
  pages={64--70},
  year={2022}
}
```