---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
(\*equal contribution, #corresponding)

**[1] NovoBench: Benchmarking Deep Learning-based De Novo Peptide Sequencing Methods in Proteomics**<br/>
Zhou J, Chen S, Xia J, Liu S, __Ling T__, Du W, Liu Y, Yin J, Li S.arXiv. 2024.

**[2] π-PrimeNovo: An Accurate and Efficient Non-Autoregressive Deep Learning Model for De Novo Peptide Sequencing** <br/>
Zhang X\*, __Ling T\*__, Jin Z\*, Xu S*, Gao Z, Sun B, Qiu Z, Dong N, Wang G, Wang G, Li L, Mageed M, Lakshmanan L, Ouyang W#, Chang C#, Sun S#. bioRxiv Preprint, 2024.<br/>

**[3] Introducing π-HelixNovo for Practical Large-scale De Novo Peptide Sequencing** <br/>
Yang T, __Ling T__, Sun B, Liang Z, Xu F, Huang X, Xie L, He Y, Li L, He F, Wang Y#, Chang C#.Brief Bioinform. 2024.<br/>

**[4] ContraNovo: A Contrastive Learning Approach to Enhance De Novo Peptide Sequencing**<br/>
Jin Z*, Xu S*, Zhang X*, __Ling T__, Dong, N, Ouyang, W#, Gao, Z#, Chang, C#, Sun, S#. AAAI.2024.<br/>

**[5] AdaNovo: Adaptive De Novo Peptide Sequencing with Conditional Mutual Information**<br/>
Xia J, Chen S, Zhou J, __Ling T__, Du W, Liu S, Li S. arXiv. 2024.<br/>

**[6] Characterizing RNA-binding Ligands on Structures, Chemical Information, Binding Affinity and Drug-likeness**<br/>
Fan C, Wang X, __Ling T__, Yang Y, Zhao H#. RNA Biology. 2023.<br/>

**[7] Systematic Analysis to Identify Transcriptome-wide Dysregulation of Alzheimer's Disease in Genes and Isoforms**<br/>
Fan C, Ken C, Zhou J, Wong P, He D, Huang Y, Wang X, __Ling T__, Yang Y. Zhao H#. Human Genetics. 2020.<br/>

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
