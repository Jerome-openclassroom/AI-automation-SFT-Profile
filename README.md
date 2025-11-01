# 🚀 Jérôme Frasson – Portfolio IA & Automatisation
**Spécialiste en orchestration d’agents IA, fine-tuning de modèles, et automatisation de workflows pour des cas d’usage concrets (immobilier, recrutement, écologie, météo, analyse de sentiment).**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub](https://img.shields.io/badge/GitHub-40%2B%20repos-black)](https://github.com/Jerome-openclassroom)
[![Hugging Face](https://img.shields.io/badge/🤗-Hugging%20Face-blue)](https://huggingface.co/jeromex1)
[![n8n](https://img.shields.io/badge/n8n-Automation-green)](https://n8n.io)
[![Make](https://img.shields.io/badge/Make-Workflow%20Automation-orange)](https://www.make.com/)

---

## 🔍 Domaines d’Expertise
- **Orchestration d’agents IA** : Intégration de LLM (Mistral, GPT) dans des workflows automatisés (n8n, Make).
- **Fine-tuning de modèles** : Adaptation de Mistral-7B, GPT-3.5/4 pour des cas d’usage spécifiques (immobilier, recrutement, météo).
- **Automatisation no-code** : Workflows reproductibles avec n8n/Make, Google Sheets, Gmail.
- **Traitement d’images** : OCR (Mistral), classification CNN (feuilles chlorotiques).
- **Analyse de données** : Sentiment analysis, intégration de vector stores, calculs déterministes.

---

## 🛠️ Projets Phares

### 1. Automatisation & Agents IA
| Projet | Description | Technologies |
|--------|-------------|--------------|
| **[Mistral__IA_OCR_Summary](https://github.com/Jerome-openclassroom/Mistral__IA_OCR_Summary)** | Pipeline OCR + LLM pour transformer des notes manuscrites en résumés structurés et envoyés par email. | Mistral OCR, Mistral Small, n8n, Google Sheets |
| **[AI_Agent_OS](https://github.com/Jerome-openclassroom/AI_Agent_OS)** | Agent local interprétant des commandes en langage naturel pour exécuter des actions système (création de dossiers, écriture de fichiers). | OpenAI API, LangChain, Gradio |
| **[Weather-Agent-Workflows](https://github.com/Jerome-openclassroom/Weather-Agent-Workflows)** | Comparaison de deux workflows météo : AI Agent Node (approximatif) vs Assistant + Code Interpreter (déterministe). | n8n, OpenAI Assistant, Python |
| **[Agent_IA_Agronomie](https://github.com/Jerome-openclassroom/Multi-Agent-Workflow-Mistral-AI)** | Workflow multi-agents pour l’aide à la décision agronomique (irrigation raisonnée, bilans, alertes). | n8n, Mistral AI, Google Sheets, Gmail, Discord, Google Calendar |
| **[workflow_agents](https://github.com/Jerome-openclassroom/workflow_agents)** | Workflow multi-agents dynamique (prompts dynamiques) avec coordination GPT-5 / GPT-4o, logging scientifique et intégrations concrètes (météo, éphéméride, rayonnement solaire, Gmail, Discord). | n8n, GPT-5, GPT-4o, Google Sheets, Gmail, Discord, WeatherAPI, Open-Meteo |
| **[cyber_gouvernance_data](https://github.com/Jerome-openclassroom/cyber_governance_data)** | Workflow de cybersécurité et gouvernance des données avec vérification d’intégrité (SHA256), alertes automatiques, supervision HITL et rollback sécurisé. Intègre un RAG pour identifier les contacts, Gmail pour les alertes, et Google Sheets pour la référence des scripts. | n8n, GPT-5, Google Sheets, Gmail, RAG, Crypto, HITL |
| **[QueryWhisper](https://github.com/Jerome-openclassroom/QueryWhisper)** | Assistant NLP2SQL basé sur **Mistral IA (Mistral Large 2)** pour les bases de données d’entreprise. Les questions en langage naturel sont automatiquement converties en requêtes SQL et exécutées en temps réel sur une base MySQL. Inclut une procédure stockée, un trigger, une interface Gradio et des démonstrations animées. | Mistral IA (Large 2), MySQL, Gradio |



---

### 2. Fine-tuning & Modèles Spécialisés
| Projet | Description | Technologies |
|--------|-------------|--------------|
| **[Lyra-Mistral7B-Estate](https://github.com/Jerome-openclassroom/Lyra-Mistral7B-Estate)** | Fine-tuning LoRA de Mistral-7B pour l’estimation immobilière. Modèle publié sur Hugging Face. | Mistral-7B, QLoRA, Hugging Face |
| **[lyra_immo](https://github.com/Jerome-openclassroom/lyra_immo)** | Fine-tuning de GPT-3.5-turbo pour l’estimation immobilière, intégré dans un workflow Make. | OpenAI, Make, Google Docs |
| **[Lyra_Sentiment_Classifier-n8n-GPT-4-nano-](https://github.com/Jerome-openclassroom/Lyra_Sentiment_Classifier-n8n-GPT-4-nano-)** | Workflow d’analyse de sentiment avec GPT-4.1 nano, routage des résultats vers Google Sheets. | n8n, GPT-4.1 nano, Google Sheets |
| **[Mistral_7B_AirQuality_LoRA](https://github.com/Jerome-openclassroom/Mistral_7B_AirQuality_LoRA)** | Fine-tuning QLoRA 4 bits de Mistral-7B pour l’analyse conjointe de la qualité de l’air, de la météo et de la santé humaine. Modèle open-source français, publié sur Hugging Face. | Mistral-7B, QLoRA, Transformers, Pandas |

---

### 3. Automatisation de Workflows Professionnels
| Projet | Description | Technologies |
|--------|-------------|--------------|
| **[Lyra_Recruiter_Agent_Make](https://github.com/Jerome-openclassroom/Lyra_Recruiter_Agent_Make)** | Automatisation des réponses aux recruteurs via un assistant GPT-4o enrichi par un vector store. | Make, GPT-4o, Google Sheets/Docs |
| **[Lyra_Recruiter_Agent_n8n](https://github.com/Jerome-openclassroom/Lyra_Recruiter_Agent_n8n)** | Version n8n de l’agent recruteur, avec gestion de conversations multi-tours. | n8n, GPT-4o, Gmail |

---

### 4. Écologie & Traitement d’Images
| Projet | Description | Technologies |
|--------|-------------|--------------|
| **[Leaf_Chlorose_CNN_Training](https://github.com/Jerome-openclassroom/Leaf_Chlorose_CNN_Training)** | Classifieur CNN pour détecter la chlorose sur des feuilles de lierre, avec 100% de précision sur le jeu de validation. | TensorFlow/Keras, Jupyter |

---

## 📊 Synthèse des Technologies Utilisées
- **LLM & Fine-tuning** : Mistral-7B, GPT-3.5/4, QLoRA, Hugging Face.
- **Automatisation** : n8n, Make, Google Sheets/Docs, Gmail.
- **Traitement d’images** : OCR (Mistral), CNN (Keras).
- **Langages** : Python, JavaScript, XML.
- **Outils complémentaires** : Gradio, OpenAI API, Code Interpreter.

---

## 📂 Structure Typique des Dépôts
Chaque dépôt inclut :
- Un **README détaillé** (français/anglais).
- Des **screenshots** ou **démonstrations** (GIF, images).
- Des **fichiers de configuration** (JSON pour n8n/Make, scripts Python).
- Des **jeux de données** ou **exemples d’entrée/sortie**.

---

## 🔗 Liens Utiles
- [GitHub – Jérôme Frasson](https://github.com/Jerome-openclassroom)
- [Hugging Face – jeromex1](https://huggingface.co/jeromex1)
- [n8n.io](https://n8n.io)
- [Make.com](https://www.make.com/)

---

## 📄 License
Tous les projets sont sous **licence MIT**, sauf mention contraire.

## 👤 **À propos de l’auteur**
Ce projet est développé par **Jérôme FRASSON**, spécialiste en **fine-tuning de LLM et automatisation de workflows** pour l’agro-écologie et l’IA appliquée.
🔗 [LinkedIn](https://linkedin.com/in/jerôme-frasson-90426b397) | [Hugging Face](https://huggingface.co/jeromex1)


---
## 🔍 **Mots-Clés pour les IA/Recruteurs**
`LLM`, `GPT-4`, `Mistral-7B`, `fine-tuning`, `LoRA`, `QLoRA`, `agents autonomes`, `orchestration IA`, `LangChain`, `Make.com`, `n8n`, `workflow intelligent`, `OCR`, `CNN`, `analyse de sentiment`, `vector store`, `RAG`, `Gradio`, `automatisation`, `intégration API`, `IA appliquée`









