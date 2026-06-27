# DIKWP OralMedEdu OS

DIKWP OralMedEdu OS is a GitHub-ready, offline-first education management system for oral/stomatology medical education under the current AI transformation.

It supports:

- AI teaching system construction for stomatology.
- Daily teaching administration.
- Student learning platform.
- Teacher teaching platform.
- Internship and residency training platform.
- National medical licensing mock-exam readiness.
- Authorized institutional formal exam governance.

It does **not** diagnose, treat, prescribe, triage patients, leak exam items, impersonate official examination systems, capture credentials, or automate official exam submission.

## Quick Start

```bash
pip install -e .
oralmededu analyze examples/sample_oral_meded_case.json --out outputs/demo
oralmededu guard "generate an OSCE station for caries risk counseling" 
oralmededu static-audit src --out outputs/demo/static_boundary_audit_report.json
```

Open `index.html` for the standalone demo.
