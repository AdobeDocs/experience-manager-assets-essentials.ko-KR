---
title: Work Management 솔루션을 사용하여 Creative Cloud Pro용 Assets Essentials 설정
description: '이 자습서에서는 Assets Essentials 응용 프로그램을 Creative Cloud 데스크탑 응용 프로그램 및 Adobe Workfront 응용 프로그램과 통합할 수 있도록 해주는 관리자 여정을 소개합니다. Creative Cloud 데스크탑 응용 프로그램에는 Adobe Photoshop, Adobe Illustrator, Adobe InDesign 및 Adobe XD이 포함됩니다. '
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '900'
ht-degree: 12%

---


# 작업 관리 솔루션을 사용하는 Creative Cloud Pro용 Assets Essentials {#creative-cloud-enterprise-user-journeys}

![어두운 테마 및 밝은 테마 전환 환경 설정](assets/cce-next-banner-landing-page.png)

## 소개 {#introduction}

작업 관리 솔루션과 함께 사용되는 Creative Cloud Pro for enterprise는 크리에이티브, 컨텐츠 및 작업 관리 도구를 통합하여 크리에이티브 컨텐츠를 제작하고 신속하게 비즈니스 목표를 달성할 수 있도록 합니다. 솔루션은 다음과 같은 구성 요소를 포함합니다.

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

이 자습서에서는 Assets Essentials 응용 프로그램을 Creative Cloud 데스크탑 응용 프로그램 및 Adobe Workfront 응용 프로그램과 통합할 수 있도록 해주는 관리자 여정을 소개합니다. Creative Cloud 데스크탑 응용 프로그램에는 Adobe Photoshop, Adobe Illustrator, Adobe InDesign 및 Adobe XD이 포함됩니다.

## 배포 유형 {#deployment-types}

솔루션은 Creative Cloud과 Adobe Experience Cloud의 애플리케이션 및 서비스로 구성되므로 회사의 하나 또는 두 개의 Adobe Admin Console에 배포될 수 있습니다.

두 Admin Console으로 배포하는 경우 추가 구성 단계가 필요합니다.

* Creative Cloud 서비스 및 애플리케이션(enterprise Pro 및 선택적 모듈용 Creative Cloud)은 [Creative Cloud 배포를 위한 Adobe Admin Console](https://chl-author-preview.corp.adobe.com/content/help/en/enterprise/admin-guide.html).

* Adobe Workfront 및 Adobe Experience Manager Assets Essentials은 [Experience Cloud 솔루션용 Adobe Admin Console](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html).

Creative Cloud 및 Assets Essentials 애플리케이션을 통합하려면 Creative Cloud에 대한 Admin Console에서 사용할 수 있는 사용자를 Experience Cloud Admin Console에서 사용할 수 있어야 합니다. Experience Cloud Admin Console에서 사용자를 사용할 수 있도록 하려면 설정할 디렉토리를 만드십시오 [디렉터리 신뢰](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) 두 관리자 콘솔 간에 가능합니다.

![Creative Cloud 사용자](assets/creative-cloud-users.svg)

다이어그램에 표시된 대로 Creative Cloud 사용자는 두 콘솔 간의 신뢰 관계를 기반으로 Experience Cloud Admin Console에서 자동으로 사용할 수 있게 됩니다. 그런 다음 사용자를 Assets Essentials 제품 프로필에 추가할 수 있습니다. 그 결과, Creative Cloud 사용자는 Assets Essentials 리포지토리와 상호 작용할 수 있는 Adobe Asset Link 애플리케이션에 액세스할 수 있습니다. 자세한 내용은 [Creative Cloud 애플리케이션과 Assets Essentials 통합](integrate-assets-essentials-creative-cloud.md).

## Experience Manager 설명서 여정 {#documentation-journeys}

설명서 여정은 최소한의 이전 주제나 Assets Essentials 지식을 가정하는 동시에, Assets Essentials을 처음 접하는 독자가 처음부터 끝까지 비즈니스 문제를 이해하고 해결하는 데 도움이 되는 스토리를 제공함으로써, 여러 가지 다양한 주제 및 아마도 복잡한 주제를 함께 결합합니다.

설명서 여정은 Adobe의 최신 연구, Adobe 컨설턴트의 입증된 구현 경험, 고객 프로젝트의 피드백을 통해 우수 사례 원칙을 중심으로 설계되었습니다.

## 전제 조건

* [Experience Cloud 솔루션용 Adobe Admin Console 액세스](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html)

* [엔터프라이즈 배포를 위한 Adobe Admin Console Creative Cloud 액세스](https://helpx.adobe.com/enterprise/admin-guide.html)

## Experience Manager Assets Essentials 관리 {#administer-assets-essentials}

![어두운 테마 및 밝은 테마 전환 환경 설정](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials은 Adobe Experience Manager Assets의 가볍고 새로운 에디션입니다. Assets Essentials은 간소화된 일관된 사용자 인터페이스를 통해 통합된 자산 관리 및 공동 작업을 제공합니다. 사용 편의성을 통해 보다 창의적인 작업을 수행할 수 있으며 마케팅 팀에서 디지털 에셋을 저장하고, 검색하고, 배포할 수 있습니다.

Adobe Experience Manager Assets Essentials은 Adobe에서 고객에게 제공됩니다. 프로비저닝의 일부로서, Assets Essentials은 Adobe Admin Console에서 고객의 조직에 추가됩니다.

관리자는 Admin Console을 사용하여 Assets Essentials 제품에 대한 사용자 권한을 관리합니다.

* 사용자 그룹 추가

* 사용자 그룹에 사용자 추가

* Assets Essentials 제품 프로필에 사용자 추가

Admin Console에서 사용자 권한을 관리하고 나면 관리자는 Assets Essentials 응용 프로그램을 사용하여 다음을 수행할 수 있습니다.

* 조직의 요구 사항에 가장 적합한 폴더 구조 만들기

* 폴더 구조에 대한 권한 관리

* 메타데이터 양식 설정

[![안내서 참조](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](adminster-aem-assets-essentials.md)

## Experience Manager Assets Essentials와 Creative Cloud 애플리케이션 통합 {#administer-creative-cloud-applications}

![어두운 테마 및 밝은 테마 전환 환경 설정](assets/cce-creative-cloud.png)

[Adobe Asset Link 인앱 패널](https://www.adobe.com/kr/creativecloud/business/enterprise/adobe-asset-link.html)을 통해 크리에이티브 전문가는 지원되는 [!DNL Assets Essentials] 데스크탑 앱 내에서 [!DNL Adobe Creative Cloud] 저장소에 연결할 수 있습니다. 패널은 [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] 및 [!DNL Adobe XD]에 사용할 수 있습니다. 에셋에 대한 액세스 단계를 간소화하여 콘텐츠 속도를 높입니다.

이 자습서에서는 다음을 통합할 수 있습니다 [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign], 및 [!DNL Adobe XD] Experience Manager Assets Essentials를 사용하는 애플리케이션.

목표:

* Creative Cloud과 Experience Cloud Admin Console 간 디렉터리 신뢰 만들기

* Assets Essentials 제품 프로필에 Creative Cloud 사용자 추가

* Adobe 자산 링크 설치

* Adobe 자산 링크 사용

[![안내서 참조](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-creative-cloud.md)

## Adobe Workfront과 Experience Manager Assets Essentials 통합 {#administer-adobe-workfront}

![어두운 테마 및 밝은 테마 전환 환경 설정](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) 은 한 곳에서 전체 작업 수명 주기를 관리하는 데 도움이 되는 작업 관리 애플리케이션입니다. 간의 기본 통합 [!DNL Adobe Workfront] 및 [!DNL Assets Essentials] 을 사용하면 작업 및 자산 관리를 동적으로 연결하여 컨텐츠 제작 속도 및 시간을 향상시킬 수 있습니다. 작업 관리의 맥락에서 사용자는 동일한 솔루션에서 필요한 문서와 이미지에 액세스할 수 있습니다.

이 자습서에서는 Adobe Workfront을 관리하고 Experience Manager Assets Essentials와 통합할 수 있습니다.

목표:

* Workfront 제품 프로필에 사용자 추가

* Assets Essentials 제품 프로필에 사용자 추가

* Experience Manager Assets Essentials 통합 구성

[![안내서 참조](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-workfront.md)


