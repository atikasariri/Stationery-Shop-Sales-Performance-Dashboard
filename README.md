# _**Stationery Shop Sales Performance & Revenue Analytics Dashboard**_

[![Looker Studio](https://img.shields.io/badge/Looker%20Studio-Google%20Data%20Studio-blue?logo=google)](https://datastudio.google.com/reporting/74dff7ad-4e48-4b81-b2da-84a68419f6a6)
[![Domain](https://img.shields.io/badge/Domain-Retail%20%26%20E--Commerce-orange)](#)
[![Role](https://img.shields.io/badge/Role-Business%20Analyst-green)](#)


_**Business Overview & Problem Statement**_

A multi-city retail stationery business generated transactional data across various product lines, customer locations, and payment methods. However, leadership lacked a centralized analytics system to track regional sales distribution, monitor brand performance, and evaluate payment channel adoptability. 

Without interactive performance tracking, store managers faced challenges in:
* Identifying high-value regional markets and customer purchasing patterns.
* Determining top-demanded brands to optimize inventory allocation.
* Understanding payment method preferences across different city demographics to streamline checkout conversion.


> _**Interactive Dashboard Preview**_

<img width="800" height="452" alt="Dashboard Preview" src="https://github.com/user-attachments/assets/a13be00a-058c-43c0-8d85-15e15385f195" />


> _**Live Interactive Dashboard:**_ [View on Looker Studio](https://datastudio.google.com/reporting/74dff7ad-4e48-4b81-b2da-84a68419f6a6)


_**Data Architecture & Tools Used**_

* **Dashboarding & Visualization:** Google Looker Studio (formerly Google Data Studio)
* **Data Source & Preparation:** Microsoft Excel (Relational dataset containing 10,000 transaction records joined across "Transactions", "Status", "Payment", and "Customer" tables)
* **Core Analytics Focus:** Sales Performance, Product & Brand Demand Analysis, Regional Distribution, Payment Channel Segmentation


_**Key Business Insights**_

1. **Top Product & Brand Demand:**
   * High-demand brands (such as *Scriba*, *Graphen*, and *Statvio*) drive the majority of sales volume across core stationery items.
   * Product performance shows consistent demand for daily operational supplies (cutters, binders, and notebooks).

2. **Geographic & Customer Segmentation:**
   * Customer transaction distribution spans major urban hubs including Jakarta, Surabaya, Bandung, Semarang, and Denpasar.
   * Region-specific purchasing behavior highlights opportunities for localized promotions and regional warehouse fulfillment.

3. **Payment Method Adoption:**
   * Payment transactions are split across **Virtual Accounts (VA)**, **Bank Transfers**, **E-Wallets**, and **Cash on Delivery (COD)**.
   * High adoption of digital payment methods indicates a customer base that favors friction-free checkout workflows.


_**Strategic Business Recommendations**_

* **Inventory Optimization:** Reallocate high-demand brand stocks directly to high-volume city clusters to reduce fulfillment delays and shipping costs (Biaya_Ongkir).
* **Targeted Regional Marketing:** Launch customized promotional campaigns tailored to top-performing cities based on historical sales volume.
* **Checkout & Payment Integration:** Prioritize Virtual Account and E-Wallet partnerships to lower transaction drop-off rates and offer targeted cashback promotions.


_**Repository Structure**_

```text
├── assets/
│   └── dashboard-preview.jpeg                   # gif of the dashboard
    └── dashboard-preview.gif                    # Screenshot image of the dashboard
├── data/
│   └── [Updated] TokoAlatTulis_FINAL_BUILD.xlsx # Raw & Structured Sales Dataset
├── README.md                                    # Project Documentation
├── LICENSE                                      # MIT License
└── .gitignore                                   # Git Ignore configuration
