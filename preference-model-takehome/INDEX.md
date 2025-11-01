# Preference Model Take-Home Assignment
## RL Task: Variance-Stabilized Dropout Implementation

---

## 📋 Start Here

**New to this submission?** → Read `QUICKSTART.md` (2 min)  
**Want quick overview?** → Read `SUBMISSION_SUMMARY.md` (5 min)  
**Need full details?** → Read `README.md` (15 min)

**To run the task:**
```bash
pip install numpy
python variance_dropout_task.py
```

---

## 📁 Files Guide

### Essential Files
- **variance_dropout_task.py** - Complete task implementation (the actual submission)
- **README.md** - Full documentation with rationale and design decisions
- **requirements.txt** - Dependencies (numpy only)


---

## 🎯 What This Is

An RL training task where language models learn to:
1. Understand a research paper concept (variance-stabilized dropout)
2. Debug a subtle mathematical error in the implementation
3. Validate the fix with statistical tests

**The bug:** Using `1/(1-p)` scaling instead of `1/√(1-p)`  
**The challenge:** Models must derive the correct formula  
**The validation:** Empirical variance tests (must preserve variance within 10%)

---

## Key Features

- **Scientific concept** - Neural network training stability
- **10-40% difficulty** - Subtle bug, requires math understanding
- **Clear grading** - Automated statistical tests
- **Educational value** - Teaches paper → code implementation
- **Production ready** - Fully documented, tested, calibrated

---

## 📊 Quick Stats

- **Code:** ~300 lines (including tests, grader, docs)
- **Dependencies:** numpy only
- **Difficulty:** Calibrated for 10-40% pass rate
- **Task type:** Debugging + mathematical reasoning

---

