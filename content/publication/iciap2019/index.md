---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Artpedia: A New Visual-Semantic Dataset with Visual and Contextual Sentences"
authors: [Matteo Stefanini, Marcella Cornia, Lorenzo Baraldi, Massimiliano Corsini, Rita Cucchiara]
date: 2019-06-07T16:31:52+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-04-07T16:31:52+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*International Conference on Image Analysis and Processing* 2019"
publication_short: "*ICIAP* 2019"

abstract: "As vision and language techniques are widely applied to realistic images, there is a growing interest in designing visual-semantic models suitable for more complex and challenging scenarios. In this paper, we address the problem of cross-modal retrieval of images and sentences coming from the artistic domain. To this aim, we collect and manually annotate the Artpedia dataset that contains paintings and textual sentences describing both the visual content of the paintings and other contextual information. Thus, the problem is not only to match images and sentences, but also to identify which sentences actually describe the visual content of a given image. To this end, we devise a visual-semantic model that jointly addresses these two challenges by exploiting the latent alignment between visual and textual chunks. Experimental evaluations, obtained by comparing our model to different baselines, demonstrate the effectiveness of our solution and highlight the challenges of the proposed dataset."

# Summary. An optional shortened abstract.
summary: "*International Conference on Image Analysis and Processing* - ICIAP 2019"

tags: [Deep Learning, Vision & Language, Cross-modal Retrieval, Visual-Semantic Embedding, Art]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://iris.unimore.it/retrieve/handle/11380/1178736/224456/paper.pdf
url_code:
url_dataset: https://aimagelab.ing.unimore.it/imagelab/uploadedFiles/artpedia.zip
url_poster:
url_project: https://aimagelab.ing.unimore.it/imagelab/page.asp?IdPage=35
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Artpedia dataset sample"
  focal_point: "Left"
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

Artpedia contains a collection of 2,930 painting images, each associated to a variable number of textual descriptions. Each sentence is labelled either as a visual sentence or as a contextual sentence, if does not describe the visual content of the artwork. Contextual sentences can describe the historical context of the artwork, its author, the artistic influence or the place where the painting is exhibited. As in standard cross-modal datasets, the association between sentences and painting is also provided. Overall, the dataset contains a total of 28,212 sentences, 9,173 labelled as visual sentences and the remaining 19,039 as contextual sentences. On average, each painting is associated with 3.1 visual and 6.5 contextual sentences.

## Download: [artpedia.zip](https://aimagelab.ing.unimore.it/imagelab/uploadedFiles/artpedia.zip)

## Full Paper: [pdf](https://iris.unimore.it/retrieve/handle/11380/1178736/224456/paper.pdf)

## Please cite with the following BibTeX:

```
@inproceedings{stefanini2019artpedia,
  title={{Artpedia: A New Visual-Semantic Dataset with Visual and Contextual Sentences}},
  author={Stefanini, Matteo and Cornia, Marcella and Baraldi, Lorenzo and Corsini, Massimiliano and Cucchiara, Rita},
  booktitle={Proceedings of the International Conference on Image Analysis and Processing},
  year={2019}
}
```