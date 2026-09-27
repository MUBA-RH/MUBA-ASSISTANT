# Documentation lifecycle

Every module and nested flow has CONTENT, UPDATE, TEST, STABLE.

STABLE 🛡️🔒 → UPDATE / WORK → TEST → PASS → NEW STABLE 🛡️🔒.

CONTENT records current scope. UPDATE holds proposals. TEST records review and evidence. STABLE records the last approved documentation baseline only; it does not certify that a feature exists or a deployment is healthy. On FAIL, STOP + REPORT and retain the previous stable baseline. Production deployment, Render services, bot identities, and secrets remain unchanged.
