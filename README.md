# 저장소 설명
핵클을 이용한 초간단 ABTest 샘플 프로젝트

## 강의 정보
| 분류    | 강의명                          |
|-------|------------------------------|
| 강의명   | 초간단 이커머스 서비스에서 대규모 서비스로 도약하기 |
| 파트 1  | 스타트업 초기 서비스 개발               |
| 챕터 07 | 초간단 ABTest 도입하기              |
| 클립 04 | ABTest 구현 도구 - Hackle        |

### 필수 의존성
```groovy
dependencies {
    implementation 'org.springframework.boot:spring-boot-starter-web'
    implementation 'org.springframework.boot:spring-boot-starter-thymeleaf'

    // Hackle SDK 의존성 추가
    implementation 'io.hackle:hackle-server-sdk:2.9.0'
}
```