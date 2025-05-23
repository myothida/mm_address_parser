# Project Title
**Myanmar Address Parsing**

## Project Description

This project parses the given address into different components (state, district, township, ward, village) to search in the Mimu database. The address will be parsed to identify the hierarchical address levels, starting with the highest level (state) and moving down to the lowest level (village or ward). This ensures that the address is accurately parsed even if certain components are ambiguous or missing.

### Tasks

1. **Extracting hierarchical components** from the address input, such as state, district, township, ward, and village.
2. **Handling different types of address formats** including those with missing or incomplete components.
3. **Parsing address in multiple languages** (Myanmar and English), ensuring compatibility with both.
4. **Standardizing parsed data** to be consistent with the Mimu database structure, facilitating easier search and geolocation retrieval.

---

### Installation

Install from [PyPI](https://pypi.org/project/mm-address-parser/):

```
pip install mm_address_parser
```
---

### Usage
```
from mm_address_parser.parser import Parser
parser = Parser()
parsed = parser.parse("ရန်ကုန်တိုင်းဒေသကြီး, လှိုင်မြို့နယ်, သီလဝါလမ်း")
print(parsed)
```
---
## Credits and Licensing

- **Project Lead:** Myo Thida
- **Institution/Affiliation:** MMDT
- **Data Source:** Myanmar Information Management Unit (MIMU), veresion 9.6 resleased in Feb 2025

This project and its outputs are released under the **MIT License**.  
You are free to use, modify, and distribute the code and dataset with proper attribution.

> © 2025 Myo Thida. All rights reserved.  
> If you use this project in your work, please cite or link back to this repository and the parent project:  
> _"From Words to Coordinates: Mapping Myanmar's Unstructured Addresses to Coordinates."_

