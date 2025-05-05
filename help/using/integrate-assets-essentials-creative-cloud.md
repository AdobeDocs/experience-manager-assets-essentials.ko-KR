---
title: Assets Essentials를 Creative Cloud 애플리케이션과 통합
description: Assets Essentials를 Creative Cloud 애플리케이션과 통합하여 Adobe Asset 링크 인앱 패널을 사용하여 지원되는 [!DNL Adobe Creative Cloud] 데스크탑 애플리케이션 내에서 [!DNL Assets Essentials] 저장소에 연결할 수 있습니다.
exl-id: 611fd958-3fd3-4c46-bee9-8b866b7dc208
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: tm+mt
source-wordcount: '812'
ht-degree: 100%

---

# Assets Essentials를 Creative Cloud 애플리케이션과 통합 {#integrate-assets-essentials-creative-cloud-applications}

![어두운 테마 및 밝은 테마 전환 환경 설정](assets/cce-creative-cloud.png)

## 지금까지의 스토리

이 튜토리얼에서 [Experience Manager Assets Essentials를 구성](adminster-aem-assets-essentials.md)한 후에는 Creative Cloud 애플리케이션을 Assets Essentials와 통합하기 위한 경험을 빌드할 수 있습니다.

## 목표

* **대상자**: Creative Cloud 관리자

* **목표**: Assets Essentials를 Creative Cloud 애플리케이션과 통합하여 크리에이티브 사용자가 Adobe Asset 링크 인앱 패널을 사용하여 지원되는 [!DNL Adobe Creative Cloud] 데스크탑 애플리케이션 내에서 [!DNL Assets Essentials] 저장소에 연결할 수 있도록 합니다.

## 개요

[Adobe Asset Link 인앱 패널](https://www.adobe.com/kr/creativecloud/business/enterprise/adobe-asset-link.html)을 통해 크리에이티브 전문가는 지원되는 [!DNL Adobe Creative Cloud] 데스크탑 앱 내에서 [!DNL Assets Essentials] 저장소에 연결할 수 있습니다. 패널은 [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] 및 [!DNL Adobe XD]에 사용할 수 있습니다. 에셋에 대한 액세스 단계를 간소화하여 콘텐츠 속도를 높일 수 있습니다.

Creative Cloud 애플리케이션 사용자는 Creative Cloud 애플리케이션을 Experience Manager Assets Essentials 저장소와 통합하는 경우에만 Adobe Asset Link 인앱 패널을 사용할 수 있습니다.

Assets Essentials를 Creative Cloud 애플리케이션과 통합하려면 다음 작업을 실행하십시오.

* [Creative Cloud와 Experience Cloud Admin Console 간에 디렉터리 위임 생성](#directory-trusting-cc-assets-essentials-consoles)

* [Assets Essentials 제품 프로필에 Creative Cloud 사용자 추가](#add-cc-users-assets-essentials-product-profiles)

* [Adobe Asset Link 설치](#install-asset-link)

* [Adobe Asset Link 사용](#use-asset-link)

## Creative Cloud와 Experience Cloud Admin Console 간에 디렉터리 위임 생성 {#directory-trusting-cc-assets-essentials-consoles}

Assets Essentials(Experience Cloud 솔루션)가 있는 것과 별도의 Adobe Admin Console에 Creative Cloud가 배포된 경우 두 콘솔 간에 트러스트 관계를 추가해야 합니다.

Creative Cloud와 Assets Essentials 애플리케이션을 통합하려면 Creative Cloud용 Admin Console에서 사용 가능한 사용자를 Experience Cloud용 Admin Console에서 사용 가능하도록 해야 합니다. Creative Cloud 및 Assets Essentials가 별도의 Admin Console에 배포된 경우 이를 활성화하려면 이들 간에 트러스트 관계가 필요합니다.

Experience Cloud Admin Console에서 **[!UICONTROL 설정]**&#x200B;을 클릭하고 **[!UICONTROL 디렉터리]** 탭을 사용하여 디렉터리를 만들어 두 Admin Console 간에 [디렉터리 위임](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html#directory-trusting)을 설정합니다.

## Assets Essentials 제품 프로필에 Creative Cloud 사용자 추가 {#add-cc-users-assets-essentials-product-profiles}

Creative Cloud용 Admin Console과 Experience Cloud용 Admin Console 간에 디렉터리 위임을 설정한 후 Creative Cloud 사용자를 Experience Cloud Admin Console의 [!DNL Assets Essentials] 제품 카드 아래에 있는 **[!DNL Assets Essentials]사용자** 제품 프로필에 할당합니다. 이를 통해 Creative Cloud 사용자는 Adobe Asset Link 플러그인 패널에서 Assets Essentials에 액세스할 수 있습니다. 또한 전체 Assets Essentials 웹 사용자 인터페이스에 액세스하여 웹 브라우저를 사용하여 디지털 에셋을 업로드하고, 구성하고, 태그를 지정하고, 찾을 수 있습니다.

다른 Assets Essentials 제품 프로필(**[!DNL Assets Essentials]관리자** 및 **[!DNL Assets Essentials]소비자 사용자**)은 다양한 사용자 권한(애플리케이션 관리자 및 Experience Cloud 통합을 통해 Assets Essentials에 액세스하는 사용자)에 대해 사용됩니다.

Assets Essentials 제품 프로필에 사용자를 할당하는 방법에 대한 자세한 내용은 [Assets Essentials 제품 프로필에 사용자 할당](adminster-aem-assets-essentials.md#add-users-to-product-profiles)을 참조하십시오.

## Adobe Asset Link 설치 {#install-asset-link}

[!DNL Adobe Asset Link] 플러그인은 다음 두 가지 방법으로 설치하고 크리에이티브 사용자에게 제공할 수 있습니다.

* 크리에이티브 사용자는 [!DNL Creative Cloud Desktop] 애플리케이션에서 플러그인을 설치할 수 있습니다.
* Creative Cloud 관리자는 Admin Console에서 Creative Cloud 패키지에 Asset Link 플러그인을 추가할 수 있습니다.

선택은 조직의 IT 정책에 따라 다릅니다.

[여기](https://helpx.adobe.com/kr/creative-cloud/kb/installingextensionsandaddons.html)에서는 **[!DNL Creative Cloud Desktop] 애플리케이션을 사용한 설치**&#x200B;에 대해 설명합니다. Creative Cloud 애플리케이션에 따라 [Adobe Exchange](https://exchange.adobe.com/) 마켓플레이스에서 사용 가능한 두 가지 플러그인이 있습니다.

* [!DNL Adobe Photoshop], [!DNL Adobe Illustrator] 및 [!DNL Adobe InDesign]의 경우: [Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* [!DNL Adobe XD]의 경우: [Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Creative Cloud 패키지를 사용한 설치**&#x200B;는 나중에 사용자 컴퓨터에 배포할 수 있는 배포 패키지를 빌드할 때 Asset Link 플러그인을 포함하여 Admin Console의 Creative Cloud 관리자가 수행합니다. 관리 플러그인 선택 화면의 **추천 비즈니스 플러그인** 섹션에서 **Adobe Asset Link**&#x200B;를 검색합니다. 자세한 내용은 [Admin Console을 통해 앱 패키징](https://helpx.adobe.com/kr/enterprise/using/package-apps-admin-console.html)을 참조하십시오.

## Adobe Asset Link 사용 {#use-asset-link}

크리에이티브 사용자는 이제 Photoshop, Illustrator, InDesign 또는 XD에서 Adobe Asset Link를 사용할 수 있습니다. InDesign 또는 Illustrator에서 패널을 열려면 Windows > 확장 기능 > Adobe Asset Link로 이동합니다. Photoshop에서는 창 > 확장 기능 (레거시) > Adobe Asset Link로 이동합니다.

Adobe XD용 Adobe Asset Link 설정 방법에 대한 자세한 내용을 확인하려면 [여기](https://helpx.adobe.com/kr/enterprise/using/adobe-asset-link-for-xd.html)를 클릭하십시오.

>[!NOTE]
>
>Apple Silicon/M1 하드웨어에서 작업할 때 Adobe Photoshop은 CEP 확장 기술을 사용하여 빌드되었기 때문에 크리에이티브 사용자가 Adobe Asset Link 패널에 액세스할 수 있도록 Rosetta 호환 모드를 사용하여 시작해야 합니다. 자세한 내용은 [Apple Silicon용 Photoshop](https://helpx.adobe.com/kr/photoshop/kb/photoshop-for-apple-silicon.html)을 참조하십시오.


Adobe Asset Link를 통해 Assets Essentials 저장소에 저장된 에셋을 사용하여 작업하고 수정합니다. 다음과 같은 다양한 작업을 수행할 수 있습니다.

* 에셋 검색 및 찾아보기

* 에셋 업로드

* 에셋 정렬 및 필터링

* 에셋 배치, 다운로드 및 드래그

* 에셋 체크아웃 및 체크인

* 버전 내역 및 파일 세부 정보 보기

이러한 작업을 수행하는 방법에 대한 지침은 [Adobe Asset Link를 사용하여 에셋 관리](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html)를 참조하십시오.

## 다음 단계

이제 Creative Cloud 애플리케이션과 Assets Essentials의 통합을 완료했으므로 [Adobe Workfront를 Experience Manager Assets Essentials와 통합](integrate-assets-essentials-workfront.md)해 보십시오.
