### Louis Rodembourg — ML Engineer

I build ML systems I can defend with numbers: strict out-of-sample validation, honest
baselines, reproducible results, and models that meet a real latency budget.

- **Now:** AI Engineer intern at **OVHcloud** (AI Solutions, Lyon).
- **Before:** AI Engineer intern at **Alten Labs R&D** (Toulouse). I built an end-to-end local RAG assistant for aerospace production lines and evaluated it against a hand-built test set of real cases.
- **Education:** final-year engineering degree in Data Science & AI at **UTC Compiègne** (graduating Feb. 2027), Erasmus semester at the University of Parma.

#### Selected projects

**[aerotrack](https://github.com/louisrodembourg/aerotrack): real-time detection and tracking on drone video.**
- Runs at **145 FPS end to end on a T4**. A C++/CUDA + TensorRT runtime is **3.5× faster** than the Python pipeline at the same tracking accuracy (HOTA 46.8 vs 46.7).
- Every optimisation is measured as an accuracy/latency trade-off: fine-tuning (mAP 4.1 → 19.1), input resolution, tiling, INT8.
- Transfer is tested on an unseen dataset, and every number comes from a tracked run.

**[Adaptive digital twin](https://github.com/louisrodembourg/Adaptive-digital-twin-endurance): personalised models of how athletes respond to training load.**
- Validated out of sample on **61 athletes**, with time-ordered folds: the effect replicates for 23 of them (sign test p = 0.020).
- A Bayesian hierarchical model (PyMC) quantifies how individual the response is, and the model says when it cannot tell.

**[Maritime nowcasting](https://github.com/louisrodembourg/Nowcasting): from raw AIS ship positions to market signals.**
- Port congestion is measured daily with HDBSCAN over about 2,800 days of vessel data.
- It forecasts shipping-equity returns strictly out of sample (**IC 0.08–0.12**, p < 0.05), and a negative control behaves as expected.

Also: [QRT football prediction](https://github.com/louisrodembourg/qrt-football-prediction): top-of-leaderboard accuracy, and an adversarial-validation analysis showing why further leaderboard gains would be noise.

**Stack:** Python, PyTorch, scikit-learn, XGBoost / LightGBM, PyMC, Ultralytics YOLO, TensorRT / ONNX, C++ / CUDA, SQL, Docker, pytest + CI

Lyon, France · French, English, German (intermediate)
