name: 💥 Troubleshooting Report
description: 디버깅 및 문제 해결 과정을 기록합니다
title: "[Trouble] 문제 요약 입력해주세요"
labels: [trouble, needs-review]
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        문제 해결 과정을 기록해주세요. 아래 항목을 채워주세요 😊

  - type: input
    id: summary
    attributes:
      label: 문제 요약
      placeholder: 예: vue-router NavigationDuplicated 오류
    validations:
      required: true

  - type: textarea
    id: symptoms
    attributes:
      label: 증상 및 상황
      placeholder: 어떤 상황에서 발생했나요?
    validations:
      required: true

  - type: textarea
    id: analysis
    attributes:
      label: 원인 분석
      placeholder: 에러 메시지, 콘솔 로그, 추정 원인 등

  - type: textarea
    id: attempts
    attributes:
      label: 시도한 해결 방법
      placeholder: 어떤 시도를 했고 어떤 결과가 있었나요?

  - type: textarea
    id: solution
    attributes:
      label: 최종 해결 방법
      placeholder: 무엇으로 문제를 해결했나요?

  - type: textarea
    id: notes
    attributes:
      label: 추가 메모
      placeholder: 다음에 비슷한 문제 생겼을 때 기억할 것들, 참고 링크 등
