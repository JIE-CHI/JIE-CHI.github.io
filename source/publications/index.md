---
title: publications
date: 2024-11-07 22:01:34
---
**Which Data Matter? Embedding-Based Data Selection for Speech Recognition**
   *Authors:* Zakaria Aldeneh, Skyler Seto, Maureen de Seyssel, Jie Chi, Zijin Gu, Takuya Higuchi, Jee-weon Jung, Shinji Watanabe, David Grangier, Barry-John Theobald, Tatiana Likhomanenko  
   *Preprint:* arXiv, 2026  
   *[preprint](https://arxiv.org/abs/2603.05819)* | <button onclick="toggleBibtex('bibtex_data_matter')">BibTeX</button>

<pre id="bibtex_data_matter" style="display: none; background: #f5f5f5; padding: 10px; border-radius: 5px;">
@misc{aldeneh2026datamatterembeddingbaseddata,
      title={Which Data Matter? Embedding-Based Data Selection for Speech Recognition}, 
      author={Zakaria Aldeneh and Skyler Seto and Maureen de Seyssel and Jie Chi and Zijin Gu and Takuya Higuchi and Jee-weon Jung and Shinji Watanabe and David Grangier and Barry-John Theobald and Tatiana Likhomanenko},
      year={2026},
      eprint={2603.05819},
      archivePrefix={arXiv},
      primaryClass={cs.SD},
      url={https://arxiv.org/abs/2603.05819}, 
}
</pre>


**Leveraging Audio-Visual Data to Reduce the Multilingual Gap in Self-Supervised Speech Models**
   *Authors:* María Andrea Cruz Blandón, Zakaria Aldeneh, Jie Chi, Maureen de Seyssel  
   *Conference:* ICASSP 2026  
   *[link](https://ieeexplore.ieee.org/abstract/document/11460798)* | *[preprint](https://arxiv.org/pdf/2509.17523)* | <button onclick="toggleBibtex('bibtex_av_ssl')">BibTeX</button>

<pre id="bibtex_av_ssl" style="display: none; background: #f5f5f5; padding: 10px; border-radius: 5px;">
@inproceedings{cruzblandon2026leveraging,
  title     = {Leveraging Audio-Visual Data to Reduce the Multilingual Gap in Self-Supervised Speech Models},
  author    = {María Andrea Cruz Blandón and Zakaria Aldeneh and Jie Chi and Maureen de Seyssel},
  year      = {2026},
  booktitle = {ICASSP 2026 - 2026 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages     = {17902--17906},
  publisher = {IEEE},
  url       = {https://ieeexplore.ieee.org/abstract/document/11460798},
}
</pre>


**Discriminating Form and Meaning in Multilingual Models with Minimal-Pair ABX Tasks**
   *Authors:* Maureen de Seyssel*, Jie Chi*, Skyler Seto, Maartje ter Hoeve, Masha Fedzechkina, Natalie Schluter 
   *Conference:* EMNLP 2025  
   *[link](https://aclanthology.org/2025.emnlp-main.1210/)* | *[preprint](https://arxiv.org/pdf/2505.17747)* | <button onclick="toggleBibtex('bibtex_abx')">BibTeX</button>

<pre id="bibtex_abx" style="display: none; background: #f5f5f5; padding: 10px; border-radius: 5px;">
@inproceedings{de-seyssel-etal-2025-discriminating,
    title = "Discriminating Form and Meaning in Multilingual Models with Minimal-Pair {ABX} Tasks",
    author = "de Seyssel, Maureen  and
      Chi, Jie  and
      Seto, Skyler  and
      Ter Hoeve, Maartje  and
      Fedzechkina, Masha  and
      Schluter, Natalie",
    editor = "Christodoulopoulos, Christos  and
      Chakraborty, Tanmoy  and
      Rose, Carolyn  and
      Peng, Violet",
    booktitle = "Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.emnlp-main.1210/",
    doi = "10.18653/v1/2025.emnlp-main.1210",
    pages = "23704--23725",
    ISBN = "979-8-89176-332-6",
    abstract = "We introduce a set of training-free ABX-style discrimination tasks to evaluate how multilingual language models represent language identity (form) and semantic content (meaning). Inspired from speech processing, these zero-shot tasks measure whether minimal differences in representation can be reliably detected. This offers a flexible and interpretable alternative to probing. Applied to XLM-R (Conneau et al, 2020) across pretraining checkpoints and layers, we find that language discrimination declines over training and becomes concentrated in lower layers, while meaning discrimination strengthens over time and stabilizes in deeper layers. We then explore probing tasks, showing some alignment between our metrics and linguistic learning performance.Our results position ABX tasks as a lightweight framework for analyzing the structure of multilingual representations."
}
</pre>




**The Role of Prosody in Spoken Question Answering**
   *Authors:* Jie Chi, Maureen de Seyssel, Natalie Schluter  
   *Conference:* Findings of NAACL  
   *[link](https://aclanthology.org/2025.findings-naacl.471.pdf)* | <button onclick="toggleBibtex('bibtex_prosody')">BibTeX</button>

<pre id="bibtex_prosody" style="display: none; background: #f5f5f5; padding: 10px; border-radius: 5px;">
@inproceedings{chi-etal-2025-role,
    title = "The Role of Prosody in Spoken Question Answering",
    author = "Chi, Jie  and
      de Seyssel, Maureen  and
      Schluter, Natalie",
    editor = "Chiruzzo, Luis  and
      Ritter, Alan  and
      Wang, Lu",
    booktitle = "Findings of the Association for Computational Linguistics: NAACL 2025",
    month = apr,
    year = "2025",
    address = "Albuquerque, New Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.findings-naacl.471/",
    doi = "10.18653/v1/2025.findings-naacl.471",
    pages = "8468--8479",
    ISBN = "979-8-89176-195-7",
    abstract = "Spoken language understanding research to date has generally carried a heavy text perspective. Most datasets are derived from text, which is then subsequently synthesized into speech, and most models typically rely on automatic transcriptions of speech. This is to the detriment of prosody{--}additional information carried by the speech signal beyond the phonetics of the words themselves and difficult to recover from text alone. In this work, we investigate the role of prosody in Spoken Question Answering. By isolating prosodic and lexical information on the SLUE-SQA-5 dataset, which consists of natural speech, we demonstrate that models trained on prosodic information alone can perform reasonably well by utilizing prosodic cues. However, we find that when lexical information is available, models tend to predominantly rely on it. Our findings suggest that while prosodic cues provide valuable supplementary information, more effective integration methods are required to ensure prosody contributes more significantly alongside lexical features."
}
</pre>


**Characterizing code-switching: Applying Linguistic Principles for Metric Assessment and Development**  
   *Authors:* Jie Chi*, Electra Wallington*, Peter Bell  
   *Conference:* InterSpeech 2024  
   *[link](https://www.isca-archive.org/interspeech_2024/chi24_interspeech.pdf)* | <button onclick="toggleBibtex('bibtex_character')">BibTeX</button>
<pre id="bibtex_character" style="display: none; background: #f5f5f5; padding: 10px; border-radius: 5px;">
@inproceedings{chi24_interspeech,
  title     = {Characterizing code-switching: Applying Linguistic Principles for Metric Assessment and Development},
  author    = {Jie Chi and Electra Wallington and Peter Bell},
  year      = {2024},
  booktitle = {Interspeech 2024},
  pages     = {7--11},
  doi       = {10.21437/Interspeech.2024-551},
  issn      = {2958-1796},
}
</pre>

**Analyzing the Role of Part-of-Speech in Code-Switching: A Corpus-Based Study**  
   *Authors:* Jie Chi, Peter Bell  
   *Conference:* Findings of EACL 2024  
   *[link](https://aclanthology.org/2024.findings-eacl.120.pdf)* | <button onclick="toggleBibtex('bibtex_pos')">BibTeX</button>
<pre id="bibtex_pos" style="display: none; background: #f5f5f5; padding: 10px; border-radius: 5px;">
@inproceedings{chi-bell-2024-analyzing,
    title = "Analyzing the Role of Part-of-Speech in Code-Switching: A Corpus-Based Study",
    author = "Chi, Jie  and
      Bell, Peter",
    booktitle = "Findings of the Association for Computational Linguistics: EACL 2024",
    month = mar,
    year = "2024",
    address = "St. Julian{'}s, Malta",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.findings-eacl.120/",
    pages = "1712--1721",
}
</pre>

**Capturing Formality in Speech Across Domains and Languages**  
   *Authors:* Debasmita Bhattacharya, Jie Chi, Julia Hirschberg, Peter Bell  
   *Conference:* InterSpeech 2023  
   *[link](https://www.isca-archive.org/interspeech_2023/bhattacharya23_interspeech.pdf)* | <button onclick="toggleBibtex('bibtex_formality')">BibTeX</button>

<pre id="bibtex_formality" style="display: none; background: #f5f5f5; padding: 10px; border-radius: 5px;">
@inproceedings{bhattacharya23_interspeech,
  title     = {Capturing Formality in Speech Across Domains and Languages},
  author    = {Debasmita Bhattacharya and Jie Chi and Julia Hirschberg and Peter Bell},
  year      = {2023},
  booktitle = {Interspeech 2023},
  pages     = {1030--1034},
  doi       = {10.21437/Interspeech.2023-1852},
  issn      = {2958-1796},
}
</pre>


**Unsupervised Code-switched Text Generation from Parallel Text**  
   *Authors:* Jie Chi*, Brian Lu*, Jason Eisner, Peter Bell, Preethi Jyothi, Ahmed M. Ali  
   *Conference:* InterSpeech 2023  
   *[link](https://www.isca-archive.org/interspeech_2023/chi23_interspeech.pdf)* |<button onclick="toggleBibtex('bibtex_cstext')">BibTeX</button>
<pre id="bibtex_cstext" style="display: none; background: #f5f5f5; padding: 10px; border-radius: 5px;">
@inproceedings{chi23_interspeech,
  title     = {Unsupervised Code-switched Text Generation from Parallel Text},
  author    = {Jie Chi and Brian Lu and Jason Eisner and Peter Bell and Preethi Jyothi and Ahmed M. Ali},
  year      = {2023},
  booktitle = {Interspeech 2023},
  pages     = {1419--1423},
  doi       = {10.21437/Interspeech.2023-1050},
  issn      = {2958-1796},
}
</pre>

**Improving Code-switched ASR with Linguistic Information**  
   *Authors:* Jie Chi, Peter Bell  
   *Conference:* COLING 2022  
   *[link](https://aclanthology.org/2022.coling-1.627.pdf)* | <button onclick="toggleBibtex('bibtex_ect')">BibTeX</button>
<pre id="bibtex_ect" style="display: none; background: #f5f5f5; padding: 10px; border-radius: 5px;">
@inproceedings{chi-bell-2022-improving,
    title = "Improving Code-switched {ASR} with Linguistic Information",
    author = "Chi, Jie  and
      Bell, Peter",
    booktitle = "Proceedings of the 29th International Conference on Computational Linguistics",
    month = oct,
    year = "2022",
    address = "Gyeongju, Republic of Korea",
    publisher = "International Committee on Computational Linguistics",
    url = "https://aclanthology.org/2022.coling-1.627/",
    pages = "7171--7176",
}
</pre>

**Querent Intent in Multi-Sentence Questions**  
   *Authors:* Laurie Burchell*, Jie Chi*, Tom Hosking*, Nina Markl*, Bonnie Webber  
   *Conference:* LAW@COLING 2020  
   *[link](https://aclanthology.org/2020.law-1.13.pdf)* | <button onclick="toggleBibtex('bibtex_msq')">BibTeX</button>
<pre id="bibtex_msq" style="display: none; background: #f5f5f5; padding: 10px; border-radius: 5px;">
@inproceedings{burchell-etal-2020-querent,
    title = "Querent Intent in Multi-Sentence Questions",
    author = "Burchell, Laurie  and
      Chi, Jie  and
      Hosking, Tom  and
      Markl, Nina  and
      Webber, Bonnie",
    booktitle = "Proceedings of the 14th Linguistic Annotation Workshop",
    month = dec,
    year = "2020",
    address = "Barcelona, Spain",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2020.law-1.13/",
    pages = "138--147",
}
</pre>


<script>
  function toggleBibtex(id) {
    var bib = document.getElementById(id);
    bib.style.display = (bib.style.display === "none") ? "block" : "none";
  }
</script>
