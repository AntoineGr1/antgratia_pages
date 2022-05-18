---
title: 'Automated and Disciplined ConvNet Architecture Exploration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Antoine Gratia
  - Gilles Perrouin
  - Paul Temple
  - Benoit Frenay

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: 'Not'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['0']

# Publication name and optional abbreviated publication name.
#publication: In *Wowchemy Conference*
#publication_short: In *ICW*

abstract: Convolutional neural networks (CNNs) are widely used for diverse tasks, such as image recognition and analysis. Recently, research aimed at finding CNN architectures that can be used in various contexts/applications and provide the latest performance has yielded fruitful results, resulting in numerous recommendation models tailored for more or less specific purposes. Finding the right CNN is a challenging issue - there are many possible architectures, hyperparameters, and frameworks that can be considered. From a software engineering perspective, having such diversity can be difficult to deal with when trying to maintain a system or trying to reason effectively (for example, consider choosing the best solution for deployment on a system with high potential impact on daily life). In this master thesis, we investigate how variability can be expressed to derive different CNN variants. We develop a generator on top of Keras for deriving variants of LeNet, ResNet, and DenseNet architectures. Our results show that we can reach accurate results on MNIST and CIFAR-10. The next step of our work is to improve the generator for other architectures (e.g. Xception, SqueezeNet,...) and find optimal ways to explore the configuration space.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Machine Learning, Variability, Convolutional Neural Networks, Deep Learning, Software Eengineering]

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
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
