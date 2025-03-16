# Thermal-Line-Detection

During my internship at the GIST MPIL lab, I focused on designing and optimizing feature detection and tracking algorithms for thermal imaging to enhance SLAM accuracy in visually constrained environments. 
<br>
🚀I updated my PPT slides which contain my research results.

## Results
I initially attempted to improve the resolution of thermal images using a GAN-based super-resolution approach, then applied LSD for line detection. ([PPT](./assets/Lab_Meeting#1.pdf))
<br>
However, the results were not satisfactory, prompting me to switch to the SOLD2 algorithm. 
By incorporating an unsharp mask, I observed significantly better performance in line detection. [PPT](./assets/Lab_Meeting#2.pdf)

## Future Tasks
- Continue utilizing the SOLD2 algorithm while training on a custom dataset collected with a DJI Mavic 3T.
- Construct an artificial environment with clearly divided thermal regions to facilitate more controlled data collection.
- Train the model on patterned 16-bit thermal images to enhance precision and robustness in feature detection.

