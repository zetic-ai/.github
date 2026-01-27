<img width="627" height="260" alt="Zetic_Logo_627x260_margin_white" src="https://github.com/user-attachments/assets/9b1bbab5-8c7f-4bf9-9953-e344420561d6" />

# ZETIC.ai - The End-to-End Software Infrastructure for On-Device AI

**Build. Deploy. Run Anywhere.**  <br/><br/>
We eliminate the need for costly GPU cloud servers by transforming your existing AI models into **NPU-optimized, on-device runtimes** in **hours, not weeks** — across **any mobile device, any OS**.

## 📡 Connect with Us
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://zetic.ai)
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-7289da?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/invite/gVFX6myuMx)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/company/zetic-ai)
[![Email](https://img.shields.io/badge/Email-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@zetic.ai)

---

## 🚀 About ZETIC.ai

AI services shouldn't be **tied** to the cloud.  
**MLange** (pronounced *Mélange*) is our flagship **end-to-end on-device AI deployment platform**. We help mobile developers run AI models locally, from flagship smartphones to budget devices, making AI **Faster, Cheaper, Safer, and Independent**.

We provide:
- **Automated Model Conversion**: PyTorch, ONNX, or TFLite → device-specific NPU libraries.
- **Peak Performance**: Up to **60× faster** than mobile CPU inference, with massive energy savings.
- **Cross-Platform SDKs**: Swift, Kotlin, Flutter, React Native for any app stack.
- **Benchmarking**: Test your models across **200+ global devices** with real-world hardware metrics.
- **Full Privacy by Design**: All inference happens locally; no data leaves the device.

## 🧠 Why We're Different

While other frameworks focus on model quantization or partial device deployment, **we handle the entire lifecycle**:
1. **Analyze** model architecture and runtime requirements.
2. **Convert & Optimize** for heterogeneous NPUs (Qualcomm, MediaTek, Apple, etc.).
3. **Benchmark** on real devices for latency, accuracy, and memory.
4. **Deliver** drop-in SDKs ready for mobile integration.
5. **Support** continuous updates at scale.

> No guesswork. No vendor lock-in. Just working on-device AI in hours, not weeks.

---

## 📊 Real Benchmark Highlights

### YOLO26 — NPU Latency (ms)
| Device | Manufacturer | CPU | GPU | NPU |
|--------|--------------|-----|-----|-----|
| Apple iPhone 16 Pro | Apple | 91.44 | 6.64 | **1.88** |
| Apple iPhone 15 Pro | Apple | 86.80 | 9.22 | **2.57** |
| Samsung Galaxy S25 Ultra | Qualcomm | 52.10 | 153.27 | **11.05** |
| Samsung Galaxy Tab S9 | Qualcomm | 64.75 | 200.13 | **13.61** |
| Xiaomi 13 Pro | Qualcomm | 58.97 | 118.20 | **12.79** |

---

### Whisper-tiny-encoder — NPU Latency (ms)
| Device | Manufacturer | CPU | GPU | NPU |
|--------|--------------|-----|-----|-----|
| Apple iPhone 16 | Apple | 553.78 | 42.56 | **18.82** |
| Apple iPhone 15 Pro | Apple | 521.65 | 40.89 | **19.67** |
| Samsung Galaxy S25 Ultra | Qualcomm | 246.08 | **102.36** | 128.94 |
| Samsung Galaxy S24 Ultra | Qualcomm | 270.61 | **120.29** | 147.12 |
| Xiaomi 12 | Qualcomm | 302.33 | 280.13 | **151.77** |

> *Note: Lower is better. Full dataset available on the [MLange Dashboard](https://mlange.zetic.ai).*

<br/>

## 👨🏻‍💻 Plug-and-play Integration

- Deploying NPU-accelerated models takes just a few lines of code with the **MLange SDK**.

- **iOS Integration** (Swift)

``` swift
// (1) Load MLange model
let model = try ZeticMLangeModel(tokenKey: "MLANGE_PERSONAL_KEY", "MODEL_REPO_NAME")

// (2) Prepare model inputs
let inputs: [Tensor] = [] // Prepare your inputs

// (3) Run and get output tensors of the model
let outputs = try model.run(inputs)

```

- **Android Integration** (Kotlin, Java)

``` kotlin
// (1) Load MLange model
val model = ZeticMLangeModel(context, "MLANGE_PERSONAL_KEY", "MODEL_REPO_NAME")

// (2) Prepare model inputs
val inputs: Array<Tensor> = // Prepare your inputs

// (3) Run and get output tensors of the model
val outputs = model.run(inputs)
```


## 🛠️ Ready to Build?

Don't start from scratch. We have created a repository of **production-ready, open-source, on-device AI apps** that you can clone, run, and modify in minutes.

### [Explore the ZETIC MLange Apps Repository](https://github.com/zetic-ai/ZETIC_MLange_apps)

<br/>
</div>

---

## 📚 Resources

### Official Links
- **Website**: [zetic.ai](https://zetic.ai)
- **MLange Dashboard**: [mlange.zetic.ai](https://mlange.zetic.ai) — Get NPU-optimized SDKs, view benchmarks, and upload custom models.
- **Documentation**: [docs.zetic.ai](https://docs.zetic.ai) — Full API reference and implementation guides.
- **Discord**: [Join our Community](https://discord.com/invite/gVFX6myuMx) — Get support, share your projects, and meet other developers.

### Check Out Our Official App
See MLange performance in action on your own device: **ZeticApp**: [**Android**](https://play.google.com/store/apps/details?id=com.zeticai.zeticapp) | [**iOS**](https://apps.apple.com/app/zeticapp/id6739862746)

<div align="center">

**By ZETIC.ai**

[⭐ Star us on GitHub](https://github.com/zetic-ai/ZETIC_MLange_apps) • [🐛 Report Bug](https://github.com/zetic-ai/ZETIC_MLange_apps/issues) • [💡 Request Features](https://discord.com/invite/gVFX6myuMx) • [🚀 Try MLange](https://mlange.zetic.ai) • [📖 Documentation](https://docs.zetic.ai)

</div>
