---
title: Creative Cloud 애플리케이션과 Assets Essentials 통합
description: Creative Cloud 응용 프로그램과 Assets Essentials을 통합하면 Adobe 자산 링크 인앱 패널을 사용하여 연결할 수 있습니다 [!DNL Assets Essentials] 지원되는 저장소 [!DNL Adobe Creative Cloud] 데스크탑 응용 프로그램.
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '854'
ht-degree: 6%

---


# Creative Cloud 애플리케이션과 Assets Essentials 통합 {#integrate-assets-essentials-creative-cloud-applications}

![어두운 테마 및 밝은 테마 전환 환경 설정](assets/cce-creative-cloud.png)

## 지금까지 그 이야기

후 [Experience Manager Assets Essentials 구성](adminster-aem-assets-essentials.md) 이 자습서에서는 경험을 기반으로 하여 Creative Cloud 애플리케이션을 Assets Essentials과 통합할 수 있습니다.

## 목표

* **Audience**: Creative Cloud 관리자

* **목표**: Assets Essentials을 Creative Cloud 애플리케이션과 통합하여 크리에이티브 사용자가 Adobe 자산 링크 인앱 패널을 사용하여 를 연결할 수 있도록 합니다 [!DNL Assets Essentials] 지원되는 저장소 [!DNL Adobe Creative Cloud] 데스크탑 응용 프로그램.

## 개요

[Adobe Asset Link 인앱 패널](https://www.adobe.com/kr/creativecloud/business/enterprise/adobe-asset-link.html)을 통해 크리에이티브 전문가는 지원되는 [!DNL Assets Essentials] 데스크탑 앱 내에서 [!DNL Adobe Creative Cloud] 저장소에 연결할 수 있습니다. 패널은 [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] 및 [!DNL Adobe XD]에 사용할 수 있습니다. 자산에 대한 액세스를 간소화하므로 컨텐츠 속도를 높이는 데 도움이 됩니다.

Creative Cloud 애플리케이션 사용자는 Creative Cloud 애플리케이션을 Experience Manager Assets Essentials 리포지토리와 통합하는 경우에만 Adobe 자산 링크 인앱 패널을 사용할 수 있습니다.

다음 작업을 실행하여 Assets Essentials을 Creative Cloud 애플리케이션과 통합합니다.

* [Creative Cloud과 Experience Cloud Admin Console 간 디렉터리 신뢰 만들기](#directory-trusting-cc-assets-essentials-consoles)

* [Assets Essentials 제품 프로필에 Creative Cloud 사용자 추가](#add-cc-users-assets-essentials-product-profiles)

* [Adobe 자산 링크 설치](#install-asset-link)

* [Adobe 자산 링크 사용](#use-asset-link)

## Creative Cloud과 Experience Cloud Admin Console 간 디렉터리 신뢰 만들기 {#directory-trusting-cc-assets-essentials-consoles}

Creative Cloud이 Assets Essentials(Experience Cloud 솔루션)가 있는 콘솔과 별도의 Adobe Admin Console에 배포된 경우 두 콘솔 간에 신뢰 관계를 추가해야 합니다.

Creative Cloud 및 Assets Essentials 애플리케이션을 통합하려면 Creative Cloud에 대한 Admin Console에서 사용할 수 있는 사용자를 Experience Cloud Admin Console에서 사용할 수 있어야 합니다. Creative Cloud과 Assets Essentials이 별도의 Admin Console에 배포되는 경우 이를 사용하려면 두 세그먼트 간의 신뢰 관계가 필요합니다.

Experience Cloud Admin Console에서 **[!UICONTROL 설정]** 그리고 **[!UICONTROL 디렉토리]** 탭하여 설정할 디렉토리를 만듭니다. [디렉터리 신뢰](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) 두 Admin Console 사이에 있을 수 있습니다.

## Assets Essentials 제품 프로필에 Creative Cloud 사용자 추가 {#add-cc-users-assets-essentials-product-profiles}

Creative Cloud에 대한 Admin Console과 Experience Cloud에 대한 Admin Console 간에 디렉터리 트러스트를 설정한 후에 Creative Cloud 사용자를 **[!DNL Assets Essentials]사용자** 아래의 제품 프로필 [!DNL Assets Essentials] Experience Cloud Admin Console의 제품 카드. 이를 통해 Creative Cloud 사용자가 Adobe Asset Link 플러그인 패널에서 Assets Essentials에 액세스할 수 있습니다. 또한 웹 브라우저를 사용하여 디지털 자산을 업로드, 구성, 태그 지정 및 찾을 수 있도록 전체 Assets Essentials 웹 사용자 인터페이스에 액세스할 수 있습니다.

기타 Assets Essentials 제품 프로필 - **[!DNL Assets Essentials]관리자** 및 **[!DNL Assets Essentials]소비자 사용자** - 다양한 사용자 권한에 사용됩니다(Experience Cloud 통합을 통해 Assets Essentials에 액세스하는 애플리케이션 관리자 및 사용자).

Assets Essentials 제품 프로필에 사용자를 할당하는 방법에 대한 자세한 내용은 [Assets Essentials 제품 프로필에 사용자 할당](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Adobe 자산 링크 설치 {#install-asset-link}

[!DNL Adobe Asset Link] 플러그인은 다음 두 가지 방법으로 크리에이티브 사용자가 설치하고 사용할 수 있도록 할 수 있습니다.

* 크리에이티브 사용자는 자신의 플러그인에서 플러그인을 설치할 수 있습니다 [!DNL Creative Cloud Desktop] 애플리케이션
* Creative Cloud 관리자는 Admin Console의 Creative Cloud 패키지에 자산 링크 플러그인을 추가할 수 있습니다

조직 IT 정책에 따라 선택할 수 있습니다.

**설치 방법 [!DNL Creative Cloud Desktop] 애플리케이션** 에 설명되어 있습니다. [여기](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html). 사용 가능하고 호스팅되는 두 개의 플러그인이 있습니다 [Adobe 교환](https://exchange.adobe.com/) marketplace를 Creative Cloud 애플리케이션에 따라 다음을 수행합니다.

* 대상 [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], 및 [!DNL Adobe InDesign]: [Adobe 자산 링크 CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* 대상 [!DNL Adobe XD]: [Adobe 자산 링크](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Creative Cloud 패키지로 설치** 배포 패키지를 작성할 때 Asset Link 플러그인을 포함하여 나중에 사용자 시스템에 배포할 수 있는 Admin Console의 Creative Cloud 관리자가 수행합니다. 관리되는 플러그인 선택 화면에서 **Adobe 자산 링크** 에서 **주요 비즈니스 플러그인** 섹션을 참조하십시오. 자세한 내용은 [Admin Console을 통해 앱 패키징](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html).

## Adobe 자산 링크 사용 {#use-asset-link}

이제 크리에이티브 사용자는 Photoshop, Illustrator, InDesign 또는 XD와 함께 Adobe 자산 링크를 사용할 수 있습니다. InDesign 또는 Illustrator에서 패널을 열려면 Windows > 확장 > Adobe 자산 링크로 이동합니다. Photoshop에서 창 > 확장(레거시) > Adobe 자산 링크로 이동합니다.

Adobe XD용 Adobe Asset Link 설정 방법에 대한 자세한 내용을 보려면 [여기](https://helpx.adobe.com/kr/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>Apple Silicon/M1 하드웨어에서 작업하는 경우, CEP 확장 기술을 사용하여 빌드되므로 크리에이티브 사용자가 Adobe 자산 링크 패널에 액세스할 수 있도록 하려면 Rosetta 호환성 모드를 사용하여 Adobe Photoshop을 시작해야 합니다. 자세한 내용은 [Apple용 Photoshop 실리콘](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html).


Adobe 자산 링크를 사용하여 Assets Essentials 저장소에 저장된 자산 작업을 수행하고 수정합니다. 다음과 같은 다양한 작업을 수행할 수 있습니다.

* 자산 검색 및 찾아보기

* 에셋 업로드

* 자산 정렬 및 필터링

* 자산 배치, 다운로드 및 드래그

* 자산 체크인 및 체크아웃

* 버전 기록 및 파일 세부 사항 보기

이러한 작업을 수행하는 방법에 대한 지침은 [Adobe 자산 링크를 사용하여 자산 관리](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## 다음은 무엇입니까?

이제 Creative Cloud 애플리케이션을 Assets Essentials과 통합했으므로, [Adobe Workfront과 Experience Manager Assets Essentials 통합](integrate-assets-essentials-workfront.md).
