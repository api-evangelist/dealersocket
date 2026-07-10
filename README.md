# DealerSocket (dealersocket)

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
