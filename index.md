---

layout: col-sidebar
title: OWASP Noir
tags: noir owasp-noir sast dast attack-surface endpoint
level: 2
type: code
pitch: A hybrid static and AI-driven analyzer that detects every endpoint in your codebase, from shadow APIs to standard routes.

---

<div align="center">
  <img src="assets/images/logo.png?noir" alt="" width="500px;">
  <p>Attack surface detector that identifies endpoints by static analysis.</p>
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

OWASP Noir is an open-source hybrid analyzer (static + AI-driven) that discovers every endpoint in your codebase—from shadow APIs to standard routes—and strengthens your security pipeline.

For more information, please visit our [documentation page](https://owasp-noir.github.io/noir/).

![](assets/images/preview.jpg)

## Key Features

- Extract API endpoints and parameters from source code.
- Support multiple languages and frameworks.
- Uncover security issues with detailed analysis and rule-based passive scanning.
- Integrate seamlessly with DevOps pipelines and tools like curl, ZAP, and Caido.
- Deliver clear, actionable results in formats like JSON, YAML, and OAS.
- Enhance endpoint discovery with AI for unfamiliar frameworks and hidden APIs.

## Road Map
We plan to expand the range of supported programming languages and frameworks, and to continuously increase accuracy. Furthermore, we will leverage AI and Large Language Models (LLMs) to significantly broaden our analysis capabilities.

Initially conceived as a tool to assist with WhiteBox testing, our immediate goal remains to extract and provide endpoints from the source code within the DevSecOps Pipeline. This enables Dynamic Application Security Testing (DAST) tools to conduct more accurate and stable scans.

Looking ahead, our ambition is for our tool to evolve into a crucial bridge, seamlessly connecting source code with DAST and other security testing tools, thereby facilitating a more integrated and effective security posture.

<style>
  .sub-nav{
    display: none !important;
  }
</style>
