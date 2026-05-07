---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '1rem'
  
sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      title: 'Biography'
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
      headings:
        about: 'Biography'
        education: 'Education'
        interests: 'Interests'
    design:
      css_id: bio
      columns: '2'
      spacing:
        padding: ['0', '0', '0', '0']
  - block: markdown
    content:
      title: Recent News
      text: |
        • **May 2026**: Started as Research Associate at University of Würzburg, Germany! 🚀
        • **February 2026**: Our paper “Common Sense vs Morality” accepted at LREC 2026 ! 🚀
        • **January 2026**: Our paper “Decision Making with Deliberation” accepted at EACL Main, 2026 ! 🚀
        • **December 2025**: I presented “Lazy Review” and “Decision Making with Deliberation” in the SciProdLLM Workshop at AACL IJCNLP, 2025 🎤
        • **November 2025**: Saugata presented our paper on Riemannian Gradient Averaging in the ELLIS Pre-NeurIPS workshop at Universität des Saarlandes. 🎤
        • **October 2025**: Our paper on Riemannian Gradient Averaging accepted at OPT workshop at NeurIPS 2025. 🎉
        • **October 2025**: I started my internship at NEC Labs, Europe! 💼
        • **July 2025**: Attending ACL 2025 at Vienna! 🇦🇹
        • **July 2025**: Our benchmark paper “CaMMT” accepted at Findings of EMNLP 2025 🎉
        • **May 2025**: Our Paper “LazyReview” accepted at ACL 2025 🎉
    design:
      css_id: news
      columns: '1'
      spacing:
        padding: ['2rem', '0', '1rem', '0']
  - block: markdown
    content:
      title: Publications
      text: |
        <span style="white-space: nowrap;">
          <a href="https://arxiv.org/abs/2602.10118">Reviewing the reviewer: Elevating review quality through LLM-guided feedback</a>
        </span><br>
        <b>Sukannya Purkayastha</b>, Qile Wan, Anne Lauscher, Lizhen Qu, Iryna Gurevych<br>
        <em>Findings of the Association for Computational Linguistics: ACL 2026</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://arxiv.org/pdf/2603.09434v1">Common Sense vs Morality: The curious case of Narrative Focus bias on LLMs.</a>
        </span><br>
        Saugata Purkayastha, Pranav Kushare, Pragya Pal, <b>Sukannya Purkayastha</b><br>
        <em>15th biennial Language Resources and Evaluation Conference (LREC), 2026</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://arxiv.org/abs/2508.05283">Decision-Making with Deliberation: Meta-reviewing as a Document-grounded Dialogue</a>
        </span><br>
        <b>Sukannya Purkayastha</b>, Nils Dycke, Anne Lauscher, Iryna Gurevych<br>
        <em>19th Conference of the European Chapter of the Association for Computational Linguistics (EACL), 2026</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://aclanthology.org/2025.acl-long.165/">LazyReview: A Dataset for Uncovering Lazy Thinking in NLP Peer Reviews</a>
        </span><br>
        <b>Sukannya Purkayastha</b>, Zhuang Li, Anne Lauscher, Lizhen Qu, Iryna Gurevych<br>
        <em>The 63rd Annual Meeting of the Association for Computational Linguistics (ACL), 2025</em>

        <span style="white-space: nowrap;"><a href="https://aclanthology.org/2025.findings-emnlp.1220/">CaMMT: Benchmarking Culturally Aware Multimodal Machine Translation</a></span><br>Emilio Villa-Cueva, Sholpan Bolatzhanova, Diana Turmakhan, …, <b>Sukannya Purkayastha</b>, …, Thamar Solorio<br><em>Findings of the Association for Computational Linguistics: EMNLP 2025</em>

        <span style="white-space: nowrap;">
          <a href="https://opt-ml.org/papers/2025/paper7.pdf">On Riemannian Gradient Descent using Gradient Averaging (RGrad-Avg)</a>
        </span><br>
        Saugata Purkayastha, <b>Sukannya Purkayastha</b><br>
        <em>17th Annual Workshop on Optimization for Machine Learning (OPT) at NeurIPS 2025</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://arxiv.org/abs/2511.05921">IDALC: A Semi-Supervised Framework for Intent Detection and Active Learning-based Correction</a>
        </span><br>
        Ankan Mullick, <b>Sukannya Purkayastha</b>, Saransh Sharma, Pawan Goyal, Niloy Ganguly<br>
        <em>IEEE Transactions on Artificial Intelligence 2025</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/1568882ba1a50316e87852542523739c-Abstract-Datasets_and_Benchmarks_Track.html">CVQA: Culturally-diverse Multilingual Visual Question Answering Benchmark</a>
        </span><br>
        David Romero, Chenyang Lyu, Haryo Akbarianto Wibowo, Teresa Lynn, Injy Hamed, Aditya Nanda Kishore, Aishik Mandal, Alina Dragonetti,… , <b>Sukannya Purkayastha</b>, …, Thamar Solorio<br>
        <em>38th Conference on Neural Information Processing Systems (NeurIPS), Datasets & Benchmarks Track, 2024</em>

        <span style="white-space: nowrap;"><a href="https://aclanthology.org/2023.emnlp-main.894/">Exploring Jiu-Jitsu Argumentation for Writing Peer Review Rebuttals</a>
        </span><br>
        <b>Sukannya Purkayastha</b>, Anne Lauscher, Iryna Gurevych<br>
        <em>Empirical Methods in Natural Language Processing (EMNLP), 2023</em>

        <span style="white-space: nowrap;">Adapters: A Unified Library for Parameter-Efficient and Modular Transfer Learning</span><br>Clifton Poth, Hannah Sterz, Indraneil Paul, <b>Sukannya Purkayastha</b>, Leon Engländer, Timo Imhof, Ivan Vulić, Sebastian Ruder, Iryna Gurevych, Jonas Pfeiffer<br><em>Empirical Methods in Natural Language Processing (EMNLP): System Demonstrations, 2023</em>

        <span style="white-space: nowrap;">Romanization-based Large-scale Adaptation of Multilingual Language Models</span><br><b>Sukannya Purkayastha</b>, Sebastian Ruder, Jonas Pfeiffer, Iryna Gurevych, Ivan Vulić<br><em>Findings of the Association for Computational Linguistics: EMNLP, 2023</em>

        <span style="white-space: nowrap;"><a href="https://aclanthology.org/2022.findings-naacl.282/">A Framework to Generate High-Quality Datapoints for Multiple Novel Intent Detection</a></span><br>Ankan Mullick*, <b>Sukannya Purkayastha</b>*, Pawan Goyal, Niloy Ganguly<br><em>Findings of the Association for Computational Linguistics: NAACL, 2022</em>

        <span style="white-space: nowrap;">
          <a href="https://dblp.org/rec/conf/ijcnn/PurkayasthaDGKB22.html">A Deep Neural Approach to KGQA via SPARQL Silhouette Generation</a>
        </span><br>
        <b>Sukannya Purkayastha</b>, Saswati Dana, Dinesh Garg, Dinesh Khandelwal, G. P. Shrivatsa Bhargav<br>
        <em>International Joint Conference on Neural Networks (IJCNN), 2022</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://arxiv.org/abs/2012.02387">A Variant of Gradient Descent Algorithm Based on Gradient Averaging</a>
        </span><br>
        Saugata Purkayastha, <b>Sukannya Purkayastha</b><br>
        <em>12th Annual Workshop on Optimization for Machine Learning (OPT) at NeurIPS 2020</em>

        <span style="white-space: nowrap;">Medical Entity Linking using Triplet Network</span><br>Ishani Mondal, <b>Sukannya Purkayastha</b>, Sudeshna Sarkar, Pawan Goyal, Jitesh Pillai, Amitava Bhattacharyya, Mahanandeeshwar Gattu<br><em>2nd Clinical Natural Language Processing Workshop, 2019</em>

        <span style="white-space: nowrap;">Drug-Drug Interactions Prediction Based on Drug Embedding and Graph Auto-Encoder</span><br><b>Sukannya Purkayastha</b>, Ishani Mondal, Sudeshna Sarkar, Pawan Goyal, Jitesh K. Pillai<br><em> IEEE 19th International Conference on Bioinformatics and Bioengineering (BIBE), 2019</em>
        <hr style="border: none; border-top: 1px solid #ddd; margin: 2rem 0;"><br>
    design:
      css_id: publications
      columns: '1'
      spacing:
        padding: ['2rem', '0', '1rem', '0']

---
