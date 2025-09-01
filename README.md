# 100x Week 1 — Depth ControlNet Practice (ComfyUI)

Practice set for the 100x Cohort (Week 1): take a **single base image**, use **Depth ControlNet** to guide 3D structure and generate multiple stylistic variations in **ComfyUI**.  

---

## 🎯 Goals
- Use a **base image** as ControlNet Depth guidance.  
- Produce **diverse variations** (styles, compositions, palettes) while **preserving depth/structure**.  
- Track parameters for **repeatable results**.  

---

## 🧭 What is Depth ControlNet?
**Depth ControlNet** uses the **depth map of the reference image**, preserving the spatial arrangement of objects while allowing style and appearance changes.  

---

## 📂 Repo Layout
- `workflows/` → ComfyUI workflow JSON  
- `inputs/` → base image(s)  
- `outputs/` → generated results  

---

## 🚀 How to Run
1. Open ComfyUI → load `workflows/depth_controlnet_workflow.json`.  
2. Input `inputs/base.jpg`.  
3. Run the workflow.  

---

## ✅ Checklist
- [ ] Workflow JSON  
- [ ] Base image  
- [ ] 3+ variations in `outputs/`  

---

## 📜 License
MIT (repo). Generated images follow base model license.
