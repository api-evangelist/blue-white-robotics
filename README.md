# Blue White Robotics

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

Blue White Robotics Ltd. — operating as **Bluewhite** — is an Israeli off-road autonomy company
founded in 2017 by Ben Alfi, Yair Shahar and Aviram Shmueli, headquartered in Tel Aviv with a US
operation in Fresno, California. Bluewhite builds an OEM-agnostic autonomy stack that retrofits
conventional vehicles into unmanned ground vehicles: **Pathfinder**, an aftermarket autonomy kit
combining control, intelligence and perception modules over a distributed CAN network, and
**Compass**, a cloud fleet-operations SaaS for remotely supervising, tasking and monitoring an
autonomous fleet. The company began in permanent-crop agriculture — roughly 150,000 US acres for
20-plus growers — and has since extended the same GPS-denied navigation and perception stack to
defense and homeland-security ground robotics. Elbit Systems' FUSE acquired 100% of Blue White
Robotics in 2026.

**API surface (checked 2026-08-07):** Bluewhite markets a "Software SDK" and an "API platform" on
its technology page, but publishes no developer portal, no API reference, and no machine-readable
specification. The Compass operator platform 302s every path — including `/openapi.json` — to a
Keycloak OIDC login (`realm maia-cloud`, `client maia-prod`), and SDK/API access runs through the
contact-sales form. See `x-coverage` in `apis.yml`.

- https://www.bluewhite.ai/
- https://www.bluewhite.ai/technology
- https://compass.bluewhite.ai/ (customer login)
