+++
title = "A Deep-Learning-based approach to VM behavior identification in cloud systems"

# Date first published.
date = "2019-03-05"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Matteo Stefanini", "Riccardo Lancellotti", "Lorenzo Baraldi", "Simone Calderara"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *International Conference on Cloud Computing and Services Science* 2019"
publication_short = "In *CLOSER* 2019"

# Abstract and optional shortened version.
abstract = "Cloud computing data centers are growing in size and complexity to the point where monitoring and management of the infrastructure become a challenge due to scalability issues. A possible approach to cope with the size of such data centers is to identify VMs exhibiting a similar behavior. Existing literature demonstrated that clustering together VMs that show a similar behavior may improve the scalability of both monitoring and management of a data center. However, available clustering techniques suffer from a trade-off between the accuracy of the clustering and the time to achieve this result. Not being able to obtain an accurate clustering in short time hinders the application of these solutions, especially in public cloud scenarios where on-demand VMs are instantiated and run for a short time span. Throughout this paper we propose a different approach where, instead of an unsupervised clustering, we rely on classifiers based on deep learning techniques to assign a newly deployed VMs to a cluster of already-known VMs. The two proposed classifiers, namely DeepConv and DeepFFT use a convolution neural network and the the latter model exploits Fast Fourier Transformation to classify the VMs. Our proposal is validated using a set of traces describing the behavior of VMs from a real cloud data center. The experiments compare our proposal with state-of-the-art solutions available in literature, such as the AGATE technique and PCA-based clustering, demonstrating that our proposal can achieve a very high accuracy (compared to the best performing alternatives) without the need to introduce the notion of a gray-area to take into account not-yet assigned VMs as in AGATE. Furthermore, we show that our solution is significantly faster than the alternatives as it can produce a perfect classification even with just a few samples of data, such as 4 observations (corresponding to 20 minutes of data), making our proposal viable also to classify on-demand VMs that are characterized by a very short life span."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "DeepVMConvImage.jpg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1903.01930.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

![deepconv](/img/DeepVMConvImage.jpg)
## Abstract:
Cloud computing data centers are growing in size and complexity to the point where monitoring and management of the infrastructure become a challenge due to scalability issues. A possible approach to cope with the size of such data centers is to identify VMs exhibiting a similar behavior. Existing literature demonstrated that clustering together VMs that show a similar behavior may improve the scalability of both monitoring and management of a data center. However, available clustering techniques suffer from a trade-off between the accuracy of the clustering and the time to achieve this result. Not being able to obtain an accurate clustering in short time hinders the application of these solutions, especially in public cloud scenarios where on-demand VMs are instantiated and run for a short time span. Throughout this paper we propose a different approach where, instead of an unsupervised clustering, we rely on classifiers based on deep learning techniques to assign a newly deployed VMs to a cluster of already-known VMs. The two proposed classifiers, namely DeepConv and DeepFFT use a convolution neural network and the the latter model exploits Fast Fourier Transformation to classify the VMs. Our proposal is validated using a set of traces describing the behavior of VMs from a real cloud data center. The experiments compare our proposal with state-of-the-art solutions available in literature, such as the AGATE technique and PCA-based clustering, demonstrating that our proposal can achieve a very high accuracy (compared to the best performing alternatives) without the need to introduce the notion of a gray-area to take into account not-yet assigned VMs as in AGATE. Furthermore, we show that our solution is significantly faster than the alternatives as it can produce a perfect classification even with just a few samples of data, such as 4 observations (corresponding to 20 minutes of data), making our proposal viable also to classify on-demand VMs that are characterized by a very short life span.
## Results:
![resultsVM](/img/accuracyVM.png)![resultsVM](/img/comparisonVMpaper.png)
## Full Paper: [pdf](https://arxiv.org/pdf/1903.01930.pdf)
