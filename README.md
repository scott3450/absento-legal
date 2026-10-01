# absento-legal

Absento's one public page: support questions and the privacy policy, in a single
self-contained `index.html` (English) and `tr/index.html` (Turkish); keep the two in step. Kept outside the app repository on purpose.

## Publishing

Public repository `scott3450/absento-legal` (only this page, never app code — owner's rule,
1 Oct 2026). GitHub ▸ Settings ▸ Pages ▸ Deploy from a branch ▸ `main`, `/ (root)`.
Edit here, commit, `git push`; Pages redeploys on its own.

| App Store Connect field | URL |
|---|---|
| Support URL | `https://scott3450.github.io/absento-legal/` |
| Privacy Policy URL | `https://scott3450.github.io/absento-legal/#privacy` |
| Turkish (App Store Connect ▸ Turkish localization) | `…/absento-legal/tr/` · `…/tr/#privacy` |

The app links the same two addresses (Settings ▸ About, `LegalPage` in
`UniAbsent/Features/Settings/SettingsView.swift`).

## Rules

- No outbound links, no `FUNDING.yml`, no Sponsor button (guidelines 2.3.10, 3.1.1).
- Keep the URL stable after submission.
- The text must agree with the App Privacy label: "Data Not Collected". In-app purchases
  handled by Apple do not change that answer; Absento keeps only a yes/no Pro flag.
- When Pro's scope, price model or Family Sharing changes, update "What is Absento Pro?"
  and the date under Privacy Policy.
