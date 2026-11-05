# autohitech

회사 SCADA · 보드 · 웹 운영 조직. 현장 프로젝트 아카이브 + 현행 제품 위주.

## 지도 (2026-11-06 기준, 총 415)

| 구분 | 저장소 | 비고 |
|---|---|---|
| 쇼케이스 (public) | [`nuriscada`](https://github.com/autohitech/nuriscada) | 무료 오픈소스 크로스플랫폼 SCADA (Rust, Apache-2.0) |
| 현행 제품 | `autobase-rea`, `AHT-SCADA-X`, `autohitech-web`, `autohitech-legacy`, `autohitech-drive`, `atech.biz`, `atech-drive` | 웹·드라이브·현행 SCADA |
| 하드웨어 | `SCB-008A`, `SCB-4KEY-BUTTONS`, `SCB-AIW`, `SCB-ES01/ES12`, `SCB-STANDARD-A/B`, `SCM-AI/AO/DI/DO/PWR/RTD` | 보드·모듈 (13종) |
| 공통 | `modbus-source-code`, `modbus-debug-tool`, `docker-hsqldb`, `legacy`, `business-card`, `certifications` | 프로토콜·인프라·문서 |
| 아카이브 후보 | `AHT-SCADA-*` 385개 + 원형 3개 (`AHT-SCADA`, `-1`, `-10`) | 2004~2025 현장 프로젝트, archive 예정 (보류 중) |

전체 목록: `autohitech-audit-2026-11-06.csv` (org audit 산출물, 별도 보관).

## 규칙

- 신규 repo: `제품명-연도` 형식만. `AHT-SCADA-N` 번호 증식 금지.
- `main` 직접 푸시 금지, PR 필수 (현행 repo부터).
- 토픽 필수: `aht` + `active|archive|showcase` + `scada|board|modbus|web` 등.
- description 1줄 필수: "용도 + 상태".
- 현장 키·DB 접속정보는 repo secrets 금지 → org/environment secrets로 (admin 승인 후).

## 문의

- 현행 제품 이슈: 각 repo Issues.
- 보안: `SECURITY.md` 참고 (공개 이슈에 취약점·키 금지).
