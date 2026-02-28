# ChopChop

**ChopChop** is an automated workflow tool that splits large files into smaller, LLM-ready chunks to stay within token limits.  
When paired with LLM summarization, it can compress system/environment parameters into a **concise summary table**, improving visibility and control of your PC environment.

---

## What it does
- ✂️ **Chops large files** into manageable pieces (token-limit friendly)
- 🤖 **Prepares chunks for LLM processing** (summarization / extraction)
- 📊 **Enables structured outputs** (e.g., a clean environment parameter table)

---

## Typical workflow
1. Input a large file (logs / configs / environment dumps)
2. ChopChop splits it into small chunks
3. Send chunks to an LLM for summarization/extraction
4. Merge results into a single **summary table**

---

## Use cases
- Large log/config review under token limits  
- Environment auditing & reproducible setup documentation  
- Debugging complex systems (quick structured overview)

---

## Example output (summary table)
| Parameter | Value | Note |
|---|---:|---|
| OS | Windows 11 | Build info |
| CPU | Intel i7 | Load stable |
| RAM | 32 GB | 78% used |
| GPU | RTX 4090 | Driver OK |

---

## Goal
Turn **messy, oversized environment files** into **small, LLM-friendly chunks** and a **clear final summary** you can use to monitor, debug, and manage your system.

<img width="650" height="201" alt="image" src="https://github.com/user-attachments/assets/19ad8e91-0e5d-4d0c-aa0d-c96e2d3b230f" />

<img width="895" height="847" alt="image" src="https://github.com/user-attachments/assets/d43ad311-0d42-4c21-be1b-0b6da93d85bf" />
