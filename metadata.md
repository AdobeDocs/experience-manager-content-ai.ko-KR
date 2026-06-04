---
cloud: Experience Cloud
solution: Experience Manager
product_v2:
  - id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
usetq: true
type: Documentation
git-repo: https://github.com/AdobeDocs/experience-manager-content-ai.en
index: true
recommendations: noDisplay
source-git-commit: a47559544a9e972285ba570f16a38272b35794a8
workflow-type: tm+mt
source-wordcount: 81
ht-degree: 2%

---


# 내부 사용을 위한 메타데이터

GitHub 제작 시스템의 메타데이터는 계층적이며 다음과 같이 증가하는 선례 수준으로 정의됩니다.

1. metadata.md
1. 종료 날짜
1. 문서

metadata.md 파일에 정의된 메타데이터는 전체 리포지토리에 적용되지만 ToC 및 문서 수준에서 재정의될 수 있습니다. 메타데이터 재정의는 가능한 한 낮은 수준에서 수행해야 합니다.

experience-manager-content-ai.en 리포지토리의 메타데이터는 필요한 최소값입니다.

metadata.md

* `product`
* `git-repo`
* `index`
* `solution-title`
* `solution-hub-url`
* `getting-started-title`
* `getting-started-url`
* `tutorials-title`
* `tutorials-url`

Tocs

* `sub-product`
* `user-guide-title`

기사

* `title`
* `description`
