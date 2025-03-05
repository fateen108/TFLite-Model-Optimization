TensorFlow Lite Model Optimization 🚀

Optimize AI models for edge devices using TensorFlow Lite quantization! This project benchmarks inference time and model size improvements when applying post-training quantization to a deep learning model.

📌 Overview

Deploying AI models on edge devices requires efficient models that run with low latency and minimal memory usage. This tutorial explores how to:

Convert a MobileNetV2 model to TensorFlow Lite format.

Apply post-training quantization to reduce model size.

Benchmark inference time before & after quantization.

Compare performance improvements.

🔧 Installation & Setup

To get started, clone this repository and install dependencies:


🚀 Running the Optimization

Run the Python script to:

Convert the MobileNetV2 model to TensorFlow Lite.

Benchmark inference time.

Apply quantization and compare performance.

python tflite_quantization.py

📊 Results (Performance Comparison)

Model Version

Inference Time (ms)

Model Size (MB)

Original Model

62.39 ms

13.34 MB

Quantized Model

21.13 ms

3.62 MB

✅ Model size reduced by ~73%✅ Inference time improved significantly


📖 References

TensorFlow Lite Documentation

MLPerf Benchmarks

TinyML Community

🛠 License

see the LICENSE file for details.

🙌 Contributions Welcome! If you found this helpful, feel free to fork the repo, improve it, and submit a pull request! 🚀
