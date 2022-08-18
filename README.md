# 持續整合<br>Continuous Integration(CI)

將所有工程師的軟體的工作內容持續整合到開發主線（mainline）的軟體工程方法，持續整合主要是為解決軟體進行系統整合時面臨的各項問題（如集成地獄（integration hell)）

![「檢查專案中的潛在問題」GitHub Actions 作業流程狀態標章](https://github.com/libre-knowledge/continuous-integration/actions/workflows/check-potential-problems.yml/badge.svg "本專案使用 GitHub Actions 自動化檢查專案中的潛在問題") [![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white "本專案使用 pre-commit 檢查專案中的潛在問題")](https://github.com/pre-commit/pre-commit) [![REUSE 規範遵從狀態標章](https://api.reuse.software/badge/github.com/libre-knowledge/continuous-integration "本專案遵從 REUSE 規範降低軟體授權合規成本")](https://api.reuse.software/info/github.com/libre-knowledge/continuous-integration)

## 基本概念

### 持續交付<br>Continuous Delivery(CD)

自動化部署到測試環境，部署到生產環境仍需要人工核准

### 持續部署<br>Continuous Deployment(CD)

自動化部署到測試環境與生產環境

## 解決方案

* Drone CI
* GitHub Actions
* GitLab CI
* Travis CI

## 參考資料

* [Continuous integration - Wikipedia](https://en.wikipedia.org/wiki/Continuous_integration)  
  [持續整合 - 維基百科，自由的百科全書](https://zh.wikipedia.org/zh-tw/持續整合)  
  維基百科的相關條目
* [什麼是持續整合？ – Amazon Web Services](https://aws.amazon.com/tw/devops/continuous-integration/)  
  說明持續整合的實務作法
* [什麼是持續交付？– Amazon Web Services](https://aws.amazon.com/tw/devops/continuous-delivery/)  
  說明持續交付的實務作法

---

本主題為[自由知識協作平台](https://libre-knowledge.github.io/)的一部分，除部份特別標註之經合理使用(fair use)原則使用的內容外允許公眾於授權範圍內自由使用

如有任何問題，歡迎於本主題的[議題追蹤系統](https://github.com/libre-knowledge/continuous-integration/issues)創建新議題反饋
