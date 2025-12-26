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
      title: ''
      text: ''
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
      design:
      # Apply a gradient background
      css_class: bg-white
      spacing:
        padding: ['0', '0', '0', '0']
      # Avatar customization
      avatar:
        size: small # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: square # Options: circle (default), square, rounded
 

  - block: markdown
    id: news
    content:
      title: News
      text: |
        <span style="white-space: nowrap;"> • December 2025: I presented "Lazy Review" and  "Decision Making with Deliberation"</span> in the <a href="https://sciprodllm.github.io/2025/index.html">SciProdLLM Workshop </a> at AACL IJCNLP, 2025<br>
        <span style="white-space: nowrap;">• November 2025: Saugata presented our paper on Riemannian Gradient Averaging in the <a href="https://lacoco-lab.github.io/events/PreNeurIPS2025/">ELLIS </span> Pre-NeurIPS workshop </a> at Universität des Saarlandes.<br>
        <span style="white-space: nowrap;">• October 2025: Our paper on Riemannian Gradient Averaging accepted at OPT workshop at NeurIPS 2025.</span><br>
        • <span style="white-space: nowrap;">October 2025:</span> I started my internship at NEC Labs, Europe!<br>
        <span style="white-space: nowrap;"> • July 2025: Attending ACL 2025 at Vienna!</span><br>
        <span style="white-space: nowrap;">• July 2025: Our benchmark paper "CaMMT" accepted at Findings of EMNLP 2025</span> <br>
        <span style="white-space: nowrap;">• May 2025: Our Paper "LazyReview" accepted at ACL 2025</span><br>
        <hr style="border: none; border-top: 1px solid #ddd; margin: 1rem 0;"><br>
    design:
      columns: '2'
      css_class: 'mt-0'
      spacing:
        padding: ['0', '0', '0', '0']
        margin: ['-1.5rem', '0', '0', '0']

  - block: markdown
    id: papers
    content:
      title: Selected Publications
      text: |
        <span style="whitespace: nowrap;">
        <a href="">Reviewing the reviewer: Elevating review quality through LLM-guided feedback</a>
        </span><br>
        <b>Sukannya Purkayastha</b>, Qile Wan, Anne Lauscher, Lizhen Qu, Iryna Gurevych<br>
        <em>Under Review</em><br><br>

        <span style="whitespace: nowrap;">
        <a href="https://arxiv.org/abs/2508.05283">Decision-Making with Deliberation: Meta-reviewing as a Document-grounded Dialogue</a>
        </span><br>
        <b>Sukannya Purkayastha</b>, Nils Dycke, Anne Lauscher, Iryna Gurevych<br>
        <em>Under Review</em><br><br>


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

        <span style="white-space: nowrap;">[Adapters: A Unified Library for Parameter-Efficient and Modular Transfer Learning](https://aclanthology.org/2023.emnlp-demo.13/)</span><br>Clifton Poth, Hannah Sterz, Indraneil Paul, <b>Sukannya Purkayastha</b>, Leon Engländer, Timo Imhof, Ivan Vulić, Sebastian Ruder, Iryna Gurevych, Jonas Pfeiffer<br><em>Empirical Methods in Natural Language Processing (EMNLP): System Demonstrations, 2023</em>

        <span style="white-space: nowrap;">[Romanization-based Large-scale Adaptation of Multilingual Language Models](https://aclanthology.org/2023.findings-emnlp.538/)</span><br><b>Sukannya Purkayastha</b>, Sebastian Ruder, Jonas Pfeiffer, Iryna Gurevych, Ivan Vulić<br><em>Findings of the Association for Computational Linguistics: EMNLP, 2023</em>

        

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


        <span style="white-space: nowrap;">[Medical Entity Linking using Triplet Network](/publications/conference-paper/mondal-etal-2019-medical/)</span><br>Ishani Mondal, <b>Sukannya Purkayastha</b>, Sudeshna Sarkar, Pawan Goyal, Jitesh Pillai, Amitava Bhattacharyya, Mahanandeeshwar Gattu<br><em>2nd Clinical Natural Language Processing Workshop, 2019</em>

        <span style="white-space: nowrap;">[Drug-Drug Interactions Prediction Based on Drug Embedding and Graph Auto-Encoder](https://doi.org/10.1109/BIBE.2019.00104)</span><br><b>Sukannya Purkayastha</b>, Ishani Mondal, Sudeshna Sarkar, Pawan Goyal, Jitesh K. Pillai<br><em> IEEE 19th International Conference on Bioinformatics and Bioengineering (BIBE), 2019</em>
        <hr style="border: none; border-top: 1px solid #ddd; margin: 1rem 0;">
    design:
      columns: '2'
      css_class: ''
      spacing:
        padding: ['0', '0', '0', '0']

---

