# Awesome-E-Procurement-Purchasing-Management

## Top E-Procurement & Purchasing Management Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Requisition-to-Pay Automation, Supplier Management & Spend Control*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **E-Procurement & Purchasing Management**. These tools help organizations digitize the entire purchasing lifecycle—from requisition creation and RFQ issuance through purchase orders, goods receipt, and invoice matching—covering everything from enterprise suites to self-hosted Laravel-based packages and EspoCRM extensions.

**Examples** include Coupa, SAP Ariba, Jaggaer, Ivalua, Procurify, Precoro, Tradogram, and open-source alternatives like Procuman, Shillinq, and Odoo Purchase (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted procurement, open-source purchasing workflows, and community-driven spend management—ideal for organizations seeking data sovereignty and avoiding per-transaction or per-user SaaS fees. The open-source landscape is genuinely functional: **Procuman** provides a free e-procurement solution built on EspoCRM , **Shillinq** integrates procurement into Nextcloud with PO revision tracking and supplier qualification , and **Odoo Purchase** delivers full requisition-to-pay automation within the broader Odoo ERP .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Coupa](https://www.coupa.com/)** | Enterprise business spend management platform covering procurement, invoicing, expense tracking, and contract management. Acquired by Thoma Bravo in 2023; includes Contractually (CLM) and LLamasoft (supply chain AI). Users consistently note it as the most expensive option in its class, but also the most flexible and user-friendly . | Quote-only (enterprise contract) | No public free tier; demo via sales |
| **[SAP Ariba](https://www.sap.com/)** | Enterprise procurement and contract management suite. Pricing for services and training is listed on SAP Store; full platform licensing is quote-only and typically bundled with broader SAP ERP engagements . | Quote-only (platform); training/best-practices services listed separately on SAP Store  | No public free tier; demo via SAP sales |
| **[Jaggaer](https://www.jaggaer.com/)** | Procurement platform with AI-powered Contract Lifecycle Management, sourcing, and supplier management. The 25.1 release emphasizes self-service contracting and faster negotiation cycles . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Ivalua](https://www.ivalua.com/)** | Enterprise spend management and procurement platform. Positioned for large organizations with complex sourcing and supplier networks. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Procurify](https://www.procurify.com/)** | Cloud procurement and spend management for mid-market. Positioned for simplicity and fast deployment. | Quote-only (tiered by features/users) | Free trial available |
| **[Precoro](https://precoro.com/)** | Procurement and spend management platform with transparent pricing. Positioned for mid-market companies wanting procurement automation without enterprise complexity . | Quote-only (tiered by features) | Free trial available |
| **[Tradogram](https://www.tradogram.com/)** | Cloud-based procurement solution for purchasing visibility and control. Capterra lists starting price at **$209/month** . | **$209/month** (Capterra listing)  | Free trial available |
| **[Gatekeeper](https://www.gatekeeperhq.com/)** | Contract management and procurement platform with AI-driven renewal management and workflow automation. Helps identify wasted spend and actively manage renewals . | From **$775/month**  | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Odoo Purchase](https://github.com/odoo/odoo/tree/master/addons/purchase)** | [![Stars](https://img.shields.io/github/stars/odoo/odoo?style=social&color=white)](https://github.com/odoo/odoo/stargazers) | **Full requisition-to-pay automation within the Odoo ERP.** Automate procurement propositions, launch RFQs, track purchase orders, manage vendor information, control product reception, and check vendor invoices. Features: **purchase tenders with vendor comparison**, email integration for negotiation traceability, vendor pricelist import, and three costing methods (standard, average, FIFO). **Best for organizations already using Odoo or wanting procurement tightly integrated with inventory and accounting.** |
| **[ERPNext Buying](https://github.com/frappe/erpnext)** | [![Stars](https://img.shields.io/github/stars/frappe/erpnext?style=social&color=white)](https://github.com/frappe/erpnext/stargazers) | **Comprehensive open-source purchasing and procurement module in ERPNext.** Features: automated material requests (requisitions), Request for Quotation (RFQ) distribution to multiple suppliers, supplier quotation capture and auto-comparison, purchase orders with multi-tier approval matrix, automated 3-way matching, purchase receipts, and supplier scorecard analytics. **Best for mid-to-large businesses seeking an end-to-end open-source ERP purchasing solution.** |
| **[Apache OFBiz](https://github.com/apache/ofbiz-framework)** | [![Stars](https://img.shields.io/github/stars/apache/ofbiz-framework?style=social&color=white)](https://github.com/apache/ofbiz-framework/stargazers) | **Enterprise-grade open-source suite with mature order and procurement management.** Features: purchase requisition handling, purchase order workflows, vendor and catalog management, pricing rules, inventory receipt matching, and multi-currency billing integration. **Best for large enterprises needing deeply customizable, Java-based enterprise procurement and ERP workflows.** |
| **[OpenBoxes](https://github.com/openboxes/openboxes)** | [![Stars](https://img.shields.io/github/stars/openboxes/openboxes?style=social&color=white)](https://github.com/openboxes/openboxes/stargazers) | **Open-source supply chain and inventory management software with purchase order tracking.** Features: purchase order creation, vendor catalogs, shipment and receiving tracking, stock movement tracking, and requisition workflows designed for global health, NGOs, and humanitarian supply operations. **Best for healthcare, humanitarian, and public sector supply chains.** |
| **[Leihs](https://github.com/leihs/leihs)** | [![Stars](https://img.shields.io/github/stars/leihs/leihs?style=social&color=white)](https://github.com/leihs/leihs/stargazers) | **Open-source equipment, asset reservation, procurement, and lending system.** Features: self-service user equipment requisitions, administrative order management and approval chains, inventory tracking, and procurement lifecycle visibility for internal assets and facilities. **Best for universities, media labs, and enterprise internal asset procurement and lending.** |
| **[OpenProcurement API](https://github.com/openprocurement/openprocurement.api)** | [![Stars](https://img.shields.io/github/stars/openprocurement/openprocurement.api?style=social&color=white)](https://github.com/openprocurement/openprocurement.api/stargazers) | **Open-source e-procurement core toolkit and tender management API powering national procurement platforms (like ProZorro).** Features: transparent reverse auctions, multi-lot tender management, bid qualification workflows, contract tracking, and Open Contracting Data Standard (OCDS) compliance. **Best for public sector, government, and consortium-level transparent e-tendering.** |
| **[WebERP](https://github.com/timschofield/webERP)** | [![Stars](https://img.shields.io/github/stars/timschofield/webERP?style=social&color=white)](https://github.com/timschofield/webERP/stargazers) | **Lightweight open-source ERP with purchasing, inventory, and accounting.** PHP/MySQL. Includes **sales order and purchase order management**, accounts payable/receivable, multi-currency, and role-based access control. **Best for SMBs wanting a complete ERP with procurement included without a modern UI.** |
| **[Procuman Community Edition](https://github.com/procuman/procuman-community-edition)** | [![Stars](https://img.shields.io/github/stars/procuman/procuman-community-edition?style=social&color=white)](https://github.com/procuman/procuman-community-edition/stargazers) | **Free e-procurement software built on EspoCRM.** GPLv3 (Community Edition). Features: supplier management with categorization and relationship tracking, product catalog with supplier associations and pricing, **purchase order management with automated totals/taxes and customizable PDF templates**, multi-language support, and REST API for integrations. **Professional Edition** (paid) adds requisitions with multi-level approvals, supplier portal, contract management, e-tendering, and inventory management. **Best for teams already on EspoCRM or wanting a straightforward PO-focused procurement tool.** |
| **[VendSync (BidFlow)](https://github.com/RavalMunjal/VendSync)** | [![Stars](https://img.shields.io/github/stars/RavalMunjal/VendSync?style=social&color=white)](https://github.com/RavalMunjal/VendSync/stargazers) | **Full-stack procurement and vendor management ERP built for hackathon.** Features: **vendor portal** (vendors register, view RFQs, submit quotations independently), RFQ management with multi-step creation, quotation engine with side-by-side comparison, approval workflow (Accept/Reject with remarks), **auto-generated POs upon quotation approval**, invoice generation with tax calculations, PDF export, real-time analytics dashboard, and **audit trail tracking "who did what and when"**. React/Node.js/MongoDB stack with JWT-based RBAC (Admin, Manager, Procurement Officer, Vendor). **Best for teams wanting a modern, deployable reference implementation.** |
| **[Shillinq](https://github.com/ConductionNL/shillinq)** | [![Stars](https://img.shields.io/github/stars/ConductionNL/shillinq?style=social&color=white)](https://github.com/ConductionNL/shillinq/stargazers) | **Complete open-source business administration suite for Nextcloud combining bookkeeping, invoicing, procurement, and contract management.** Features: **purchase orders & procurement workflows**, supplier management & approval chains, **PO revision management with change tracking and re-approval workflow**, supplier qualification with configurable questionnaires, contract spend dashboard, and **free plan available for basic procurement management without cost**. **Best for organizations already on Nextcloud wanting integrated financial and procurement workflows.** |
| **[Nexus Procurement](https://github.com/azaharizaman/nexus-procurement)** | [![Stars](https://img.shields.io/github/stars/azaharizaman/nexus-procurement?style=social&color=white)](https://github.com/azaharizaman/nexus-procurement/stargazers) | **Framework-agnostic procurement management package for Laravel applications.** Features: purchase requisitions, purchase orders, goods receipts, **3-way matching engine (Invoice-PO-GRN alignment in <500ms for 100 lines)**, vendor quote management (RFQ comparison), **segregation of duties (Requester ≠ Approver ≠ Receiver ≠ Payment Authorizer)**, budget controls (PO cannot exceed requisition by >10% without re-approval), multi-tenant support, and comprehensive audit logging. **Zero Laravel dependencies in core**—implements interfaces for your application to fulfill. **Best for developers embedding procurement logic into custom Laravel applications.** |

**Frameworks for building custom systems**: Choose **Procuman** for a free EspoCRM-based PO tool , **Shillinq** for Nextcloud-integrated procurement with PO revision tracking , **Odoo Purchase** for full ERP-integrated requisition-to-pay , or **Nexus Procurement** for embedding procurement logic into custom Laravel applications —all without per-transaction or per-user SaaS fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- E-procurement platforms handle supplier banking details, pricing agreements, and purchase approvals; enforce segregation of duties, budget controls, and audit logging to prevent fraud.
- **Open-source procurement tools vary significantly in scope.** **Procuman** focuses on supplier/product/PO management with PDF generation—no approval workflows in the free edition . **Shillinq** integrates procurement into Nextcloud with PO revision and supplier qualification, but requires the Nextcloud ecosystem . **Odoo Purchase** provides full ERP-integrated requisition-to-pay automation, but requires the broader Odoo stack . **Nexus Procurement** is a framework-agnostic package for developers—you implement the persistence layer . **SaaS platforms are universally quote-only** except Tradogram ($209/month) and Gatekeeper ($775/month) . Validate scope against your actual procurement workflow (approval chains, 3-way matching, supplier portals) before committing.

---

**Made for procurement managers, finance teams, and developers building purchasing infrastructure.**  
Let's make e-procurement and purchasing management more open, auditable, and cost-predictable.
