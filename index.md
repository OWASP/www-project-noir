---

layout: col-sidebar
title: OWASP Noir
tags: noir owasp-noir sast dast ai-sast llm attack-surface endpoint shadow-api
level: 2
type: code
pitch: Hunt every Endpoint in your code, expose Shadow APIs, map the Attack Surface.

---

<div align="center">
  <img src="assets/images/logo.png?noir" alt="" width="500px;">
  <p>Hunt every Endpoint in your code, expose Shadow APIs, map the Attack Surface.</p>
</div>

<p align="center">
<a href="https://github.com/owasp-noir/noir/blob/main/CONTRIBUTING.md">
<img src="https://img.shields.io/badge/CONTRIBUTIONS-WELCOME-000000?style=for-the-badge&labelColor=black"></a>
<a href="https://github.com/owasp-noir/noir/releases">
<img src="https://img.shields.io/github/v/release/owasp-noir/noir?style=for-the-badge&color=black&labelColor=black&logo=web"></a>
<a href="https://crystal-lang.org">
<img src="https://img.shields.io/badge/Crystal-000000?style=for-the-badge&logo=crystal&logoColor=white"></a>
<a href="https://owasp.org/www-project-noir/">
<img src="https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white"></a>
</p>

<hr>

Noir reads source code and extracts every endpoint your application exposes, including shadow APIs, deprecated routes, and hidden surfaces.

That inventory drives two downstream stacks. ZAP, Burp Suite, and Caido pick up endpoints they would never have crawled on their own. AI SAST (LLM-based code auditors and security agents) gets the entrypoints, files, parameters, and tags it needs to review attacker-reachable code, instead of skimming the whole repository.

For more information, please visit our [documentation page](https://owasp-noir.github.io/noir/).

![](assets/images/preview.jpg)

## Key Features

- **Attack Surface Discovery**: Analyzes source code to identify your application's complete attack surface, including hidden endpoints, shadow APIs, and other security blind spots.
- **AI-Powered Analysis**: Leverages Large Language Models (LLMs) to detect endpoints in any language or framework, even those not natively supported.
- **Feeds DAST & AI SAST**: One endpoint inventory drives ZAP, Burp Suite, and Caido on the dynamic side, and points LLM-based SAST and code auditors at the entrypoints, files, and parameters worth reviewing on the static side.
- **DevSecOps Ready**: Designed for seamless integration into security pipelines with support for tools like ZAP, Burp Suite, Caido, and more.
- **Multi-Format Output**: Delivers results in JSON, YAML, TOML, OpenAPI Specification, SARIF, and other formats for easy integration with your existing workflow.

## Road Map
We plan to expand the range of supported programming languages and frameworks, and to continuously increase accuracy. Furthermore, we will leverage AI and Large Language Models (LLMs) to significantly broaden our analysis capabilities.

Initially conceived as a tool to assist with WhiteBox testing, our immediate goal remains to extract and provide endpoints from the source code within the DevSecOps Pipeline. This enables Dynamic Application Security Testing (DAST) tools to conduct more accurate and stable scans.

Looking ahead, our ambition is for Noir to become the canonical attack-surface layer for application security: the single inventory that DAST tools and AI SAST share, so every downstream consumer starts from the same view of what is actually exposed.

<style>
  .sub-nav{
    display: none !important;
  }
</style>
