# Graph Report - .  (2026-06-08)

## Corpus Check
- Corpus is ~12,987 words - fits in a single context window. You may not need a graph.

## Summary
- 31 nodes · 48 edges · 5 communities
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 2 edges (avg confidence: 0.8)
- Token cost: 12,000 input · 2,800 output

## Community Hubs (Navigation)
- [[_COMMUNITY_행정업무 혁신 및 정책 관리|행정업무 혁신 및 정책 관리]]
- [[_COMMUNITY_서식 및 시행규칙|서식 및 시행규칙]]
- [[_COMMUNITY_전자문서 및 디지털 서명|전자문서 및 디지털 서명]]
- [[_COMMUNITY_관인 및 전자이미지관인|관인 및 전자이미지관인]]
- [[_COMMUNITY_업무·지식행정 시스템|업무·지식행정 시스템]]

## God Nodes (most connected - your core abstractions)
1. `행정업무의 운영 및 혁신에 관한 규정 (대통령령)` - 22 edges
2. `행정업무의 운영 및 혁신에 관한 규정 시행규칙 (행정안전부령)` - 8 edges
3. `전자문서 (전자적 형태로 작성·송수신·저장된 문서)` - 4 edges
4. `전자문서시스템` - 4 edges
5. `업무관리시스템` - 4 edges
6. `정책연구 (중앙행정기관 연구과제 계약)` - 4 edges
7. `행정정보시스템` - 3 edges
8. `전자이미지관인` - 3 edges
9. `관인 (청인·직인)` - 3 edges
10. `정책연구심의위원회` - 3 edges

## Surprising Connections (you probably didn't know these)
- `행정업무의 운영 및 혁신에 관한 규정 시행규칙 (행정안전부령)` --implements--> `행정업무의 운영 및 혁신에 관한 규정 (대통령령)`  [EXTRACTED]
  kr/행정업무의운영및혁신에관한규정/시행규칙.md → kr/행정업무의운영및혁신에관한규정/대통령령.md
- `문서관리카드 (별지 제6호 서식)` --implements--> `업무관리시스템`  [EXTRACTED]
  kr/행정업무의운영및혁신에관한규정/시행규칙.md → kr/행정업무의운영및혁신에관한규정/대통령령.md
- `전자이미지관인대장 (별지 제8호 서식)` --implements--> `전자이미지관인`  [EXTRACTED]
  kr/행정업무의운영및혁신에관한규정/시행규칙.md → kr/행정업무의운영및혁신에관한규정/대통령령.md
- `관인대장 (별지 제7호 서식)` --implements--> `관인 (청인·직인)`  [EXTRACTED]
  kr/행정업무의운영및혁신에관한규정/시행규칙.md → kr/행정업무의운영및혁신에관한규정/대통령령.md
- `정책연구심의위원회 구성·운영 (시행규칙)` --implements--> `정책연구심의위원회`  [EXTRACTED]
  kr/행정업무의운영및혁신에관한규정/시행규칙.md → kr/행정업무의운영및혁신에관한규정/대통령령.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **전자문서 처리 통합 시스템군 (전자문서시스템·업무관리시스템·행정정보시스템 연계)** — 대통령령_전자문서시스템, 대통령령_업무관리시스템, 대통령령_행정정보시스템 [EXTRACTED 1.00]
- **정책연구 관리 체계 (정책연구·심의위원회·관리시스템)** — 대통령령_정책연구, 대통령령_정책연구심의위원회, 대통령령_정책연구관리시스템 [EXTRACTED 1.00]
- **행정업무 혁신 추진체계 (행정협업·혁신책임관·행정업무혁신시스템)** — 대통령령_행정협업, 대통령령_혁신책임관, 대통령령_행정업무혁신시스템 [EXTRACTED 1.00]

## Communities (5 total, 0 thin omitted)

### Community 0 - "행정업무 혁신 및 정책 관리"
Cohesion: 0.29
Nodes (10): 공문서 (행정기관 공무상 작성·시행 문서), 문서 결재 절차 (결재·위임전결·대결), 영상회의실 (정부영상회의실 포함), 정책실명제, 정책연구 (중앙행정기관 연구과제 계약), 정책연구관리시스템, 행정업무혁신시스템, 행정협업 및 행정협업과제 (+2 more)

### Community 1 - "서식 및 시행규칙"
Cohesion: 0.25
Nodes (8): 기안문 (문서 기안 서식), 서식 (행정기관 공통 반복 문서 양식), 정책연구심의위원회, 기안문 서식 (별지 제1호~제4호 서식), 서식 설계 기준 (별표 4·5), 정부영상회의실 관리·운영 (시행규칙), 정책연구심의위원회 구성·운영 (시행규칙), 행정업무의 운영 및 혁신에 관한 규정 시행규칙 (행정안전부령)

### Community 2 - "전자문서 및 디지털 서명"
Cohesion: 0.40
Nodes (5): 개방형 문서 형식 (기계 판독 가능, 표준 공개), 전자문서 (전자적 형태로 작성·송수신·저장된 문서), 전자문서시스템, 정부전자문서유통지원센터, 행정전자서명

### Community 3 - "관인 및 전자이미지관인"
Cohesion: 0.50
Nodes (4): 관인 (청인·직인), 전자이미지관인, 관인대장 (별지 제7호 서식), 전자이미지관인대장 (별지 제8호 서식)

### Community 4 - "업무·지식행정 시스템"
Cohesion: 0.50
Nodes (4): 업무관리시스템, 지식행정 (행정지식 공동이용), 행정정보시스템, 문서관리카드 (별지 제6호 서식)

## Knowledge Gaps
- **5 isolated node(s):** `공문서 (행정기관 공무상 작성·시행 문서)`, `행정전자서명`, `문서 결재 절차 (결재·위임전결·대결)`, `영상회의실 (정부영상회의실 포함)`, `정부영상회의실 관리·운영 (시행규칙)`
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `행정업무의 운영 및 혁신에 관한 규정 (대통령령)` connect `행정업무 혁신 및 정책 관리` to `서식 및 시행규칙`, `전자문서 및 디지털 서명`, `관인 및 전자이미지관인`, `업무·지식행정 시스템`?**
  _High betweenness centrality (0.822) - this node is a cross-community bridge._
- **Why does `행정업무의 운영 및 혁신에 관한 규정 시행규칙 (행정안전부령)` connect `서식 및 시행규칙` to `행정업무 혁신 및 정책 관리`, `관인 및 전자이미지관인`, `업무·지식행정 시스템`?**
  _High betweenness centrality (0.256) - this node is a cross-community bridge._
- **Why does `전자문서 (전자적 형태로 작성·송수신·저장된 문서)` connect `전자문서 및 디지털 서명` to `행정업무 혁신 및 정책 관리`?**
  _High betweenness centrality (0.068) - this node is a cross-community bridge._
- **What connects `공문서 (행정기관 공무상 작성·시행 문서)`, `행정전자서명`, `문서 결재 절차 (결재·위임전결·대결)` to the rest of the system?**
  _5 weakly-connected nodes found - possible documentation gaps or missing edges._