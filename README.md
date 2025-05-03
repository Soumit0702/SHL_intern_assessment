# SHL_intern_assessment
The Grammar Scoring Engine is an AI system that evaluates grammar in 45–60s spoken samples, scoring 0–5. It combines acoustic and text-based analysis to mirror human judgment, achieving a **0.6303** Pearson correlation with expert ratings, offering fast, consistent, and objective grammar assessment.

1. Data Preparation workflow

data/
├── audios/
│   ├── train/
│   │   ├── audio_710.wav
│   │   └── ...
│   └── test/
│       ├── audio_804.wav
│       └── ...
├── train.csv
└── test.csv


2.Notebook Execution Order

1. Environment Setup
2. Data Loading
3. Feature Extraction
4. Data Preprocessing
5. Model Training
6. Performance Visualization
7. Test Prediction
8. Submission Generation


This README provides:
- Clear setup instructions
- Visual workflow explanation
- Troubleshooting guide
- Performance benchmarks
- File structure requirements

For detailed implementation, refer to the Jupyter notebook comments and report section.
