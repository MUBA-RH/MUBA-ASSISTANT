# MUBA-ASSISTANT module map

Architecture source: [MUBA/architecture/02-assistant](https://github.com/MUBA-RH/MUBA/tree/main/architecture/02-assistant). Active code and deployment remain at their current locations. Listed areas are ownership boundaries, not evidence of an implemented standalone service.

| Area | Responsibility |
| --- | --- |
| [01-MUBA-ASK](modules/01-MUBA-ASK/CONTENT/README.md) | Module boundary |
| ↳ [FLOW-01-MUBA-YI-TANI](modules/01-MUBA-ASK/flows/FLOW-01-MUBA-YI-TANI/CONTENT/README.md) | Flow of 01-MUBA-ASK |
| ↳ ↳ [ORIGIN](modules/01-MUBA-ASK/flows/FLOW-01-MUBA-YI-TANI/ORIGIN/CONTENT/README.md) | Subflow of FLOW-01-MUBA-YI-TANI |
| ↳ ↳ [IDENTITY](modules/01-MUBA-ASK/flows/FLOW-01-MUBA-YI-TANI/IDENTITY/CONTENT/README.md) | Subflow of FLOW-01-MUBA-YI-TANI |
| ↳ [FLOW-02-MUBA-YI-ANLA](modules/01-MUBA-ASK/flows/FLOW-02-MUBA-YI-ANLA/CONTENT/README.md) | Flow of 01-MUBA-ASK |
| ↳ ↳ [DIFFERENCE](modules/01-MUBA-ASK/flows/FLOW-02-MUBA-YI-ANLA/DIFFERENCE/CONTENT/README.md) | Subflow of FLOW-02-MUBA-YI-ANLA |
| ↳ ↳ [PURPOSE](modules/01-MUBA-ASK/flows/FLOW-02-MUBA-YI-ANLA/PURPOSE/CONTENT/README.md) | Subflow of FLOW-02-MUBA-YI-ANLA |
| ↳ [FLOW-03-MUBA-DUNYASI](modules/01-MUBA-ASK/flows/FLOW-03-MUBA-DUNYASI/CONTENT/README.md) | Flow of 01-MUBA-ASK |
| ↳ ↳ [COMMUNITY](modules/01-MUBA-ASK/flows/FLOW-03-MUBA-DUNYASI/COMMUNITY/CONTENT/README.md) | Subflow of FLOW-03-MUBA-DUNYASI |
| ↳ ↳ [FUTURE](modules/01-MUBA-ASK/flows/FLOW-03-MUBA-DUNYASI/FUTURE/CONTENT/README.md) | Subflow of FLOW-03-MUBA-DUNYASI |
| [02-CONVERSATION](modules/02-CONVERSATION/CONTENT/README.md) | Module boundary |
| ↳ [LANGUAGE-DETECTION](modules/02-CONVERSATION/flows/LANGUAGE-DETECTION/CONTENT/README.md) | Subflow of 02-CONVERSATION |
| ↳ [CONTEXT](modules/02-CONVERSATION/flows/CONTEXT/CONTENT/README.md) | Subflow of 02-CONVERSATION |
| ↳ [CONTINUITY](modules/02-CONVERSATION/flows/CONTINUITY/CONTENT/README.md) | Subflow of 02-CONVERSATION |
| ↳ [NATURAL-RESPONSE](modules/02-CONVERSATION/flows/NATURAL-RESPONSE/CONTENT/README.md) | Subflow of 02-CONVERSATION |
| [03-CAMERA](modules/03-CAMERA/CONTENT/README.md) | Module boundary |
| ↳ [IMAGE-INTAKE](modules/03-CAMERA/flows/IMAGE-INTAKE/CONTENT/README.md) | Subflow of 03-CAMERA |
| ↳ [USER-REQUEST](modules/03-CAMERA/flows/USER-REQUEST/CONTENT/README.md) | Subflow of 03-CAMERA |
| ↳ [IMAGE-PROCESSING](modules/03-CAMERA/flows/IMAGE-PROCESSING/CONTENT/README.md) | Subflow of 03-CAMERA |
| ↳ [RESULT-DELIVERY](modules/03-CAMERA/flows/RESULT-DELIVERY/CONTENT/README.md) | Subflow of 03-CAMERA |
| [04-KNOWLEDGE-ACCESS](modules/04-KNOWLEDGE-ACCESS/CONTENT/README.md) | Module boundary |
| ↳ [OFFICIAL-KNOWLEDGE](modules/04-KNOWLEDGE-ACCESS/flows/OFFICIAL-KNOWLEDGE/CONTENT/README.md) | Subflow of 04-KNOWLEDGE-ACCESS |
| ↳ [SOURCE-POLICY](modules/04-KNOWLEDGE-ACCESS/flows/SOURCE-POLICY/CONTENT/README.md) | Subflow of 04-KNOWLEDGE-ACCESS |
| ↳ [CURRENT-INFORMATION](modules/04-KNOWLEDGE-ACCESS/flows/CURRENT-INFORMATION/CONTENT/README.md) | Subflow of 04-KNOWLEDGE-ACCESS |
| [05-DAILY](modules/05-DAILY/CONTENT/README.md) | Module boundary |
| ↳ [REQUEST](modules/05-DAILY/flows/REQUEST/CONTENT/README.md) | Subflow of 05-DAILY |
| ↳ [PREPARE](modules/05-DAILY/flows/PREPARE/CONTENT/README.md) | Subflow of 05-DAILY |
| ↳ [RESPONSE](modules/05-DAILY/flows/RESPONSE/CONTENT/README.md) | Subflow of 05-DAILY |
| [06-NEWS](modules/06-NEWS/CONTENT/README.md) | Module boundary |
| ↳ [REQUEST](modules/06-NEWS/flows/REQUEST/CONTENT/README.md) | Subflow of 06-NEWS |
| ↳ [SOURCE-VALIDATION](modules/06-NEWS/flows/SOURCE-VALIDATION/CONTENT/README.md) | Subflow of 06-NEWS |
| ↳ [RESPONSE](modules/06-NEWS/flows/RESPONSE/CONTENT/README.md) | Subflow of 06-NEWS |
| [07-PRICE](modules/07-PRICE/CONTENT/README.md) | Module boundary |
| ↳ [REQUEST](modules/07-PRICE/flows/REQUEST/CONTENT/README.md) | Subflow of 07-PRICE |
| ↳ [DATA-VALIDATION](modules/07-PRICE/flows/DATA-VALIDATION/CONTENT/README.md) | Subflow of 07-PRICE |
| ↳ [RESPONSE](modules/07-PRICE/flows/RESPONSE/CONTENT/README.md) | Subflow of 07-PRICE |
| [08-HUMAN-CONVERSATION](modules/08-HUMAN-CONVERSATION/CONTENT/README.md) | Module boundary |
| ↳ [INPUT](modules/08-HUMAN-CONVERSATION/flows/INPUT/CONTENT/README.md) | Subflow of 08-HUMAN-CONVERSATION |
| ↳ [CONTEXT](modules/08-HUMAN-CONVERSATION/flows/CONTEXT/CONTENT/README.md) | Subflow of 08-HUMAN-CONVERSATION |
| ↳ [RESPONSE](modules/08-HUMAN-CONVERSATION/flows/RESPONSE/CONTENT/README.md) | Subflow of 08-HUMAN-CONVERSATION |
| [09-TELEGRAM-UI](modules/09-TELEGRAM-UI/CONTENT/README.md) | Module boundary |
| ↳ [LANGUAGE-MENU](modules/09-TELEGRAM-UI/flows/LANGUAGE-MENU/CONTENT/README.md) | Subflow of 09-TELEGRAM-UI |
| ↳ [MAIN-MENU](modules/09-TELEGRAM-UI/flows/MAIN-MENU/CONTENT/README.md) | Subflow of 09-TELEGRAM-UI |
| ↳ [CALLBACK-ROUTING](modules/09-TELEGRAM-UI/flows/CALLBACK-ROUTING/CONTENT/README.md) | Subflow of 09-TELEGRAM-UI |
| ↳ [NAVIGATION](modules/09-TELEGRAM-UI/flows/NAVIGATION/CONTENT/README.md) | Subflow of 09-TELEGRAM-UI |

Each area has CONTENT / UPDATE / TEST / STABLE. See [LIFECYCLE.md](LIFECYCLE.md). No new Render service, Telegram bot, token, key, Vault, or deployment trigger is created here.
