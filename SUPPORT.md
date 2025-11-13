# Vision Playground - 지원

## 앱 정보

Vision Playground는 Apple Vision Framework의 RecognizeTextRequest API를 테스트하기 위한 개발자 도구입니다.

## 시스템 요구사항

- macOS 10.15 (Catalina) 이상
- Apple Silicon 또는 Intel Mac

## 사용 방법

### 1. 이미지/PDF 업로드
- 파일 선택 버튼 클릭 또는 드래그 앤 드롭
- 지원 형식: JPG, PNG, PDF

### 2. 인식 모드 선택
- **Fast**: 빠른 인식 (낮은 정확도)
- **Accurate**: 정확한 인식 (느린 속도)

### 3. 언어 선택
- 인식할 텍스트의 언어 선택

### 4. 결과 확인
- 인식된 텍스트와 바운딩 박스 확인
- JSON으로 내보내기

## 개발자 정보

이 앱의 주요 목적:
- RecognizedTextObservation 구조 확인
- Bounding box 좌표 분석
- Confidence score 확인
- 다국어 인식 결과 비교

## 문제 해결

### 앱이 실행되지 않는 경우
- macOS 버전 확인 (10.15 이상 필요)
- 앱을 재설치해보세요

### 파일을 열 수 없는 경우
- 파일 형식 확인 (JPG, PNG, PDF만 지원)
- 파일이 손상되지 않았는지 확인

### OCR 결과가 부정확한 경우
- Accurate 모드로 전환
- 적절한 언어 선택
- 이미지 품질 확인

## 피드백

버그 리포트나 기능 요청은 GitHub Issues를 통해 제출해주세요.

## 라이선스

이 앱은 개발 및 학습 목적으로 제공됩니다.
