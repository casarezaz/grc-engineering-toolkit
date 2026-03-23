# Enterprise GRC Engineering Toolkit

**Interactive GRC dashboards for enterprise governance & compliance**  
*Interactive HTML dashboards for compliance automation, risk management, and audit readiness*

Built by [Angie Agee, CISSP](https://linkedin.com/in/ageean) — GRC leader, auditor, and standards contributor (IEEE, NIST COSAIS, ENISA CAR).

---

## Tools

### 1. [GRC Controls Tracker](grc-controls-tracker.html)
ISO 27001 / NIST 800-53 / SOX / PCI-DSS control mapping dashboard with real-time compliance rate tracking, framework filtering, and CSV export. Add, edit, and manage controls with audit evidence status.

### 2. [Risk Register & Heat Map](risk-register-heatmap.html)
Interactive risk register with 5×5 likelihood × impact heat map visualization. Tracks risk trends, mitigation status, and residual scores. Supports categorization, filtering, and full CRUD operations.

### 3. [Compliance Metrics & KPI Dashboard](compliance-metrics-dashboard.html)
Real-time compliance posture dashboard with KPI cards, framework compliance rates, SLA tracking, vulnerability remediation metrics, and audit finding trends. Designed for board-level risk communication.

### 4. [DR/BC Asset Criticality Ranker](drbc-asset-criticality-ranker.html)
Business Impact Analysis tool that scores assets across four dimensions (revenue, operational, regulatory, reputational) and auto-assigns recovery tiers. Tracks RTO/RPO targets and DR test coverage.

### 5. [Audit Readiness Scorecard](audit-readiness-scorecard.html)
Pre-audit assessment tool covering SOX, PCI-DSS, ISO 27001, GDPR, CMMC, and FedRAMP. Features overall readiness scoring, dimension breakdown (evidence, controls, testing, documentation), audit timeline, pre-audit checklist, and gap remediation tracker.

---

## Design Philosophy

These tools reflect an **engineering-first approach to GRC** — the belief that compliance should be automated, measurable, and embedded into operational workflows rather than managed through spreadsheets and email chains.

Each tool is:
- **Standalone** — Single HTML file, no build process, no dependencies
- **Interactive** — Full CRUD operations with local storage persistence
- **Exportable** — CSV export for integration with existing GRC platforms
- **Visual** — Heat maps, donut charts, sparklines, and progress bars for instant comprehension
- **Dark-themed** — Enterprise-grade UI designed for extended use

---

## Frameworks Covered

| Framework | Controls Tracker | Risk Register | Metrics | DR/BC | Audit Scorecard |
|-----------|:---:|:---:|:---:|:---:|:---:|
| NIST 800-53 | ✓ | ✓ | ✓ | — | ✓ |
| ISO 27001 | ✓ | ✓ | ✓ | — | ✓ |
| SOX | ✓ | ✓ | ✓ | — | ✓ |
| PCI-DSS | ✓ | ✓ | ✓ | — | ✓ |
| GDPR | ✓ | ✓ | ✓ | — | ✓ |
| CMMC | — | ✓ | — | — | ✓ |
| FedRAMP | — | ✓ | — | — | ✓ |

---

## Usage

Open any `.html` file directly in a browser. No server required.

```bash
# Clone and open
git clone https://github.com/casarezaz/grc-engineering-toolkit.git
open grc-controls-tracker.html
```

---

## Author

**Angie Agee, CISSP**  
Enterprise Governance, Risk & Compliance Executive  
IEEE Standards Committee Member · NIST COSAIS Volunteer · ENISA CAR Working Group  

[LinkedIn](https://linkedin.com/in/ageean) · [GitHub](https://github.com/casarezaz)

---

*These tools demonstrate the engineering-first, automation-driven approach to GRC that modern enterprise governance demands.*
