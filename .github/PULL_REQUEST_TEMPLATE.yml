name: "Pull Request"
description: "풀 리퀘스트 생성"
title: "[대분류] 챕터 제목"
body:
  - type: markdown
    attributes:
      value: |
        ## 작성 가이드라인
        1. 담당파트 작성 후 PR을 생성해 병합한다.
        2. 라벨은 해당 대분류와 일치하는 라벨을 선택한다.
        3. 관련 이슈를 닫아준다.
  - type: checkboxes
    attributes:
      label: ✅ 작성 완료 항목
      description: 작성 완료한 항목에 체크해주세요.
      options:
        - label: 소제목 1
        - label: 소제목 2
        - label: 소제목 3
  - type: input
    attributes:
      label: 🔗 관련 이슈
      description: 이 PR이 닫는 이슈 번호를 입력해주세요.
      placeholder: "closes #이슈번호"
    validations:
      required: true
  - type: textarea
    attributes:
      label: 📍 추가 설명
      description: 필요한 경우 추가 설명을 작성해주세요.