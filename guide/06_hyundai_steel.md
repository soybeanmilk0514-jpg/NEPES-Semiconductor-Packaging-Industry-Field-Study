# 06. Hyundai Steel — Large-Scale Manufacturing Observation

## What I Directly Observed

현대제철에서는 실제 생산이 진행되는 공장 내부에 들어가, 고온의 쇳물 / 철강 반제품이 만들어지고 공정 사이를 이동하는 제조 흐름을 관찰했다.

대규모 장비와 물류가 실제로 연결되어 움직이는 모습은 반도체 cleanroom과는 전혀 다른 scale이었지만, manufacturing system 관점에서는 공통점이 많았다.

## Official Integrated Steelmaking Flow

Hyundai Steel의 공식 일관제철 공정:

1. iron ore / coal
2. sintering / coke preparation
3. blast furnace
4. molten iron
5. torpedo car
6. pre-treatment
7. converter
8. refining
9. continuous casting
10. slab
11. reheating / rolling
12. final steel product

Torpedo car는 molten iron을 다음 steelmaking stage로 운반한다.

## What Stood Out

### Process Continuity

앞 공정 결과가 다음 공정 input이 된다.

따라서 upstream delay / abnormality가 downstream productivity에 영향을 준다.

### Material Flow

제품만 만드는 것이 아니라 intermediate material을 **언제, 어디로, 어떤 상태로 이동시킬지**도 생산 시스템의 일부다.

### Equipment Scale & Reliability

대형 furnace / transport / casting / rolling equipment는 downtime impact가 매우 크다.

### Safety

고온 material과 대형 equipment가 움직이는 환경에서는 standard procedure와 safety discipline이 생산성과 분리될 수 없다.

## Semiconductor Comparison

| Hyundai Steel | Semiconductor / Packaging |
|---|---|
| molten iron / slab flow | wafer / lot flow |
| furnace / converter | process equipment |
| composition / temperature | recipe / chemical / chamber condition |
| continuous casting | repeated process module |
| rolling dimensions | CD / thickness / bump geometry |
| final inspection | metrology / electrical test |
| plant logistics | lot dispatch / WIP management |

두 산업의 physics는 다르지만 **flow, equipment reliability, process control, quality assurance**가 함께 움직여야 한다는 점은 공통적이다.
