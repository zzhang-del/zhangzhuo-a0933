---
title: 'Home'
share: false 
type: landing
sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
        show_social: false  # 新增选项，禁用社交链接

  - block: collection
    content:
      filters:
        folders:
          - blog
    design:
      spacing:
        padding: ['3rem', 0, '6rem', 0]

  - block: markdown # Define a markdown block
    content:
      title: 'News 🚀' # This will be the title for your news section
      text: | # Use 'text: |' to indicate multi-line content
        * **December 2023:** I completed an internship at the National Supercomputing Center in Tianjin.
        * **September 2024:** Kicking off my doctoral studies – an exciting new chapter begins! 🎓
        * **December 2024:** My first journal paper in the **AI for Science (AI4S)** field was accepted by **Physics of Fluids (PoF)**! 🎉
        * **January 2025:** As a co-author, a medical image segmentation article was accepted by **ICASSP**. 🔬
        * **March 2025:** Another medical image processing article, where I was a co-author, was accepted by **ICME**. 💻
        * **May 2025:** Three of our papers were accepted by the **ICIC conference**! 🥳 A big congratulations to Zhang Fan and Wang Shuaidan for their excellent work as first authors on two of those papers.
        * **June 2025:** I'm thrilled to share that I've been awarded the **CSC Visiting PhD Scholarship**! 🌍
    design:
      columns: '1' # This makes the content span one column, usually full width
      # You can add more design options here if needed, like spacing or background
---
