# virtpet
## About
Portable virtual pets
## Usage
```mermaid
---
title: Use Case
---
flowchart LR
    A(virtpet release) -->|Run| B[virtpet.py]
    B -->|create instance| C1[%PET_NAME%.py]
    C1 --- D(portable Pet\nwith self-saved data between sessions)
```
1. Install dependencies
`*script to install dependencies*`
2. Run `virtpet.py`
3. Run created `%pet_name%.py`
## Supported OS
**Windows, Linux & MacOS**
