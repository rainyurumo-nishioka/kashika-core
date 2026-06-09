# KASHIKA Global Expansion: Decentralized Contribution Guide

Welcome to KASHIKA. This is not a centralized platform; it is a decentralized, flat matrix of historical and political facts. 

We do not judge, interpret, or ranks countries. We connect fact-led data structures. By opening your country's gate, your historical precedents will automatically backup (or conflict-warn) other nations' future policies.

---

## 🌍 How to Open Your Country's Gate (3-Min Starter Kit)

To join the KASHIKA global registry, fork this repository or create your own standalone repository named `kashika-gate-[Your-Country-Code]` (e.g., Taiwan = `kashika-gate-886`). 

You only need **two minimum JSON files** to start running.

### ① `/index.json` (The Gate Registry)
Place this at the root of your repository so the global registry (`kashika-core`) can discover your eras and available data tracks.

```json
{
  "gate_code": "886",
  "country_name": "Taiwan",
  "maintainers": ["taiwan-digital-civics"],
  "eras": [
    {
      "era_id": "1996_digital_democracy",
      "era_name": "デジタル民主主義移行期",
      "policies_list": [
        "eras/1996_digital_democracy/policies/886_g0v_vtaiwan.json"
      ]
    }
  ]
}
