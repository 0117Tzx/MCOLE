# SAUD2.0-Dataset and MCOLE-Method for underwater image quality assessment
implementation of ''Towards Dimension-Enriched Underwater Image Quality Assessment''.

## 📋 Table of content
1. 📎[Paper Link](#paper-link)
2. 💡[Abstract](#abstract)
3. 📃[Requirement](#requirement)
4. 📖[Usage](#usage)
5. ✨[Statement](#statement)
6. 🔍[Citation](#citation)

## 📎Paper Link
Towards Dimension-Enriched Underwater Image Quality Assessment
- Authors: Qiuping Jiang, Xiao Yi, Li Ouyang, Jingchun Zhou, Zhihua Wang
- Institution: The School of Information Science and Engineering, Ningbo University

## 💡Abstract
The absorption and scattering of light in the water medium naturally impair the quality of underwater images, leading to multiple degradation effects including color casts, reduced visibility, and blurriness. Underwater Image Enhancement (UIE) techniques strive to mitigate these issues, yet the efficacy of different UIE algorithms remains highly variable. This variability underscores the necessity for an objective quality metric capable of precisely assessing the visual quality of underwater images. Traditional quality metrics, which primarily rely on a single score to depict the overall quality level, are insufficiently comprehensive to describe the complex degradation characteristics intrinsic to underwater environments and the multi dimensional nature of underwater image quality. To address this issue, we construct the first UIE quality evaluation dataset with multi-dimensional quality annotations, broadening the subjective labels from a single overall quality score to multiple specific degradation-related scores. The dataset is known as an enhanced version of our previous Subjectively Annotated UIE Benchmark Dataset (SAUD) and is called SAUD2.0 hereinafter. Based on the SAUD2.0 dataset, we also introduce a Multi-stream COllaborative LEarning network (MCOLE) tailored for quality evaluation of enhanced underwater images. MCOLE capitalizes on the multidimensional quality annotations within SAUD2.0, facilitating the training of three specialized networks focused on extracting distinct sets of features: color, visibility, and semantic. These extracted features are then interacted and cohesively merged for quality prediction. Comprehensive experiments conducted on two benchmark datasets reveal that the proposed MCOLE outperforms current underwater image quality metrics. These results clearly validate the efficacy of exploring the multi-dimensional nature of underwater image quality and integrating such multi-dimensional quality annotations into underwater image quality evaluation.

## 📃Requirement
pytorch

## 📖Usage
You can download our SAUD-Dataset from（Modification date 2022.05.05）
>BaiduYun Disk: [SAUD2.0-Dataset-released](https://pan.baidu.com/s/1pLIMWQtDjgjbwrHwagKjRg)  (key1234)
>
>Google Drive: [SAUD2.0-Dataset-released](https://drive.google.com/file/d/1LaI-JjillyTPItTfLyphly8rukZF3hRz/view?usp=sharing)

You can download our NUIQ-Metric from
>BaiduYun Disk: [MCOLE-Metric-released](https://pan.baidu.com/s/1xp20E2yvCVTfuoiPViC7JQ)  (key:1234)
>
>Google Drive: [MCOLE-Metric-released](https://drive.google.com/file/d/12qxlh54mReVOwgJVQW5SXs7dtxpejYdi/view?usp=sharing)


## ✨Statement
This project is for research purpose only, please contact us for the licence of commercial use. For any other questions please contact jiangqiuping@nbu.edu.cn. 1664457169@qq.com.

## 🔍Citation
- If you find this work useful for you. Please cite:

[回到顶部](#readme)
