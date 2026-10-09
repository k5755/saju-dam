# 사주담 소스 코드

사주담 사이트의 공개 배포 버전 13 소스 스냅샷입니다.

- 운영 사이트: https://saju-dam.workspace-893387.chatgpt.site
- 소스 압축 파일: `saju-dam-source-v13.zip`
- 압축 파일에는 Git 추적 파일 123개가 포함되어 있으며, `.git`, `node_modules`, 빌드 캐시, 환경 파일은 포함하지 않았습니다.
- 룰렛 이벤트의 6칸 UI와 33% / 12% / 16% / 39% 정수 난수 추첨 로직이 포함되어 있습니다.

압축을 푼 뒤 Node.js 22.13 이상에서 `npm ci` 후 `npm run build`로 빌드할 수 있습니다.
