# 🏷️ Naming Conventions

## Overview

Futurion Systems uses standardized naming conventions to maintain consistency across its Active Directory environment. These conventions simplify administration, improve documentation, and support future scalability.

---

## Servers

| Role               | Naming Format | Example    |
| ------------------ | ------------- | ---------- |
| Domain Controller  | `FS-DC##`     | `FS-DC01`  |
| File Server        | `FS-FS##`     | `FS-FS01`  |
| Application Server | `FS-APP##`    | `FS-APP01` |
| Backup Server      | `FS-BKP##`    | `FS-BKP01` |

---

## Client Devices

| Device         | Naming Format | Example   |
| -------------- | ------------- | --------- |
| Windows Client | `FS-CL##`     | `FS-CL01` |

---

## User Accounts

| Format                      | Example                        |
| --------------------------- | ------------------------------ |
| `<first initial><lastname>` | `jsmith`, `sjohnson`, `mbrown` |

---

## Organizational Units (OUs)

| Department           | OU               |
| -------------------- | ---------------- |
| Executive Management | `Executive`      |
| Technology Services  | `Technology`     |
| Sales                | `Sales`          |
| Marketing            | `Marketing`      |
| Operations           | `Operations`     |
| Finance              | `Finance`        |
| Human Resources      | `HumanResources` |

---

## Security Groups

| Type              | Format            | Example         |
| ----------------- | ----------------- | --------------- |
| Security Group    | `SG-<Department>` | `SG-Technology` |
| Distribution List | `DL-<Name>`       | `DL-AllStaff`   |

---

## Group Policy Objects (GPOs)

| Format             | Example              |
| ------------------ | -------------------- |
| `GPO-<Purpose>`    | `GPO-PasswordPolicy` |
| `GPO-<Department>` | `GPO-Technology`     |

---

## Shared Folders

| Format                   | Example             |
| ------------------------ | ------------------- |
| `\\FS-FS01\<Department>` | `\\FS-FS01\Finance` |

---

Following these conventions ensures a consistent and organized Active Directory environment while making future administration and troubleshooting more efficient.
