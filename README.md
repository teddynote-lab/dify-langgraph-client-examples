![](./assets/thumbnail.png)

Dify 와 LangGraph API 를 활용해서 AI 앱을 배포하기 위한 클라이언트 유스케이스를 소개하는 레포지토리입니다.

## Dify

### 1. 단일 페이지 웹 앱으로 배포

Dify 콘솔에서 바로 싱글 페이지 웹 앱을 내보낼 수 있습니다.

좌측 상단 로고, 봇 이미지, 색상 테마를 커스텀 할 수 있습니다.

Powered By Dify 워터마크가 포함됩니다.

### 2. [웹사이트 내부에 삽입 (Embed)](https://github.com/teddynote-lab/dify-embedding-usecase/tree/6e69d5afed30d26ac7c77ad65faf413df97ca8cd)

Dify 에서 제작한 채팅앱은 웹사이트에 삽입이 가능합니다.
(단, 워크플로우 앱은 임베드 옵션이 제공되지 않습니다)

단일 페이지 웹 앱이 iframe 으로 그대로 웹사이트에 포함됩니다.

### 3. [StreamLit 앱으로 제작]()

Dify API 를 이용해서 StreamLit 앱을 제작할 수 있습니다.  
이미 StreamLit 을 이용한 앱 제작에 익숙하신 분이라면 사용해볼만 합니다.

### 4. [프론트엔드 템플릿 사용]()

Dify API 를 활용한 공식 프론트엔드 템플릿이 존재합니다.  
Next.js 프로젝트여서 본격적으로 커스텀하려면 프론트엔드 지식이 필요합니다.  
프론트엔드 지식 없이도 간단하게 수정해서 배포할 수 있게 제작된 포크 버전을 확인하실 수 있습니다.

### 5. AI 클라이언트 사용하기

#### OpenWebUI

OpenWebUI 의 경우 Pipeline 을 통해서 Dify 와 연동이 가능합니다. [예시 코드](https://github.com/teddylee777/dify-openwebui) 와 주주총회 영상을 참고해주세요.

- TeddyFlow
  - 100% 노코드로 AI 기능들 사용가능하게 만들고 싶다.
  - B2B SaaS 사내 [ AI 어드민 / AI 생산성 ] 플랫폼을 지향
  - 현재 베타 서비스 중. 올해 상반기에 아래 기능 추가 예정
    - 애널리틱스
      - 앱 별 / 사용자 별 사용량 확인, 제한 기능
      - 자주 쓰이는 키워드 등, 사용 데이터 요약 기능
    - 팀 워크스페이스
      - 팀 내에서 앱 공유 가능
    - Teams 등 협업 툴 통합
      - Dify, LangGraph 앱을 노코드로 Teams 등의 협업툴에 통합 가능하도록
    - 고객사 인프라에 맞춘 온프레미스 설치 옵션 제공

### 6. 협업 툴에 통합

Discord, Teams, Slack 등 현존하는 대부분의 협업 툴에 API 를 이용하여 통합 가능합니다.  
[Discord](https://github.com/teddynote-lab/dify-langgraph-discord-bot) 와 [Teams](https://github.com/teddynote-lab/dify-langgraph-teams-bot) 예시 코드를 제공합니다.

## LangGraph Platform

### 1. 프론트엔드 템플릿 사용

[LangGraph 공식 프론트엔드 템플릿](https://github.com/langchain-ai/agent-chat-ui)을 사용하실 수 있습니다.  
InputState 에 messages 를 가진 Graph 와 통합 가능합니다.
프론트엔드 지식 없이도 간단하게 수정해서 배포할 수 있게 제작된 [포크 버전](https://github.com/teddynote-lab/langgraph-platform-webapp)을 확인하실 수 있습니다.

### 2. AI 클라이언트 사용하기

#### OpenWebUI

OpenWebUI 의 경우 Pipeline(Python Code) 을 통해서 LangGraph 코드를 직접 연결할 수 있습니다.
[예시 코드](https://github.com/casedone/langgraph-agent-openwebui-demo) 와 [예시 영상](https://www.youtube.com/live/4fg0KGmSjv8) 을 참고해보셔도 좋을 것 같습니다.

#### TeddyFlow

- 100% 노코드로 AI 기능들 사용가능하게 만들고 싶다.
- B2B SaaS 사내 [ AI 어드민 / AI 생산성 ] 플랫폼을 지향
- 현재 베타 서비스 중. 올해 상반기에 아래 기능 추가 예정
  - 애널리틱스
    - 앱 별 / 사용자 별 사용량 확인, 제한 기능
    - 자주 쓰이는 키워드 등, 사용 데이터 요약 기능
  - 팀 워크스페이스
    - 팀 내에서 앱 공유 가능
  - Teams 등 협업 툴 통합
    - Dify, LangGraph 앱을 노코드로 Teams 등의 협업툴에 통합 가능하도록
  - 고객사 인프라에 맞춘 온프레미스 설치 옵션 제공

### 3. 협업 툴에 통합

Discord, Teams, Slack 등 현존하는 대부분의 협업 툴에 API 를 이용하여 통합 가능합니다.  
[Discord](https://github.com/teddynote-lab/dify-langgraph-discord-bot) 와 [Teams](https://github.com/teddynote-lab/dify-langgraph-teams-bot) 예시 코드를 제공합니다.

## License

[MIT LICENSE](LICENSE.md)

## Contributing

기여는 언제나 환영합니다! 이슈 등록이나 풀 리퀘스트를 통해 프로젝트에 참여해 주세요. :)
