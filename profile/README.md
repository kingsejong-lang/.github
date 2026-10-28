<div align="center">

# KingSejong

**한글 문법으로 프로그래밍하는 언어**

`배열을 걸러낸다(...)` 처럼 조사로 메서드를 잇는 인터프리터 언어입니다. 받침에 따라 `을/를` 처럼 달라지는 조사를 모두 알아듣습니다.

*A programming language with Korean grammar: particle-based method chaining, a tree-walking evaluator and a bytecode VM, written in C++23.*

[플레이그라운드](https://kingsejong-lang.github.io/kingsejong-lang/) ·
[문서](https://kingsejong-lang.github.io/kingsejong-lang/docs/) ·
[API 레퍼런스](https://kingsejong-lang.github.io/kingsejong-lang/api/) ·
[릴리스](https://github.com/kingsejong-lang/kingsejong-lang/releases) ·
[토론](https://github.com/kingsejong-lang/kingsejong-lang/discussions)

</div>

---

## 맛보기

```ksj
가져오기 "stdlib/math"
가져오기 "stdlib/array"

숫자들 = 범위(1, 30)
소수들 = 숫자들을 걸러낸다(소수인가)
출력(소수들)

함수 인사(이름) {
    반환 "안녕하세요, " + 이름 + "님!"
}
출력(인사("세종"))
```

```
[2, 3, 5, 7, 11, 13, 17, 19, 23, 29]
안녕하세요, 세종님!
```

설치 없이 [플레이그라운드](https://kingsejong-lang.github.io/kingsejong-lang/)에서 바로 실행해 볼 수 있습니다.

## 저장소

| 저장소 | 설명 |
|---|---|
| [kingsejong-lang](https://github.com/kingsejong-lang/kingsejong-lang) | 언어 본체: 렉서·파서·평가기·바이트코드 VM, 표준 라이브러리, LSP 서버, 린터·포매터, VS Code 확장, 웹 플레이그라운드 |
| [playground-frontend](https://github.com/kingsejong-lang/playground-frontend) | 여러 언어를 실행하는 웹 코드 플레이그라운드의 프런트엔드 (Next.js) |

## 참여하기

- **질문과 아이디어**: [Discussions](https://github.com/kingsejong-lang/kingsejong-lang/discussions)
- **버그와 기능 제안**: [Issues](https://github.com/kingsejong-lang/kingsejong-lang/issues/new/choose)
- **코드 기여**: [기여 가이드](https://github.com/kingsejong-lang/kingsejong-lang/blob/main/docs/CONTRIBUTING.md)를 먼저 읽어 주세요
- **보안 취약점**: 공개 이슈 대신 [보안 정책](https://github.com/kingsejong-lang/.github/blob/main/SECURITY.md)에 따라 비공개로 알려 주세요
