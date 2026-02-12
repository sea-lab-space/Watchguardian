# Watchguardian

Website for the Personalized Intervention (Watchguardian) research project.

Paper: WatchGuardian: Enabling User-Defined Personalized Just-in-Time Intervention on Smartwatch

Link: https://dl.acm.org/doi/abs/10.1145/3788689

Website: https://sea-lab.space/Watchguardian/

## Abstract
While just-in-time interventions (JITIs) have effectively targeted common health behaviors, individuals often have unique needs to intervene in personal undesirable actions that can negatively affect physical, mental, and social well-being. We present WatchGuardian, a smartwatch-based JITI system that empowers users to define custom interventions for personal actions with few samples. To detect new actions from limited data, we developed a few-shot learning pipeline that finetuned a pre-trained inertial measurement unit (IMU) model on public hand-gesture datasets. We then designed a data augmentation and synthesis process to train additional classification layers for customization. Our offline evaluation with 26 participants showed that with three, five, and ten examples, our approach achieved an accuracy of 76.8%, 84.7%, and 87.7%, and an F1 score of 74.8%, 84.2%, and 87.3%. We then conducted a four-hour intervention study to compare WatchGuardian against a rule-based intervention. Our results demonstrated that our system led to a significant reduction by 64.0±22.6% in undesirable actions, substantially outperforming the baseline by 29.0%. Our findings underscore the effectiveness of a customizable, AI-driven JITI system for individuals in need of behavioral intervention in personal undesirable actions. We envision that our work can inspire broader applications of user-defined personalized intervention with advanced AI solutions.

![WatchGuardian Overview](static/images/Figure1.png)

## Citing this work
If you use this work, please cite:

```bibtex
@article{lei2025watchguardian,
  title={Watchguardian: Enabling user-defined personalized just-in-time intervention on smartwatch},
  author={Lei, Ying and Cao, Yancheng and Wang, Will Ke and Dong, Yuanzhe and Yin, Changchang and Cao, Weidan and ...},
  journal={ACM Transactions on Computing for Healthcare},
  year={2025},
  publisher={ACM New York, NY}
}
```