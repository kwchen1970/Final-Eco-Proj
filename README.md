# 🎮 Unreal Project Repository

This repository contains an Unreal Engine project.  
We use **Git LFS (Large File Storage)** to handle Unreal assets like `.uasset` and `.umap`.

---

## ⚠️ Important: Git LFS Required

Unreal assets are stored using **Git LFS**.  
If you don’t set it up, you’ll only see small text pointer files and Unreal won’t open correctly.

---

## 🔹 First-Time Setup (once per computer)

Run this after installing Git:

```bash
git lfs install
---
## ⚠️ Caveat: If You Already Cloned Without LFS

If you cloned this repo **before setting up Git LFS**, you will only see small pointer files instead of real Unreal assets.  

To fix this:

git lfs install
git lfs pull
