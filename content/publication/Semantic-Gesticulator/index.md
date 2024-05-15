---
title: "Semantic Gesticulator: Semantics-aware Co-speech Gesture Synthesis"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zeyi Zhang
- Tenglong Ao
- Yuyao Zhang
- Qingzhe Gao
- Chuan Lin
- Baoquan Chen
- Libin Liu

# Author notes (optional)
author_notes:
- "Equal Contribution"
- "Equal Contribution"
- "Equal Contribution"
-
-
-
- "Corresponding Author"


date: "2024-05-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Graphics (**TOG**), **SIGGRAPH 2024**."
publication_short: ""

abstract: "In this work, we present Semantic Gesticulator, a novel framework designed to synthesize realistic gestures accompanying speech with strong semantic correspondence. Semantically meaningful gestures are crucial for effective non-verbal communication, but such gestures often fall within the long tail of the distribution of natural human motion. The sparsity of these movements makes it challenging for deep learning-based systems, trained on moderately sized datasets, to capture the relationship between the movements and the corresponding speech semantics. To address this challenge, we develop a generative retrieval framework based on a large language model. This framework efficiently retrieves suitable semantic gesture candidates from a motion library in response to the input speech. To construct this motion library, we summarize a comprehensive list of commonly used semantic gestures based on findings in linguistics, and we collect a high-quality motion dataset encompassing both body and hand movements. We also design a novel GPT-based model with strong generalization capabilities to audio, capable of generating high-quality gestures that match the rhythm of speech. Furthermore, we propose a semantic alignment mechanism to efficiently align the retrieved semantic gestures with the GPT's output, ensuring the naturalness of the final animation. Our system demonstrates robustness in generating gestures that are rhythmically coherent and semantically explicit, as evidenced by a comprehensive collection of examples. User studies confirm the quality and human-likeness of our results, and show that our system outperforms state-of-the-art systems in terms of semantic appropriateness by a clear margin."

# Summary. An optional shortened abstract.
summary: "We introduce Semantic Gesticulator, a novel framework designed to synthesize realistic co-speech gestures with strong semantic correspondence. Semantic Gesticulator fine-tunes an LLM to retrieve suitable semantic gesture candidates from a motion library. Combined with a novel, GPT-style generative model, the generated gesture motions demonstrate strong rhythmic coherence and semantic appropriateness."

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://pku-mocca.github.io/Semantic-Gesticulator-Page/'
url_slides: ''
url_source: ''
url_video:  ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
