---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Deep-Learning-based approach to VM behavior identification in cloud systems"
authors: [Matteo Stefanini, Riccardo Lancellotti, Lorenzo Baraldi, Simone Calderara]
date: 2019-03-05T15:36:12+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-04-07T15:36:12+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*International Conference on Cloud Computing and Services Science* 2019"
publication_short: "*CLOSER* 2019"

abstract: "Cloud computing data centers are growing in size and complexity to the point where monitoring and management of the infrastructure become a challenge due to scalability issues. A possible approach to cope with the size of such data centers is to identify VMs exhibiting a similar behavior. Existing literature demonstrated that clustering together VMs that show a similar behavior may improve the scalability of both monitoring and management of a data center. However, available techniques suffer from a trade-off between accuracy and time to achieve this result. Throughout this paper we propose a different approach where, instead of an unsupervised clustering, we rely on classifiers based on deep learning techniques to assign a newly deployed VMs to a cluster of already-known VMs. The two proposed classifiers, namely DeepConv and DeepFFT use a convolution neural network and (in the latter model) exploits Fast Fourier Transform to classify the VMs. Our proposal is validated using a set of traces describing the behavior of VMs from a real cloud data center. The experiments compare our proposal with state-of-the-art solutions available in literature, demonstrating that our proposal achieve better performance. Furthermore, we show that our solution is significantly faster than the alternatives as it can produce a perfect classification even with just a few samples of data, making our proposal viable also to classify on-demand VMs that are characterized by a short life span."

# Summary. An optional shortened abstract.
# summary: "The two proposed classifiers, namely DeepConv and DeepFFT use a CNN and, the latter, exploits Fast Fourier Transform to classify Virtual Machines, achieving state-of-the-art results."
summary: "*International Conference on Cloud Computing and Services Science* - CLOSER 2019"

tags: [Deep Learning, VMs classification, Cloud computing]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/pdf/1903.01930.pdf"
url_code: "https://github.com/MatteoStefanini/DeepVM"
url_dataset:
url_poster:
url_project:
url_slides: "https://pdfs.semanticscholar.org/e726/68d7047955ab19b2df60ff172794116eb9ae.pdf"
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "DeepConv model"
  focal_point: "Center"
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

# ![deepconv](/img/DeepVMConvImage.jpg)
---

## Results:
![resultsVM](/img/accuracyVM.png)![resultsVM](/img/comparisonVMpaper.png)

## Full Paper: [pdf](https://arxiv.org/pdf/1903.01930.pdf)

## Slides: [slides](https://pdfs.semanticscholar.org/e726/68d7047955ab19b2df60ff172794116eb9ae.pdf)

## Code: [github](https://github.com/MatteoStefanini/DeepVM)

## Please cite with the following BibTeX:

```
@article{stefanini2019deep,
  title={A Deep Learning based approach to VM behavior identification in cloud systems},
  author={Stefanini, Matteo and Lancellotti, Riccardo and Baraldi, Lorenzo and Calderara, Simone},
  journal={arXiv preprint arXiv:1903.01930},
  year={2019}
}
```
