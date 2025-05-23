# Splunk Core Certified User - Study Notes

These are my personal notes while preparing for the Splunk Core Certified User exam.

---

## 🔍 1. Search Modes
- **Fast** – Prioritizes speed; skips field discovery
- **Smart** – Adjusts based on whether the search is transforming or not
- **Verbose** – Includes all fields and raw event data

---

## 🧠 2. Search Commands
- `stats count by host` – Counts events by host
- `table user, action` – Displays results in table format
- `fields - _raw` – Excludes the `_raw` field from results
- `rename status_code as code` – Renames a field

---

## 🧱 3. Fields
- **Default selected fields**: `host`, `source`, `sourcetype`
- **Interesting fields**: Appear in ≥ 20% of events
- **Field discovery**: Extracts fields at search time

---

## 🔔 4. Knowledge Objects
- **Reports** – Saved searches that can be scheduled
- **Alerts** – Triggered by search results meeting a condition
- **Dashboards** – Visual displays of data using panels
- **Event types** – Saved sets of search criteria

---

## 📅 5. Time Modifiers
- `earliest=-24h@h latest=now`
- `earliest=-7d@d latest=@d`
- Relative time options for filtering

---

## 🧪 6. Exam Reminders
- Events returned by default in **reverse chronological order**
- `search` command is used to **further filter** results
- Fields with `=` at search time: **left = field name, right = value**
- To **exclude fields**: use `fields - fieldname`

---

## 📌 Resources
- Splunk Docs: https://docs.splunk.com/
- TryHackMe Splunk Room
- Free Splunk Fundamentals Course
