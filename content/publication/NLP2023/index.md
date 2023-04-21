---
title: "Masked Image Modelingを利用した情景画像中のテキスト認識"
authors:
- admin
- 宮崎智
- 大町真一郎
date: "2023-03-07T00:00:00Z"
doi: ""

#draft: true

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 既存のテキスト認識手法は実世界におけるデータセットのサンプル数が少ないため，合成データセットを用いて学習がされているが、実世界で発生する問題に対応できない。そこで，ラベルがない実画像の利用によってテキスト認識モデルの可能性を引き出すことが考えられており，テキスト認識に対する自己教師あり学習手法が検討されている。本研究では、Masked Image Modeling を利用し、文脈情報を考慮した新たなマスキング戦略を提案した。実験の結果，提案するマスキング戦略の有効性が実証された．

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Text Recognition
- Self-supervised Learning
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://www.anlp.jp/proceedings/annual_meeting/2023/pdf_dir/Q9-12.pdf
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Random MaskingとSpan Maskingの例'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!--
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
