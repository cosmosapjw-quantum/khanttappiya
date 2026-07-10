# 깐따삐야어 RC3.9 공개핵 문법 — 학습자용 정리본

## 0. 읽는 법

이 문서는 RC3.9 공개핵을 배우기 위한 정리본이다. 내부 검토 이력은 빼고, 실제로 학습자가 써야 하는 규칙만 남겼다. 예문 ID(`RC3-####`)는 안정 참조를 위해 보존한다.

예문은 네 줄 형식으로 읽는다.

```text
자연 표기
분석 표기
gloss
자유 번역
```

분석 표기에서 접사는 `-`, clitic은 `=`로 표시한다. 자연 표기에서는 경계 표시를 쓰지 않는다.

## 1. 기본 어순과 격

깐따삐야어의 기본 절은 동사가 끝에 온다. 자동사 S와 타동사 P는 절대격 `∅`, 타동사 A는 능격 `-스`를 받는다.

**예문 RC3-0011 / RC3-TXT-0001**

```text
아누스 치세 열루
아누-스 치세-∅ 열=루
Anu-ERG house-ABS open=DECL
“아누가 집을 연다.”
```

가능, 상태, 부정, 시제는 타동 A를 지우지 않는다. 타동 어근이 A와 P를 요구하면 A `-스`는 계속 유지된다.

## 2. 결합가와 태

기본 타동문은 `A-스 P-∅ V`이다. 결합가를 바꾸는 장치는 제한되어 있다.

| 장치 | 기능 | 핵심 효과 |
|---|---|---|
| `-누` | 중간/수렴 | P가 S처럼 표면화될 수 있음 |
| `-흐` DIF.ANTIP | 반수동 독법 | bounded P를 억제하고 A-like participant를 S처럼 표면화 |
| `-흐` DIF.EMIT | 방출/드러남 | source/theme이 장으로 드러남 |
| SELF.CAUS | 자기 원인화 | 별도 등재 구문 |

`-흐`는 표면형 하나지만 gloss와 독법에서 `DIF.ANTIP`와 `DIF.EMIT`을 구별한다.

## 3. 부정과 가능

일반 부정은 `ROOT-CNEG NEG-TENSE=FINAL`이다. 가능 부정의 기본 작용역은 `NEG > POT`이다.

**예문 RC3-0038a**

```text
쿠안스 열실 열헷무 니랏루
쿠안-스 열-실-∅ 열-헷-무 니-랏=루
1SG-ERG open-PATH-ABS open-POT-CNEG NEG-PAST=DECL
“나는 입구를 열 수 없었다.”
```

부정 명령은 새 금지 표지를 만들지 않고 같은 부정 구조에 명령 종결을 붙인다.

**예문 RC3-0125**

```text
걸무 니얀
걸-무 니=얀
walk-CNEG NEG=IMP
“걷지 마라.”
```

**예문 RC3-0157**

```text
에안스 열실 열얀
에안-스 열-실-∅ 열=얀
2SG-ERG open-PATH-ABS open=IMP
“너는 입구를 열어라.”
```

## 4. 종결과 절경계 clitic

기본 종결 clitic은 `=루` DECL, `=호` YNQ, `=셴` WHQ, `=얀` IMP이다. 이들은 같은 FINAL slot의 대안이므로 서로 쌓지 않는다. 전청·인용 edge clitic은 RC3.9 공개핵에서 평서 `=루` 뒤에 붙는 형식만 실증되어 있다. 이것은 final stacking이 아니라 edge marking이다. `=호`, `=셴`, `=얀` 뒤에 바로 `=헌`/`=두`를 붙이는 형식은 별도 확장 전까지 쓰지 않는다.

| 기능 | 형식 | 예 |
|---|---|---|
| 평서 | `=루` | `걸=루` |
| 예/아니오 의문 | `=호` | `에안 걸=호` |
| 의문사 의문 | `=셴` | `마사름 걸=셴` |
| 명령 | `=얀` | `걸=얀` |
| 전청 edge | `=헌` | `열=루=헌` |
| 인용 edge | `=두` | `열=루=두` |

## 5. WHQ

`=셴`은 WH 어휘와 함께 쓴다. WH 어휘가 타동 A 자리에 오면 일반 A처럼 `-스`를 받는다. WH 어휘 없이 `=셴`만 붙인 bare WHQ는 허용하지 않는다.

| WH 어휘 | 의미 | 예 |
|---|---|---|
| `마사름` | 누가/누구 | `마사름 걸셴` |
| `마담` | 무엇/어떤 내용 | `쿠안스 마담 에라만앋셴` |
| `마테` | 어디/어느 위치 | `에안 마테 걸셴` |

**예문 RC3-0155**

```text
마사름스 열실 열셴
마사름-스 열-실-∅ 열=셴
WH.PERSON-ERG open-PATH-ABS open=WHQ
“누가 입구를 여느냐?”
```

## 6. 소유

소유는 새 격 없이 `POSSESSOR HEAD-CASE`로 표시한다. 소유자가 아니라 head 명사가 절 안의 격을 받는다.

**예문 RC3-0098**

```text
쿠안 벗스 시눔 누카라루
쿠안 벗-스 시눔-∅ 누카라=루
1SG.POSS friend-ERG 3SG-ABS see=DECL
“내 친구가 그를 본다.”
```

`=겨`는 소유 표지가 아니다. recipient/interface 표지와 소유 명사구는 분리한다.

## 7. `=겨`와 core case

`=겨`는 ERG/ABS를 대체하지 않는다. 같은 host에서는 core case가 먼저 붙고 clitic이 뒤에 붙는다.

**예문 RC3-0118**

```text
아누스겨 치세 열루
아누-스=겨 치세-∅ 열=루
Anu-ERG=FRC house-ABS open=DECL
“아누가 완충된/접촉면이 표시된 행위자로서 집을 연다.”
```

`*아누=겨-스`처럼 clitic 뒤에 case를 붙일 수 없다.

## 8. 관계절 head 전략

관계절 head 전략은 세 가지를 분리해서 배운다.

| Head type | 표지 전략 | 관계절 내부 보존 | 금지되는 것 |
|---|---|---|---|
| Theme/P head | bare ABS 또는 matrix case | A와 recipient/interface 보존 | theme resumptive, theme head에 `=겨` |
| FRC/interface head | `HEAD-CASE=겨` | A와 theme 보존, interface gap | bare interface head, `=겨` 뒤 case |
| Ordinary recipient head | `HEAD-CASE=겨` | A와 theme 보존, recipient gap | bare recipient head, theme omission |

### 8.1 Theme/P head

**예문 RC3-0107**

```text
아누스 에안겨 코레울 에라만담굳둠 므겁누루
아누-스 에안=겨 코레=울 에라만-담-굳-둠-∅ 므겁-누=루
Anu-ERG 2SG=FRC give=ADN know-CONTENT-CONDENSE-STORE-ABS heavy-CVG=DECL
“아누가 너에게 준 책/지식 저장물이 무겁다.”
```

### 8.2 FRC/interface head

**예문 RC3-0134**

```text
쿠안스 열실 헨두겨울 누카라굳믓겨 므겁누루
쿠안-스 열-실-∅ 헨두-겨=울 누카라-굳-믓-∅=겨 므겁-누=루
1SG-ERG open-PATH-ABS say-PRED.FRC=ADN see-CONDENSE-SINK-ABS=FRC heavy-CVG=DECL
“내가 입구를 설명하는 데 쓰는 시각 자료가 무겁다.”
```

### 8.3 Ordinary recipient head

**예문 RC3-0144**

```text
아누스 헨두담 코레울 쿠안겨 걸루
아누-스 헨두-담-∅ 코레=울 쿠안-∅=겨 걸=루
Anu-ERG say-CONTENT-ABS give=ADN 1SG-ABS=FRC walk=DECL
“아누가 말해진 내용을 전한 대상인 내가 걷는다.”
```

## 9. 공개핵 경계

이 정리본은 WHQ, 소유, theme-head, FRC/interface-head, ordinary recipient-head, ERG+=겨 경계, 부정 명령까지를 다룬다. 소유자 추출, locative extraction, adjunct-head 관계절, 추가 final clitic은 별도 확장 없이는 사용하지 않는다.
