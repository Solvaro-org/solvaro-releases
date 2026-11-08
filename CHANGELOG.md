# Changelog
Published releases, newest first, summarized from each release's notes. Dates are GitHub `published_at` dates (UTC). Unpublished drafts are listed separately at the end.

## 1.5.2 — 2026-10-28 (Latest)
- Rest of the user-visible Arcus → Solvaro rename (desktop UI, health `service: solvaro`, docs)
- Structured investigation case-file memory
- Installer/exe renamed to Solvaro (`Solvaro-Setup-1.5.2.exe`, `Solvaro.exe`); the notes say the same appId is kept, so auto-update continues
## 1.5.1 — 2026-10-28
- Case-file memory keeps clone and verdict across follow-ups / Close & Summarize
- Retention controls, security page, Freshdesk/Intercom paging
- First-response `created_at` pass-through
## 1.5.0 — 2026-10-28 — Solvaro cutover
- UI, tray, and installer branded Solvaro; the notes say the appId, `arcus://` protocol, and `Arcus` userData folder are kept so 1.4.x installs can auto-update
## 1.4.11 — 2026-10-28 (Arcus)
- Ticket filters, Zendesk progressive load; HubSpot CRM panel; live Zendesk first-reply SLA; Insights impact; fix stale Planning/Working; auto-investigate new tickets
## 1.4.9 — 2026-10-28 (Arcus)
- Cases sidebar shows all open Jira/Zendesk/ServiceNow tickets with refresh; Windows exe icon and product name
## 1.4.8 — 2026-10-28 (Arcus)
- Repo badge, `~/` expansion, and local clone dedupe fixes
## 1.4.7 — 2026-10-27 (Arcus)
- Shows all New/Open/In Progress tickets; resolved tickets limited to 6 months with filters; Cases across ticket systems plus CRM panel
## 1.4.6 — 2026-10-27 (Arcus)
- Fixes chat errors with newer Claude models; multiple AI providers per org
## 1.4.5 — 2026-10-26 (Arcus)
- AI provider step is now optional during setup; backup model picker moved to Settings
## 1.4.4 — 2026-10-26 (Arcus)
- Windows app/taskbar icon fix
## 1.4.3 — 2026-10-26 (Arcus)
- Bundled fixes and a yauzl packaging fix
## 1.4.2 — 2026-10-14 (Arcus)
- Windows + macOS (arm64/Intel) unsigned installers
## 1.4.1 — 2026-07-09 (Arcus)
- Windows, macOS, Linux installers
## 1.4.0 — 2026-07-09 (Arcus)
- Windows, macOS, Linux installers (no release notes)

## Unpublished drafts (not available to users or the updater)
- v1.5.4: Windows + macOS arm64/x64 build (unsigned); publishing is pending a release-owner/QA decision
- v1.5.4-main-f03a1af, v1.5.3-main-5447: CI builds (the second one contains 1.5.4 assets despite its name)
- v1.5.3-ga1: 1.5.3 Win+Mac build with full draft notes (51 PRs)
- v1.5.3: incomplete, has no installer
