# Russell's transaction Risk Scoring Model

This project scores financial transactions based on how risky they are. It uses:
- Whether the card was swiped or used with a chip
- Whether the transaction had an error

---

## 💾 What It Does

- Loads transaction data from a CSV file
- Cleans and converts the amount column
- Creates risk scores based on:
  - Chip usage (swipe = more risky)
  - Presence of error messages
- Combines them into one `total_risk` score



### Technologies Used:
- Python 3
- pandas

### Mitigation Strategies
### 2. **Error Handling Enhancement**
   - Transactions with errors indicate possible fraud or system issues. Regular system audits and cleaner transaction protocols can reduce error-related risks.

### 3. **Threshold-Based Alerting**
   - Implement a threshold to trigger fraud alerts or additional verification steps.


