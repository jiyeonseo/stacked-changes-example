# stacked-changes-example

[코드 리뷰의 또 다른 접근 방법: Pull Requests vs. Stacked Changes](https://infcon.day/speaker/%ec%84%9c%ec%a7%80%ec%97%b0-%ec%bd%94%eb%93%9c%eb%a6%ac%eb%b7%b0-%ea%b9%83%ed%97%99/) 발표에서 사용될 예제 프로젝트입니다. 

**코드 리뷰 흐름**을 보기 위한 프로젝트로, 내부 구현은 없이 큰 구조만 가지고 있는 프로젝트입니다. 

## Structure

```
    app
    ├── api              - API 관련 로직
    │   ├── router       - API endpoints 
    │   └── server       - 서버 로직
    └── web              - 프론트 관련 로직
        └── components   - 프론트 컴포넌트들
```