---
title: 지원되는 파일 형식
description: 다양한 사용 사례에 대해 지원되는 파일 형식 [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: b9d333a862cca6227ef386ae8dadf431c2fb6d71
workflow-type: tm+mt
source-wordcount: '308'
ht-degree: 15%

---

# 파일 형식은 [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] 는 다양한 파일 형식을 지원하며 각 기능은 다양한 파일 유형을 지원합니다.

* ![이미지 파일 유형 아이콘](assets/image-icon.svg) 이미지: JPG, PNG, GIF, TIFF 등
* ![creative cloudtype 아이콘](assets/creative-cloud-files.svg) Creative Cloud 파일: PSD, AI 및 INDD
* ![카메라 유형 아이콘](assets/camera-icon.svg) Camera Raw 파일: CR2/CR3, NEF, SRW/SRF 등
* ![문서 파일 유형 아이콘](assets/document-icon.svg) 문서: DOCX, PDF, PPTX 및 XLSX
* ![비디오 파일 유형 아이콘](assets/video-icon.svg) 비디오: MP4

[!DNL Assets Essentials] 저장, 업로드, 복사, 이동, 삭제 및 메타데이터 추가와 같은 기본 서비스를 사용하는 모든 이진 파일 형식을 지원합니다.

[!DNL Assets Essentials] 또한 Adobe Camera Raw에서 제공하는 Canon(CR2/CR3), Nikon(NEF), Sony(SRW/SRF), Fujifilm(RAF), Olympus(ORF) 등 다양한 주요 카메라 제조업체에서 카메라 RAW 파일을 지원합니다.

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
| RAW 파일 | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| 폴더 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| MP4 비디오 | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD, AI 및 INDD | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| 기타 이진 파일 | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## 자산 검색, 사용 및 편집 {#support-to-search-use-edit}

| 자산 유형 | [다운로드](/help/manage-organize.md#download) | 드래그하여 놓기 | [이미지 편집기](/help/edit-images.md) | [검색](/help/search.md) | [스마트 태그](/help/metadata.md#tags) | [이름 변경](/help/manage-organize.md) | [버전](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| 래스터 이미지 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW 파일 | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ | ✓ |
| 폴더 | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |
| 비디오 | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| CC Libraries | - | - | - | - | - | ✓ | ✓ |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| PSD, AI 및 INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| 기타 이진 파일 | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |


## 자산 검토 및 공동 작업 {#support-to-review-collaborate}

| 자산 유형 | 주석 | 주석 | 작업 만들기 및 검토 |
|---------------|----------|----------|-------------------------|
| 래스터 이미지 | ✓ | ✓ | ✓ |
| RAW 파일 | ✓ | ✓ | ✓ |
| 폴더 | - | - | - |
| 비디오 | - | ✓ | ✓ |
| CC Libraries | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD, AI 및 INDD | - | ✓ | ✓ |
| 기타 이진 파일 | - | ✓ | ✓ |

## 기타 자산 관리 작업 {#support-to-manage-assets}

| 자산 유형 | [메타데이터](/help/metadata.md) | [표현물](/help/add-delete.md#renditions) | [휴지통](/help/add-delete.md#delete-assets) | 복사 | 이동 |
|---------------|-------------------|------------|----------|----------|----------|
| 래스터 이미지 | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW 파일 | ✓ | ✓ | ✓ | ✓ | ✓ |
| 폴더 | ✓ | - | ✓ | ✓ | ✓ |
| 비디오 | ✓ | - | ✓ | ✓ | ✓ |
| CC Libraries | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| PSD, AI 및 INDD | ✓ | - | ✓ | ✓ | ✓ |
| 기타 이진 파일 | ✓ | - | ✓ | ✓ | ✓ |

의 사용자 [!DNL Adobe Asset Link] 파일을 업로드하고 체크 인(새 버전 업로드)할 수 있습니다. [!DNL Assets Essentials] 지원되는 저장소의 리포지토리 [!DNL Adobe Creative Cloud] 데스크탑 응용 프로그램.

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
