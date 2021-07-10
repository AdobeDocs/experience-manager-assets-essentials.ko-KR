---
title: 지원되는 파일 형식
description: 다양한 사용 사례에 대해 지원되는 파일 형식 [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: c63e9ab1054398dc055643f0dca6631bae881047
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 23%

---


# 파일 형식은 [!DNL Assets Essentials]에서 지원됩니다. {#file-format-support}

[!DNL Assets Essentials] 는 다양한 파일 형식을 지원하며 각 기능은 다양한 파일 유형을 지원합니다.

* ![이미지 파일 유형 ](assets/do-not-localize/image-icon.png) 아이콘이미지: GIF, JPG, PNG 및 TIFF
* ![문서 파일 유형 ](assets/do-not-localize/document-icon.png) 아이콘문서: DOCX, PDF, PPTX 및 XLSX
* ![비디오 파일 유형 ](assets/do-not-localize/video-icon.png) icon비디오: MP4

다양한 파일 유형에는 아래에 설명된 대로 사용 사례 및 기능에 대한 지원 수준이 다릅니다. 지원 수준을 이해하려면 범례를 사용합니다.

| 지원 수준 | 설명 |
|-------------------|-------------------------|
| ✓ | 지원됨 |
| ✓ ‡ | 지원되는 조건자 |
| - | 해당 사항 없음 |

## 자산 추가, 업로드 및 보기 {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| 자산 유형 | [찾아보기](/help/navigate-view.md) | 복사 | [업로드](/help/add-delete.md) | 만들기 | [삭제](/help/add-delete.md#delete-assets) | 세부 사항 | 이미지 확대/축소 | [최근에 본 항목](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| 래스터 이미지 | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| 폴더 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| MP4 비디오 | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD, AI 및 INDD | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## 자산 검색, 사용 및 편집 {#support-to-search-use-edit}

| 자산 유형 | [다운로드](/help/manage-organize.md#download) | 드래그하여 놓기 | [이미지 편집기](/help/edit-images.md) | [검색](/help/search.md) | [스마트 태그](/help/metadata.md#tags) | [이름 변경](/help/manage-organize.md) | [버전](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| 래스터 이미지 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| 폴더 | ✓ | ✓ | - | ✓ | - | ✓ | - |
| 비디오 | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| CC Libraries | - | - | - | - | - | ✓ | - |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| PSD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| AI | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |

## 자산 검토 및 공동 작업 {#support-to-review-collaborate}

| 자산 유형 | 주석 | 주석 | 작업 만들기 및 검토 |
|---------------|----------|----------|-------------------------|
| 래스터 이미지 | ✓ | ✓ | ✓ |
| 폴더 | - | - | - |
| 비디오 | - | ✓ | ✓ |
| CC Libraries | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD | - | ✓ | ✓ |
| AI | - | ✓ | ✓ |
| INDD | - | ✓ | ✓ |

## 기타 자산 관리 작업 {#support-to-manage-assets}

| 자산 유형 | [메타데이터](/help/metadata.md) | [표현물](/help/add-delete.md#renditions) | [휴지통](/help/add-delete.md#delete-assets) | 복사 | 이동 |
|---------------|-------------------|------------|----------|----------|----------|
| 래스터 이미지 | ✓ | ✓ | ✓ | ✓ | ✓ |
| 폴더 | ✓ | - | ✓ | ✓ | ✓ |
| 비디오 | ✓ | - | ✓ | ✓ | ✓ |
| CC Libraries | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| PSD | ✓ | - | ✓ | ✓ | ✓ |
| AI | ✓ | - | ✓ | ✓ | ✓ |
| INDD | ✓ | - | ✓ | ✓ | ✓ |

[!DNL Adobe Asset Link] 사용자는 지원되는 [!DNL Adobe Creative Cloud] 데스크탑 응용 프로그램에서 래스터 이미지를 [!DNL Assets Essentials] 리포지토리로 체크 인할 수 있습니다.

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->
