---
title: Content Credentials 통합
description: AEM Assets에 통합되고 AEM Assets Essentials UI 내에 포함된 Content Credentials은 에셋의 생성 방법 및 생성 관련 사용자를 포함하여 에셋 기록에 컨텍스트를 제공할 수 있습니다. 디지털 콘텐츠의 영양 레이블처럼, Content Credentials은 투명성을 높이고 대상자와 신뢰를 구축하는 데 도움이 될 수 있습니다.
role: User
exl-id: 703f74a6-24d4-4181-8174-9ff4a90ee7aa
TQID: https://experienceleague.adobe.com/witCqgAh8EKfD-hdn8efjZ-M4sypX44KB2ELs3ECInI
product_v2: id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: ec4263d9-bf7c-44c7-b3f1-3e664861c8f2
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 474
ht-degree: 100%

---

# Content Credentials {#content-credentials}

브랜드에 대한 콘텐츠 투명성, AI 공개, 에셋 변조 방지가 그 어느 때보다 우려되고 있습니다. Adobe의 Content Authenticity Initiative(CAI)는 [Coalition for Content Provenance and Authenticity](https://c2pa.org/specifications/specifications/1.1/specs/C2PA_Specification.html#_trust_model)&#x200B;(C2PA) 기술 표준을 준수하는 도구를 빌드합니다. Content Credentials는 암호화되어 변조 방지 기능을 갖춘 새로운 유형의 메타데이터로, 뷰어들이 콘텐츠의 계보를 이해하고 브랜드 에셋의 무결성을 보장하는 데 도움이 될 수 있습니다. 여기에는 디지털 에셋의 기록에 대한 인사이트를 제공하는 다양한 출처의 데이터가 포함될 수 있습니다.

이 정보에는 다음 내용이 포함됩니다.

* **발급자 또는 서명자:** 인증서를 인증하거나 에셋에 서명하기 위해 디지털 서명을 발급한 엔티티 또는 회사에 대한 정보입니다.
* **발급 날짜:** Content Credential이 에셋에 적용된 날짜입니다.
* **크레딧 및 사용:** 이름, 소셜 미디어 핸들 또는 기타 ID 관련 정보를 포함한 에셋 생성자 관련 정보입니다.
* **프로세스:** 에셋에 대한 편집 또는 수정 사항의 기록입니다.
* **디바이스 세부 정보:** 에셋을 만들거나 편집하는 데 사용되는 앱 또는 장치 관련 정보입니다.
* **사용된 AI 도구:** 생성형 AI를 사용하여 에셋을 편집하거나 만든 경우 사용된 모델의 이름이 포함될 수 있습니다.
* **기타 관련 정보:** 에셋 내역에 대한 추가 컨텍스트를 제공하는 데 도움이 되도록 추가 데이터가 포함될 수 있습니다.

완전한 파악을 위해서 [확인](https://contentcredentials.org/verify)을 통해 에셋 내역에 보다 포괄적인 인사이트를 제공할 수 있습니다.

이제 Adobe Experience Manager Assets이 Content Credentials를 지원하므로 사용자가 AEM의 Assets Essentials UI 내에서 직접 Content Credentials를 볼 수 있습니다. 에셋 세부 정보를 보면 Content Credentials이 포함된 모든 이미지(예: 생성형 AI 서비스로 만든 이미지)가 전용 패널에 매니페스트 세부 정보를 표시합니다. 에셋이 다운로드, 게재 또는 공유되는 경우 자격 증명이 에셋과 함께 그대로 유지됩니다.

![에셋](/help/using/assets/content-credentials.png)

## Content Credentials 액세스 {#access-content-credentials}

1. Assets Essentials UI로 이동한 다음 왼쪽 창에서 **에셋**&#x200B;을 클릭합니다.
1. 폴더로 이동하여 원하는 에셋을 선택합니다.
1. **세부 정보**&#x200B;를 클릭하고 맨 오른쪽 창에서 `Cr pin`을 선택합니다. Content Credentials 탭에는 에셋에 대한 다음 정보가 표시됩니다.
   1. **생성된 이미지:** Content Credentials가 적용된 날짜 및 시간입니다.
   1. **콘텐츠 요약:** 에셋 생성 시 AI 사용 여부(부분 또는 전체) 또는 편집된 방법을 나타냅니다.
      ![콘텐츠 요약](/help/using/assets/content-credentials1.png)
   1. **프로세스:** 에셋을 생성하는 데 사용되는 애플리케이션, 디바이스 및 AI 도구(예: Adobe Firefly)와 이후에 변경한 내용을 자세히 설명합니다.
      ![프로세스](/help/using/assets/CR-Process.png)
   1. **이 Content Credentials 정보:** 발급자 이름과 발급 날짜 및 시간을 표시합니다.
      ![발급자](/help/using/assets/CR-issuer.png)
