## Multi modal CrossViT using 3D-Spatial Information for Visual Localization [[Paper](https://drive.google.com/file/d/137iiBTtcethQDKu4zLgoHLvPYTEIGufb/view?usp=sharing)]    

**!아직 논문 Publish 이전 단계이므로, 코드를 제공하지 않습니다.** 

---
## Purpose
![image](https://github.com/user-attachments/assets/27cb6dda-0b9b-4b9e-a2d3-193918806657)

## Pipe-Line
![image](https://github.com/user-attachments/assets/dfbdde7a-63c7-44af-a12e-01ed88ac0269)

## Architecture
![image](https://github.com/user-attachments/assets/f160ace0-70f0-4b27-b52a-6ece1ea4c80a)

## Loss Function
![image](https://github.com/user-attachments/assets/4bed04f1-9009-44e2-aaa5-491fb02d957d)

w_{i,j} = \begin{cases}
  0.5 + 0.5 \times \frac{IoU - IoU_{min}}{IoU_{max} - IoU_{min}} & \text{if } IoU < IoU_{max} \\
  1.0 & \text{otherwise}
\end{cases}

![강준구_논문요약본_page-0002](https://github.com/user-attachments/assets/3759e5ee-9a02-40f1-a573-7719366881d0)
![강준구_논문요약본_page-0003](https://github.com/user-attachments/assets/ef0fe2e4-fb4c-41c0-8eae-1573911ded77)
![강준구_논문요약본_page-0004](https://github.com/user-attachments/assets/0ec8402e-ddf6-4d2f-a6da-d95f13a20d54)
![강준구_논문요약본_page-0005](https://github.com/user-attachments/assets/85eccff8-b40c-4df9-841f-1bd9ec7a9b69)
![강준구_논문요약본_page-0006](https://github.com/user-attachments/assets/5eb40f4f-bf4a-4a3b-826d-fc429020fa14)
