# 🔥 High Temperature Processes – Laser Engraving / Cutting

This project explores laser–material interaction through practical raster engraving and cutting using a VLS 3.5 CO₂ laser system. The work integrates Gaussian beam theory, focalization calculations, and engraving workflows to evaluate beam behavior and machining precision.

## 🧩 Overview
- Module: High Temperature Processes  
- Practical Work: Laser Engraving / Cutting  
- Laser System: VLS 3.5 – 50W CO₂ (λ = 10.6 μm)  
- Capabilities: Engraving & cutting non-metallic chlorine-free materials  
- Operations: Raster engraving, beam characterization, focalization, software preparation  

---

## 📐 Beam Theory & Calculations
Gaussian beam parameters were evaluated to characterize optical performance:

| Parameter | Result |
|---|---|
| Minimum waist radius (w₀) | **1.35 × 10⁻³ m** |
| Rayleigh length (Zᵣ) | **0.54 m** |
| Beam radius at mirror (w(z)) | **1.548 × 10⁻³ m** |
| Focused spot size | **9.412 × 10⁻⁵ m** |

These values describe laser divergence, diffraction, and energy distribution prior to material interaction.

---

## 🪵 Raster Engraving Procedure
Raster mode engraves images via bi-directional scanning lines. Workflow steps included:

1. **Photograv:**  
   - Import JPG/BMP  
   - Material selection & 600 DPI  
   - Grayscale conversion & preview  
   - Final processing  

2. **Inkscape:**  
   - Frame creation (red, 0.01 mm vector cut)  
   - Export to PDF  

3. **UCP Control Software:**  
   - Color layer recognition  
     - **Black/Gray:** engraving  
     - **Red:** cutting  
     - **Blue:** vector paths  
   - Pointer positioning  
   - Material thickness input  
   - Time estimation & execution  

Final engraving performed on wood.

---

## 🧪 Results & Discussion
- Beam theory validated engraving performance and focal conditions.
- Raster engraving provided high-detail reproduction based on DPI and image preparation.
- Spatial beam parameters governed sharpness, thermal interaction, and engraving depth.
- The VLS 3.5 proved accurate, repeatable, and adaptable for non-metallic substrates.

---

## 🏁 Conclusion
Integrating Gaussian beam modeling with raster machining techniques enabled both theoretical and experimental understanding of laser-material interactions. The VLS 3.5 demonstrated precise focal control, efficient material removal, and versatile engraving performance suitable for scientific, industrial, and artistic applications.

---
