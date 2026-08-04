# Friendly Captcha (friendly-captcha)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Friendly Captcha is a privacy-first, GDPR-compliant bot protection
service from Germany that uses proof-of-work cryptographic puzzles
instead of image-labeling challenges. The widget solves a puzzle in
the background while a user fills out a form, then submits a token
the server validates against the Friendly Captcha siteverify endpoint.
The result includes a risk verdict and additional signal intelligence
(IP, bot detection, browser identification, anonymization detection).
Friendly Captcha publishes open-source widgets and framework
integrations for React, Vue, and Angular, plus pre-built plugins for
WordPress, Magento, and other CMS platforms.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/friendly-captcha/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/friendly-captcha/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- CAPTCHA
- Bot Defense
- Privacy
- Proof of Work
- GDPR
- European Hosting
- Accessibility

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Friendly Captcha Siteverify API

The siteverify endpoint validates a Friendly Captcha solution
token. The server POSTs the token and API key (with optional
sitekey) and receives a JSON response indicating success, risk
score, IP intelligence, bot detection signals, and any error
codes. This is the canonical server-side check for protected
form submissions and API calls.

- **Human URL:** [https://developer.friendlycaptcha.com/docs/v2/getting-started/verify](https://developer.friendlycaptcha.com/docs/v2/getting-started/verify)
- **Base URL:** `https://global.frcapi.com/api/v2/captcha/siteverify`

#### Tags

- Siteverify
- Token Verification
- Risk Signals

#### Properties

- [Documentation](https://developer.friendlycaptcha.com/docs/v2/getting-started/verify)
- [API Reference](https://developer.friendlycaptcha.com/docs/v2/api-reference)
- [Endpoint U R L](https://global.frcapi.com/api/v2/captcha/siteverify)
- [Postman Collection](collections/friendly-captcha.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/friendly-captcha.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Friendly Captcha Widget

The Friendly Captcha widget is the JavaScript component that runs
the proof-of-work puzzle in the browser and produces a solution
token. It is configured via a script tag and a div with the
sitekey and API endpoint, and can run automatically or on demand.

- **Human URL:** [https://developer.friendlycaptcha.com/docs/v2/getting-started/widget](https://developer.friendlycaptcha.com/docs/v2/getting-started/widget)
- **Base URL:** `https://developer.friendlycaptcha.com/docs/v2/getting-started/widget`

#### Tags

- JavaScript
- Widget
- Proof of Work
- Frontend

#### Properties

- [Documentation](https://developer.friendlycaptcha.com/docs/v2/getting-started/widget)
- [Repository](https://github.com/FriendlyCaptcha/friendly-challenge)
- [Package](https://www.npmjs.com/package/friendly-challenge)
- [Postman Collection](collections/friendly-captcha.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/friendly-captcha.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Friendly Captcha Framework SDKs

Friendly Captcha publishes open-source wrappers for React, Vue,
and Angular that expose the widget as an idiomatic component in
each framework, handling lifecycle, callbacks, and token flow.

- **Human URL:** [https://developer.friendlycaptcha.com/docs/v2/integrations](https://developer.friendlycaptcha.com/docs/v2/integrations)
- **Base URL:** `https://developer.friendlycaptcha.com/docs/v2/integrations`

#### Tags

- React
- Vue
- Angular
- SDK

#### Properties

- [Documentation](https://developer.friendlycaptcha.com/docs/v2/integrations)
- [S D K React](https://github.com/FriendlyCaptcha/friendly-captcha-react)
- [S D K Vue](https://github.com/FriendlyCaptcha/friendly-captcha-vue)
- [S D K Angular](https://github.com/FriendlyCaptcha/friendly-captcha-angular)
- [GitHub Organization](https://github.com/FriendlyCaptcha)
- [Postman Collection](collections/friendly-captcha.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/friendly-captcha.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Friendly Captcha CMS Plugins

Pre-built plugins integrate Friendly Captcha into WordPress,
Magento, and other CMS platforms, letting non-developers add
privacy-preserving bot defense to common forms without writing
code.

- **Human URL:** [https://friendlycaptcha.com/integrations/](https://friendlycaptcha.com/integrations/)
- **Base URL:** `https://friendlycaptcha.com`

#### Tags

- WordPress
- Magento
- CMS Plugin

#### Properties

- [Integrations Page](https://friendlycaptcha.com/integrations/)
- [Postman Collection](collections/friendly-captcha.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/friendly-captcha.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://friendlycaptcha.com/)
- [Documentation](https://developer.friendlycaptcha.com/)
- [API Reference](https://developer.friendlycaptcha.com/docs/v2/api-reference)
- [Pricing](https://friendlycaptcha.com/pricing/)
- [Integrations](https://friendlycaptcha.com/integrations/)
- [GitHub Organization](https://github.com/FriendlyCaptcha)
- [Blog](https://friendlycaptcha.com/insights/)
- [Privacy](https://friendlycaptcha.com/legal/privacy-end-users/)
- [Contact](https://friendlycaptcha.com/contact/)
- [L L Ms Txt](https://developer.friendlycaptcha.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
