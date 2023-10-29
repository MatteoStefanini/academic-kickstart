---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Predicting gene and protein expression levels from DNA and protein sequences with Perceiver"
authors: [Matteo Stefanini, Marta Lovino, Rita Cucchiara, Elisa Ficarra]
date: 2023-03-29T15:26:27+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-03-29T15:26:27+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computer Methods and Programs in Biomedicine"
publication_short: "CMPB"

abstract: "The functions of an organism and its biological processes result from the ex- pression of genes and proteins. Therefore quantifying and predicting mRNA and protein levels is a crucial aspect of scientific research. Concerning the prediction of mRNA levels, the available approaches use the sequence upstream and downstream of the Transcription Start Site (TSS) as input to neural networks. The State-of-the-art models (e.g., Xpresso and Basenjii) predict mRNA levels exploiting Convolutional (CNN) or Long Short Term Memory (LSTM) Networks. However, CNN prediction depends on convolutional kernel size, and LSTM suffers from capturing long-range dependencies in the sequence. Concerning the predic- tion of protein levels, as far as we know, there is no model for predicting protein levels by exploit- ing the gene or protein sequences. Methods: Here, we exploit a new model type (called Perceiver) for mRNA and protein level prediction, exploiting a Transformer-based architecture with an attention mod- ule to attend to long-range interactions in the sequences. In addition, the Perceiver model overcomes the quadratic complexity of the standard Transformer architectures. This work’s contributions are 1. DNAPer- ceiver model to predict mRNA levels from the sequence upstream and downstream of the TSS; 2. Pro- teinPerceiver model to predict protein levels from the protein sequence; 3. Protein&DNAPerceiver model to predict protein levels from TSS and protein sequences. Results: The models are evaluated on cell lines, mice, glioblastoma, and lung cancer tissues. The results show the effectiveness of the Perceiver-type mod- els in predicting mRNA and protein levels. Conclusions: This paper presents a Perceiver architecture for mRNA and protein level prediction. In the future, inserting regulatory and epigenetic information into the model could improve mRNA and protein level predictions."

# Summary. An optional shortened abstract.
summary: "omputer Methods and Programs in Biomedicine - CMPB 2023"

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

url_pdf: https://www.sciencedirect.com/science/article/pii/S0169260723001700
url_code: https://github.com/MatteoStefanini/DNAPerceiver
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

## Full Paper: [pdf](https://www.sciencedirect.com/science/article/pii/S0169260723001700)

## Please cite with the following BibTeX:
```
@article{stefanini2023predicting,
  title={Predicting gene and protein expression levels from DNA and protein sequences with Perceiver},
  author={Stefanini, Matteo and Lovino, Marta and Cucchiara, Rita and Ficarra, Elisa},
  journal={Computer Methods and Programs in Biomedicine},
  volume={234},
  pages={107504},
  year={2023},
  publisher={Elsevier}
}
```