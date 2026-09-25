# NEPES Semiconductor Packaging Industry Field Study

2026년 9월 18–19일 진행한 산업시찰에서 **NEPES(네패스)**와 **현대제철**의 실제 제조 현장을 방문하고, 현장 설명을 통해 제조 공정·설비·품질·물류가 어떻게 연결되는지 관찰한 field-study project입니다.

두 기업 모두 대규모 제조업이라는 공통점이 있었지만, 이 저장소는 반도체 공정/양산/품질 직무를 희망하는 관점에서 **NEPES 경험을 중심으로 약 80%**, 현대제철 경험을 제조 시스템 비교 관점에서 약 20% 비중으로 정리했습니다.

NEPES에서는 첨단 반도체 후공정과 공정 소재를 중심으로, 방문 후 추가 조사를 통해 다음 흐름을 연결했습니다.

- Bumping / RDL
- WLP
- FOWLP / PLP / PoP
- SiP
- Test
- Developer / Cu electroplating / stripper / etchant
- equipment condition control
- SPC / defect improvement
- yield / productivity
- quality change control

> This repository distinguishes direct field observation from post-visit company research and career interpretation. It does not claim that I personally operated production equipment or performed process experiments during the visit.

---

## Field Visit at a Glance

| Item | Details |
|---|---|
| Period | 2026.09.18–19 |
| Companies | NEPES · Hyundai Steel |
| Main portfolio focus | NEPES semiconductor packaging / process materials |
| Observation type | company tour + production-site observation + employee explanation |
| Engineering lens | Process · Manufacturing · Quality · Equipment |
| NEPES research focus | Advanced packaging, Cu plating, developer, RDL, yield, SPC |
| Hyundai Steel role | Large-scale continuous manufacturing comparison |

---

## Why NEPES Was the Main Focus

NEPES officially provides semiconductor back-end solutions across:

- Bumping
- WLP
- FOWLP / PLP / PoP
- SiP
- Test

and describes itself as providing full turnkey packaging solutions including 8-inch / 12-inch flip-chip bumping and test.

Its WLP flow also combines **bumping and redistribution layer(RDL)** processing at wafer level, while FOWLP/PLP expands I/O beyond the chip area for higher-density packaging.

This made the visit especially relevant because advanced packaging sits directly at the intersection of:

```text
Material
   ↓
Lithography / Wet Process
   ↓
Cu RDL / Bump
   ↓
Equipment
   ↓
Inspection / Test
   ↓
Yield / Reliability
   ↓
Final Package
```

---

## What I Connected After the Visit

### 1. Packaging Is a Manufacturing System, Not a Single Process

A package is not completed by one unit process.

For example, a Cu redistribution / bump structure can require:

- dielectric formation
- photoresist coating / patterning
- developer
- metal seed / sputtering
- Cu electroplating
- photoresist stripping
- metal etching
- cleaning
- inspection
- electrical test

A defect or variation at any step can propagate into downstream yield.

The industrial visit therefore helped me view packaging from a **process-integration and mass-production perspective** rather than as a package-structure diagram.

---

## 2. NEPES Process Chemicals

NEPES also supplies semiconductor / display process chemicals.

### Developer

Official product:
**CPD-series**

Role:
high-purity photoresist developer used after lithography to realize fine patterns.

### Cu Electroplating

Official product:
**Damascene-series**

NEPES states that the product can be applied to plating equipment from Lam, Applied Materials, TEL, and Ebara.

### Other Materials

- NDP-series organic insulator
- BMS-series PR stripper
- BCE / BTE / GME-series metal etchants

This was particularly meaningful because advanced packaging links **materials engineering directly to electrical interconnect formation**.

---

## 3. Why Cu Plating Matters in Packaging

Cu electroplating can be used for structures such as:

- RDL
- Cu pillar bump
- TSV-related metallization
- high-density interconnect

The manufacturing challenge is not only depositing Cu.

Mass production requires control of:

- plating-bath condition
- deposition uniformity
- feature filling
- interface adhesion
- residue
- undercut
- process margin
- equipment stability

NEPES's current 8-inch process-engineering recruitment page explicitly lists:

- plating-solution analysis and management
- defect-improvement evaluation
- statistical process control
- abnormal-product handling
- defect root-cause analysis for yield improvement

as actual duties.

This made the connection between the industrial visit and semiconductor process-engineering work much clearer.

---

## 4. Equipment Engineering & Mass-Production Stabilization

NEPES's current advanced-packaging equipment roles include:

- equipment setup
- maintenance / preventive maintenance
- abnormality response
- equipment-condition optimization
- yield / productivity improvement
- new-equipment installation and verification
- production stabilization
- collaboration across process / quality / production teams

This is close to the type of work I want to prepare for.

The visit helped me understand that equipment engineers are not only responsible for fixing machines.

They also affect:

```text
Equipment condition
       ↓
Process stability
       ↓
Defect rate
       ↓
Yield / productivity
       ↓
Mass-production competitiveness
```

---

## 5. Quality Engineering & Change Control

NEPES's semiconductor quality recruitment materials describe work including:

- internal quality verification
- change-point management
- prevention of quality issues
- customer quality response

This connects directly to a key lesson from the visit:

**mass production must control not only the nominal process recipe, but also changes.**

Potential change points include:

- equipment replacement
- chemical lot
- recipe revision
- supplier material
- maintenance
- process sequence
- operator / production condition

A technically small change can become a customer-quality issue if it is not verified and traced properly.

---

## NEPES Manufacturing Loop

```text
Incoming Material
      ↓
Lithography / Wet Chemical
      ↓
Cu Plating / RDL / Bump
      ↓
Package Integration
      ↓
Inspection / Test
      ↓
SPC & Defect Analysis
      ↓
Yield / Productivity Improvement
      ↓
Change Control
      ↓
Stable Mass Production
```

![NEPES manufacturing loop](./figures/nepes-manufacturing-loop.svg)

---

## Hyundai Steel — What I Learned from a Large-Scale Production Site

현대제철에서는 실제 생산이 이루어지는 공장 내부에 들어가 **고온의 쇳물/철강 반제품이 만들어지고 다음 공정으로 이동하는 대규모 연속 생산 흐름**을 직접 관찰했습니다.

현대제철 공식 일관제철 공정은 다음과 같이 정리됩니다.

```text
Iron ore / Coal
      ↓
Sinter / Coke
      ↓
Blast Furnace
      ↓
Molten Iron
      ↓
Torpedo Car
      ↓
Converter / Refining
      ↓
Continuous Casting
      ↓
Slab
      ↓
Rolling
      ↓
Steel Product
```

특히 molten iron은 **torpedo car**를 이용해 다음 steelmaking process로 운반됩니다.

### Why This Was Useful Even for a Semiconductor Career

산업은 다르지만 실제 제조현장에서 다음 공통점을 볼 수 있었습니다.

- material flow cannot stop independently of production scheduling
- equipment uptime strongly affects throughput
- process stages are tightly coupled
- intermediate product movement is part of manufacturing
- safety / standard operation are inseparable from productivity
- an upstream abnormality can affect downstream quality

이를 반도체 fab / packaging line과 비교하면:

| Steel manufacturing | Semiconductor manufacturing |
|---|---|
| molten material / slab flow | wafer / lot flow |
| furnace / converter / rolling equipment | process / packaging equipment |
| composition / temperature control | recipe / chemical / equipment-condition control |
| continuous production | lot-based mass production |
| inspection / specification | metrology / test / quality control |

두 산업의 scale과 process physics는 다르지만, **stable flow + equipment reliability + process control + quality assurance**가 제조 경쟁력의 핵심이라는 점은 공통적으로 느꼈습니다.

---

## My Career Takeaways

### Process Engineering

공정기술은 단순히 recipe를 이해하는 것이 아니라:

- material behavior
- chemical condition
- equipment state
- defect mechanism
- SPC
- downstream interaction

을 함께 봐야 하는 직무라고 이해했습니다.

### Mass-Production Engineering

양산의 목표는 최고 성능을 한 번 얻는 것이 아니라 **같은 품질을 반복적으로 생산하는 것**입니다.

중요한 관점:

- repeatability
- process window
- equipment stability
- throughput
- yield
- change control

### Quality Engineering

품질은 최종 검사에서만 만들어지는 것이 아니라 공정 중간 단계부터 쌓입니다.

```text
Change detection
      ↓
Verification
      ↓
Defect prevention
      ↓
Traceability
      ↓
Customer quality
```

### Equipment Companies

NEPES의 장비직무 내용을 조사하면서 장비사 지원 시에도 다음 경험과 연결할 수 있다고 느꼈습니다.

- equipment setup / qualification
- preventive maintenance
- troubleshooting
- process-condition optimization
- customer production stabilization
- cross-functional communication

---

## Read the Project

| Page | Description |
|---|---|
| [Project Page](./index.html) | 산업시찰 전체 요약 |
| [Navigation](./guide/00_navigation.md) | 전체 문서 안내 |
| [Visit Context](./guide/01_visit_context.md) | 직접 관찰한 산업시찰 범위 |
| [NEPES Overview](./guide/02_nepes_packaging.md) | 첨단 후공정과 패키징 |
| [Process Materials](./guide/03_process_materials.md) | Developer · Cu plating · wet chemicals |
| [Mass Production](./guide/04_mass_production.md) | 장비·SPC·수율·생산성 |
| [Quality Engineering](./guide/05_quality_change_control.md) | 품질검증·변경점 관리 |
| [Hyundai Steel](./guide/06_hyundai_steel.md) | 대규모 연속제조 관찰 |
| [Engineering Takeaways](./guide/07_career_takeaways.md) | 공정·양산·품질·장비 직무 연결 |
| [Evidence Scope](./guide/08_evidence_scope.md) | 현장 관찰과 사후조사 구분 |
| [References](./references/README.md) | 공식 기업·채용 자료 |

---

## Structured Analysis

- [nepes_process_map.csv](./results/nepes_process_map.csv)
- [career_relevance_matrix.csv](./results/career_relevance_matrix.csv)
- [industrial_manufacturing_comparison.csv](./results/industrial_manufacturing_comparison.csv)

These are portfolio-organized analysis tables, not company production data.

---

## Repository Structure

```text
NEPES-Semiconductor-Packaging-Industry-Field-Study/
├── README.md
├── index.html
├── index.md
├── _config.yml
├── assets/
├── figures/
├── guide/
├── results/
├── study/
├── references/
├── appendix/
├── source/
└── report/
```

---

## Scope

This repository separates:

1. **Direct industrial visit experience**
2. **Official company / recruitment information researched after the visit**
3. **My career interpretation for semiconductor process / manufacturing / quality roles**

No claim is made that I personally operated NEPES equipment, analyzed production chemicals, or participated in Hyundai Steel production control.

---

[← Back to Subin Joo's GitHub Portfolio](https://github.com/soybeanmilk0514-jpg)
