# PatientMgmtSys

Monorepo containing the Patient Management system and a `demo/` Spring Boot example application.

## demo/

- Location: `demo/` (Spring Boot Gradle project)
- How to run locally (from the repository root):
  - cd demo
  - ./gradlew bootRun
  - App URL: http://localhost:8080
  - H2 console (if enabled in `application.properties`) : http://localhost:8080/h2-console

## Branches & PRs

- Demo was added on branch `feature/v1/pkr`.
- Please open a Pull Request from `feature/v1/pkr` → `main` or a `release/*` branch.
- Branch protection requires at least 1 reviewer and dismisses stale approvals on push.

## Next steps

- Open a PR to start code review. Authenticate locally with `gh auth login` and run `gh pr create`, or open a PR via the GitHub web UI. Do not share personal access tokens or GitHub CLI authentication with external tools or services.  
- Add CI checks for `demo/` (Gradle/Maven workflows) if desired.

---

(Generated/updated by automation)