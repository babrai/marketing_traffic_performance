# Subscription Revenue Analysis

## Task
Analyze user transaction data for a weekly subscription plan.

**Dataset columns:**
- `transaction_id` — unique transaction ID  
- `original_transaction_id` — ID of the first subscription transaction (unique per user)  
- `purchase_date` — transaction date  
- `original_purchase_date` — date of the first subscription transaction  

**Additional info:**
- Subscription duration: 1 week  
- Price: $4.99  
- First week is a free trial

## Goals
- Calculate conversion rate from trial to paid subscription  
- Calculate ARPU on day 14 after starting the trial  
- Forecast ARPU on day 90 of user lifetime

## Results
- **Conversion rate:** 32.76%  
- **ARPU Day 14:** $2.33  
- **ARPU Day 90 (forecast):** $3.01

## Tools
- Python (pandas, matplotlib)
- Jupyter Notebook
