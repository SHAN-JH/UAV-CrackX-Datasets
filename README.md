# UAV-CrackX

This dataset is a **UAV-based pavement crack semantic segmentation dataset** captured at a flying altitude of **50 m** with **different magnification levels**.  
The detailed data acquisition and processing procedures can be found in our IEEE Transactions on Intelligent Transportation Systems paper:  
> [**Unmanned Aerial Vehicle (UAV)-Based Pavement Image Stitching Without Occlusion, Crack Semantic Segmentation, and Quantification**](https://doi.org/10.1109/TITS.2024.3424525)
> *IEEE Transactions on Intelligent Transportation Systems*, vol. 25, no. 11, pp. 17038–17053, Nov. 2024. 
---

## 📘 About

The **public dataset** contains **1,500 UAV road images**, including:  
- 🟦 500 images at **×4 magnification**  (UAV-CrackX4)
- 🟩 500 images at **×8 magnification**  (UAV-CrackX8)  
- 🟨 500 images at **×16 magnification**  (UAV-CrackX16)

A detailed dataset description is available in our paper published in *Automation in Construction*:  
> [**Bridging Cross-Domain and Cross-Resolution Gaps for UAV-Based Pavement Crack Segmentation**](https://doi.org/10.1016/j.autcon.2025.106141)  
> *Automation in Construction*, vol. 174, p. 106141, 2025.

We also release **1,200 annotated images** (400 for each magnification level).  
The annotations are grayscale masks, where:  
- `0` = pavement  
- `1` = crack

---

## 🏁 Competition

A benchmark competition using **300 test images** (from different magnification levels) is hosted at:  
👉 [http://vlp.chd.edu.cn/tasks/4](http://vlp.chd.edu.cn/tasks/4)

Participants can submit segmentation masks to evaluate their models on multiple performance metrics.

---

## 📩 Contact

For any questions, please contact:  **📧 jhshan@chd.edu.cn**

---

## 📚 Citing

If you find this dataset useful in your research, please cite the following papers:

> Shan Jinhuan, *et al.*, “**Bridging Cross-Domain and Cross-Resolution Gaps for UAV-Based Pavement Crack Segmentation**,”  
> *Automation in Construction*, vol. 174, p. 106141, Jun. 2025.  
> DOI: [10.1016/j.autcon.2025.106141](https://doi.org/10.1016/j.autcon.2025.106141)

> Shan Jinhuan, *et al.*, “**Unmanned Aerial Vehicle (UAV)-Based Pavement Image Stitching Without Occlusion, Crack Semantic Segmentation, and Quantification**,”  
> *IEEE Transactions on Intelligent Transportation Systems*, vol. 25, no. 11, pp. 17038–17053, Nov. 2024.  
> DOI: [10.1109/TITS.2024.3424525](https://doi.org/10.1109/TITS.2024.3424525)

You may also refer to our related studies on UAV-based pavement crack segmentation:

> - Shan Jinhuan, *et al.*, “**GLoU-MiT: Lightweight Global-Local Mamba-Guided U-Mix Transformer for UAV-Based Pavement Crack Segmentation**,”  
>   *Advanced Engineering Informatics*, vol. 65, p. 103384, May 2025.  
>   DOI: [10.1016/j.aei.2025.103384](https://doi.org/10.1016/j.aei.2025.103384)

> - Shan Jinhuan, *et al.*, “**DCUFormer: Enhancing Pavement Crack Segmentation in Complex Environments with Dual-Cross/Upsampling Attention**,”  
>   *Expert Systems with Applications*, vol. 264, p. 125891, Mar. 2025.  
>   DOI: [10.1016/j.eswa.2024.125891](https://doi.org/10.1016/j.eswa.2024.125891)
>


---

⭐ **If you find this dataset helpful, please star this repository to support our work!**
