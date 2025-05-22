

### 요구기능
- 정해진 날짜에 했는지, 안했는지
- 답변이 yes 인지, no인지
- Level별로

- (지연답변에 대한 상황 고려)
- 근무일수 연동 - 불가 시 공휴일, 주말 제외하고 카운팅되도록 


---
# 2025-05-22 회의내용

## 2025 RBKB special system audit OFI – LPC

[MM-641.19](https://kms.wam-sso.bosch.com/bbmdved/en/mm-641-19-em-layered-process-confirmation-lpc-1031967392.html?artefactId=2ec72cca-0042-407f-82c0-abcbc3a58848)

- LPC Process review에 대한 measure
- Plan, checklist, guide 가 변경될 때 System CIP project review meeting에서 review 해야함. 자료 부족으로 지적됨.

n   1. Updated plan – 첨부자료(implementation)에 기존 Level별 스케쥴을 업데이트 해서 보완. 주 단위 스케쥴 추가

n   2. Checklist – VSQB 질문항목을 추린 checklist 제작. L5 부사장님 confirmation 진행 시 활용. 일정에 맞추어 플래너가 프린트하여 함께 LPC 진행.

n   3. Guide – 기존 매뉴얼 활용. Review 미팅 시 업데이트 사항 있으면 공유

- Measure schedule

n   Action plan **– 2025-06-20**

n   Confirmation of implementation – 2025-08-15

n   유효성 파악 – 2025-11-15

- eLPC 통계자료 활용 방안

n   PowerBI 혹은 Excel 활용하여 review meeting 때 한 눈에 상황을 확인할 수 있는 템플릿 제작 필요.

n   요구사항 명세:

u  정해진 날짜 LPC 진행여부 확인할 수 있어야 함.

u  LPC 질문에 대한 답변이 Yes인지, No 인지 비율, 색깔 등을 활용해 직관적으로 확인할 수 있어야 함.

u  Level별로 위 항목들을 나눠서 확인 할 수 있어야 함.

u  위 항목들을 date timeline으로 필터링 할 수 있어야 하고, 기간 동안의 데이터를 한 번에 확인할 수 있어야 함.

n   고려가 필요한 사항:

u  지연답변 (ex. 월요일에 LPC 진행을 못해서 화요일에 LPC를 진행한 상황)에 대한 고려

u  실제 근무일수에 대한 연동 – 공휴일, 라인휴무, 주말 등 LPC 일정은 등록되어 있으나 진행할 필요가 없는 상황 고려

## L4, L5 추가 세팅

- L4(상무) – 일정 항목에 선택 참석자 추가 _ T.L, 직장, planner, (반장)
- L5(부사장) –

n   일정 항목에 필수 참석자 추가 _ 플래너

n   일정 항목에 추가 참석자 추가 _ HoD, T.L, 직장, planner, (반장)

n   L5 confirmation 진행 시, checklist 프린트하여 부사장님과 confirmation 진행.