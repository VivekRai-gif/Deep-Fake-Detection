# 🎭 Deepfake Detection using Deep Learning (ResNeXt + LSTM)

> ⭐ **Star this repo** if you find it useful  
> ☕ **Support the project**: Buy Me A Coffee

---

## 🚀 Latest Update

🎉 **Dockerized Deployment Added!**  
Easily run the Django application in seconds using Docker — no more worrying about dependencies or environments.

---

## 📘 Introduction

This project aims to detect deepfake videos using deep learning, combining **ResNeXt** (a convolutional neural network) for feature extraction and **LSTM** (Long Short-Term Memory) for temporal sequence learning.

We use **transfer learning** by extracting frame-level features using a pretrained ResNeXt model, followed by LSTM classification to detect real vs. fake content.

📺 Watch the full [YouTube Playlist](#) for installation and demo  
📝 Read more on [Medium](#)  
📚 Check the [Documentation](#) for detailed insights

---

## 📁 Directory Structure


---

## 🖥️ Demo

▶️ **Watch Demo Video**: [YouTube Link](#)

---

## 📊 Our Results

| Model Name                             | Videos | Frames | Accuracy (%) |
|---------------------------------------|--------|--------|---------------|
| model_84_acc_10_frames_final_data.pt  | 6000   | 10     | 84.21         |
| model_87_acc_20_frames_final_data.pt  | 6000   | 20     | 87.79         |
| model_89_acc_40_frames_final_data.pt  | 6000   | 40     | 89.35         |
| model_90_acc_60_frames_final_data.pt  | 6000   | 60     | 90.59         |
| model_91_acc_80_frames_final_data.pt  | 6000   | 80     | 91.50         |
| model_93_acc_100_frames_final_data.pt | 6000   | 100    | **93.59**     |

---

## ⚖️ License

This project is licensed under the **GNU GPL v3 License**.  
See the [LICENSE](./LICENSE) file for more information.

---

## 🤝 We Welcome Open Source Contributions

We encourage contributions from the community! Some improvement ideas:
- 🌐 Deploy on free cloud platforms
- 🌍 Build a public API for detection
- 🎥 Support full video processing instead of limited frames
- ⚡ Optimize for speed and lower memory usage

✅ Already Completed:
- ✅ Dockerized deployment  
- ✅ Support for non-CUDA systems (including AMD GPUs)

---

## 🙌 Support the Project

If this project helped you, consider:
- ⭐ **Starring** the repository  
- ☕ **[Buying Me A Coffee](#)** to support continued development

---

## 📦 Repository Info

- **License:** GPL-3.0  
- **Languages:**  
  - Jupyter Notebook: 99.7%  
  - Other: 0.3%  
- **Stars:** 🌟 1  
- **Forks:** 🍴 0  
- **Watchers:** 👀 0

---

> Made with ❤️ by passionate deep learning enthusiasts.
