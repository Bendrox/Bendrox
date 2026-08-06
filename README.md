<h1 align="center">Hi 👋, I'm Ouss, an  AI Engineer & Data Scientist - LLMs,RAG , Agents, MCP, Pytorch, JAX, LLM inference engineering </h1>

<h3 align="center">Languages and Tools:</h3>
<p align="center"> 
  <a href="https://www.python.org/" target="_blank" rel="noreferrer"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> 
  </a> 
   <a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> 
    <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40"/> 
</a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> 
  </a> 
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> 
    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> 
  </a> 
  <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> 
  </a> 
  <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> 
    <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> 
  </a> 
  <a href="https://jax.readthedocs.io/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/google/jax/main/images/jax_logo_250px.png" alt="jax" width="55" height="40"/> 
  </a> 
  <a href="https://huggingface.co/" target="_blank" rel="noreferrer"> 
    <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="huggingface" width="40" height="40"/> 
  </a> 
  <a href="https://www.langchain.com/" target="_blank" rel="noreferrer"> 
    <img src="https://avatars.githubusercontent.com/u/126733545?s=200&v=4" alt="langchain" width="40" height="40"/> 
  </a> 
  <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> 
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> 
  </a> 
  <a href="https://www.databricks.com/" target="_blank" rel="noreferrer"> 
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/63/Databricks_Logo.png" alt="databricks" width="40" height="40"/> 
  </a> 
  <a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="fastapi" width="40" height="40"/> 
  </a> 
</p>

<p align="center"><sub>🔒 = dépôt privé · accès sur demande / private repository · access on request</sub></p>

<br>

<div align="justify">
<h3>Projets perso :</h3>

<h4> LLM Inference</h4>
<ul>
  <li><b><a href="https://github.com/Bendrox/GPU_sizer_for_llm_inference" target="_blank">GPU Memory Sizer for LLM Inference</a></b> (+ <a href="https://huggingface.co/spaces/eldiablo92/GPU_memory_sizer_for_LLM_inference" target="_blank">Space Hugging Face</a>) : API qui estime la VRAM nécessaire au serving d'un LLM (KV cache, poids, plus long contexte tenant sur une carte) à partir de la seule architecture d'attention, détaillée en FP32 / BF16 / FP8 avec un graphe contexte-vs-mémoire.</li>
  <li><b><a href="https://github.com/Bendrox/study_kvcache_impact_bench" target="_blank">KV Cache Impact Benchmark</a></b> : étude et benchmark du KV caching dans les Transformers décodeur (génération naïve vs avec cache, gains vitesse/mémoire jusqu'à ×8, comportement GPU, distinction prefill / decode).</li>
</ul>

<h4> Entraînement de modèles (from scratch) & Fine-tuning</h4>
<ul>
  <li><b><a href="https://github.com/Bendrox/slm_from_scratch_jax" target="_blank">SLM from Scratch — JAX</a> 🔒</b> : entraînement d'un mini GPT-2 <i>from scratch</i> en JAX/XLA (Flax NNX, Optax, Grain, Orbax), architecture propre et modulaire, premiers entraînements et tests d'inférence réalisés.</li>
  <li><b><a href="https://github.com/Bendrox/Gpt2_from_scratch" target="_blank">GPT-2 from Scratch — JAX</a> 🔒</b> : entraînement expérimental d'un LLM léger à partir de zéro avec JAX (grad/jit/vmap, model & data sharding) orienté performance GPU.</li>
</ul>

<h4> IA Agentique</h4>
<ul>
  <li><b><a href="https://github.com/Bendrox/MCP_chatbot" target="_blank">MCP Chatbot</a></b> : assistants multi-outils et multi-niveaux (LvL3→5) orchestrant GPT-5 (OpenAI) et Claude (Anthropic) via le Model Context Protocol, avec serveurs MCP locaux et distants (filesystem, fetch, Git, recherche arXiv, serveur LégiFrance maison) pour la recherche et la synthèse de contenus académiques et juridiques.</li>
  <li><b><a href="https://github.com/Bendrox/azure_ai_agents" target="_blank">Azure AI Agents</a> 🔒</b> : construction, évaluation et déploiement d'agents et systèmes multi-agents sur Azure AI Foundry + Microsoft Agent Framework, avec orchestration serverless (Functions, Queue & Blob Storage).</li>
  <li><b><a href="https://github.com/Bendrox/x_with_langgraph" target="_blank">Agents avec LangGraph</a> 🔒</b> : workflows d'agents orientés graphe construits avec LangGraph.</li>
  <li><b><a href="https://github.com/Bendrox/projet_x_langsmith" target="_blank">Expérimentations LangSmith</a> 🔒</b> : tracing, évaluation et observabilité de pipelines LLM/agents avec LangSmith.</li>
</ul>

<h4> IA Générative</h4>
<ul>
  <li><b><a href="https://github.com/Bendrox/ConformIA" target="_blank">ConformIA</a> 🔒</b> : solution métier de suivi des évolutions réglementaires — récupération automatique des mises à jour législatives, diff avant/après des articles, analyse LLM ligne par ligne et résumés référencés.</li>
  <li><b><a href="https://github.com/Bendrox/Legal-French-Tracker" target="_blank">Legal French Tracker</a> 🔒</b> : suit et résume les évolutions des textes législatifs français pour faire gagner du temps aux juristes.</li>
  <li><b><a href="https://github.com/Bendrox/LLM_Azure_Whisper_For_Supervision" target="_blank">LLM Azure Whisper</a> 🔒</b> : transforme les vidéos de résultats annuels des assureurs en fiches d'analyse préformatées, en chaînant Azure Whisper (speech-to-text) et un LLM (GPT-4).</li>
  <li><b><a href="https://github.com/Bendrox/gen-fiches-synthese" target="_blank">gen-fiches-synthese</a></b> : génère des fiches d'analyse structurées (résultat, provisions, solvabilité, gouvernance, perspectives) à partir de rapports SFCR de 30 à 80 pages, avec des modèles OpenAI, LangChain et Azure.</li>
  <li><b><a href="https://github.com/Bendrox/Advanced_RAG" target="_blank">Advanced RAG</a> 🔒</b> : techniques avancées de Retrieval-Augmented Generation (réécriture de requêtes, reranking, RAG auto-réflexif et correctif, RAG-fusion) + benchmark/fine-tuning de modèles d'embedding open source évalués sur MTEB.</li>
  <li><b><a href="https://github.com/Bendrox/voice_cloner" target="_blank">Voice Cloner</a> 🔒</b> : clonage de voix zero-shot 100% open-source (moteurs XTTS-v2 et Chatterbox), interface Streamlit, détection CUDA automatique, packagé avec uv.</li>
  <li><b><a href="https://github.com/Bendrox/Open-Source_models_with_HuggingFace" target="_blank">Open-Source Models with Hugging Face</a></b> : déploiement de modèles open source en NLP (génération, embeddings, résumé), vision (Image2Text, RAG image) et audio (TTS, STT).</li>
</ul>

<h4> Autres — Data Science & Analyse</h4>
<ul>
  <li><b><a href="https://github.com/Bendrox/DS_Valeo_challenge" target="_blank">DS Valeo Challenge</a></b> : XGBoost sur un problème de classification déséquilibré (détection de pièces endommagées) — 7 méthodes de recherche d'hyperparamètres, 3 stratégies d'imputation et du feature engineering.</li>
  <li><b><a href="https://github.com/Bendrox/DS_Vin_portugais" target="_blank">DS Vin Portugais</a></b> : modélisation de la qualité de vins portugais à partir de 11 variables physico-chimiques.</li>
  <li><b><a href="https://github.com/Bendrox/DA_etude_bonvivre" target="_blank">DA Étude Bonvivre</a></b> : construction d'un dataset pour étudier 119 pays selon des critères de "bon vivre" et les regrouper en catégories.</li>
</ul>
</div>

---

<div align="justify">
<h3>My Personal Projects :</h3>

<h4> LLM Inference</h4>
<ul>
  <li><b><a href="https://github.com/Bendrox/GPU_sizer_for_llm_inference" target="_blank">GPU Memory Sizer for LLM Inference</a></b> (+ <a href="https://huggingface.co/spaces/eldiablo92/GPU_memory_sizer_for_LLM_inference" target="_blank">Hugging Face Space</a>): an API that estimates the VRAM an LLM needs for serving (KV cache, model weights, longest context that fits a given card) from the model's attention architecture alone, broken down across FP32 / BF16 / FP8 with a context-vs-memory chart.</li>
  <li><b><a href="https://github.com/Bendrox/study_kvcache_impact_bench" target="_blank">KV Cache Impact Benchmark</a></b>: a study and benchmark of KV caching in decoder Transformers (naïve recompute vs cached generation, speed/memory gains up to ×8, GPU behaviour, prefill vs decode).</li>
</ul>

<h4> Model Training (from scratch) & Fine-tuning</h4>
<ul>
  <li><b><a href="https://github.com/Bendrox/slm_from_scratch_jax" target="_blank">SLM from Scratch — JAX</a> 🔒</b>: training a mini GPT-2 <i>from scratch</i> in JAX/XLA (Flax NNX, Optax, Grain, Orbax) with a clean modular architecture; first training and inference runs done.</li>
  <li><b><a href="https://github.com/Bendrox/Gpt2_from_scratch" target="_blank">GPT-2 from Scratch — JAX</a> 🔒</b>: experimental light-LLM training from zero with JAX (grad/jit/vmap, model & data sharding) targeting GPU performance.</li>
</ul>

<h4> Agentic AI</h4>
<ul>
  <li><b><a href="https://github.com/Bendrox/MCP_chatbot" target="_blank">MCP Chatbot</a></b>: multi-tool, multi-level assistants (LvL3→5) orchestrating GPT-5 (OpenAI) and Claude (Anthropic) via the Model Context Protocol, with local and remote MCP servers (filesystem, fetch, Git, arXiv research, a homemade LégiFrance server) for academic and legal search and synthesis.</li>
  <li><b><a href="https://github.com/Bendrox/azure_ai_agents" target="_blank">Azure AI Agents</a> 🔒</b>: building, evaluating and deploying AI agents and multi-agent systems on Azure AI Foundry + Microsoft Agent Framework, with serverless orchestration (Functions, Queue & Blob Storage).</li>
  <li><b><a href="https://github.com/Bendrox/x_with_langgraph" target="_blank">Agents with LangGraph</a> 🔒</b>: graph-based agent workflows built with LangGraph.</li>
  <li><b><a href="https://github.com/Bendrox/projet_x_langsmith" target="_blank">LangSmith Experiments</a> 🔒</b>: tracing, evaluation and observability of LLM/agent pipelines with LangSmith.</li>
</ul>

<h4> Generative AI</h4>
<ul>
  <li><b><a href="https://github.com/Bendrox/ConformIA" target="_blank">ConformIA</a> 🔒</b>: a business solution for legal regulatory-change tracking — automatic retrieval of legislative updates, before/after diff of articles, line-by-line LLM analysis and referenced summaries.</li>
  <li><b><a href="https://github.com/Bendrox/Legal-French-Tracker" target="_blank">Legal French Tracker</a> 🔒</b>: tracks and summarizes changes in French legislative texts to save time for legal professionals.</li>
  <li><b><a href="https://github.com/Bendrox/LLM_Azure_Whisper_For_Supervision" target="_blank">LLM Azure Whisper</a> 🔒</b>: turns insurers' annual-results videos into preformatted analyst briefs by chaining Azure Whisper (speech-to-text) with an LLM (GPT-4).</li>
  <li><b><a href="https://github.com/Bendrox/gen-fiches-synthese" target="_blank">gen-fiches-synthese</a></b>: generates structured analyst briefs (results, provisions, solvency, governance, outlook) from 30–80 page SFCR reports with OpenAI models, LangChain and Azure.</li>
  <li><b><a href="https://github.com/Bendrox/Advanced_RAG" target="_blank">Advanced RAG</a> 🔒</b>: advanced Retrieval-Augmented Generation techniques (query rewriting, reranking, self-reflective and corrective RAG, RAG-fusion) plus open-source embedding benchmarking/fine-tuning evaluated on MTEB.</li>
  <li><b><a href="https://github.com/Bendrox/voice_cloner" target="_blank">Voice Cloner</a> 🔒</b>: 100% open-source zero-shot voice cloning (XTTS-v2 and Chatterbox engines), Streamlit UI, CUDA auto-detection, packaged with uv.</li>
  <li><b><a href="https://github.com/Bendrox/Open-Source_models_with_HuggingFace" target="_blank">Open-Source Models with Hugging Face</a></b>: deploying open-source models across NLP (generation, embeddings, summarization), vision (Image2Text, image RAG) and audio (TTS, STT).</li>
</ul>

<h4> Other — Data Science & Analytics</h4>
<ul>
  <li><b><a href="https://github.com/Bendrox/DS_Valeo_challenge" target="_blank">DS Valeo Challenge</a></b>: XGBoost on an imbalanced classification problem (damaged-part detection) — 7 hyperparameter-search methods, 3 imputation strategies and feature engineering.</li>
  <li><b><a href="https://github.com/Bendrox/DS_Vin_portugais" target="_blank">DS Vin Portugais</a></b>: modeling Portuguese wine quality from 11 physico-chemical variables.</li>
  <li><b><a href="https://github.com/Bendrox/DA_etude_bonvivre" target="_blank">DA Étude Bonvivre</a></b>: building a dataset to study 119 countries on "good living" criteria and clustering them into categories.</li>
</ul>
</div>
