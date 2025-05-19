<p align="center">HBUED: An EEG Dataset for Emotion Recognition</p>

<p style="text-align: justify;">Emotion recognition via electroencephalogram (EEG) data is crucial for improving human-computer interaction. In practice, researchers require a substantial quantity of EEG samples for the training and validation of models. However, existing EEG datasets typically have a limited number of subjects. To address this issue, this paper presents a large-scale EEG dataset, the Hebei University Emotional EEG Dataset (HBUED), specifically designed for research on human emotion recognition. Furthermore, this research presents a deep learning methodology aimed at improving emotion recognition performance by efficiently handling complicated samples in EEG-based emotion recognition. This method first constructs a dual-input network architecture to extract discriminative features of EEG signals from two perspectives for classification. Furthermore, this paper uses a parallel feature extraction module for EEG signals, which increases the number of neurons per layer by expanding the network width, thereby extracting more comprehensive feature information while avoiding overfitting caused by excessive network depth. In addition, a topological feature extraction module has been created to better capture the topological characteristics of EEG signals. Lastly, the proposed method is validated on both the self-constructed HBUED and the public DEAP datasets, with experimental results demonstrating its effectiveness. The HBUED datasets and the source code of the proposed method are publicly available at: https://tensorground.github.io/HBUED.github.io/.</p>

If you need to use this dataset, please complete the license agreement we provide and send it to the designated email address. We will provide access as soon as possible.

After filling out the license agreement, please send it to the following email address: cvmdsp@163.com. We will reply as soon as possible.

**Cite**: Shuaiqi Liu, Xinrui Wang, Yanling An, Zeyao Wang, Zhihui Gu, Yudong Zhang, Shuhuan Zhao, HBUED: An EEG dataset for emotion recognition, Journal of Affective Disorders, 2025: 119397.

**Dataset Description**: This dataset contains the EEG data of 50 subjects (the data have been preliminarily preprocessed using eeglab), and the stimulation forms of the dataset are as follows:
| Target Emotion Category | Duration | Frame Rate | Video Content Description |
| ---- | ---- | ---- | ---- |
| **High Valence**<br>**High Arousal** | 120 sec | 15 fps | Olympic hurdling gold medal clip |
|  |  |  | Olympic shooting gold medal clip |
|  |  |  | Scene from City of Rock |
|  |  |  | Scene from Lost on Journey |
|  |  |  | Scene from The Mermaid |
|  |  |  | Women's football match clip |
| **High Valence**<br>**Low Arousal** | 120 sec | 15 fps | Grassland scenery video |
|  |  |  | Seaside travel video |
|  |  |  | Waterfall scenery video |
|  |  |  | Afternoon relaxation video |
|  |  |  | Violin music video |
|  |  |  | Calming nature landscape video |
| **Low Valence**<br>**High Arousal** | 120 sec | 15 fps | Scene from Cry Me a Sad River |
|  |  |  | Scene from Fist of Fury |
|  |  |  | Scene from a wartime documentary |
|  |  |  | Scene from The Ring |
|  |  |  | Scene from The Bravest |
|  |  |  | Scene from a documentary on Japan's Unit 731 |
|  |  |  | Closing credits clip from a film |
| **Low Valence** | 120 sec | 15 fps | Scene from a documentary on Miao silver - crafting |
|  |  |  | Micro - video of classroom teaching |
