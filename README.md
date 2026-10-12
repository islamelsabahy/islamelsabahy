# Islam El-Sherbiny · إسلام الشربيني

**EN** — IT Manager in Cairo with 14 years in IT, running technology for real estate development companies. I build small, tested, dependency-light tools for the problems I meet at work: ERP and e-invoicing, contracts and cheques, infrastructure and operations. Everything here uses fictional sample data only.

**AR** — مدير تقنية معلومات في القاهرة، 14 سنة خبرة، بشتغل في قطاع التطوير العقاري. بعمل أدوات صغيرة ومختبرة من مشاكل الشغل الحقيقية: ERP والفاتورة الإلكترونية والعقود والشيكات والبنية التحتية. كل بيانات الأمثلة وهمية.

## Try in the browser / جرّب من المتصفح

| Tool | What it does | Live |
|---|---|---|
| **einvoice-validator** | Pre-flight check for Egyptian Tax Authority (ETA) e-invoice JSON: fields, enums, dates, VAT and totals | [open](https://islamelsabahy.github.io/einvoice-validator/) |
| **arabic-contract-clause-checker** | Missing clauses and risky wording in Arabic sale/lease contracts, with PDF report | [open](https://islamelsabahy.github.io/arabic-contract-clause-checker/) |
| **cctv-storage-planner** | Disks, retention and bandwidth for mixed camera systems, with PDF report | [open](https://islamelsabahy.github.io/cctv-storage-planner/) |
| **odoo-real-estate-addons** | Installment schedule calculator (same logic as the Odoo module), PDF/CSV export | [open](https://islamelsabahy.github.io/odoo-real-estate-addons/) |

All four run entirely client-side: nothing you paste is uploaded. / كلها بتشتغل في المتصفح من غير رفع أي بيانات.

## Repositories / الريبوهات

| Repo | Summary |
|---|---|
| [odoo-real-estate-addons](https://github.com/islamelsabahy/odoo-real-estate-addons) | Odoo 17 units catalog and installment plans for developers; tested on the official Odoo image in CI |
| [cheque-tracker-odoo](https://github.com/islamelsabahy/cheque-tracker-odoo) | Post-dated cheque life-cycle for Odoo 17, linked to installment lines |
| [einvoice-validator](https://github.com/islamelsabahy/einvoice-validator) | Offline ETA e-invoice JSON validator (CLI + browser), English/Arabic messages |
| [arabic-contract-clause-checker](https://github.com/islamelsabahy/arabic-contract-clause-checker) | Rule-based first-pass review of Arabic real estate contracts (not legal advice) |
| [cctv-storage-planner](https://github.com/islamelsabahy/cctv-storage-planner) | CCTV storage and bandwidth planner (CLI + browser) |
| [it-ops-scripts](https://github.com/islamelsabahy/it-ops-scripts) | Scripts for everyday IT operations |
| [awesome-odoo-egypt](https://github.com/islamelsabahy/awesome-odoo-egypt) | Curated Odoo and ETA e-invoicing resources for Egypt |

## How I build / طريقة الشغل

- Python standard library where possible; Python and JavaScript versions of the same logic are checked against each other on shared test vectors in CI.
- Bilingual (Arabic/English) output and RTL-correct pages from day one.
- Honest limits stated in every README.

Interested in Odoo, ETA e-invoicing or IT operations in Egyptian real estate? Open an issue on any repo.
