---
title: "Research"
permalink: /research/
author_profile: true
---

## Robotic Research
* ## Manipulation Planning by Exploiting Environmental Contact Using Screw Theory and Free Rotational Motion at Manipulator-Object Contact Interfaces (Ongoing Research)
In conventional contact-aided manipulation, the assumption of rigid contact between the manipulators and the object, limits the workspace and dexterity of the manipulators, particularly, when the object approaches configurations where the end-effector must execute extreme orientations, or when the manipulators approach the joint limits or singular configurations. In order to reduce the possibility of violating the manipulators' joint limits and increase the dexterity in object manipulation while at least one point of the object remains in contact with the environment, we can allow rotational motion/slippage at the contact interfaces of the manipulators and the object.

<table style="height:auto; width:auto;" cellspacing="0" cellpadding="0">
  <tr>
    <td><img src="https://raw.githubusercontent.com/MahiBoroji/MahiBoroji.github.io/master/_pages/research/v1.gif" width=auto height=auto alt=""></td>
    <td><img src="https://raw.githubusercontent.com/MahiBoroji/MahiBoroji.github.io/master/_pages/research/v4.gif" width=auto height=auto alt=""></td>
  </tr>
</table> 
<center>
    <img src="https://raw.githubusercontent.com/MahiBoroji/MahiBoroji.github.io/master/_pages/research/pivot.png" style="width: 40%; height: 40%;" alt="">
</center>

* ## Motion Planning for Object Manipulation by Edge-Rolling
A common way to manipulate heavy objects is to maintain at least one point of the object in contact with the environment during the manipulation. When the object has a cylindrical shape or, in general, a curved edge, not only sliding and pivoting motions but also rolling the object along the edge can effectively satisfy this condition. Edge-rolling offers several advantages in terms of efficiency and maneuverability. This paper aims to develop a novel approach for approximating the prehensile edge-rolling motion on any path by a sequence of constant screw displacements, leveraging the principles of screw theory. Based on this approach, we proposed an algorithmic method for task-space-based path generation of object manipulation between two given configurations using a sequence of rolling and pivoting motions. The method is based on an optimization algorithm that takes into account the joint limitations of the robot. To validate our approach, we conducted experiments to manipulate a cylinder along linear and curved paths using the Franka Emika Panda manipulator.

<table style="height:auto; width:auto;" cellspacing="0" cellpadding="0">
  <tr>
    <td><img src="https://raw.githubusercontent.com/MahiBoroji/MahiBoroji.github.io/master/_pages/research/EdgeRolling.png" width=480 height=360 alt=""></td>
    <td><img src="https://raw.githubusercontent.com/MahiBoroji/MahiBoroji.github.io/master/_pages/research/EdgeRolling_BackAndForthPath.gif" width=auto height=auto alt=""></td>
    <td><img src="https://raw.githubusercontent.com/MahiBoroji/MahiBoroji.github.io/master/_pages/research/EdgeRolling_FullCirclePath.gif" width=auto height=auto alt=""></td>
  </tr>
</table>

**Publication:**
- M. Boroji, V. Danesh, I. Kao, A. Fakhari, "[Motion Planning for Object Manipulation by Edge-Rolling](https://ieeexplore.ieee.org/document/10802581)," *2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, 2024.

<hr>


## Engineering-Medicine Research
* ## Skin Cancer Detection Using In-Vivo Raman Spectroscopy and Machine Learning Techniques (Ongoing Research)
This research focuses on the development of a non-invasive diagnostic approach for skin cancer detection by integrating in-vivo Raman spectroscopy with machine learning-based classification methods. Raman spectroscopy provides a molecular fingerprint of biological tissues, enabling the differentiation between healthy and malignant skin based on subtle biochemical variations. By collecting real-time spectral data through an in-vivo Raman probe, the study aims to identify diagnostic spectral features associated with different cancer types. Machine learning algorithms are employed to analyze and classify these spectra, improving diagnostic accuracy and reducing the need for invasive biopsies. 

**Related Presentations:**
- R. Basak, V. Danesh, M. Boroji, I. Kao, X. Qian, T. Zhang, S. Ryu, K. Mani, R. Cattel, "Skin Lesion Subtype Classification Using Lesion and Border Radiomic Features," *AAPM 67th Annual Meeting & Exhibition*, 2025. 

- M. Boroji, V. Danesh, P. Prasanna, J. Kim, X. Qian, M. Khari, K. Mani, B. Boyce, F. Khan, S. Ryu, I. Kao, R. Cattell, "Convolutional Neural Network Attention-Guided Segmentation to More Accurately Identify the Edges of Benign and Malignant Skin Tumors," *AAPM 66th Annual Meeting & Exhibition*, 2024. 

* ## Ex-vivo Raman spectroscopy and AI-based classification of soft tissue sarcomas
This research demonstrates how combining Raman spectroscopy—a tool that reveals the biochemical fingerprint of tissues—with AI can accurately distinguish between different types of soft tissue sarcomas and normal tissues. By scanning tissue samples from seven patients and collecting thousands of Raman spectra, a custom AI model (ResNet) was trained to classify eight tissue types, achieving an overall accuracy of 97.1%. This method provides an efficient, fast, and non-invasive alternative to traditional margin-assessment techniques, which are often slow and prone to errors.

<table style="height:auto; width:auto;" cellspacing="0" cellpadding="0">
  <tr>
    <td><img src="https://raw.githubusercontent.com/MahiBoroji/MahiBoroji.github.io/master/_pages/research/average_spectra.png" width=auto height=auto alt=""></td>
    <td><img src="https://raw.githubusercontent.com/MahiBoroji/MahiBoroji.github.io/master/_pages/research/cnn.png" width=auto height=auto alt=""></td>
  </tr>
</table>
<center>
  <td><img src="https://raw.githubusercontent.com/MahiBoroji/MahiBoroji.github.io/master/_pages/research/eval.png" width=auto height=auto alt=""></td>
</center>


**Publication and Open-access Data**
- M. Boroji, V. Danesh, D. Barrera, E. Lee, P. Arauz, R. Farrell, B. Boyce, F. Khan, I. Kao, “[Ex-vivo Raman spectroscopy and AI-based classification of soft tissue sarcomas](https://journals.plos.org/plosone/article/metrics?id=10.1371/journal.pone.0330618#viewedHeader),” *PLoS One*, vol. 20, iss. 9, 2025.
- M. Boroji "[RamanSTS dataset, a large collection of Raman spectra of soft tissue sarcomas](https://doi.org/10.7910/DVN/NGEZPA)," *Harvard Dataverse*, 2025.

* ## Uncertainty Propagation and Quantitative Assessment of Resection Planes of Vision-Guided Orthopedic Surgery Systems
Precise replication of the preoperative surgical plan is critical in computer-assisted orthopedic surgery (CAOS) systems to ensure accurate osteotomy lines for effective tumor resection. Existing surgical guidance systems rely on cameras, fiducial markers, or fluoroscopy for bone registration and real-time tracking. 
Thus, uncertainty due to errors in measurements, modeling, and calibration can accumulate and propagate within the CAOS system to the final resection. Quantifying such uncertainty is essential to evaluate the reliability of the system and to ensure safe surgical outcomes. 
This paper presents an experimental methodology to estimate uncertainties of a vision-guided orthopedic surgical system. The maximum distance deviation is evaluated for five Type II pelvic tumor resections, based on the quantitative uncertainty in each resection plane, to assess the risk of tumor intrusion and ensure the adequacy of the planned surgical margins. The objective of this research is to understand the uncertainty propagation stochastically,
to provide assessment of resection planes quantitatively in comparison with the preoperative plan, and to improve surgical decision-making and accuracy for patient safety.
 
<table style="height:auto; width:auto;" cellspacing="0" cellpadding="0">
  <tr>
    <td><img src="https://raw.githubusercontent.com/MahiBoroji/MahiBoroji.github.io/master/_pages/research/pelvic.png" width=auto height=auto alt=""></td>
    <td><img src="https://raw.githubusercontent.com/MahiBoroji/MahiBoroji.github.io/master/_pages/research/Uncertainty.png" width=auto height=auto alt=""></td>
  </tr>
</table>

**Publication:**
- M. Boroji, V. Danesh, P. Arauz, J. Tsai, I. Kao, "Uncertainty Propagation and Quantitative Assessment of Resection Planes of Vision-Guided Orthopedic Surgery Systems," *IEEE Transactions on Instrumentation & Measurement*, 2025, (under review).

*Related Publications:*
- V. Danesh, P. Arauz, M. Boroji, A. Zhu, M. Cottone, E. Gould, F. Khan, I. Kao, "[Improved Accuracy in Pelvic Tumor Resections Using a Real-Time Vision-Guided Surgical System](https://onlinelibrary.wiley.com/doi/full/10.1002/jor.26111#)," *Journal of orthopaedic research*, vol. 43, iss. 8, pp. 1485-1492, 2025.
- G. He, V. Danesh, M. Boroji, A. Kermanian, P. Arauz, F. Khan, I. Kao, "[Real-Time, Vision-Guided Orthopedic Surgery for Wide Resection of Primary Bone Sarcomas](https://shop.elsevier.com/books/handbook-of-robotic-and-image-guided-surgery/abedin-nasab/978-0-443-13912-3)," *Handbook of Robotic and Image-Guided Surgery 2nd edition, Elsevier*, ch. 37 (expected release date: December 2025).
