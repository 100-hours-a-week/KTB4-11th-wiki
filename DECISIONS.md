# Decision Log

이 문서는 팀에서 **합의되어 확정된** 제품·기술·운영 결정을 기록합니다. 논의 중인 내용은 이슈나 회의 문서에 먼저 남기고, 합의 후 이곳에 기록합니다.

## Status

- **Proposed**: 논의 중이며 아직 팀 합의가 아님
- **Accepted**: 팀이 채택한 결정
- **Superseded**: 이후 결정으로 대체됨

---

## 2026-08-29 — Shared knowledge-base repository

- **Status:** Accepted
- **Context:** 기획 전담자가 없는 6인 개발팀이 프로젝트 맥락과 합의 사항을 일관되게 관리할 공용 기록이 필요하다.
- **Decision:** `100-hours-a-week/KTB4-11th-wiki`를 팀의 공유 지식베이스로 사용한다. Discord 기반 팀 어시스턴트 **죠르디**가 논의 맥락을 정리하고, 확정된 내용은 PR을 통해 저장소에 반영한다.
- **Rationale:** 팀원이 동일한 최신 의사결정 기록을 확인할 수 있고, 변경 이력과 검토 과정이 GitHub에 남는다.
- **Owners:** Team
- **Follow-up:** GitHub Issues와 Pull Requests 이벤트를 죠르디에게 전달하는 webhook을 설정한다.
