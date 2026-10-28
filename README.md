# fuelvo-legal

Redirects only. The pages that lived here (a support page and the privacy policy, in English and
Spanish) moved to https://fuelvo.app, the site built from `fuelvo-web`:

| Here                     | Now                                 |
| ------------------------ | ----------------------------------- |
| `/fuelvo-legal/`         | https://fuelvo.app/soporte/         |
| `/fuelvo-legal/privacy/` | https://fuelvo.app/en/privacy/      |
| `/fuelvo-legal/es/`      | https://fuelvo.app/soporte/         |
| `/fuelvo-legal/es/privacy/` | https://fuelvo.app/privacidad/   |

Never delete this repository or turn off its GitHub Pages: app builds 1.0 and 1.1 link here
(`LegalLinks` in fuelvo-app), and so may the store listings. Each page is a `<meta http-equiv="refresh">`
plus `rel="canonical"`, since GitHub Pages cannot send a 301. The policy itself is edited in
`fuelvo-web` now (`src/pages/privacidad/`, `src/pages/en/privacy/`).
