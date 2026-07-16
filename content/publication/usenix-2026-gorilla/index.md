---
title: "From Mirai to Gorilla: Deep Dive into a Long-Lasting DDoS-for-Hire Botnet"
# slug: "usenix-2026-gorilla"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Maarten Weyns
  - admin
  - Stefan Op de Beek
  - Daniel Wagner
  - Georgios Smaragdakis
  - Harm Griffioen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-06-01T00:00:00Z'
doi: '10.1145/3730567.3764498'

# Schedule page publish date (NOT publication's date).
# publishDate: '2025-10-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the *35th Usenix Security Symposium*
# publication_short: In *Usenix 2026*

abstract: In 2016, the Mirai botnet swept the Internet, ushering in a new era of DDoS attacks. Over the following decade, spinoffs of the Mirai botnet transitioned from simple attack tools into commercial platforms, offering Distributed Denial of Service (DDoS) attacks for Hire. Such platforms enable users to launch large-scale DDoS attacks with minimal technical expertise. One notable example is the Gorilla Botnet, which was operational between Fall 2024 and Summer 2025, an unusually long lifetime compared to similar Mirai-based Botnets. In this paper, we reverse-engineer the Mirai-based Gorilla Botnet and aim to understand its design, engineering decisions, and marketing strategies to enhance its resilience and success. We investigate its operational characteristics, including the types of attacks it supports, its underlying infrastructure, and the behavior of its bots. We find that Gorilla's longevity stems from targeted improvements, including two software development phases and learning from previous releases, setting it apart from typical Mirai-based botnets. In the process, we analyze the firepower and attack vectors of the Gorilla botnet and characterize the business types of its targets.

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
