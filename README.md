# DealerSocket (dealersocket)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

DealerSocket is an automotive dealership CRM and Dealer Management System (DMS) software platform for franchise and independent auto dealers, covering customer relationship management, inventory management, websites, digital marketing, and desking/deals. DealerSocket is a **Solera company** (acquired 2021; part of Solera's Vehicle Solutions line of business).

> **Access model: partner / certification-gated.** DealerSocket exposes inbound and outbound integration APIs, but access is **not self-serve**. Integrations are delivered through DealerSocket's **Certified Partners program** (launched 2013, with 500-plus integration points) and are application-, contract-, and certification-gated. There is **no public developer portal, no published authentication reference, and no public endpoint or base-URL documentation.** DealerSocket also participates in DMS third-party access programs (for example ADP's Third-Party Access Program at the Managed Bi-Directional Integration level). Pricing is enterprise/contract (contact sales). The logical APIs below are **modeled from DealerSocket's public integrations page** ([dealersocket.com/apis/](https://dealersocket.com/apis/)), not from a self-serve API reference, and are flagged `endpointsModeled` in `apis.yml`.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dealersocket/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dealersocket/refs/heads/main/apis.yml)

## Tags

- Automotive
- Dealership
- CRM
- DMS
- Leads
- Inventory
- Deals
- Solera
- Partner API
- Certified Partners

## Timestamps

- **Created:** 2026-07-10
- **Modified:** 2026-07-10

## APIs (modeled)

### DealerSocket CRM & Leads API

Lead and CRM integration surface: the outbound **Lead Forwarding Service** (forwards incoming and processed dealership lead data to a third-party vendor as XML or email), inbound **Activity Insert/Update** (create or update activity/to-do records such as calls, appointments, work notes, and web leads), and **EntitySync** (link website visitor data to existing customer records).

- **Human URL:** [https://dealersocket.com/apis/](https://dealersocket.com/apis/)
- **Endpoints modeled** (partner-gated; endpoints/auth not public)

### DealerSocket Customers API

Inbound customer integration surface: the **Customer Update** integration modifies customer records in DealerSocket CRM (with insert of not-yet-found customers noted as forthcoming on the public integrations page).

- **Human URL:** [https://dealersocket.com/apis/](https://dealersocket.com/apis/)
- **Endpoints modeled** (partner-gated; endpoints/auth not public)

### DealerSocket Deals & Desking API

Outbound deal integration surface: **Deal Push Basic** performs a one-way push of basic deal data (customer, co-buyer, salesperson, vehicle of interest) to the DMS, and **Deal Push Advanced** extends it with desking and financial information.

- **Human URL:** [https://dealersocket.com/apis/](https://dealersocket.com/apis/)
- **Endpoints modeled** (partner-gated; endpoints/auth not public)

### DealerSocket CTI & Activity Logging API

Inbound call-tracking and activity-logging surface: **CTI Direct Post** (logs inbound/outbound call information), **Call Vendor Direct Post Work Note Update** (appends call follow-up data and transcripts), **Event Update** (updates sales and service event work notes), and **Work Note Insert** (appends notes to open events).

- **Human URL:** [https://dealersocket.com/apis/](https://dealersocket.com/apis/)
- **Endpoints modeled** (partner-gated; endpoints/auth not public)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/dealersocket)
- [Website](https://dealersocket.com)
- [Documentation (Integrations)](https://dealersocket.com/apis/)
- [Certified Partners](https://dealersocket.com/resources/certified-partners/)
- [Parent Company (Solera)](https://www.solera.com/solutions/dealers/dealersocket/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
