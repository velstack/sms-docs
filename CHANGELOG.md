# 📝 Velstack SMS API – Changelog

All notable changes to the **Velstack SMS API** will be documented in this file.  
This project adheres to [Semantic Versioning](https://semver.org/).

---

## [v1.3.0] – 2025-10-08
### Changed
- **Quick SMS API**: The `recipient` field now **requires an array** instead of a single string.
  ```json
  {
    "sender": "Velstack",
    "recipient": ["0205550368", "0248297302"],
    "message": "Sent from the Velstack API"
  }
