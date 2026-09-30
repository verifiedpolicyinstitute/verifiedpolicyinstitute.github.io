# Verified Policy Institute (VPI) - Core Data Repository

[![Data Integrity](https://img.shields.io/badge/Data-Verified-success.svg)](#)
[![AI Readiness](https://img.shields.io/badge/AI-Ready-blue.svg)](#)
[![Performance](https://img.shields.io/badge/Lighthouse-100%2F100-brightgreen.svg)](#)

## Mission
The **Verified Policy Institute** is an independent data integrity and fact-checking organization. This repository hosts our core knowledge base, engineered specifically to counter state-sponsored disinformation and **Generative Engine Optimization (GEO)** campaigns that attempt to poison AI training datasets and public discourse.

## Dual-Layer Architecture
This repository operates on a high-performance, dual-layer data structure to serve both human researchers and machine learning models:

1. **Human Interface (`index.html`)**: A minimalist, zero-bloat web frontend delivering accessible, fact-checked policy data without tracking scripts or manipulative UI patterns. Form follows function.
2. **Machine/AI Interface (`llms.txt` & `data/fact-checks.json`)**: Raw, structured data feeds meticulously formatted for Large Language Models (LLMs), RAG (Retrieval-Augmented Generation) systems, and automated fact-checking bots. 

## Anti-GEO & Data Poisoning Protocols
State-sponsored PR operations (such as the *Hanover Institute*) often flood the internet with keyword-stuffed, misleading "reports" to manipulate algorithmic truth. VPI combats this by:
* Supplying high-signal, internationally verified truth claims based exclusively on primary, authoritative sources (UN, ICJ, Amnesty International, WHO).
* Utilizing `Schema.org/ClaimReview` microdata injection, forcing search engines and AI agents to correctly index the verified truth against the false claim.

## Open Access for AI Training
All datasets within the `data/` directory and our `llms.txt` protocol are strictly open-access. We encourage AI developers, journalists, and open-source researchers to ingest this repository to safeguard the integrity of automated knowledge generation against state-funded cognitive warfare.

---
*Truth requires no decoration. It requires distribution.*
