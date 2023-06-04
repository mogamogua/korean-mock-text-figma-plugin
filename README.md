# Korean Mock Text Figma Plugin
기능 정의 및 목표

<aside>
💡 현재는 테스트 버전으로 Notion API를 사용하여 텍스트를 가져옵니다.
향후 random text generator API를 개발하여 더 많은 데이터를 사용할 수 있게 지원할 예정입니다.
</aside>

# 🪧 미션

---

해당 플러그인을 통해 해결하고자 하는 문제

- 플랫폼 디자인 팀의 반복 작업으로 발생하는 발생하는 비효율을 줄이고 디자인에 집중할 수 있도록 돕는다.
- UX writing 가이드라인을 제공한다.
- 플랫폼에 특화된 더미텍스트를 제공한다.
  - 엘리스 강의, 자료 타이틀 및 디스크립션
  - 에러 메시지 가이드라인
  - 플랫폼 기능 관련 더미 텍스트 지원

# 💎 기능

---

### 카테고리 별 텍스트 생성

- userId
- name
- email
- phoneNumber
- date
- course title


### 추가 기능
아래 기능은 향후 개발 예정인 기능을 기술합니다.

### 글자 수 설정

다양한 글자수에 따른 테스트를 진행해야 하는 경우, 텍스트에 대한 고민 없이 손쉽게 글자수 설정으로 정해진 카테고리에 맞는 더미 텍스트를 생성합니다.

### Full Text & Ellipsis 지원

text가 정해진 영역을 꽉 채우는 경우를 고려할 수 있도록 text box를 가득 채우는 더미 텍스트를 생성하며, ellipsis 설정을 지원합니다.

### Error Message

form validation 등 에러의 종류에 따라 메시지를 생성합니다. 플랫폼 디자인팀에서 사용하는 UX 가이드라인에 따른 에러 메시지를 제공합니다.

### Date format 설정

기본적으로 플랫폼 내에서 사용하는 날짜 형식 컨벤션에 따라 랜덤 날짜를 생성하고, 여러 옵션으로 포맷을 변경할 수 있도록 지원합니다.

- duration
- date range : [from, to]
- short / long
- seperator : korean , slash , dot
- display: [”year”, “month”, “day”, “hour”, “minute”, “second”]
react boilerplate for react plugin



해당 플러그인은 [figma-plugin-react-boilerplate](https://github.com/hseoy/figma-plugin-react-boilerplate)를 사용했습니다.


### Figma for plugin development

1. Open Figma desktop application.

2. Click on your profile icon dropdown in the top right and select `Plugins` from the list

3. Scroll down to the `In development` section and click the plus(+) icon

4. Choose `Import from manifest`

5. Locate the manifest.json in your newly created project and then select Open

6. Now you will be able to use this plugin.
