---
title: 'Literal Selection in Switching Lattice Design'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-10-09T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Master's Thesis
publication_short: Master's Thesis

abstract: 'In undirected graphs, a clique is a subset of its vertices which are all pairwise connected.
The problem of detecting all cliques of a graph has received extensive study due to its various fields of applications, ranging from detecting social communities, through the development of integrated circuits, to extracting information from protein interactions and even detecting communities of dolphins in the ocean.
The clique problem is also of relevant interest from the theoretical point of view, since it is one of the first 21 problems to be classified as NP-Complete by Karp in 1972. For these reasons many different strategies were adopted throughout the years to solve it as fast as possible, including heuristics and approximation algorithms.

The version of the clique problem that we attack in this thesis is the enumerative one, as we want to list and count every inclusion-maximal clique found in large graphs.
Nowadays graphs are used to formalize a huge variety of contexts and their size is growing at a fast pace, thus the need to design faster algorithms that are capable to process them in a reasonable amount of time.

One of the first algorithms able to enumerate all maximal cliques of a graph was that by Bron and Kerbosch, a recursive backtracking algorithm which performs a depth first visit of the search tree that it explores, adding one vertex at a time to the clique being formed.
While the authors gave no time bounds for their algorithm, it has later been proven that with a particular strategy for pruning, it achieves O(3^(|V|/3)) time, which is worst-case optimal.
More recently Eppstein et al. proposed a further enhancement on this algorithm, making it fixed-parameter tractable and very fast in practice by exploiting a particular ordering of the vertices.

The goal of this thesis is to specialize the version of the algorithm by Eppstein et al. to find cliques of at least k vertices, motivated by the fact that larger cliques often carry more significant information about communities rather than the small ones.
We design new fast methods to further reduce the number of recursive calls made by the algorithm, practically expanding the pool of affordable graphs to process.
We plug our strategy into the existing implementation of the algorithm by D. Strash and we do extensive testing both on real and randomly generated datasets with different properties to show its practical efficiency with respect to Eppstein's starting algorithm, and how this relates to the structure of the graphs.'

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
links:
  - name: Official UniPi Page
    url: https://etd.adm.unipi.it/t/etd-07012020-125844

url_pdf: 'https://bit.ly/rucci-master-thesis'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects: []


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""


# {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
---
