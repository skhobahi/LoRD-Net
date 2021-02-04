# LoRD-Net: Unfolded Deep Detection Network with Low-Resolution Receivers

This is a code package is related to the follow scientific article:

Shahin Khobahi, Nir Shlezinger, Mojtaba Soltanalian, and Yonina C. Eldar, “LoRD-Net: Unfolded Deep Detection Network with Low-Resolution Receivers,” Submitted to IEEE Transactions on Signal Processing, February 2021.

The package contains contains the code to reproduces parts of the numerical results and figures in the article.

## Abstract of Article
The need to recover high-dimensional signals from their noisy low-resolution quantized measurements is widely encountered in communications and sensing. In this paper, we focus on the extreme case of one-bit quantizers, and propose a deep detector entitled  LoRD-Net for recovering information symbols from one-bit measurements. Our method is a model-aware data-driven architecture based on deep unfolding of first-order optimization iterations. LoRD-Net has a task-based architecture dedicated to recovering the underlying signal of interest from the one-bit noisy measurements without requiring prior knowledge of the channel matrix through which the one-bit measurements are obtained. The proposed deep detector has much fewer parameters compared to black-box deep networks due to the incorporation of domain-knowledge in the design of its architecture, allowing it to operate in a data-driven fashion while benefiting from the flexibility, versatility, and reliability of model-based optimization methods. LoRD-Net operates in a blind fashion, which requires addressing both the non-linear nature of the data-acquisition system as well as identifying a proper optimization objective for signal recovery. Accordingly, we propose a two-stage training method for LoRD-Net, in which the first stage is dedicated to identifying the proper form of the optimization process to unfold, while the latter trains the resulting model in an end-to-end manner. We numerically evaluate the proposed receiver architecture for one-bit signal recovery in wireless communications and demonstrate that the proposed hybrid methodology outperforms both data-driven and model-based state-of-the-art methods, while utilizing small datasets, on the order of merely ~ 500 samples, for training. 

## Code Content

[TBW]

## License and Referencing
This code package is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.
