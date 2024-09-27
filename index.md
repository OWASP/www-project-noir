---

layout: col-sidebar
title: OWASP Noir
tags: noir owasp-noir sast dast attack-surface endpoint
level: 2
type: code
pitch: An open-source project that identifies attack surfaces to enhance whitebox security testing and security pipelines.

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

Noir is an open-source project specializing in identifying attack surfaces for enhanced whitebox security testing and security pipeline. 
This includes the capability to discover API endpoints, web endpoints, and other potential entry points within source code for thorough security analysis and DAST. For more information, please visit our [documentation page](https://owasp-noir.github.io/noir/).

![](assets/images/preview.jpg)

## Key Features
- Identify API endpoints and parameters from source code.
- Support various source code languages and frameworks.
- Provide analysts with technical information and security issues identified during source code analysis.
- Friendly pipeline & DevOps integration, offering multiple output formats (JSON, YAML, OAS spec) and compatibility with tools like curl and httpie.
- Friendly Offensive Security Tools integration, allowing usage with tools such as ZAP and Caido, Burpsuite.
- Generate elegant and clear output results.

## Road Map
We plan to expand the range of supported programming languages and frameworks, and to increase accuracy. 
Initially conceived as a tool to assist with WhiteBox testing, our goal is to extract and provide endpoints from the source code within the DevSecOps Pipeline, enabling DAST to conduct more accurate and stable scans.

<style>
  .sub-nav{
    display: none !important;
  }
</style>
