<div align="center">

# ⚡ SYNAPSE // SOLUTION ARCHIVE

<p align="center">
  <img src="https://img.shields.io/badge/AUTO--SYNC-ACTIVE-0ea5e9?style=for-the-badge&logo=github&logoColor=white" alt="Auto-Sync" />
  <img src="https://img.shields.io/badge/ALGORITHMS-OPTIMIZED-10b981?style=for-the-badge" alt="Algorithms" />
</p>

### 📡 Automated Competitive Programming Vault

A fully automated, living archive of accepted submissions from major competitive programming platforms. Automatically extracted, formatted, and pushed via [Git-Rabbit](https://github.com/omkar/git-rabbit).

</div>

---

## 🗃️ PLATFORMS

| Platform | Domain | Protocol | Source |
|:---------|:-------|:---------|:-------|
| <img src="https://upload.wikimedia.org/wikipedia/commons/1/19/LeetCode_logo_black.png" width="14"/> **LeetCode** | `leetcode.com` | GraphQL | API |
| <img src="https://upload.wikimedia.org/wikipedia/commons/b/b1/Codeforces_logo.svg" width="14"/> **Codeforces** | `codeforces.com` | Public API | JSON |
| **AtCoder** | `atcoder.jp` | Kenkoooo | Scraping |

---

## 📊 METRICS // LIVE STATS

> [!NOTE]
> Stats are updated automatically on every successful commit.

<!-- STATS:START -->
<!-- STATS:END -->

---

## 🏗️ ARCHITECTURE & STRUCTURE

Each accepted solution triggers a localized atomic push, storing exactly three components:

```text
📦 root
├── 📁 LeetCode/
│   ├── 📁 0001-Two-Sum/
│   │   ├── 📄 Question.md        [Problem Description & Rules]
│   │   ├── 📄 Solution.cpp       [Accepted Code]
│   │   └── 📄 Notes.md           [Time/Space Complexity & Sub Stats]
│   └── ...
├── 📁 Codeforces/
│   └── 📁 1500A-Watermelon/
│       └── ...
└── 📄 README.md                  [You are here]
```

---

## ⚙️ DEPLOYMENT & SYNC

1. **Solve** a problem and receive an `Accepted` verdict.
2. The extension intercepts the network request and extracts metadata (Runtime, Memory, Difficulty).
3. The UI widget overlays on the page, allowing injection of Time/Space complexity notes.
4. **`COMMIT`** initiates a single atomic multi-file push via GitHub's Git Data API.

<div align="center">
<sub>Powered by <strong>Git-Rabbit</strong>. Manifest V3.</sub>
</div>
