# ⚡ Trashformer - Quick Start Guide

## Get Started in 3 Minutes

---

## 🚀 Option 1: Run the Web App (Fastest)

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run the Flask app
python app.py

# 3. Open your browser
# Visit: http://127.0.0.1:5000
```

**Features Available**:
- 📸 **Upload Images**: File upload and drag & drop
- 📷 **Camera Capture**: Direct photo capture from device  
- 🎥 **Live Localization**: Start/Stop live camera with continuous predictions
- 📊 **Batch Processing**: Process multiple images simultaneously
- ♻️ **Disposal Tips**: Contextual tips under results
- 📈 **Analytics Dashboard**: Counts, confidence trend, geo map, leaderboard
- ⬇️ **Exports**: CSV and PDF

---

## 🧪 Option 2: Test the Model

```bash
# Test on validation set (if you have the dataset)
python scripts/test_model.py 2

# Visualize training results
python scripts/visualize_training.py
```

---

## 📊 Option 3: Train Your Own Model

**Note**: Requires dataset download from [TrashBox](https://github.com/nikhilvenkatkumsetty/TrashBox)

```bash
# 1. Download and organize dataset into waste_data_split/train and waste_data_split/val

# 2. Run training
python scripts/train_trashformer.py

# Training time: ~3.5 hours on CPU (AMD Ryzen 5 5500)
```

---

## 📁 Project Structure

```
Trashformer/
├── app.py              # Flask web app (run this!)
├── templates/          # HTML templates
├── static/             # CSS/JS assets
│   ├── styles.css      # UI styling
│   ├── script.js       # App logic
│   └── analytics.js    # Analytics visuals
├── models/             # Trained models (4 files)
├── scripts/            # Training & testing scripts
├── docs/               # Documentation
├── images/             # Visualizations
└── README.md           # Full documentation
```

---

## 🎯 What You Get

- 🤖 **AI Model**: 85.16% accuracy waste classifier
- 🌐 **Flask Interface**: Professional web application
- 📱 **Mobile Support**: Camera capture
- 📊 **Visualizations**: Training graphs and metrics
- 📚 **Documentation**: Complete guides

---

## 📚 Documentation

- **README.md** - Complete overview (start here)
- **docs/ROADMAP.md** - How it was built
- **docs/PRESENTATION_GUIDE.md** - For teachers
- **docs/TECHNICAL_DOCS.md** - Technical details

---

## 🏆 Key Features

| Feature | Status |
|---------|--------|
| Web Application | ✅ Working |
| AI Model (85% accuracy) | ✅ Trained |
| Mobile Support | ✅ Included |
| Documentation | ✅ Complete |
| Visualizations | ✅ Professional |

---

##  Requirements

```
Python 3.10+
TensorFlow 2.12+
Flask 2.3+
4GB+ RAM
```

---

## ⚡ Fast Demo

```bash
python app.py
```

Then upload any image - the AI will classify it instantly!

---

**Need help?** See `README.md` for full documentation.

**For teachers?** Check `docs/PRESENTATION_GUIDE.md`

---

<div align="center">

**Ready in 3 commands!** 🚀

`pip install -r requirements.txt` → `python app.py` → Open browser

</div>

