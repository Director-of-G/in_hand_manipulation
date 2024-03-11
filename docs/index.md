# Contact-Implicit Model Predictive Control for Dexterous In-hand Manipulation: A Long-Horizon and Robust Approach

The paper is submitted to [IROS2024](https://iros2024-abudhabi.org/).

The source code will be released after the publication of the paper.

<!-- [[arXiv](https://arxiv.org/abs/2310.09899)] -->

You can access the pre-print version on [arXiv](https://arxiv.org/abs/2402.18897)!

## Video

<p align="center">
<iframe width="800" height="450" src="./video_short.mp4" title="24_inhand_manipulation_iros" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

## Abstract

Dexterous in-hand manipulation is an essential skill of production and life. Nevertheless, the highly stiff and mutable features of contacts cause limitations to real-time contact discovery and inference, which degrades the performance of model-based methods.

Inspired by recent advancements in contact-rich locomotion and manipulation, this paper proposes a novel model-based approach to control dexterous in-hand manipulation and overcome the current limitations.The proposed approach has the attractive feature, which allows the robot to robustly execute long-horizon in-hand manipulation without pre-defined contact sequences or separated planning procedures. 

Specifically, we design a contact-implicit model predictive controller at high-level to generate real-time contact plans, which are executed by the low-level tracking controller. 

Compared with other model-based methods, such a long-horizon feature enables replanning and robust execution of contact-rich motions to achieve large-displacement in-hand tasks more efficiently; Compared with existing learning-based methods, the proposed approach achieves the dexterity and also generalizes to different objects without any pre-training.

Detailed simulations and ablation studies demonstrate the efficiency and effectiveness of our method. It runs at 20Hz on the 23-degree-of-freedom long-horizon in-hand object rotation task.


## Contact
If you have any question, feel free to contact the authors: Yongpeng Jiang, [jiangyp19@gmail.com](mailto:jiangyp19@gmail.com) .

Yongpeng Jiang's Homepage is at [director-of-g.github.io](https://director-of-g.github.io).
