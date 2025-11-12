🧠 Overview

This experiment demonstrates how High-Performance Computing (HPC) environments, enhanced by GPU and TPU acceleration, can significantly reduce model training time while improving performance stability. The task focuses on image classification using the CIFAR-10 dataset, highlighting how computational parallelism transforms both speed and scalability in deep learning research.

✏️ Objective

To compare the performance and efficiency of GPU-based and TPU-based training for a convolutional neural network (CNN), analyze training speed differences, and observe improvements in stability and memory utilization across hardware configurations.

📗 Results

The experiment achieved a notable reduction in epoch duration and improved convergence when using GPU and TPU acceleration compared to CPU-based training. GPU execution provided consistent throughput with balanced resource usage, while TPU execution demonstrated faster batch processing and lower memory latency, confirming the advantage of parallel computation frameworks in AI research.

📓 Notes


Ensure GPU or TPU runtime is properly activated in Colab before execution.


Batch size and learning rate can be tuned to test scalability under HPC conditions.


The code structure is modular to allow integration with larger distributed training pipelines.


Performance may vary slightly depending on the Colab hardware version and available cores.

