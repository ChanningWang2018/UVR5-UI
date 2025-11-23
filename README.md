---
domain: #领域：cv/nlp/audio/multi-modal/AutoML
# - cv
tags: #自定义标签
-
datasets: #关联数据集
  evaluation:
  #- iic/ICDAR13_HCTR_Dataset
  test:
  #- iic/MTWI
  train:
  #- iic/SIBR
models: #关联模型
- OhMyDearAI/audio-separator-models

# 启动文件(若SDK为Gradio/Streamlit，默认为app.py, 若为Static HTML, 默认为index.html)
deployspec:
   entry_file: app.py
license: MIT License
---

Ultimate Vocal Remover 5 with Gradio UI on ModelScope. Separate an audio file into various stems, using multiple models.