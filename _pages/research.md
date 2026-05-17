---
permalink: /research/
title: "科研经历"
author_profile: true
---

科研经历主要沿两条线索展开：一是面向第三代半导体器件、忆阻器与生物芯片的材料-器件-表征链路；二是面向 DAS 多事件识别与器件映射神经网络的智能感知建模。

<div class="research-card">
  <div class="research-head"><div><h2>后处理诱导界面 GaOxN1-x 层调控 Ag/GaN/ITO 忆阻器开关特性</h2><p>负责人｜2025.09 - 2026.03｜独立第一作者投稿</p></div><span class="status-tag">第三代半导体器件 / 忆阻器</span></div>
  <div class="research-visuals two-col">
    <figure><img src="{{ site.baseurl }}/images/research/memristor-structure.png" alt="Ag/GaN/ITO 忆阻器器件结构与后处理策略示意图"><figcaption>器件结构、导电细丝机制与未处理 / 退火 / O2 等离子体后处理策略。</figcaption></figure>
    <figure><img src="{{ site.baseurl }}/images/research/memristor-mechanism.png" alt="三组 Ag/GaN/ITO 忆阻器导电细丝机理对比图"><figcaption>不同界面状态下，导电细丝生长与 reset 后残余细丝形态发生分化。</figcaption></figure>
  </div>
  <div class="research-columns"><div><h3>研究内容</h3><p>围绕 <strong>Ag/GaN/ITO 结构忆阻器</strong>，设计未处理、空气退火与 O2 等离子体三组对照实验，系统研究后处理对界面化学状态及电阻开关行为的调控作用。结合 I–V 循环、set/reset 参数统计、电阻读取稳定性测试，以及 XPS、XRD、SEM、AFM 等表征，建立“<strong>后处理—界面 GaOxN1-x 演化—细丝动力学改变—阻变模式分化</strong>”的机理链条。</p></div><div><h3>责任分工</h3><p>负责论文整体方案设计与推进，独立完成器件制备与功能层后处理全流程，包括 GaN、Ag 磁控溅射薄膜沉积、高温退火、等离子体轰击、制备工艺参数优化与后处理条件筛选；完成电学测试方案设计与实施，并进行表征数据整理与对比分析。</p></div></div>
  <div class="result-band"><strong>阶段成果：</strong>论文已投稿至 <em>Journal of Materials Science: Materials in Electronics</em>（Q2 区，独立第一作者）。</div>
</div>

<div class="research-card">
  <div class="research-head"><div><h2>基于多时频融合与器件映射轻量模型的 DAS 多事件识别研究</h2><p>上海交通大学实习生｜2026.01 - 至今｜独立第一作者拟投稿</p></div><span class="status-tag">DAS / CNN / BNN / 器件映射</span></div>
  <div class="research-visuals two-col wide-figures">
    <figure><img src="{{ site.baseurl }}/images/research/das-overview.png" alt="DAS 多时频融合与忆阻器感知 BNN 框架图"><figcaption>面向 DAS 多事件识别的四通道特征融合与 Digital BNN / Memristor-aware BNN 框架。</figcaption></figure>
    <figure><img src="{{ site.baseurl }}/images/research/das-monte-carlo.png" alt="忆阻器交叉阵列结构、二值卷积与 Monte Carlo 稳定性图"><figcaption>忆阻器交叉阵列 I–V 特性、二值卷积硬件映射与不同扰动模型下的稳定性评估。</figcaption></figure>
  </div>
  <div class="research-columns"><div><h3>研究内容</h3><p>面向 <strong>DAS 多事件识别</strong>，构建多通道 CNN / BNN 框架；在大样本数据集上系统比较单/多通道方案及多类轻量模型的 Test Accuracy、Macro-F1、混淆矩阵与训练推理效率等性能指标。进一步利用忆阻器高低电导模拟神经网络二值权重，进行矩阵卷积计算，并结合 Monte Carlo 测试评估模型在器件波动条件下的稳定性。</p></div><div><h3>责任分工</h3><p>作为实习项目唯一负责人，独立完成 .mat / .npz 数据读取、多通道特征提取、训练/测试/可视化/报告脚本自动化；负责 SmallCNN、ResNet 等单通道 CNN 与多通道 BNN 的适配和对比实验，完成二值卷积核权重与忆阻器高低电导的硬件映射、pointwise std 扰动建模、重训及 Monte Carlo 稳定性评估流程设计与实现。</p></div></div>
  <div class="result-band"><strong>阶段成果：</strong>论文拟投稿至 <em>Journal of Lightwave Technology</em>（Q1 区，独立第一作者）。</div>
</div>

<div class="research-card">
  <div class="research-head"><div><h2>第三代半导体生物芯片研制及其应用研究（省级大创项目）</h2><p>负责人｜2024.12 - 2026.03</p></div><span class="status-tag">GaN HEMT / 微流控芯片</span></div>
  <div class="research-visuals two-col compact">
    <figure><img src="{{ site.baseurl }}/images/research/biochip-structure.png" alt="内置 HEMT 器件微流控芯片结构示意图"><figcaption>微流控-氮化镓异质集成生物芯片结构示意。</figcaption></figure>
    <figure><img src="{{ site.baseurl }}/images/research/biochip-device.png" alt="微流控芯片实物图"><figcaption>微流控芯片实物与封装验证。</figcaption></figure>
  </div>
  <div class="research-columns"><div><h3>研究内容</h3><p>设计完成“<strong>微流控-氮化镓异质集成生物芯片</strong>”，深入探究第三代半导体芯片与微流控技术的集成，解决生物芯片在复杂液体环境下的界面连接与封装集成问题，完成从底层器件制备到系统集成的完整技术攻关。</p></div><div><h3>责任分工</h3><p>负责 GaN HEMT 器件的微纳加工与制备实验，熟练掌握并独立执行高精度光刻、套刻、台面刻蚀、磁控溅射镀膜、等离子体处理及快速退火重构等全套制备工艺。</p></div></div>
  <div class="result-band"><strong>阶段成果：</strong>以第一发明人公开国家发明专利一项（CN120169453A），以第一著作权人授权软件著作权两项。</div>
</div>

<div class="research-card">
  <div class="research-head"><div><h2>基于实体状态微调的时序知识图谱长效预测框架研究</h2><p>核心成员｜2025.10 - 2026.01｜ACL 2026 接收</p></div><span class="status-tag">Temporal Knowledge Graph / EST</span></div>
  <div class="research-visuals single"><figure><img src="{{ site.baseurl }}/images/research/est-analysis.png" alt="EST 超参数分析与结构编码器对比图"><figcaption>围绕历史长度、时间嵌入维度、结构编码器等关键超参数进行敏感性分析。</figcaption></figure></div>
  <div class="research-columns"><div><h3>研究内容</h3><p>提出通用框架 EST，通过双轨记忆机制解决时序图谱预测中的“<strong>情景性遗忘</strong>”问题。在多个工况数据集上优于对比方法，其中在噪声较大的 GDELT 数据集上较顶尖基线提升近 20%。</p></div><div><h3>责任分工</h3><p>负责论文超参数分析部分的实验验证、数理分析及数据可视化工作。针对关键超参数进行敏感性测试，量化不同参数对模型性能的贡献度。</p></div></div>
  <div class="result-band"><strong>阶段成果：</strong>论文已被自然语言处理顶会 ACL 2026 接收（CCF-A，第二作者），Meta：4.0 / 5.0。</div>
</div>

