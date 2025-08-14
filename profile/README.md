![ZETIC.ai Banner](assets/banner.jpg)

# ZETIC.ai — On-Device AI for Every Device

**Build. Deploy. Run. Anywhere.**  
We eliminate the need for costly GPU cloud servers by transforming your existing AI models into **NPU-optimized, on-device runtimes** in **under 24 hours** — across **any mobile device, any OS**.

---

## 📡 Connect with Us
[![GitHub Repos](https://img.shields.io/badge/Codebase-grey?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ZETIC-ai)
[![Email](https://img.shields.io/badge/Email-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@zetic.ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/company/zetic-ai)
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://zetic.ai)

---

## 🚀 About ZETIC.ai

AI services shouldn't be shackled to the cloud.  
**ZETIC.MLange** is our flagship **end-to-end on-device AI deployment platform**, enabling developers to **run AI models anywhere** — from flagship smartphones to entry-level devices — without rewriting code or hiring specialized hardware engineers.

We provide:
- **Automated Model Conversion**: PyTorch, ONNX, or TFLite → device-specific NPU libraries.
- **Peak Performance**: Up to **60× faster** than GPU cloud inference, **0 accuracy loss**.
- **Cross-Platform SDKs**: Swift, Kotlin, C/C++, Python bindings for any app stack.
- **Benchmarking at Scale**: Test your models across **50+ global devices** with real-world hardware metrics.
- **Full Privacy by Design**: All inference happens locally; no data leaves the device.

---

## 🧠 Why We're Different

While other frameworks focus on model quantization or partial device deployment, **we handle the entire lifecycle**:
1. **Analyze** model architecture and runtime requirements.
2. **Convert & Optimize** for heterogeneous NPUs (Qualcomm, MediaTek, Apple, etc.).
3. **Benchmark** on real devices for latency, accuracy, battery drain.
4. **Deliver** drop-in SDKs ready for mobile integration.
5. **Support** continuous updates at scale.

> No guesswork. No vendor lock-in. Just working on-device AI in 24 hours.

---

## 📊 Real Benchmark Highlights

### YOLOv8n — NPU Latency (ms)
| Device | Manufacturer | CPU | GPU | NPU |
|--------|--------------|-----|-----|-----|
| Apple iPhone 16 Pro | Apple | 122.23 | - | **1.69** |
| Samsung Galaxy S24 Ultra | Qualcomm | 69.33 | 23.31 | **3.82** |
| Samsung Galaxy S23 Ultra | Qualcomm | 96.61 | 30.34 | **4.71** |
| Google Pixel 8a | Google | 105.14 | 42.91 | — |

### Whisper-tiny-encoder — NPU Latency (ms)
| Device | Manufacturer | CPU | GPU | NPU |
|--------|--------------|-----|-----|-----|
| Apple iPhone 16 Pro | Apple | 540.04 | - | **18.15** |
| Samsung Galaxy S24+ | Qualcomm | 278.78 | 133.48 | **106.44** |
| Xiaomi 12 | Qualcomm | 319.26 | 304.82 | **162.25** |
| Samsung Galaxy A34 | MediaTek | 837.03 | 593.11 | **6080.97** |

> Full dataset: [MLange Benchmark Dashboard](https://zetic.ai/benchmarks)

---

## 👨🏻‍💻 Plug-and-play To Your App

- The runtime SDK is also provided for your AI model with ZETIC.MLange

- **iOS Integration** (Swift)

``` swift

// import
import ZeticMLange

// ...

// (1) Load Zetic MLange model
let model = try ZeticMLangeModel("MLANGE_PROJECT_API_KEY")

// (2) Run model after preparing model inputs
let inputs: [Data] = [] // Prepare your inputs

try model.run(inputs)

// (3) Get output data array
let outputs = model.getOutputDataArray()

```

- **Android Integration** (Kotlin, Java)

``` kotlin
// import
import com.zeticai.mlange.core.model.Target
import com.zeticai.mlange.core.model.ZeticMLangeModel

// ...

// (1) Load Zetic MLange model
val model = ZeticMLangeModel(this, "MLANGE_PROJECT_API_KEY")

// (2) Run model after preparing model inputs
val inputs: Array<ByteBuffer> = // Prepare your inputs

model.run(inputs)

// (3) Get output buffers of the model
val outputs = model.outputBuffers
```


