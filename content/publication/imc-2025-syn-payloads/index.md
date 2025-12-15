---
title: 'Have you SYN What I See? Analyzing TCP SYN Payloads in the Wild'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Enrico Bassetti
  - Harm Griffioen
  - Georgios Smaragdakis

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-11-01T00:00:00Z'
doi: '10.1145/3730567.3764498'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-11-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM Internet Measurement Conference 2025*
# publication_short: In *IMC 2025*

abstract: TCP SYN packets are typically meant to initiate a three-way handshake for new connections and do not carry a payload. The only exception, according to the standards, is TCP Fast Open, where data is transmitted as TCP SYN payload. In this paper, we perform an empirical analysis of other cases where TCP SYN carries a payload. We utilize a large passive and a reactive network telescope to collect pure TCP SYN packets over two years. Our analysis shows that around 75% of these payloads are HTTP GET requests for potentially censored content performed by researchers and activists originated by a relatively small number of IPs. We also observe scouting and intrusion attempt activity related to port 0, operating systems, middleware, and edge router vulnerability exploitation. We make our data and methodology publicly available as we want to raise awareness of this type of TCP SYN that typically goes unnoticed.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
