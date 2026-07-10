# 연구 인수인계용 handoff packet — 깐따삐야어 (2026-04-10, turn14)

## 1. 초압축 요약
turn13에서 유보한 파생어 3개 `보나ㅸ앙 / 보나눌 / 알돈ㅸ앙`에 대해 **register-specific corpus 15행**을 추가했다. 결론은 **2개 승격, 1개 유보**다. 이제 고빈도 파생어 사전은 **canon-facing 55 / candidate 1** 상태이며, audited master는 **720행**으로 증가했다.

## 2. 현재 기준 상태
- audited master v3: 705행
- Stage F corpus 추가: 15행
- audited master v4: 720행
- 어근: 약 330
- 실효 어휘: 약 1,850+
- `KKANTTAPPIYA_REFERENCE_GRAMMAR_V1_11.md`: 17장 + 부록 G

## 3. 문법/파생 SSOT
- 동사 템플릿: `[REFL:NP악]-(PREV)-ROOT-(ASP)-(VOICE)-(EVID)-(HON)-FINAL/NONFIN`
- `-루-` = VOICE(INT), aspect inventory 아님
- canonical negation에서 PREVERB는 `몰-` 쪽으로 이동
- REFL은 left-edge incorporation
- DIF+NEG는 `ROOT-포-아 (PREV)-몰-(EVID)-(HON)-FINAL/NONFIN`이 provisional freeze candidate
- 파생 SSOT = `ROOT + L1 + (FLOW-MODE) + L2`
- 흐름양태는 L2 없이는 허용되지 않음
- L1/L2 stacking 금지
- direct-L2 primitive noun 허용
- 파생 표면형 기본값은 단순 접합 + 최소 음운 후처리
- quotation-internal REFL = licensed but marked
- DIF-causative = peripheral / non-productive
- OBL+IMP = frozen lexicalized exception
- restricted register에서도 plain/admin frame을 통과하면 domain-stable canon noun으로 승격 가능

## 4. turn14 핵심 결론
### 4.1 Stage F register-specific corpus
- `STAGE_F_REGISTER_SPECIFIC_PROMOTION_V1.csv` 15행 생성
- turn13 holdout 3개 전부 register-specific frame에 투입

### 4.2 승격 (2)
- `보나ㅸ앙` — gallery/archive/visual repository noun
- `알돈ㅸ앙` — campus complex / academic cluster noun

### 4.3 유보 (1)
- `보나눌` — marked residual-image noun; interpretable but 아직 narrow

### 4.4 사전 상태
- `HIGH_FREQUENCY_DERIVATIONAL_LEXICON_V3.csv/.md`
- 총 56개 표제어
- canon-facing 55
- expansion-candidate 1 (`보나눌`)

## 5. Audit 상태
### 완료
- Stage A audit 완료
- Stage B vocab audit 완료
- Stage C audit 완료
- Stage D polite audit 완료
- DIF+NEG / voice / verb-template / derivational / surface-phonology / peripheral micro-audit 완료
- 고빈도 파생어 사전 1차 정비 완료
- Stage E candidate promotion corpus 완료
- Stage F register-specific promotion corpus 완료

### 잔여
- `보나눌` poetic/clinical mini-corpus 미실시
- 코퍼스 1,350행 증설 미착수
- narrative/dialogue/admin 대규모 증설 미착수

## 6. 다음 즉시 실행 순서
1. `보나눌`만 대상으로 poetic/clinical mini-corpus 8~12행 추가
2. `빌나 / 지나 / 말파ㅸ온 / 보나ㅸ앙 / 알돈ㅸ앙`을 administrative / polite / dialogue register에 깊게 투입
3. audited master를 750+까지 증설

## 7. 이번 턴 신규 산출물
- `STAGE_F_REGISTER_SPECIFIC_PROMOTION_V1.csv`
- `REGISTER_SPECIFIC_PROMOTION_LEDGER_20260410.csv`
- `REGISTER_SPECIFIC_PROMOTION_REPORT_20260410.md`
- `HIGH_FREQUENCY_DERIVATIONAL_LEXICON_V3.csv`
- `HIGH_FREQUENCY_DERIVATIONAL_LEXICON_V3.md`
- `MASTER_CORPUS_V1_AUDITED_v4.csv`
- `KKANTTAPPIYA_REFERENCE_GRAMMAR_V1_11.md`

---

## 12. 2026-04-10 turn15 update — 보나눌 mini-corpus

- `보나눌`을 poetic/clinical mini-corpus 10행으로 재검증했다.
- 판정:
  - **retain as candidate**
  - **do not promote**
- 이유:
  - 임상/시적 영역에서는 잘 작동한다.
  - 그러나 범용 고빈도 기본 명사로 승격시키기엔 의미장이 너무 좁다.
- 현재 고빈도 파생어 사전 상태:
  - **canon-facing 55**
  - **candidate 1 (`보나눌`)**
- audited master:
  - **720 → 730행**

---

## 13. 2026-04-10 turn16 update — admin/polite/dialogue register expansion

- `빌나 / 지나 / 말파ㅸ온 / 보나ㅸ앙 / 알돈ㅸ앙`을 admin/polite/dialogue register 코퍼스 24행으로 검증했다.
- 결론:
  - 다섯 항목 모두 **stable canon-facing**
  - ordinary speech portability 확인
- 새 Stage:
  - `STAGE_H_ADMIN_POLITE_DIALOGUE_V1.csv` (24행)
- audited master:
  - **730 → 754행**
- Reference Grammar:
  - **v1.13**

---

## 14. 2026-04-10 turn17 update — 800+ corpus threshold crossed

- `STAGE_I_ORDINARY_NARRATIVE_SERVICE_V1.csv` 50행 추가
- ordinary narrative + service dialogue 중심으로 저빈도 canon-facing 파생어를 재배치했다.
- 결과:
  - audited master **754 → 804행**
  - hard fail 0
- Reference Grammar:
  - **v1.14**
- 새 보조 문서:
  - `EARLY_CHAPTER_EXAMPLE_BANK_V1.md`

---

## 15. 2026-04-10 turn18 update — continuous texts + early integration

- `STAGE_J_CONTINUOUS_TEXTS_V1.csv` 30행 추가
- 짧은 연속 서사문 1개 + 서비스 대화문 1개 작성
- 결과:
  - audited master **804 → 834행**
  - hard fail 0
- 새 문서:
  - `CONTINUOUS_TEXTS_V1.md`
  - `EARLY_CHAPTER_EXAMPLE_INTEGRATION_V1.md`
- Reference Grammar:
  - **v1.15**

---

## 16. 2026-04-10 turn19 update — actual rewrite of early chapters

- 실제 본문 rewrite 수행:
  - 서론
  - 1장 음운론
  - 2장 형태음운과 융합
  - 3장 격과 정렬
- 핵심 정리:
  - 초반부를 example-rich tutorial 방식으로 재작성
  - `TRK(=길)`를 core inventory에서 제거
  - core case inventory를 **8격 + TOP**으로 다시 고정
- 새 파일:
  - `EARLY_CHAPTER_REWRITE_V1.md`
  - `EARLY_CHAPTER_ACTUAL_REWRITE_REPORT_20260410.md`
- Reference Grammar:
  - **v1.16**
- audited master:
  - **834행 유지**

---

## 17. 2026-04-10 turn20 update — mid-chapter rewrite + diagnostics

- 실제 본문 rewrite 수행:
  - 4장 명사구 확장
  - 7장 부정
  - 8장 시제·상·양태
  - 9장 증거성
- diagnostic corpus:
  - `STAGE_K_NOMINAL_NEG_EVID_DIAGNOSTICS_V1.csv` 24행
- 결과:
  - audited master **834 → 858행**
  - hard fail 0
- 핵심 정리:
  - 4장에서 quantifier / numeral / comparison / plurality를 example-rich 방식으로 재구성
  - 7장에서 connegative + NEG.AUX 구조를 중심축으로 재정리
  - 8장에서 `-루-`는 aspect가 아니라 voice(INT)라는 SSOT를 재확인
  - 9장에서 동사 내부 EVID와 절 경계 clitic의 이중 구조를 분명히 함
- Reference Grammar:
  - **v1.17**

---

## 18. 2026-04-10 turn21 update — rewrite of chapters 10–13

- 실제 본문 rewrite 수행:
  - 10장 비종결 접미사와 절연쇄
  - 11장 관계절과 보문절
  - 12장 인용과 전청
  - 13장 담화 접속과 정보구조
- diagnostic corpus:
  - `STAGE_L_NONFINITE_QUOT_DISC_DIAGNOSTICS_V1.csv` 24행
- 결과:
  - audited master **858 → 882행**
  - hard fail 0
- 핵심 정리:
  - 10장에서 비종결형의 절연쇄 기능과 반사실 조건을 명확히 함
  - 11장에서 gap 유형 5종과 보문절 논항화를 재정리
  - 12장에서 `=락`과 `=맬`의 층위 차이를 선명화
  - 13장에서 담화 접속사와 정보구조를 discourse steering 관점으로 재서술
- Reference Grammar:
  - **v1.18**

---

## 19. 2026-04-10 turn22 update — chapter 17 + appendices cleanup

- 17장 주석 텍스트를 실제 annotated text 장으로 재작성
  - Text A: 도서관으로 가는 날
  - Text B: 접수대 앞 대화
- 부록 구조를 A–J로 재편
- 중복 제거:
  - Part 7 제목 중복 제거
  - Appendix G 중복 제거
  - scattered addendum을 revision notes 성격으로 재정리
- Reference Grammar:
  - **v1.19**
- audited master:
  - **882행 유지**

---

## 20. 2026-04-10 turn23 update — long-form texts + Chapter 15 alignment

- long-form continuous text 2종 추가:
  - Text C: 전시 준비하는 날
  - Text D: 고치돈 접수대
- `STAGE_M_LONGFORM_CONTINUOUS_TEXTS_V1.csv` 40행 추가
- 핵심 작업:
  - 15장 기본 어휘 actual rewrite
  - 부록 C 요약 사전과 15장 정합화
  - 17장 주석 텍스트와의 어휘군도 맞춤
- audited master:
  - 실파일 기준 **883 → 923행**
- Reference Grammar:
  - **v1.20**
- 보류:
  - `보나눌` specialized candidate 유지

---

## 21. 2026-04-10 turn24 update — 950+ corpus and Chapter 16 reinforcement

- long-form continuous text 2종 추가:
  - Text E: 생활관 앞 밤
  - Text F: 정중한 접수대
- `STAGE_N_LONGFORM_AND_POLITE_LINK_V1.csv` 32행 추가
- 16장 정중성 actual rewrite v2 수행
- 핵심:
  - 정중성을 FRC 기반 기능 확장으로 재서술
  - service dialogue 코퍼스를 16장 anchor example로 직접 연결
- audited master:
  - 실파일 기준 **923 → 955행**
- Reference Grammar:
  - **v1.21**
- 보류:
  - `보나눌` specialized candidate 유지

---

## 22. 2026-04-10 turn25 update — `보나눌` listed-exception 재분류

- 사용자 제안에 따라 `보나눌`의 지위를 재검토했다.
- 결론:
  - `candidate`가 아니라 **listed-exception**
- 이유:
  - ordinary high-frequency noun으로는 아직 과하지만,
  - 임상/시적/지각 잔류 domain에서는 lexicalized 예외 어휘로 충분히 안정적임
- 운영 원칙:
  - 허용 domain: clinical / poetic / perceptual residue
  - productive family 일반화 근거로 사용 금지
- high-frequency derivational lexicon:
  - canon-facing 55
  - candidate 0
  - listed-exception 1 (`보나눌`)
- Reference Grammar:
  - **v1.22**
- audited master:
  - **955행 유지**

---

## 23. 2026-04-10 turn26 update — 1000+ corpus crossed

- long-form continuous text 2종 추가:
  - Text G: 비 뒤 아침 점검
  - Text H: 정중한 보나ㅸ앙 데스크
- `STAGE_O_1000_PLUS_CONTINUOUS_TEXTS_V1.csv` 50행 추가
- audited master:
  - 실파일 기준 **955 → 1005행**
- 17장 주석 텍스트 갱신:
  - Text C / Text D를 실제 본문+주석+학습 포인트 구조로 반영
- 부록 K 추가:
  - listed-exception 운용 규정
- Reference Grammar:
  - **v1.23**
- `보나눌`:
  - listed-exception 유지

---

## 24. 2026-04-10 turn27 update — chapter17 v3 + index/cross-reference

- 새 코퍼스 추가 없음
- audited master:
  - 실파일 기준 **1005행 유지**
- 17장 주석 텍스트 v3:
  - Text A–D 모두를 본문+주석+학습 포인트 구조로 정리
- 새 문서:
  - `GRAMMAR_INDEX_AND_CROSS_REFERENCE_V1.md`
- 부록 K 강화:
  - listed-exception 한 항목이 family 전체 승인 근거가 되지 않음을 명시
- Reference Grammar:
  - **v1.23 유지** (구조 정리 업데이트)

---

## 25. 2026-04-10 turn28 update — remaining tasks closed out

- 새 코퍼스 추가 없음
- audited master:
  - 실파일 기준 **1005행 유지**
- Reference Grammar:
  - **v1.24**
- 완료한 정리 작업:
  - 부록 L: 장별 index / cross-reference
  - 부록 M: 내부 참조와 anchor 정리 규약
  - 0.7 빠른 탐색 추가
- 판단:
  - 남은 필수 정리 작업은 사실상 종료
  - 이후는 선택적 확장 단계
