# market-wiki

퍼포먼스 마케팅을 위한 **업종/경쟁사 분석 위키**입니다.
[Andrej Karpathy의 LLM Wiki](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) 패턴을 따라, LLM(Claude Code)이 위키를 작성하고 관리합니다.

- 👉 **시작점: [wiki/index.md](wiki/index.md)** · [종합 인사이트](wiki/overview.md) · [작업 기록](wiki/log.md)
- 📐 운영 규칙(스키마): [CLAUDE.md](CLAUDE.md)

## 구조

| 레이어 | 위치 | 누가 쓰나 |
|---|---|---|
| 원본 자료 | `raw/` | 사람이 넣음 (수정하지 않음) |
| 위키 | `wiki/` | LLM이 작성·관리 |
| 스키마 | `CLAUDE.md` | 사람과 LLM이 함께 고쳐 나감 |

## 사용법

```bash
cd market-wiki && claude
```

- **자료 반영**: 광고 라이브러리 캡처나 메모를 `raw/ad-library/`에 넣고 → "raw/ad-library/2026-10-22_브랜드.md 반영해줘"
- **질문**: "토너패드 브랜드들 오퍼 비교해줘"
- **점검**: "위키 린트 해줘"

> 공개 저장소입니다. 공개된 정보만 다루고, 고객사 내부 데이터는 넣지 않습니다.
