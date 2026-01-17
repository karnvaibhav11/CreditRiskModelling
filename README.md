# This is the project for "**CreditRisk-Modelling**" from Kaggle DataSet

# Used WoE (Weight of Evidence) for Encoding Categorical Columns

# =============================
# ADVANCED: Weight of Evidence (WoE) Encoding – Credit Risk 
# =============================
# Why WoE can be used here:
# 1. Built for binary classification (default vs non-default)
# 2. Creates monotonic, interpretable features (regulator friendly)
# 3. Works insanely well with Logistic Regression & tree models
# 4. Handles categorical + binned numerical variables uniformly
# 5. Allows IV (Information Value) for feature selection
#
# Why WoE may NOT be used:
# 1. Requires binning (engineering effort)
# 2. Sensitive to data drift (needs monitoring & re-binning)
# 3. Not ideal for ultra-high-cardinality IDs (merchant_id, device_id)
# 4. Less flexible than Target Encoding for raw performance
# 5. Needs business sanity checks (monotonicity)
#
# When to use WoE:
# - Credit Risk PD Models
# - Scorecards
# - Regulatory environments (RBI, Basel, IFRS9)
#
# When NOT to use WoE:
# - Streaming crypto signals
# - Recommendation systems
# - Ultra low latency trading

