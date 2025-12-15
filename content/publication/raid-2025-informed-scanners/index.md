---
title: 'Revealing Informed Scanners by Colocating Reactive and Passive Telescopes'
slug: 'raid-2025-informed-scanners'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Georgios Smaragdakis
  - Harm Griffioen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-10-25T00:00:00Z'
doi: '10.1145/3730567.3764498'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-10-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the *28th International Symposium on Research in Attacks, Intrusions and Defenses (RAID 2025)*
# publication_short: In *RAID 2025*

abstract: Network telescopes have been utilized for decades to detect scanning activity on the Internet. Such telescopes are typically passive, i.e., they do not reply to TCP SYN packets. Recently, reactive network telescopes that respond to TCP SYN packets have been proposed to unveil a new wave of scanners, namely two-phase scanners, and collect malicious payloads from TCP ACK packets. In this paper, we propose a methodology that combines the modus operandi of passive and reactive telescopes to identify an additional wave of scanners - that we call "informed scanners"- that participate in attacks. Our main observation is that small reactive telescopes operating within larger passive telescopes are visited by "informed" clients that are aware of the liveness of hosts without performing scanning themselves; thus, are not visible in the passive telescope. We identify these informed clients as an additional class of highly targeted scanners and attackers. Indeed, by operating a /25 reactive telescope within a /16 passive telescope, we can filter out routine and two-phase scanning activity from informed one and identify clients that participate in service-targeted attacks. We discuss the scalability and sensitivity of our methodology and how it can be used to swiftly identify and profile malicious hosts on the Internet. We show that "mini-telescopes" of relatively smaller sizes, such as /20, can be comparably effective as larger sizes, such as a /16. Thus, our methodology can be useful to security operators that may only be able to allocate a relatively small address space to run a telescope. 

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
