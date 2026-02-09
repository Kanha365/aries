# aries
**notebook187488c281.ipynb** is first best submission with (`submission(8)`).csv as output with public score** 0.73922**

**notebook187488c281 (2).ipynb** is second best submission with (`submission_ensemble_70_30.csv`) as output with public score **0.72012** , here **Roberta **and **DeBerta** used as DAtaset to the final code.
###  Key Findings
1.  **Context Matters:** The **RoBERTa** model (`submission(8)`) vastly outperformed DeBERTa. This is likely because we increased the input length to **512 tokens**, capturing the full customer complaint details (which DeBERTa missed at 256 tokens).
2.  **Ensemble Failure:** The weighted ensemble (`70_30`) actually **lowered** our score to **0.720**. This happened because the DeBERTa model (0.717) was significantly weaker than RoBERTa (0.739), effectively "polluting" the high-quality predictions of the stronger model.
