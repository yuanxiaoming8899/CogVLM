<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM 和 CogAgent</font></font></h1><a id="user-content-cogvlm--cogagent" class="anchor" aria-label="永久链接：CogVLM 和 CogAgent" href="#cogvlm--cogagent"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📗</font></font><a href="/THUDM/CogVLM/blob/main/README_zh.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文版自述文件</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🌟</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跳转详细介绍：</font></font><a href="#introduction-to-cogvlm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM介绍</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><a href="#introduction-to-cogagent"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🆕CogAgent介绍</font></font></a></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📔更详细的使用信息请参考：</font></font><a href="https://zhipu-ai.feishu.cn/wiki/LXQIwqo1OiIVTykMh9Lc3w1Fn7g" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM &amp; CogAgent 的技术文档（中文）</font></font></a></p>
<table>
  <tbody><tr>
    <td>
      <div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM</font></font></h2><a id="user-content--cogvlm-" class="anchor" aria-label="永久链接：CogVLM" href="#-cogvlm-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
      <p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📖 论文：</font></font><a href="https://arxiv.org/abs/2311.03079" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM：预训练语言模型的视觉专家</font></font></a></p>
      <p dir="auto"><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM</font></font></b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个功能强大的开源视觉语言模型 (VLM)。 CogVLM-17B拥有100亿个视觉参数和70亿个语言参数，</font></font><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持图像理解和多轮对话，分辨率为490*490</font></font></b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
      <p dir="auto"><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM-17B 在 10 个经典跨模式基准测试中实现了最先进的性能</font></font></b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，包括 NoCaps、Flicker30k 字幕、RefCOCO、RefCOCO+、RefCOCOg、Visual7W、GQA、ScienceQA、VizWiz VQA 和 TDIUC。</font></font></p>
    </td>
    <td>
      <div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">协同代理</font></font></h2><a id="user-content--cogagent-" class="anchor" aria-label="永久链接：CogAgent" href="#-cogagent-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
      <p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📖 论文：</font></font><a href="https://arxiv.org/abs/2312.08914" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogAgent：GUI 代理的视觉语言模型</font></font></a></p>
      <p dir="auto"><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogAgent</font></font></b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是基于CogVLM改进的开源视觉语言模型。 CogAgent-18B拥有110亿个视觉参数和70亿个语言参数，</font></font><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持1120*1120分辨率的图像理解</font></font></b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">除了CogVLM的功能之外，它还具备GUI图像代理功能</font></font></b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
      <p dir="auto"> <b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogAgent-18B 在 9 个经典跨模态基准测试上实现了最先进的通用性能</font></font></b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，包括 VQAv2、OK-VQ、TextVQA、ST-VQA、ChartQA、infoVQA、DocVQA、MM-Vet 和 POPE。它显着超越了</font><font style="vertical-align: inherit;">包括 AITW 和 Mind2Web 在内的</font></font><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GUI 操作数据集上的现有模型。</font></font></b><font style="vertical-align: inherit;"></font></p>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🌐 CogVLM 和 CogAgent 的 Web 演示：</font></font><a href="http://36.103.203.44:7861" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此链接</font></font></a></p>
    </td>
  </tr>
</tbody></table>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></strong></p>
<ul dir="auto">
<li><a href="#cogvlm--cogagent"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM 和 CogAgent</font></font></a>
<ul dir="auto">
<li><a href="#release"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布</font></font></a></li>
<li><a href="#get-started"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始使用</font></font></a>
<ul dir="auto">
<li><a href="#option-1-inference-using-web-demo"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项 1：使用 Web 演示进行推理。</font></font></a></li>
<li><a href="#option-2deploy-cogvlm--cogagent-by-yourself"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">方案二：自行部署CogVLM / CogAgent</font></font></a>
<ul dir="auto">
<li><a href="#situation-21-cli-sat-version"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">情况2.1 CLI（SAT版本）</font></font></a></li>
<li><a href="#situation-22-cli-huggingface-version"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">情况2.2 CLI（Hugingface版本）</font></font></a></li>
<li><a href="#situation-23-web-demo"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">情况2.3 网页演示</font></font></a></li>
</ul>
</li>
<li><a href="#option-3finetuning-cogagent--cogvlm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项3：微调CogAgent / CogVLM</font></font></a></li>
<li><a href="#option-4-openai-vision-format"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项 4：OpenAI Vision 格式</font></font></a></li>
<li><a href="#hardware-requirement"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">硬件要求</font></font></a></li>
<li><a href="#model-checkpoints"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型检查点</font></font></a></li>
</ul>
</li>
<li><a href="#introduction-to-cogvlm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM 简介</font></font></a>
<ul dir="auto">
<li><a href="#examples"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></a></li>
</ul>
</li>
<li><a href="#introduction-to-cogagent"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogAgent简介</font></font></a>
<ul dir="auto">
<li><a href="#gui-agent-examples"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GUI 代理示例</font></font></a></li>
</ul>
</li>
<li><a href="#cookbook"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">食谱</font></font></a>
<ul dir="auto">
<li><a href="#task-prompts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务提示</font></font></a></li>
<li><a href="#which---version-to-use"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用哪个版本</font></font></a></li>
<li><a href="#faq"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常问问题</font></font></a></li>
</ul>
</li>
<li><a href="#license"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></a></li>
<li><a href="#citation--acknowledgements"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文与致谢</font></font></a></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布</font></font></h2><a id="user-content-release" class="anchor" aria-label="永久链接：发布" href="#release"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔥🔥🔥  </font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">: </font></font><code>2024/4/5</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">: </font></font><a href="https://arxiv.org/abs/2312.08914" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogAgent</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">被选为 CVPR 2024 亮点！</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔥🔥  </font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">: </font></font><code>2023/12/26</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">: 我们发布了</font></font><a href="/THUDM/CogVLM/blob/main/dataset.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM-SFT-311K</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据集，其中包含超过 150,000 条我们仅用于</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM v1.0</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">训练的数据。欢迎关注和使用。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔥</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">: </font></font><code>2023/12/18</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">:</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新网页用户界面推出！</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们推出了基于 Streamlit 的新 Web UI，用户可以在我们的 UI 中轻松地与 CogVLM、CogAgent 对话。拥有更好的用户体验。</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">:: </font></font><code>2023/12/15</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogAgent</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正式上线！</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> CogAgent是基于CogVLM开发的图像理解模型。它具有</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于视觉的 GUI Agent 功能</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并进一步增强了图像理解能力。支持分辨率1120*1120的图像输入，并具备图像多轮对话、GUI Agent、Grounding等多种能力。</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><code>2023/12/8</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们已将 cogvlm-grounding-generalist 的检查点更新为 cogvlm-grounding-generalist-v1.1，在训练期间进行图像增强，因此更加稳健。查看</font></font><a href="#introduction-to-cogvlm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具体信息</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><code>2023/12/7</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM 现在支持</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4 位量化</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！只需</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">11GB</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> GPU 内存</font><font style="vertical-align: inherit;">即可进行推理！</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><code>2023/11/20</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们将cogvlm-chat的检查点更新为cogvlm-chat-v1.1，统一了chat和VQA的版本，并刷新了各个数据集上的SOTA。查看</font></font><a href="#introduction-to-cogvlm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具体信息</font></font></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><code>2023/11/20</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们</font><font style="vertical-align: inherit;">在🤗Huggingface 上发布了</font></font><strong><a href="https://huggingface.co/THUDM/cogvlm-chat-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm-chat</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><a href="https://huggingface.co/THUDM/cogvlm-grounding-generalist-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm-grounding-generalist</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> / </font></font><a href="https://huggingface.co/THUDM/cogvlm-grounding-base-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">base</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><a href="https://huggingface.co/THUDM/cogvlm-base-490-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm-base-490</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> / </font></font><a href="https://huggingface.co/THUDM/cogvlm-base-224-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">224</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 。现在您可以通过</font></font><a href="#situation-22-cli-huggingface-version"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">几行代码</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Transformer 进行推断！</font></font></p>
</li>
<li>
<p dir="auto"><code>2023/10/27</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM 双语版本已上</font></font><a href="https://chatglm.cn/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！欢迎大家来尝试一下！</font></font></p>
</li>
<li>
<p dir="auto"><code>2023/10/5</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM-17B发布。</font></font></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始使用</font></font></h2><a id="user-content-get-started" class="anchor" aria-label="永久链接：开始" href="#get-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项 1：使用 Web 演示进行推理。</font></font></h3><a id="user-content-option-1-inference-using-web-demo" class="anchor" aria-label="永久链接：选项 1：使用 Web 演示进行推理。" href="#option-1-inference-using-web-demo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">点击此处进入</font></font><a href="http://36.103.203.44:7861/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM &amp; CogAgent Web Demo</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果需要使用Agent和Grounding功能，请参考</font></font><a href="#task-prompts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cookbook - 任务提示</font></font></a></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">方案二：自行部署CogVLM / CogAgent</font></font></h3><a id="user-content-option-2deploy-cogvlm--cogagent-by-yourself" class="anchor" aria-label="永久链接：选项2：自行部署CogVLM / CogAgent" href="#option-2deploy-cogvlm--cogagent-by-yourself"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们支持两种用于模型推理的 GUI：</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CLI</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web demo</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。如果您想在 Python 代码中使用它，可以轻松地根据您的情况修改 CLI 脚本。</font></font></p>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，我们需要安装依赖项。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> CUDA &gt;= 11.8</span>
pip install -r requirements.txt
python -m spacy download en_core_web_sm</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# CUDA >= 11.8
pip install -r requirements.txt
python -m spacy download en_core_web_sm" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有推理代码都位于该</font></font><code>basic_demo/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录下。请先切换到该目录，然后再进行进一步操作。</font></font></strong></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">情况2.1 CLI（SAT版本）</font></font></h4><a id="user-content-situation-21-cli-sat-version" class="anchor" aria-label="永久链接：情况 2.1 CLI（SAT 版本）" href="#situation-21-cli-sat-version"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过以下方式运行 CLI 演示：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> CogAgent</span>
python cli_demo_sat.py --from_pretrained cogagent-chat --version chat --bf16  --stream_chat
python cli_demo_sat.py --from_pretrained cogagent-vqa --version chat_old --bf16  --stream_chat

<span class="pl-c"><span class="pl-c">#</span> CogVLM</span>
python cli_demo_sat.py --from_pretrained cogvlm-chat --version chat_old --bf16  --stream_chat
python cli_demo_sat.py --from_pretrained cogvlm-grounding-generalist --version base --bf16  --stream_chat</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# CogAgent
python cli_demo_sat.py --from_pretrained cogagent-chat --version chat --bf16  --stream_chat
python cli_demo_sat.py --from_pretrained cogagent-vqa --version chat_old --bf16  --stream_chat

# CogVLM
python cli_demo_sat.py --from_pretrained cogvlm-chat --version chat_old --bf16  --stream_chat
python cli_demo_sat.py --from_pretrained cogvlm-grounding-generalist --version base --bf16  --stream_chat" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">程序将自动下载 sat 模型并在命令行中进行交互。您可以通过输入说明并按 Enter 键来生成回复。输入</font></font><code>clear</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可清除对话历史记录并</font></font><code>stop</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">停止程序。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们还支持模型并行推理，将模型分割到多个 (2/4/8) GPU。</font></font><code>--nproc-per-node=[n]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下命令控制使用的 GPU 数量。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>torchrun --standalone --nnodes=1 --nproc-per-node=2 cli_demo_sat.py --from_pretrained cogagent-chat --version chat --bf16
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="torchrun --standalone --nnodes=1 --nproc-per-node=2 cli_demo_sat.py --from_pretrained cogagent-chat --version chat --bf16" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果要手动下载权重，可以将后面的路径替换</font></font><code>--from_pretrained</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为模型路径。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的模型支持SAT的</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4位量化</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8位量化</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。您可以更改</font></font><code>--bf16</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>--fp16</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、 或</font></font><code>--fp16 --quant 4</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、 或</font></font><code>--fp16 --quant 8</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python cli_demo_sat.py --from_pretrained cogagent-chat --fp16 --quant 8 --stream_chat
python cli_demo_sat.py --from_pretrained cogvlm-chat-v1.1 --fp16 --quant 4 --stream_chat
<span class="pl-c"><span class="pl-c">#</span> In SAT version，--quant should be used with --fp16</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python cli_demo_sat.py --from_pretrained cogagent-chat --fp16 --quant 8 --stream_chat
python cli_demo_sat.py --from_pretrained cogvlm-chat-v1.1 --fp16 --quant 4 --stream_chat
# In SAT version，--quant should be used with --fp16" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该程序提供了以下超参数来控制生成过程：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>usage: cli_demo_sat.py [-h] [--max_length MAX_LENGTH] [--top_p TOP_P] [--top_k TOP_K] [--temperature TEMPERATURE]

optional arguments:
-h, --help            show this help message and exit
--max_length MAX_LENGTH
                        max length of the total sequence
--top_p TOP_P         top p for nucleus sampling
--top_k TOP_K         top k for top k sampling
--temperature TEMPERATURE
                        temperature for sampling
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="usage: cli_demo_sat.py [-h] [--max_length MAX_LENGTH] [--top_p TOP_P] [--top_k TOP_K] [--temperature TEMPERATURE]

optional arguments:
-h, --help            show this help message and exit
--max_length MAX_LENGTH
                        max length of the total sequence
--top_p TOP_P         top p for nucleus sampling
--top_k TOP_K         top k for top k sampling
--temperature TEMPERATURE
                        temperature for sampling" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">点击</font></font><a href="#which---version-to-use"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看不同型号及</font></font><code>--version</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
参数的对应关系。</font></font></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">情况2.2 CLI（Hugingface版本）</font></font></h4><a id="user-content-situation-22-cli-huggingface-version" class="anchor" aria-label="永久链接：情况 2.2 CLI（Huggingface 版本）" href="#situation-22-cli-huggingface-version"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过以下方式运行 CLI 演示：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> CogAgent</span>
python cli_demo_hf.py --from_pretrained THUDM/cogagent-chat-hf --bf16
python cli_demo_hf.py --from_pretrained THUDM/cogagent-vqa-hf --bf16

<span class="pl-c"><span class="pl-c">#</span> CogVLM</span>
python cli_demo_hf.py --from_pretrained THUDM/cogvlm-chat-hf --bf16
python cli_demo_hf.py --from_pretrained THUDM/cogvlm-grounding-generalist-hf --bf16</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# CogAgent
python cli_demo_hf.py --from_pretrained THUDM/cogagent-chat-hf --bf16
python cli_demo_hf.py --from_pretrained THUDM/cogagent-vqa-hf --bf16

# CogVLM
python cli_demo_hf.py --from_pretrained THUDM/cogvlm-chat-hf --bf16
python cli_demo_hf.py --from_pretrained THUDM/cogvlm-grounding-generalist-hf --bf16" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果要手动下载权重，可以将后面的路径替换</font></font><code>--from_pretrained</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为模型路径。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以更改</font></font><code>--bf16</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>--fp16</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, 或</font></font><code>--quant 4</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。例如，我们的模型支持 Huggingface 的</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4 位量化</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python cli_demo_hf.py --from_pretrained THUDM/cogvlm-chat-hf --quant 4</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python cli_demo_hf.py --from_pretrained THUDM/cogvlm-chat-hf --quant 4" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">情况2.3 网页演示</font></font></h4><a id="user-content-situation-23-web-demo" class="anchor" aria-label="永久链接：情况 2.3 Web 演示" href="#situation-23-web-demo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们还提供基于 Gradio 的本地网络演示。首先，通过运行以下命令安装 Gradio：</font></font><code>pip install gradio</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。然后下载并进入这个存储库并运行</font></font><code>web_demo.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。详细使用方法见下一节：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python web_demo.py --from_pretrained cogagent-chat --version chat --bf16
python web_demo.py --from_pretrained cogagent-vqa --version chat_old --bf16
python web_demo.py --from_pretrained cogvlm-chat-v1.1 --version chat_old --bf16
python web_demo.py --from_pretrained cogvlm-grounding-generalist --version base --bf16</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python web_demo.py --from_pretrained cogagent-chat --version chat --bf16
python web_demo.py --from_pretrained cogagent-vqa --version chat_old --bf16
python web_demo.py --from_pretrained cogvlm-chat-v1.1 --version chat_old --bf16
python web_demo.py --from_pretrained cogvlm-grounding-generalist --version base --bf16" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web 演示的 GUI 如下所示：</font></font></p>
<div align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/THUDM/CogVLM/blob/main/assets/web_demo-min.png"><img src="/THUDM/CogVLM/raw/main/assets/web_demo-min.png" width="70%" style="max-width: 100%;"></a>
</div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项3：微调CogAgent / CogVLM</font></font></h3><a id="user-content-option-3finetuning-cogagent--cogvlm" class="anchor" aria-label="永久链接：选项 3：微调 CogAgent / CogVLM" href="#option-3finetuning-cogagent--cogvlm"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可能想在自己的任务中使用 CogVLM，这需要</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不同的输出样式或领域知识</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有微调的代码都位于该</font></font><code>finetune_demo/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录下。</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们在这里提供了一个使用 lora 进行</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">验证码识别</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的微调示例。</font></font></p>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先下载</font></font><a href="https://www.kaggle.com/datasets/aadhavvignesh/captcha-images" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">验证码图像数据集</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。下载后，解压 ZIP 文件的内容。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要以 80/5/15 的比例创建训练/验证/测试拆分，请执行以下命令：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python utils/split_dataset.py</pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用以下命令启动微调过程：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>bash finetune_demo/finetune_(cogagent/cogvlm)_lora.sh</pre><div class="zeroclipboard-container">
  
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将模型合并为</font></font><code>model_parallel_size=1</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：（将下面的 4 替换为您的训练</font></font><code>MP_SIZE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>torchrun --standalone --nnodes=1 --nproc-per-node=4 utils/merge_model.py --version base --bf16 --from_pretrained ./checkpoints/merged_lora_(cogagent/cogvlm490/cogvlm224)</pre><div class="zeroclipboard-container">
  
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评估模型的性能。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>bash finetune_demo/evaluate_(cogagent/cogvlm).sh</pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项 4：OpenAI Vision 格式</font></font></h3><a id="user-content-option-4-openai-vision-format" class="anchor" aria-label="永久链接：选项 4：OpenAI Vision 格式" href="#option-4-openai-vision-format"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们提供与 相同的 API 示例</font></font><code>GPT-4V</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，您可以在 中查看</font></font><code>openai_demo</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先启动节点</font></font></li>
</ol>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python openai_demo/openai_api.py
</code></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ol start="2" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接下来，运行请求示例节点，这是一个连续对话的示例</font></font></li>
</ol>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python openai_demo/openai_api_request.py
</code></pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ol start="3" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您将得到类似于以下内容的输出</font></font></li>
</ol>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>This image showcases a tranquil natural scene with a wooden pathway leading through a field of lush green grass. In the distance, there are trees and some scattered structures, possibly houses or small buildings. The sky is clear with a few scattered clouds, suggesting a bright and sunny day.
</code></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">硬件要求</font></font></h3><a id="user-content-hardware-requirement" class="anchor" aria-label="永久链接：硬件要求" href="#hardware-requirement"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型推论：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 INT4 量化：1 * RTX 3090(24G)（CogAgent 占用约 12.6GB，CogVLM 占用约 11GB）</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 FP16：1 * A100(80G) 或 2 * RTX 3090(24G)</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">微调：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 FP16：4 * A100(80G) </font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[推荐]</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或 8* RTX 3090(24G)。</font></font></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型检查点</font></font></h3><a id="user-content-model-checkpoints" class="anchor" aria-label="永久链接：模型检查点" href="#model-checkpoints"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您</font></font><code>basic_demo/cli_demo*.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从代码存储库运行，它将自动下载 SAT 或 Hugging Face 权重。或者，您可以选择手动下载必要的权重。</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">协同代理</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">型号名称</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">输入分辨率</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">抱脸模型</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卫星模型</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">共助聊天</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1120</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogAgent 的聊天版本。支持GUI Agent、多轮聊天、视觉接地。</font></font></td>
<td align="center"><a href="https://huggingface.co/THUDM/cogagent-chat-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a> <br> <a href="https://openxlab.org.cn/models/detail/THUDM/cogagent-chat-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
<td align="center"><a href="https://huggingface.co/THUDM/CogAgent/tree/main" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a><br> <a href="https://openxlab.org.cn/models/detail/THUDM/CogAgent" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">辅助剂-VQA</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1120</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogAgent 的 VQA 版本。具有较强的单轮视觉对话能力。推荐用于 VQA 基准测试。</font></font></td>
<td align="center"><a href="https://huggingface.co/THUDM/cogagent-vqa-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a><br> <a href="https://openxlab.org.cn/models/detail/THUDM/cogagent-vqa-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
<td align="center"><a href="https://huggingface.co/THUDM/CogAgent/tree/main" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a> <br> <a href="https://openxlab.org.cn/models/detail/THUDM/CogAgent" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
</tr>
</tbody>
</table>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">型号名称</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">输入分辨率</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">抱脸模型</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卫星模型</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm-聊天-v1.1</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第490章</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同时支持多轮聊天和vqa，并有不同的提示。</font></font></td>
<td align="center"><a href="https://huggingface.co/THUDM/cogvlm-chat-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a> <br> <a href="https://openxlab.org.cn/models/detail/THUDM/cogvlm-chat-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
<td align="center"><a href="https://huggingface.co/THUDM/CogVLM/tree/main" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a>  <br> <a href="https://openxlab.org.cn/models/detail/THUDM/CogVLM" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm-base-224</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">224</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本图像预训练后的原始检查点。</font></font></td>
<td align="center"><a href="https://huggingface.co/THUDM/cogvlm-base-224-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a> <br> <a href="https://openxlab.org.cn/models/detail/THUDM/cogvlm-base-224-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
<td align="center"><a href="https://huggingface.co/THUDM/CogVLM/tree/main" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a> <br> <a href="https://openxlab.org.cn/models/detail/THUDM/CogVLM" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm-base-490</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第490章</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过位置编码插值将分辨率放大到 490 </font></font><code>cogvlm-base-224</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="center"><a href="https://huggingface.co/THUDM/cogvlm-base-490-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a> <br> <a href="https://openxlab.org.cn/models/detail/THUDM/cogvlm-base-490-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
<td align="center"><a href="https://huggingface.co/THUDM/CogVLM/tree/main" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a> <br> <a href="https://openxlab.org.cn/models/detail/THUDM/CogVLM" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm 基础通才</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第490章</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该检查点支持不同的视觉基础任务，例如录制、基础字幕等。</font></font></td>
<td align="center"><a href="https://huggingface.co/THUDM/cogvlm-grounding-generalist-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a>  <br> <a href="https://openxlab.org.cn/models/detail/THUDM/cogvlm-grounding-generalist-hf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
<td align="center"><a href="https://huggingface.co/THUDM/CogVLM/tree/main" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 链接</font></font></a>   <br> <a href="https://openxlab.org.cn/models/detail/THUDM/CogVLM" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab 链接</font></font></a></td>
</tr>
</tbody>
</table>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM 简介</font></font></h2><a id="user-content-introduction-to-cogvlm" class="anchor" aria-label="永久链接：CogVLM 简介" href="#introduction-to-cogvlm"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM 是一个功能强大的</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源视觉语言模型</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">VLM</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。 CogVLM-17B拥有100亿个视觉参数和70亿个语言参数。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM-17B 在 NoCaps、Flicker30k 字幕、RefCOCO、RefCOCO+、RefCOCOg、Visual7W、GQA、ScienceQA、VizWiz VQA 和 TDIUC 等 10 个经典跨模态基准测试中实现了最先进的性能，并在 VQAv2 上排名第二， OKVQA、TextVQA、COCO字幕等，</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">超越或匹配PaLI-X 55B</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。 CogVLM 还可以</font></font><a href="http://36.103.203.44:7861" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与您讨论</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像。</font></font></p>
</li>
</ul>
<div align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/THUDM/CogVLM/blob/main/assets/metrics-min.png"><img src="/THUDM/CogVLM/raw/main/assets/metrics-min.png" width="50%" style="max-width: 100%;"></a>
</div>
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单击查看 MM-VET、POPE、TouchStone 的结果。</font></font></summary>
<table>
    <tbody><tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">方法</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">法学硕士</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">职业教育与培训</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">教皇（对抗性）</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">试金石</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BLIP-2</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼毛-13B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">22.4</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">獭</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MPT-7B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">24.7</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迷你GPT4</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼毛-13B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">24.4</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">70.4</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">531.7</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指导BLIP</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼毛-13B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">25.6</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">77.3</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">552.4</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaMA 适配器 v2</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拉马-7B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">31.4</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">590.1</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拉瓦</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaMA2-7B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">28.1</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">66.3</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">602.7</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mPLUG-Owl</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拉马-7B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">66.8</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">605.4</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaVA-1.5</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼毛-13B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">36.3</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">84.5</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">鸸</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaMA-13B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">36.3</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Qwen-VL-聊天</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">645.2</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">梦想法学硕士</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼毛-7B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">35.9</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">76.5</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼毛-7B</font></font></td>
        <td> <b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">52.8</font></font></b> </td>
        <td><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">87.6</font></font></b></td>
        <td><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">742.0</font></font></b></td>
    </tr>
</tbody></table>
</details>
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单击可查看 cogvlm-grounding-generalist-v1.1 的结果。</font></font></summary>
<table>
    <tbody><tr>
        <td></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参考COCO</font></font></td>
        <td></td>
        <td></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参考COCO+</font></font></td>
        <td></td>
        <td></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参考COCOg</font></font></td>
        <td></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视觉7W</font></font></td>
    </tr>
    <tr>
        <td></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">瓦尔</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试A</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">瓦尔</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试A</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试B</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">瓦尔</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvim 基础通才</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">92.51</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">93.95</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">88.73</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">87.52</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">91.81</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">81.43</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">89.46</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">90.09</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">90.96</font></font></td>
    </tr>
    <tr>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvim-grounding-generalist-v1.1</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">**92.76**</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">**94.75**</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">**88.99**</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">**88.68**</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">**92.91**</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">**83.39**</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">**89.75**</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">**90.79**</font></font></td>
        <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">**91.05**</font></font></td>
    </tr>
</tbody></table>
</details>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></h3><a id="user-content-examples" class="anchor" aria-label="永久链接：示例" href="#examples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM可以准确地详细描述图像，</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">几乎没有幻觉</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
  <details>
  <summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">点击查看与 LLAVA-1.5 和 MiniGPT-4 的比较。</font></font></summary>
  <a target="_blank" rel="noopener noreferrer" href="/THUDM/CogVLM/blob/main/assets/llava-comparison-min.png"><img src="/THUDM/CogVLM/raw/main/assets/llava-comparison-min.png" width="50%" style="max-width: 100%;"></a>
  </details>
  <br>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM可以理解并回答各种类型的问题，并且有</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视觉基础</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本。</font></font></p>
</li>
</ul>
<div align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/THUDM/CogVLM/blob/main/assets/pear_grounding.png"><img src="/THUDM/CogVLM/raw/main/assets/pear_grounding.png" width="50%" style="max-width: 100%;"></a>
</div>
<br>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogVLM 有时捕获比 GPT-4V(ision) 更详细的内容。</font></font></li>
</ul>
<div align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/THUDM/CogVLM/blob/main/assets/compare-min.png"><img src="/THUDM/CogVLM/raw/main/assets/compare-min.png" width="50%" style="max-width: 100%;"></a>
</div>

<br> 
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单击展开更多示例。</font></font></summary>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/THUDM/CogVLM/blob/main/assets/chat.png"><img src="/THUDM/CogVLM/raw/main/assets/chat.png" alt="聊天示例" style="max-width: 100%;"></a></p>
</details>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogAgent简介</font></font></h2><a id="user-content-introduction-to-cogagent" class="anchor" aria-label="永久链接：CogAgent 简介" href="#introduction-to-cogagent"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogAgent是基于CogVLM改进的开源视觉语言模型。 CogAgent-18B拥有110亿个视觉参数和70亿个语言参数</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CogAgent-18B 在 9 个经典跨模态基准测试上实现了最先进的通用性能，包括 VQAv2、OK-VQ、TextVQA、ST-VQA、ChartQA、infoVQA、DocVQA、MM-Vet 和 POPE。它显着超越了 AITW 和 Mind2Web 等 GUI 操作数据集上的现有模型。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">除了 CogVLM 中已有的所有功能（视觉多轮对话、视觉基础）之外，CogAgent：</font></font></p>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持更高分辨率的视觉输入和对话问答。</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它支持1120x1120的超高分辨率图像输入。</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拥有可视化 Agent 的功能</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，能够在任何 GUI 屏幕截图上返回计划、下一步行动和特定操作以及任何给定任务的坐标。</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">增强了GUI相关的问答功能</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，使其可以处理任何GUI屏幕截图的问题，例如网页、PC应用程序、移动应用程序等。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过改进预训练和微调，增强 OCR 相关任务的能力。</font></font></p>
</li>
</ol>
<div align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/THUDM/CogVLM/blob/main/assets/cogagent_function.jpg"><img src="/THUDM/CogVLM/raw/main/assets/cogagent_function.jpg" width="60%" style="max-width: 100%;"></a>
</div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GUI 代理示例</font></font></h3><a id="user-content-gui-agent-examples" class="anchor" aria-label="永久链接：GUI 代理示例" href="#gui-agent-examples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/THUDM/CogVLM/blob/main/assets/cogagent_main_demo.jpg"><img src="/THUDM/CogVLM/raw/main/assets/cogagent_main_demo.jpg" width="90%" style="max-width: 100%;"></a>
</div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">食谱</font></font></h2><a id="user-content-cookbook" class="anchor" aria-label="永久链接：食谱" href="#cookbook"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务提示</font></font></h3><a id="user-content-task-prompts" class="anchor" aria-label="永久链接：任务提示" href="#task-prompts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般多轮对话</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：想说什么就说什么。</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GUI 代理任务</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：使用</font></font><a href="https://github.com/THUDM/CogVLM/blob/main/utils/utils/template.py#L761"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代理模板</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
并将 &lt;TASK&gt; 替换为用双引号括起来的任务指令。该查询可以使 CogAgent 推断出计划和下一步行动。如果</font></font><code>(with grounding)</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在查询末尾添加，模型将返回带有坐标的形式化动作表示。</font></font></p>
</li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，要询问模型如何在当前 GUI 屏幕截图上完成“搜索 CogVLM”任务，请按照以下步骤操作：</font></font></p>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/THUDM/CogVLM/blob/main/utils/utils/template.py#L761"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从Agent 模板</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中随机选择一个模板</font><font style="vertical-align: inherit;">。在这里，我们选择</font></font><code>What steps do I need to take to &lt;TASK&gt;?</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">替换为用双引号括起来的任务指令，例如</font></font><code>What steps do I need to take to "Search for CogVLM"?</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.将其输入模型会产生：</font></font></p>
</li>
</ol>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计划： 1. 在 Google 搜索栏中输入“CogVLM”。 2. 查看显示的搜索结果。 3. 单击相关结果以阅读有关 CogVLM 的更多信息或访问更多资源。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下一步操作：将光标移至 Google 搜索栏，然后输入“CogVLM”。</font></font></p>
</blockquote>
<ol start="3" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果</font></font><code>(with grounding)</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在最后添加，即将输入更改为</font></font><code>What steps do I need to take to "Search for CogVLM"?(with grounding)</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，CogAgent 的输出将是：</font></font></li>
</ol>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计划： 1. 在 Google 搜索栏中输入“CogVLM”。 2. 查看显示的搜索结果。 3. 单击相关结果以阅读有关 CogVLM 的更多信息或访问更多资源。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下一步操作：将光标移至 Google 搜索栏，然后输入“CogVLM”。接地操作：[combobox] 搜索 -&gt; 类型：CogVLM 位于框 [[212,498,787,564]]</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提示：对于 GUI Agent 任务，建议仅对每个图像进行单轮对话以获得更好的结果。</font></font></p>
<ol start="3" dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视觉接地</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。支持三种接地方式：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带有接地坐标（边界框）的图像描述。使用</font></font><a href="https://github.com/THUDM/CogVLM/blob/main/utils/utils/template.py#L537"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">caption_with_box模板</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中的任何模板作为模型输入。例如：</font></font></li>
</ul>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您能否提供图像的描述并包含每个提到的对象的坐标 [[x0,y0,x1,y1]] ？</font></font></p>
</blockquote>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据对象的描述返回接地坐标（边界框）。使用</font></font><a href="https://github.com/THUDM/CogVLM/blob/main/utils/utils/template.py#L345"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">caption2box template</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中的任何模板</font><font style="vertical-align: inherit;">，替换</font></font><code>&lt;expr&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为对象的描述。例如：</font></font></li>
</ul>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">你能指出</font><font style="vertical-align: inherit;">图像中</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">穿着蓝色 T 恤的孩子并提供他们所在位置的边界框吗？</font></font></em><font style="vertical-align: inherit;"></font></p>
</blockquote>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供基于边界框坐标的描述。使用</font></font><a href="https://github.com/THUDM/CogVLM/blob/main/utils/utils/template.py#L400"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">box2caption template</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中的模板</font><font style="vertical-align: inherit;">，替换</font></font><code>&lt;objs&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为位置坐标。例如：</font></font></li>
</ul>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">告诉我你在图中</font><font style="vertical-align: inherit;">指定区域</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[[086,540,400,760]]内看到了什么。</font></font></em><font style="vertical-align: inherit;"></font></p>
</blockquote>
</li>
</ol>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">坐标格式：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型输入输出中的边界框坐标采用格式</font></font><code>[[x1, y1, x2, y2]]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，原点位于左上角，x轴向右，y轴向下。 (x1, y1) 和 (x2, y2) 分别是左上角和右下角，其值为相对坐标乘以 1000（以零到三位数字为前缀）。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用哪个版本</font></font></h3><a id="user-content-which---version-to-use" class="anchor" aria-label="永久链接：使用哪个版本" href="#which---version-to-use"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于机型功能的差异，不同机型版本的</font></font><code>--version</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本处理器规格可能不同，即所使用的提示格式也有所不同。</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">型号名称</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 版本</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">共助聊天</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聊天</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">辅助剂-VQA</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聊天旧</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm 聊天</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聊天旧</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm-聊天-v1.1</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聊天旧</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm 基础通才</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm-base-224</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cogvlm-base-490</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常问问题</font></font></h3><a id="user-content-faq" class="anchor" aria-label="永久链接：常见问题解答" href="#faq"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您在访问 Huggingface.co 时遇到问题，您可以添加</font></font><code>--local_tokenizer /path/to/vicuna-7b-v1.5</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加载分词器。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您在使用 🔨 </font></font><a href="https://github.com/THUDM/SwissArmyTransformer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SAT</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动下载模型时遇到问题，请尝试从 🤖 </font></font><a href="https://www.modelscope.cn/models/ZhipuAI/CogVLM/summary" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">modelscope</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或 🤗 </font></font><a href="https://huggingface.co/THUDM/CogVLM" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Huggingface</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或 💡wisemodel</font></font><a href="https://www.wisemodel.cn/models/ZhipuAI/CogVLM" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手动</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载
。</font></font></li>
<li><font style="vertical-align: inherit;"></font><a href="https://github.com/THUDM/SwissArmyTransformer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用🔨 SAT</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载模型</font><font style="vertical-align: inherit;">，模型将保存到默认位置</font></font><code>~/.sat_models</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。通过设置环境变量更改默认位置</font></font><code>SAT_HOME</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。例如，如果要将模型保存到</font></font><code>/path/to/my/models</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，可以</font></font><code>export SAT_HOME=/path/to/my/models</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在运行 python 命令之前运行。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库中的代码是在</font></font><a href="/THUDM/CogVLM/blob/main/LICENSE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache-2.0 许可证</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下开源的，而 CogVLM 模型权重的使用必须遵守</font></font><a href="/THUDM/CogVLM/blob/main/MODEL_LICENSE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型许可证</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文与致谢</font></font></h2><a id="user-content-citation--acknowledgements" class="anchor" aria-label="永久链接：引文和致谢" href="#citation--acknowledgements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现我们的工作有帮助，请考虑引用以下论文</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@misc{wang2023cogvlm,
      title={CogVLM: Visual Expert for Pretrained Language Models}, 
      author={Weihan Wang and Qingsong Lv and Wenmeng Yu and Wenyi Hong and Ji Qi and Yan Wang and Junhui Ji and Zhuoyi Yang and Lei Zhao and Xixuan Song and Jiazheng Xu and Bin Xu and Juanzi Li and Yuxiao Dong and Ming Ding and Jie Tang},
      year={2023},
      eprint={2311.03079},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@misc{hong2023cogagent,
      title={CogAgent: A Visual Language Model for GUI Agents}, 
      author={Wenyi Hong and Weihan Wang and Qingsong Lv and Jiazheng Xu and Wenmeng Yu and Junhui Ji and Yan Wang and Zihan Wang and Yuxiao Dong and Ming Ding and Jie Tang},
      year={2023},
      eprint={2312.08914},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

</code></pre><div class="zeroclipboard-container">
   
@misc{hong2023cogagent,
      title={CogAgent: A Visual Language Model for GUI Agents}, 
      author={Wenyi Hong and Weihan Wang and Qingsong Lv and Jiazheng Xu and Wenmeng Yu and Junhui Ji and Yan Wang and Zihan Wang and Yuxiao Dong and Ming Ding and Jie Tang},
      year={2023},
      eprint={2312.08914},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在CogVLM的指令微调阶段，有一些来自</font></font><a href="https://github.com/Vision-CAIR/MiniGPT-4"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MiniGPT-4</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/haotian-liu/LLaVA"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLAVA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/FuxiaoLiu/LRV-Instruction"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LRV-Instruction</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/SALT-NLP/LLaVAR"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaVAR</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
和</font></font><a href="https://github.com/shikras/shikra"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Shikra</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目的英文图文数据，以及许多经典的跨模态工作数据集。我们衷心感谢他们的贡献。</font></font></p>
</article></div>
