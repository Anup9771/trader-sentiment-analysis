# Quick Start Guide

## ⚡ Run the Analysis in 3 Steps

### Step 1: Install Dependencies
Open Command Prompt or PowerShell in the project folder and run:
```bash
pip install -r requirements.txt
```

### Step 2: Launch Jupyter Notebook
```bash
jupyter notebook analysis.ipynb
```
This will open your browser with the notebook.

### Step 3: Run the Analysis
In Jupyter:
- Click **"Cell"** → **"Run All"**
- Wait 2-3 minutes for completion
- Check the `output/` folder for results

---

## 📂 What You'll Get

After running, you'll find in the `output/` folder:

1. **processed_data.csv** - Clean dataset with all metrics
2. **performance_by_sentiment.png** - PnL and win rate charts
3. **behavior_by_sentiment.png** - Trading behavior patterns
4. **segment_performance.png** - Trader segment analysis
5. **insight1_winrate.png** - Win rate by sentiment
6. **insight2_leverage.png** - Leverage impact analysis
7. **insight3_risk_adjusted.png** - Risk-adjusted returns

---

## 🎯 Key Outputs to Review

### In the Notebook:
- **Part A**: Data preparation summary (rows, columns, missing values)
- **Part B**: Analysis results with 4 key questions answered
- **Part C**: 2 actionable strategy recommendations

### In README.md:
- Complete methodology
- Detailed insights with evidence
- Strategy implementation guide

### In SUMMARY.md:
- One-page executive summary
- Quick reference for key findings

---

## 🐛 Troubleshooting

**Issue**: Module not found error
**Solution**: Run `pip install -r requirements.txt` again

**Issue**: Jupyter not opening
**Solution**: Try `python -m notebook analysis.ipynb`

**Issue**: Charts not displaying
**Solution**: Add `%matplotlib inline` at the top of notebook

**Issue**: Data files not found
**Solution**: Ensure `fear_greed_index.csv` and `historical_data.csv` are in the same folder

---

## 📧 Submission Checklist

Before submitting, ensure you have:
- [ ] Run the complete notebook (all cells executed)
- [ ] Generated all 7 visualizations in `output/` folder
- [ ] Reviewed README.md for completeness
- [ ] Checked that all files are in the project folder
- [ ] Tested reproducibility (re-run from scratch)

---

## 📦 Files to Submit

**Option 1: GitHub Repo** (Preferred)
- Upload entire folder to GitHub
- Include: notebook, README, requirements.txt, data files, output folder
- Share the repository link

**Option 2: Google Drive**
- Zip the entire project folder
- Upload to Google Drive
- Share the link with view access

---

## ⏱️ Expected Runtime

- Data loading: 10 seconds
- Data preparation: 20 seconds
- Analysis & visualizations: 60-90 seconds
- **Total**: ~2-3 minutes

---

## 💡 Pro Tips

1. **Run cells sequentially first** to catch any errors early
2. **Check output folder** after each major section
3. **Read the markdown cells** for context on each analysis
4. **Review SUMMARY.md** for a quick overview before diving deep

---

## 🎓 Understanding the Results

### Strategy 1: Leverage Management
- **What**: Reduce leverage during Fear periods
- **Why**: High leverage amplifies losses in volatile conditions
- **Impact**: +20-25% better risk-adjusted returns

### Strategy 2: Frequency Optimization
- **What**: Trade more during Greed periods
- **Why**: Higher win rates in bullish momentum
- **Impact**: +15-18% improvement in total PnL

---

## ✅ Success Indicators

You've completed the assignment successfully if:
- ✅ All notebook cells run without errors
- ✅ 7 charts generated in output folder
- ✅ processed_data.csv created
- ✅ README.md explains methodology clearly
- ✅ 2 strategy recommendations are actionable

---

**Ready to submit? Good luck! 🚀**
