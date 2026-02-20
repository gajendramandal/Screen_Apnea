# Screen_Apnea
```
ScreenApnea/
.gitattributes
CollectedData/
├── Gajendra2025-02-1615-03-39.avi
└── thermalvideo.txt
Frameextraction/
└── 01gajframes/
    ├── 01frame[0-261].png (~262 files)
    └── 01varied[22-258].png (~150 files)
Resultanalysisallfile/
├── P011/ (*.csv: EXP-1*, ex1*, meanpixel*, processedchestresp)
├── P012/ (*.csv: EXP-2*, ex2*, downsample*, exp2; graphs.png, thermalrec2.avi)
├── P013/ (*.csv: EXP-3*, ex3*; output.png, thermalrec3.avi)
└── P014/ (*.csv: EXP-4*, ex4*; thermalrec4.avi)
YOLOModelTraining/
├── .venv/Lib/site-packages/ (pip packages, *.pyc, *.py - thousands)
├── best.pt
├── *.ipynb (main100, mean, mean1, sc)
├── data.yaml
├── runs/
│   ├── detect/
│   └── train[1-8]/ (args.yaml x8, events.out.tfevents.* x8, labels.jpg x8)
├── test/images/ (*.png: 01-12frame*, 01-12varied* - ~200 files)
├── labels/ (*.txt: 01-12frame*, 01-12varied* - ~2000 files)
└── train/images/ (01frame[0-261].png, 01varied* - ~400 files)
README.md
```

