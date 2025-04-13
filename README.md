# Frigg

![YAML Validation](https://github.com/OnyxJeff/Frigg/actions/workflows/validate-yaml.yml/badge.svg)
![Last Commit](https://img.shields.io/github/last-commit/OnyxJeff/Frigg)
![Repo Size](https://img.shields.io/github/repo-size/OnyxJeff/Frigg)
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen)

Frigg is my **Home Assistant node**, running on a Raspberry Pi 4 with **HassOS**.  
It acts as the brains of my smart home—automating, alerting, and occasionally judging my lighting choices.

---

## 🔧 Key Components

- **Automations**: YAML-based logic for everything from lights to routines.
- **Blueprints**: Reusable automation templates to speed up my tinkering.
- **Lovelace Dashboards**: My custom UI layout (dark mode, obviously).
- **Secrets Template**: Safe placeholder for sensitive config.
- **Backups**: Manual or scheduled snapshot exports.

---

## 🧪 CI / Linting

This repo uses [Yamllint](https://github.com/adrienverge/yamllint) via GitHub Actions to ensure all YAML files are well-formatted and ready to deploy.

---

## 📁 Repo Structure

```text
Frigg/
├── automations/          # YAML-based automations
├── blueprints/           # Shared/reusable automation logic
├── dashboards/           # Lovelace UI configurations
├── secrets/              # Redacted secret file examples
├── backups/              # Exported or example snapshot files
├── .github/workflows/    # CI for YAML validation
└── README.md             # You're reading it!
```

---

## 🚨 Note on Backups

This repo does not store real .tar snapshots or secrets.
Only redacted or example data is tracked.

---

## 💡 Home Assistant Details

- **Platform**: HassOS (Raspberry Pi 4)
- **Add-ons Used**: UI-based configuration and Supervisor
- **Version**: Rolling updates; see dashboard for current

---

📬 Maintained By
Jeff M. • [@OnyxJeff](https://www.github.com/onyxjeff)