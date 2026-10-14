<div align="center">

<img src="assets/banner.svg" width="100%" alt="Sofien Krir — Data Science & AI Engineer · Tunis, Tunisie">

<br>

`Machine Learning` · `Deep Learning` · `LLMs` · `RAG` · `Agents IA`

<br>

<a href="https://portfolio-data-science-ia-sof.vercel.app"><img src="https://img.shields.io/badge/Portfolio-6366F1?style=for-the-badge&amp;logo=vercel&amp;logoColor=white" alt="Portfolio"></a>
<a href="https://linkedin.com/in/sofien-krir-28b34b34b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn"></a>
<a href="mailto:sofienkrir11@gmail.com"><img src="https://img.shields.io/badge/Email-334155?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email"></a>

<br><br>

<img src="https://skillicons.dev/icons?i=python,r,java,ts,fastapi,tensorflow,sklearn,mongodb,postgres,mysql,docker,git,linux" alt="Stack technique">

<img src="assets/divider.svg" width="100%" alt="">

</div>

## &nbsp;&nbsp;À propos

> Ingénieur **Data Science & IA** diplômé de **TEK-UP University** (Tunis, 2026), avec une première
> formation en électronique et énergies renouvelables.

Je construis des systèmes **RAG** et des **agents LLM** de bout en bout — de la collecte et de
l'indexation des données jusqu'à l'API, l'interface et la mesure de la qualité des réponses.

Ce qui m'intéresse dans ces systèmes, c'est précisément la part que l'on peut mesurer : savoir
*ce qu'un système a réellement trouvé*, plutôt que lui faire produire une réponse à tout prix.
Les deux projets ci-dessous sont construits autour de cette idée, et chacun publie ses chiffres.

<table>
<tr>
<td>🎯</td><td><b>En ce moment</b> — je recherche un poste junior en <b>Data Science, IA ou Data Analytics</b>, à Tunis.</td>
</tr>
</table>

<div align="center">
<img src="assets/divider.svg" width="100%" alt="">
</div>

<div align="center">

# ⚡ Projets sélectionnés

<i>Deux systèmes complets, documentés et mesurés.</i>

</div>

<br>

### &nbsp;`01` &nbsp;Conseiller Clientèle Augmenté par l'IA &nbsp;<sub><sup>· Projet de fin d'études</sup></sub>

<div align="center">
  <a href="https://github.com/sofienkrir/Conseiller-Client-le-Augment-par-Intelligence-Artificielle_PFE">
    <img src="https://raw.githubusercontent.com/sofienkrir/Conseiller-Client-le-Augment-par-Intelligence-Artificielle_PFE/main/docs/screenshots/01-chat-french.png" width="100%" alt="Conseiller bancaire intelligent — interface de chat RAG">
  </a>
</div>

<br>

Plateforme bancaire conversationnelle fondée sur une architecture **RAG multi-sources**, réalisée au
**Digital Center d'Attijari Bank Tunisie**. Elle répond aux clients à partir de la seule documentation
produit de la banque, et outille les conseillers.

|  | |
| --- | --- |
| 🔍 **RAG ancré** | Recherche hybride dense + mots-clés sur un corpus produit indexé dans ChromaDB, segments *Particulier* / *Professionnel*, réponses citées — et un refus explicite quand l'information manque |
| 🇹🇳 **Derja** | Détection de l'arabe tunisien, puis reformulation en requête française avant la recherche sémantique, avec des embeddings multilingues affinés sur un corpus parallèle |
| 👤 **Copilote conseiller** | Fiches clients, notes de préparation de RDV générées par IA, partage de documents avec suivi de lecture |
| 🔐 **Sécurité** | JWT · 2FA par e-mail · authentification basée sur le risque (7 facteurs, score 0-100) · chiffrement Fernet des champs sensibles |
| 📊 **Qualité mesurée** | Score automatique par réponse, *LLM-as-a-judge* en tâche de fond, et métriques de récupération sur jeu annoté |

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&amp;logo=langchain&amp;logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square" alt="ChromaDB">
  <img src="https://img.shields.io/badge/Llama_3.3_70B-Groq-F55036?style=flat-square" alt="Llama 3.3 70B via Groq">
  <img src="https://img.shields.io/badge/Sentence--Transformers-FFBF00?style=flat-square" alt="Sentence-Transformers">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&amp;logo=mongodb&amp;logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&amp;logo=react&amp;logoColor=black" alt="React 19">
</p>

**Mesuré** &nbsp;
<img src="https://img.shields.io/badge/Recall@10-69.6%25-6366F1?style=flat-square" alt="Recall@10 69.6%">
<img src="https://img.shields.io/badge/MRR-0.449-8B5CF6?style=flat-square" alt="MRR 0.449">
<img src="https://img.shields.io/badge/questions_annot%C3%A9es-46-06B6D4?style=flat-square" alt="46 questions annotées">
<img src="https://img.shields.io/badge/tests_de_charge-Locust-3FB950?style=flat-square" alt="Tests de charge Locust">

<a href="https://github.com/sofienkrir/Conseiller-Client-le-Augment-par-Intelligence-Artificielle_PFE"><img src="https://img.shields.io/badge/Explorer_le_d%C3%A9p%C3%B4t-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="Explorer le dépôt"></a>

<sub>Prototype académique exécuté en local. Toutes les données client du dépôt sont <b>synthétiques</b>.</sub>

<br>

---

<br>

### &nbsp;`02` &nbsp;LangGraph AI Research Agent

<div align="center">
  <a href="https://github.com/sofienkrir/langgraph-ai-agent">
    <img src="https://raw.githubusercontent.com/sofienkrir/langgraph-ai-agent/main/assets/screenshots/report.png" width="100%" alt="LangGraph Research Agent — rapport cité">
  </a>
</div>

<br>

Agent de recherche qui décompose une question, cherche dans vos PDF et sur le web, puis rédige un
rapport cité — et **déclare ce qu'il n'a pas trouvé au lieu de l'inventer**.

La plupart des agents de recherche répondent à tout, parce que rien en eux ne distingue *trouver des
sources* de *trouver une réponse*. Celui-ci en est capable.

|  | |
| --- | --- |
| 🧩 **Décomposition** | Une question devient 2 à 6 sous-questions autonomes et cherchables |
| 🔀 **Récupération hybride** | Corpus PDF local (Chroma + fastembed, embeddings multilingues) et web (Tavily), fusionnés en une liste de citations numérotées |
| 📐 **Contrôle mesuré, non généré** | Un nœud en **Python pur** vérifie le nombre de sources pertinentes *et* la présence des termes distinctifs de la question. Aucun modèle n'évalue sa propre confiance |
| 🔁 **Second tour ciblé** | Seules les lacunes sont re-cherchées, plus en profondeur, dans une boucle bornée qui garantit la terminaison |
| ⚠️ **Limites assemblées en Python** | La section « limites » est construite à partir des lacunes mesurées — le modèle ne peut ni l'oublier ni l'adoucir |

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&amp;logo=streamlit&amp;logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Chroma_%2B_fastembed-5A4FCF?style=flat-square" alt="Chroma + fastembed">
  <img src="https://img.shields.io/badge/Tavily-0EA5E9?style=flat-square" alt="Tavily">
  <img src="https://img.shields.io/badge/Groq_%7C_Anthropic-F55036?style=flat-square" alt="Groq ou Anthropic">
</p>

**Mesuré** &nbsp;
<img src="https://img.shields.io/badge/tests-61_passing-3FB950?style=flat-square" alt="61 tests">
<img src="https://img.shields.io/badge/Recall@4-0.69-6366F1?style=flat-square" alt="Recall@4 0.69">
<img src="https://img.shields.io/badge/couverture-0.88-8B5CF6?style=flat-square" alt="Couverture 0.88">
<img src="https://img.shields.io/badge/citations_valides-1.00-06B6D4?style=flat-square" alt="Citations valides 1.00">

<a href="https://github.com/sofienkrir/langgraph-ai-agent"><img src="https://img.shields.io/badge/Explorer_le_d%C3%A9p%C3%B4t-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="Explorer le dépôt"></a>

<sub>Chaque chiffre provient d'une exécution du harnais d'évaluation, versionnée dans le dépôt — aucun n'est écrit à la main.</sub>

<div align="center">
<img src="assets/divider.svg" width="100%" alt="">
</div>

## &nbsp;&nbsp;Autres réalisations

<table>
<tr>
<td width="33%" align="center">
<b>🌐 Portfolio</b><br><br>
<sub>Expériences, projets, formation et CV — dont un dashboard <b>Power BI</b> de pilotage d'un réseau de <b>170 agences</b> (stage Data Analyst, Attijari Bank, été 2025).</sub><br><br>
<a href="https://portfolio-data-science-ia-sof.vercel.app"><img src="https://img.shields.io/badge/Voir_le_site-6366F1?style=flat-square&amp;logo=vercel&amp;logoColor=white" alt="Voir le site"></a>
<a href="https://github.com/sofienkrir/portfolio_Data_science_IA_-sofien-"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&amp;logo=github&amp;logoColor=white" alt="Code"></a>
</td>
<td width="33%" align="center">
<b>📈 bitcoin-price-analysis</b><br><br>
<sub>Séries temporelles sur le cours BTC-USD : ACF/PACF et STL, modèles <b>ARIMA</b> et <b>GARCH</b>, réseau <b>LSTM</b>, puis comparaison (RMSE, MAE, MAPE). En Python et en R.</sub><br><br>
<a href="https://github.com/sofienkrir/bitcoin-price-analysis"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&amp;logo=github&amp;logoColor=white" alt="Code"></a>
</td>
<td width="33%" align="center">
<b>📊 Data Analytics</b><br><br>
<sub>Scoring de risque bancaire, analyse de sentiment et extraction de factures par <b>OCR</b> — présentés sur le portfolio.</sub><br><br>
<a href="https://portfolio-data-science-ia-sof.vercel.app"><img src="https://img.shields.io/badge/Voir-6366F1?style=flat-square&amp;logo=vercel&amp;logoColor=white" alt="Voir"></a>
</td>
</tr>
</table>

<div align="center">
<img src="assets/divider.svg" width="100%" alt="">
</div>

## &nbsp;&nbsp;Compétences techniques

| Domaine | Outils |
| --- | --- |
| 🐍 **Langages** | Python · SQL · R · TypeScript / JavaScript · Java |
| 🤖 **IA générative & NLP** | LangChain · LangGraph · Hugging Face · Sentence-Transformers · RAG · embeddings |
| 📊 **Machine Learning & Deep Learning** | Pandas · NumPy · Scikit-learn · TensorFlow · séries temporelles (ARIMA, GARCH, LSTM) |
| 🗄️ **Bases de données & vecteurs** | MySQL · PostgreSQL · SQL Server · MongoDB · ChromaDB |
| 📈 **BI & visualisation** | Power BI (DAX, Power Query) · Matplotlib |
| ⚙️ **Backend & déploiement** | FastAPI · Streamlit · Docker · Git · n8n · Linux |

<div align="center">
<img src="assets/divider.svg" width="100%" alt="">
</div>

## &nbsp;&nbsp;Formation & certifications

| Diplôme | Établissement | Période |
| --- | --- | --- |
| 🎓 **Diplôme National d'Ingénieur**, spécialité *Data Science & Intelligence Artificielle* | Université TEK-UP, Tunis | 2023 – 2026 |
| 🎓 **Licence** en Électronique, Électrotechnique & Automatique, spécialité *Énergie Électrique Renouvelable* | ISSIG, Université de Gabès | 2020 – 2023 |

<img src="https://img.shields.io/badge/PCAP-Certified_Associate_in_Python_Programming-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="PCAP">
<img src="https://img.shields.io/badge/OCA-Oracle_Certified_Associate,_Java-F80000?style=flat-square&amp;logo=oracle&amp;logoColor=white" alt="OCA">

<br>

<div align="center">

<br>

### Parlons-en

<a href="https://portfolio-data-science-ia-sof.vercel.app"><img src="https://img.shields.io/badge/Portfolio-6366F1?style=for-the-badge&amp;logo=vercel&amp;logoColor=white" alt="Portfolio"></a>
<a href="https://linkedin.com/in/sofien-krir-28b34b34b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn"></a>
<a href="mailto:sofienkrir11@gmail.com"><img src="https://img.shields.io/badge/sofienkrir11%40gmail.com-334155?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email"></a>

<br><br>

<img src="assets/divider.svg" width="100%" alt="">

</div>
