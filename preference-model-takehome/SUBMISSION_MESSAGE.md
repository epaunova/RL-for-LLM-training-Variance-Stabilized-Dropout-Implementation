# Submission Message Template

---

**To:** ai@xor.ai / Aida (Telegram: @ai_aida11)  
**Subject:** Take-Home Assignment Submission - RL Environments Engineer

---

Hi Aida,

I've completed the take-home assignment for the RL Environments Engineer position. 

## Submission Details

**Task Created:** Variance-Stabilized Dropout Implementation  
**Time Spent:** ~4 hours  
**Difficulty:** Calibrated for 10-40% pass rate

## What I Built

An RL task that teaches models to implement a neural network training technique from a research paper:

- **Scientific concept**: Variance stabilization in dropout layers
- **The challenge**: Debug a subtle mathematical error (1/p vs 1/√p scaling)
- **Validation**: Statistical tests verify variance preservation
- **Educational value**: Teaches mean vs variance preservation in neural nets

## Why This Task Works

✅ **Hits 10-40% difficulty** - Subtle one-character bug, requires mathematical understanding  
✅ **Scientific domain** - Real ML research concept with practical applications  
✅ **Clear grading** - Automated statistical tests (variance within 10% tolerance)  
✅ **Teaches value** - Paper-to-code implementation + debugging skills  
✅ **Tool usage** - Code execution and numerical validation  

## Quick Test

```bash
pip install numpy
python variance_dropout_task.py
```

You'll see:
- Buggy version fails (43% variance error)
- Correct version passes (0.1% variance error)

## Files Included

- `variance_dropout_task.py` - Complete task implementation (~300 lines)
- `README.md` - Full documentation and rationale
- `SUBMISSION_SUMMARY.md` - Quick overview
- `QUICKSTART.md` - How to run and integrate
- `CHECKLIST.md` - Requirements verification

## Next Steps

I'm available to:
- Discuss the task design rationale
- Adjust difficulty calibration if needed
- Create additional tasks
- Integrate into your RL pipeline

Looking forward to hearing from you!

Best regards,
[Your Name]

---

**GitHub/HackerRank:** [Your submission link if applicable]  
**Contact:** [Your email/telegram]

---

## Attachment

📎 preference-model-takehome.zip (or link to folder)

---

## For HackerRank Submission

If submitting via HackerRank (https://hr.gs/pm-takehome-x):

1. Upload all files from `preference-model-takehome/` folder
2. Main file: `variance_dropout_task.py`
3. Run command: `python variance_dropout_task.py`
4. Expected output: Shows buggy failing + correct passing

Then message Aida confirming submission complete.
