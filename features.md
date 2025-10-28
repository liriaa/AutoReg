# Syntactic Feature List

This document lists the **20 syntactic features** used in our feature extraction process.  
These features capture patterns such as character composition, delimiters, and formatting cues.

---

## 📋 Feature Overview

| No. | Feature Name | Description |
|-----|---------------|-------------|
| 1 | Uppercase Count | Number of uppercase alphabetic characters (`A–Z`). |
| 2 | Lowercase Count | Number of lowercase alphabetic characters (`a–z`). |
| 3 | Digit Count | Number of numeric characters (`0–9`). |
| 4 | Whitespace Count | Number of whitespace characters (spaces, tabs, etc.). |
| 5 | Punctuation Count | Number of punctuation marks (e.g., `.`, `,`, `;`, `!`, `?`). |
| 6 | Non-Alphanumeric Count | Number of characters that are neither letters nor digits (excluding delimiters). |
| 7 | Segment Count | Number of segments obtained when splitting the string by delimiters (`-`, `_`, `/`). |
| 8 | Avg. Segment Length | Average length of segments obtained after splitting by delimiters. |
| 9 | Contains Alphabet | Boolean (1/0): 1 if any alphabetic character exists, else 0. |
| 10 | Contains Digit | Boolean (1/0): 1 if any numeric character exists, else 0. |
| 11 | Contains Hyphen | Boolean (1/0): 1 if any hyphen (`-`) appears, else 0. |
| 12 | Contains Slash | Boolean (1/0): 1 if any slash (`/`) appears, else 0. |
| 13 | Contains Underscore | Boolean (1/0): 1 if any underscore (`_`) appears, else 0. |
| 14 | Contains At-Symbol | Boolean (1/0): 1 if an “@” symbol is present, else 0. |
| 15 | Leading/Trailing Whitespace | Boolean (1/0): 1 if the string begins or ends with whitespace, else 0. |
| 16 | Repeated Delimiters | Boolean (1/0): 1 if consecutive delimiters (like `--`, `__`, `//`) occur, else 0. |
| 17 | Starts with Digit | Boolean (1/0): 1 if the string starts with a numeric character, else 0. |
| 18 | Ends with Digit | Boolean (1/0): 1 if the string ends with a numeric character, else 0. |
| 19 | Contains Mixed Case | Boolean (1/0): 1 if both uppercase and lowercase letters appear, else 0. |
| 20 | Contains Special Symbol | Boolean (1/0): 1 if any special character (e.g., `#`, `$`, `%`, `&`, `*`) is present, else 0. |

---

## 💡 Notes

- Features **1–8** capture *counts and segment structure*.  
- Features **9–20** describe *presence or pattern-based properties* such as delimiters, digits, symbols, and case usage.  
- Boolean features are encoded as `1` (present) or `0` (absent).  


---
