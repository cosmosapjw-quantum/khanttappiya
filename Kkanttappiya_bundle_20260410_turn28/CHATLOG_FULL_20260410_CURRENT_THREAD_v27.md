# CHATLOG FULL — Kkanttappiya current thread (through turn10+, 2026-04-10)

## Turn 1
### User
깐따삐야어 프로젝트 handoff (2026-04-10 세션 완료). 현재 상태, 문법 체계, 어휘 원칙, 즉시 실행 순서, 주의사항과 첨부 zip 제공.

### Assistant
handoff 수령 및 현재 기준 상태 승인. 우선순위를 Stage A–D audit → Reference Grammar 확장 → 코퍼스 증설로 재정렬.

## Turn 2
### User
Stage A-D audit부터 시작

### Assistant
Stage A–D 1차 audit 수행. 핵심 결과:
- 제거: `SA-INT-003`, `SA-DIF-005`
- 교체: `SC-DESC-005` -> `잡파` 전략
- 유지(조건부): `SA-DIF-008` = `빛포아 느몰온`
- Stage D는 구조 오류보다 paradigm fragment 정규화 문제로 판정

## Turn 3
### User
앞으로는 대화내역 전체 md + 업데이트되거나 새로 추가된 모든 파일들 + handoff packet을 항상 zip 파일로 묶어 제공해주고 매 턴마다 업데이트해줘.

### Assistant
이 워크플로를 기본으로 고정. 누적 세션 번들 체계를 시작함.

## Turn 4
### User
좋아. 이어서 진행해줘.

### Assistant
`DIF+NEG` micro-corpus 생성 및 검증.
핵심 결론:
- `빛-포-아 느-몰-온` 계열은 provisional freeze candidate
- 금지형: `*빛-아 느-몰-포-온`, `*빛-포-아 느-포-몰-온`

## Turn 5
### User
좋아. 이어서 진행해줘.

### Assistant
Reference Grammar 6장(태) 확장.
핵심 결론:
- INT NEG = `ROOT-루-아 + NEG.AUX`
- REFL = 편입, suffix 아님
- DIF NEG = `ROOT-포-아 + NEG.AUX`

## Turn 6
### User
좋아. 이어서 진행해줘.

### Assistant
Reference Grammar 5장(동사 템플릿) 확장.
핵심 결론:
- `-루-`는 aspect가 아니라 **VOICE(INT)**
- PREVERB는 canonical negation에서 `몰-`로 이동
- canonical order = `ROOT-ASP-VOICE-EVID-HON-FINAL/NONFIN`

## Turn 7
### User
좋아. 이어서 진행해줘.

### Assistant
Reference Grammar 14장(파생 형태론) 확장.
핵심 결론:
- 파생 SSOT = `ROOT + L1 + (FLOW-MODE) + L2`
- 흐름양태는 L2 없이는 불가
- L1/L2 stacking 금지
- 원초 명사는 L2 direct attachment 허용

## Turn 8
### User
좋아. 이어서 진행해줘.

### Assistant
Reference Grammar 16장(정중성) 확장.
핵심 결론:
- Level 0/1/2 체계 운영 규칙 명시
- HON 위치 = EVID 뒤, FINAL 앞
- formal clitic과 NEG/IMP/NONFIN/QUOT 상호작용 정리

## Turn 9
### User
좋아. 이어서 진행해줘.

### Assistant
Stage D polite corpus와 16장 규칙을 상호 검증.
핵심 결론:
- 36/36 retained, hard fail 0
- formal clitic rule refined:
  - predicate domain에서는 HON과 공기
  - fragment/header domain에서는 단독 가능
- Stage D를 audited pass로 승격

## Turn 10
### User
좋아. 이어서 진행해줘.

### Assistant
Stage B vocab audit 수행.
핵심 결론:
- hard fail 0, audited pass
- revised 2:
  - `SB-TOOL-007` `ㆍ갈` -> `거울`
  - `SB-TOOL-008` `ㅸ틀` -> `틀`
- Stage A–D 전체 audit 완료

## Turn 11
### User
좋아. 이어서 진행해줘.

### Assistant
파생 표면형 음운 규칙표 작성 및 surface-phonology micro-audit 수행.
핵심 결론:
- 기본값은 `형태 검증 -> 단순 접합 -> 최소 음운 후처리`
- direct-L2 primitive noun 유지
- 파생 경계에서 유음화/구개음화/임의 자연화 금지
- 대표 기각형:
  - `*불리`
  - `*불파나`
  - `*불ㅿ은눌`
  - `*불련ㅸ온`
산출물:
- `SURFACE_PHONOLOGY_RULETABLE_V1.md`
- `SURFACE_PHONOLOGY_DIAGNOSTIC_MICROCORPUS_V1.csv`
- `SURFACE_PHONOLOGY_AUDIT_REPORT_20260410.md`
- `KKANTTAPPIYA_REFERENCE_GRAMMAR_V1_7.md`
- updated handoff / continuation brief / chatlog / bundle

## Current next steps
1. quotation-internal REFL stress test
2. DIF-causative stress test
3. OBL+IMP stress test
4. 고빈도 파생어 사전 1차 정비

## Turn 12
### User
좋아. 이어서 진행해줘.

### Assistant
quotation-internal REFL / DIF-causative / OBL+IMP stress test 수행.
핵심 결론:
- quotation-internal REFL = licensed but marked
- DIF-causative = peripheral / marked / non-productive
- OBL+IMP = frozen lexicalized exception
- ordinary PREVERB는 imperative와 결합 불가, `바-`만 constructional exception으로 생존
산출물:
- `PERIPHERAL_STRESS_TEST_MICROCORPUS_V1.csv`
- `PERIPHERAL_STRESS_TEST_REPORT_20260410.md`
- `KKANTTAPPIYA_REFERENCE_GRAMMAR_V1_8.md`
- updated handoff / continuation brief / chatlog / bundle

## Current next steps
1. 고빈도 파생어 사전 1차 정비
2. 파생어별 gloss/의미장/금지 대립형 정리
3. 코퍼스 증설

## Turn 13
### User
좋아. 이어서 진행해줘.

### Assistant
고빈도 파생어 사전 1차 정비 수행.
핵심 결론:
- 총 표제어 56개 정리
- canon-facing 41 / expansion-candidate 15
- `알-`, `말-`, `물-`, `불-`, `나무-` 군집을 중심으로 lexical lattice 정리
- `보-`, `쓰-`, `말파-` 계열은 합법하지만 아직 corpus-backed freeze는 아님
산출물:
- `HIGH_FREQUENCY_DERIVATIONAL_LEXICON_V1.csv`
- `HIGH_FREQUENCY_DERIVATIONAL_LEXICON_V1.md`
- `DERIVATIONAL_LEXICON_PASS1_REPORT_20260410.md`
- `KKANTTAPPIYA_REFERENCE_GRAMMAR_V1_9.md`
- updated handoff / continuation brief / chatlog / bundle

## Current next steps
1. expansion-candidate 파생어 15개를 대상으로 코퍼스 30~50행 작성
2. `말- / 쓰- / 보-` 군집 중심 register 확장
3. lexicon v2 승격 판단


## Turn 13
### User
좋아. 이어서 진행해줘.

### Assistant
expansion-candidate 15개를 대상으로 Stage E corpus 36행 작성.
핵심 결론:
- 12개 승격, 3개 유보
- 고빈도 파생어 사전 v2 = canon-facing 53 / candidate 3
- audited master v3 = 705행


## Turn 14
### User
좋아. 이어서 진행해줘.

### Assistant
turn13 잔류 candidate 3개(`보나ㅸ앙`, `보나눌`, `알돈ㅸ앙`)를 대상으로 register-specific corpus 15행 작성.
핵심 결론:
- `보나ㅸ앙`, `알돈ㅸ앙` 승격
- `보나눌`은 marked-specialized noun으로 candidate 유지
- 고빈도 파생어 사전 v3 = canon-facing 55 / candidate 1
- audited master v4 = 720행
산출물:
- `STAGE_F_REGISTER_SPECIFIC_PROMOTION_V1.csv`
- `REGISTER_SPECIFIC_PROMOTION_LEDGER_20260410.csv`
- `REGISTER_SPECIFIC_PROMOTION_REPORT_20260410.md`
- `HIGH_FREQUENCY_DERIVATIONAL_LEXICON_V3.csv/.md`
- `MASTER_CORPUS_V1_AUDITED_v4.csv`
- `KKANTTAPPIYA_REFERENCE_GRAMMAR_V1_11.md`
- updated handoff / continuation brief / chatlog / bundle

## Current next steps
1. `보나눌` poetic/clinical mini-corpus 8~12행 작성
2. `빌나 / 지나 / 말파ㅸ온 / 보나ㅸ앙 / 알돈ㅸ앙` admin/polite/dialogue 확장
3. 코퍼스를 750+까지 증설


## Turn 15
User: 좋아. 이어서 진행해줘.
Assistant: `보나눌` poetic/clinical mini-corpus를 작성해 재판정했다. 결론은 승격 보류, marked-specialized candidate 유지. 관련 lexicon, grammar, handoff, manifest, bundle을 갱신했다.


## Turn 16
User: 좋아. 이어서 진행해줘.
Assistant: admin/polite/dialogue register 코퍼스 24행을 추가해 `빌나 / 지나 / 말파ㅸ온 / 보나ㅸ앙 / 알돈ㅸ앙`의 ordinary portability를 검증했다. 관련 lexicon, grammar, handoff, manifest, bundle을 갱신했다.


## Turn 17
User: 좋아. 이어서 진행해줘.
Assistant: ordinary narrative + service dialogue 50행을 추가해 audited master를 804행으로 올렸고, early chapter example bank도 따로 작성했다. 관련 lexicon, grammar, handoff, manifest, bundle을 갱신했다.


## Turn 18
User: 좋아. 이어서 진행해줘.
Assistant: continuous text 2종(짧은 서사문 + 서비스 대화문)을 작성하고, early chapter example bank를 초반부 본문에 연결하는 통합안을 만들었다. audited master는 834행으로 늘었고 관련 lexicon, grammar, handoff, manifest, bundle을 갱신했다.


## Turn 19
User: 좋아. 이어서 진행해줘.
Assistant: 서론/1장/2장/3장을 실제로 다시 써서 Reference Grammar v1.16을 만들었다. 초반부는 example-rich tutorial 방식으로 재구성했고, 3장에서 TRK(=길)을 core inventory에서 제거해 8격+TOP SSOT를 다시 고정했다.


## Turn 20
User: 좋아. 이어서 진행해줘.
Assistant: 4장, 7장, 8장, 9장을 실제로 다시 쓰고 그 장들에 대응하는 diagnostic corpus 24행을 추가했다. Reference Grammar는 v1.17이 되었고 audited master는 858행으로 늘었다.


## Turn 21
User: 좋아. 이어서 진행해줘.
Assistant: 10장, 11장, 12장, 13장을 실제로 다시 쓰고 diagnostic corpus 24행을 추가했다. Reference Grammar는 v1.18이 되었고 audited master는 882행으로 늘었다.


## Turn 22
User: 좋아. 이어서 진행해줘.
Assistant: 17장 주석 텍스트를 실제 annotated text 장으로 다시 쓰고, 부록을 A–J 구조로 정리했다. 중복된 제7부 제목과 Appendix G를 제거하고 scattered addendum을 revision notes 쪽으로 흡수했다.


## Turn 23
User: 좋아. 이어서 진행해줘.
Assistant: long-form continuous text 2종을 추가하고, 15장 기본 어휘를 실제로 다시 써서 17장/부록 C와 어휘군을 맞췄다. 이번부터는 요약 숫자보다 실제 CSV 행수를 source of truth로 사용한다.


## Turn 24
User: 좋아. 이어서 진행해줘.
Assistant: long-form text 2종을 더 추가해 actual master를 950행대로 올렸고, 16장 정중성 장을 service dialogue 코퍼스와 직접 연결하는 방향으로 실제로 다시 썼다. 이후 숫자는 항상 실제 CSV 행수를 source of truth로 삼는다.


## Turn 25
User: 좋아. 이어서 진행해줘. 보나눌은 자연언어에 존재하는 특수 예외 케이스처럼 다루어서 추가하는건 어떄?
Assistant: 그 제안은 타당하다고 보고, `보나눌`을 candidate에서 listed-exception으로 재분류했다. ordinary core noun으로는 올리지 않되, clinical/poetic/perceptual domain에 허용되는 lexicalized 예외 어휘로 등재하고, 다른 `-눌` 형식의 일반화 근거로는 쓰지 않도록 규정했다.


## Turn 26
User: 좋아. 이어서 진행해줘.
Assistant: long-form text 2종을 추가해 actual master를 1005행으로 올렸고, 17장 주석 텍스트와 listed-exception 부록도 갱신했다. 보나눌은 listed-exception으로 유지하고 일반화는 금지한다.


## Turn 27
User: 좋아. 이어서 진행해줘.
Assistant: 17장을 v3로 올려 Text A–D를 전부 본문+주석+학습 포인트 구조로 정리하고, 장별 index / cross-reference 표를 추가했다. 새 코퍼스는 늘리지 않았고 actual master는 1005행을 유지한다.


## Turn 28
User: 이제 나머지 작업들을 다 해줘.
Assistant: 부록 L과 M을 grammar 본문에 실제로 접속하고, 서론에 빠른 탐색을 추가해 남은 필수 정리 작업을 마무리했다. 이제 이후 작업은 선택적 확장 단계로 넘어간다.
