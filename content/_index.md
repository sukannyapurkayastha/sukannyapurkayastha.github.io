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
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
      headings:
        about: ''
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
        <a id="news"></a>
        <span style="white-space: nowrap;"><strong>May 2026</strong>: Started as Research Associate at University of Würzburg, Germany! 🚀</span><br>
        <span style="white-space: nowrap;"><strong>February 2026</strong>: Our paper “Common Sense vs Morality” accepted at LREC 2026! 🚀</span><br>
        <span style="white-space: nowrap;"><strong>January 2026</strong>: Our paper “Decision Making with Deliberation” accepted at EACL 2026! 🚀</span><br>
        <span style="white-space: nowrap;"><strong>December 2025</strong>: I presented “Lazy Review” and “Decision Making with Deliberation” at the SciProd-LLM Workshop (AACL IJCNLP 2025) 🎤</span><br>
        <span style="white-space: nowrap;"><strong>November 2025</strong>: Saugata presented our paper on Riemannian Gradient Averaging at the ELLIS Pre-NeurIPS workshop 🎤</span><br>
        <span style="white-space: nowrap;"><strong>October 2025</strong>: Our paper on Riemannian Gradient Averaging accepted at OPT workshop (NeurIPS 2025) 🎉</span><br>
        <span style="white-space: nowrap;"><strong>October 2025</strong>: Started internship at NEC Labs, Europe 💼</span><br>
        <span style="white-space: nowrap;"><strong>July 2025</strong>: Attended ACL 2025 in Vienna 🇦🇹</span><br>
        <span style="white-space: nowrap;"><strong>July 2025</strong>: Our benchmark paper “CaMMT” accepted at Findings of EMNLP 2025 🎉</span><br>
        <span style="white-space: nowrap;"><strong>May 2025</strong>: Our paper “LazyReview” accepted at ACL 2025 🎉</span><br>
    design:
      css_id: news
      columns: '1'
      spacing:
        padding: ['2rem', '0', '1rem', '0']
  - block: markdown
    content:
      title: Publications
      text: |
        <a id="publications"></a>
        <span style="white-space: nowrap;">
          <a href="https://arxiv.org/abs/2602.10118">Reviewing the reviewer: Elevating review quality through LLM-guided feedback</a>
        </span><br>
        Sukannya Purkayastha, Qile Wan, Anne Lauscher, Lizhen Qu, Iryna Gurevych<br>
        <em>ArXiv preprint, 2026</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://arxiv.org/pdf/2603.09434v1">Common Sense vs Morality: The curious case of Narrative Focus bias on LLMs.</a>
        </span><br>
        Saugata Purkayastha, Pranav Kushare, Pragya Pal, Sukannya Purkayastha<br>
        <em>LREC, 2026</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://arxiv.org/abs/2508.05283">Decision-Making with Deliberation: Meta-reviewing as a Document-grounded Dialogue</a>
        </span><br>
        Sukannya Purkayastha, Nils Dycke, Anne Lauscher, Iryna Gurevych<br>
        <em>EACL, 2026</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://aclanthology.org/2025.acl-long.165/">LazyReview: A Dataset for Uncovering Lazy Thinking in NLP Peer Reviews</a>
        </span><br>
        Sukannya Purkayastha, Zhuang Li, Anne Lauscher, Lizhen Qu, Iryna Gurevych<br>
        <em>ACL, 2025</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://aclanthology.org/2025.findings-emnlp.1220/">CaMMT: Benchmarking Culturally Aware Multimodal Machine Translation</a>
        </span><br>
        Emilio Villa-Cueva, Sholpan Bolatzhanova, Diana Turmakhan, …, Sukannya Purkayastha, …, Thamar Solorio<br>
        <em>Findings EMNLP, 2025</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://opt-ml.org/papers/2025/paper7.pdf">On Riemannian Gradient Descent using Gradient Averaging (RGrad-Avg)</a>
        </span><br>
        Saugata Purkayastha, Sukannya Purkayastha<br>
        <em>OPT @ NeurIPS, 2025</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://arxiv.org/abs/2511.05921">IDALC: A Semi-Supervised Framework for Intent Detection and Active Learning-based Correction</a>
        </span><br>
        Ankan Mullick, Sukannya Purkayastha, Saransh Sharma, Pawan Goyal, Niloy Ganguly<br>
        <em>IEEE Transactions on AI, 2025</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/1568882ba1a50316e87852542523739c-Abstract-Datasets_and_Benchmarks_Track.html">CVQA: Culturally-diverse Multilingual Visual Question Answering Benchmark</a>
        </span><br>
        David Romero, Chenyang Lyu, Haryo Akbarianto Wibowo, Teresa Lynn, Injy Hamed, Aditya Nanda Kishore, Aishik Mandal, Alina Dragonetti, …, Sukannya Purkayastha, …, Thamar Solorio<br>
        <em>NeurIPS (Datasets & Benchmarks), 2024</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://aclanthology.org/2023.emnlp-main.894/">Exploring Jiu-Jitsu Argumentation for Writing Peer Review Rebuttals</a>
        </span><br>
        Sukannya Purkayastha, Anne Lauscher, Iryna Gurevych<br>
        <em>EMNLP, 2023</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://aclanthology.org/W19-1912/">Medical Entity Linking using Triplet Network</a>
        </span><br>
        Ishani Mondal, Sukannya Purkayastha, Sudeshna Sarkar, Pawan Goyal, Jitesh Pillai, Amitava Bhattacharyya, Mahanandeeshwar Gattu<br>
        <em>Clinical NLP Workshop, 2019</em><br><br>

        <span style="white-space: nowrap;">
          <a href="https://ieeexplore.ieee.org/abstract/document/8941958/">Drug-Drug Interactions Prediction Based on Drug Embedding and Graph Auto-Encoder</a>
        </span><br>
        Sukannya Purkayastha, Ishani Mondal, Sudeshna Sarkar, Pawan Goyal, Jitesh K. Pillai<br>
        <em>BIBE, 2019</em><br>
        <hr style="border: none; border-top: 1px solid #ddd; margin: 2rem 0;">
    design:
      css_id: publications
      columns: '1'
      spacing:
        padding: ['2rem', '0', '1rem', '0']

---
