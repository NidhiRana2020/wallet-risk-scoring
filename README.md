# wallet-risk-scoring
Risk scoring model for Ethereum wallets based on their transaction history using Etherscan API, feature engineering, and weighted scoring.

## 📌 Objective

Calculate risk scores for given wallet addresses based on their transaction history using Etherscan API, focusing on DeFi protocol interactions.

## 📝 Files

- **Wallet_Risk_Scoring_Final.ipynb:** Colab notebook with full stepwise implementation.
- **Wallet_Risk_Scoring_Explanation.pdf:** Detailed explanation of data collection, feature engineering, and scoring method.
- **requirements.txt:** Python dependencies for running the notebook.

## 🚀 Key Highlights

✅ Fetches transaction data using Etherscan API  
✅ Extracts features like total supplied, borrowed, repayment ratio  
✅ Normalizes data and computes weighted risk scores (0-1000 scale)  
✅ Clean, scalable approach ready for production extensions.

## 💡 Future Improvements

- Integrate Graph decentralized network APIs for decoded DeFi positions
- Extend to Aave V2/V3 and Compound V3

---

### 🔗 **Connect**

**Author:** Nidhi Rana  
[LinkedIn Profile](https://www.linkedin.com/in/nidhi-rana-54b6471a6)
