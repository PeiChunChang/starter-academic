---
abstract: Investigating the identity, distribution, and evolution of bird
  species is important for both biodiversity assessment and environmental
  conservation. The discrete wavelet transform (DWT) has been widely exploited
  to extract time-frequency features for acoustic signal analysis. Traditional
  approaches usually compute statistical measures (e.g., maximum, mean, standard
  deviation) of the DWT coefficients in each subband independently to yield the
  feature descriptor, without considering the intersubband correlation. A new
  acoustic descriptor, called the local wavelet acoustic pattern (LWAP), is
  proposed to characterize the correlation of the DWT coefficients in different
  subbands for birdsong recognition. First, we divide a variable-length birdsong
  segment into a number of fixed-duration texture windows. For each texture
  window, several LWAP descriptors are extracted. The vector of locally
  aggregated descriptors (VLAD) is then used to aggregate the set of LWAP
  descriptors into a single VLAD vector. Finally, principal component analysis
  (PCA) plus linear discriminant analysis (LDA) are employed to reduce the
  feature dimensionality for classification purposes. Experiments on two
  birdsong datasets show that the proposed LWAP descriptor outperforms other
  local descriptors, including linear predictive coding cepstral coefficients,
  Mel-frequency cepstral coefficients, perceptual linear prediction cepstral
  coefficients, chroma features, and prosody features. Furthermore, the proposed
  LWAP descriptor, followed by VLAD encoding, PCA plus LDA feature extraction,
  and a simple distance-based classifier, yields promising results that are
  competitive with those obtained by the state-of-the-art convolutional neural
  networks.
slides: ""
url_pdf: ""
publication_types:
  - "2"
authors:
  - Sheng-Bin Hsu
  - Chang-Hsing Lee
  - Pei-Chun Chang
  - Chin-Chuan Han
  - Kuo-Chin Fan
author_notes: []
publication: IEEE Transactions on Multimedia
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: "Local Wavelet Acoustic Pattern: A Novel Time–Frequency Descriptor for
  Birdsong Recognition"
doi: ""
featured: true
tags: []
projects: []
image:
  caption: The block diagram of the proposed birdsong recognition system.
  focal_point: ""
  preview_only: false
  filename: 擷取.png
date: 2018-05-08T16:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---
