# 🏭 Manufacturing Process Control with SPC

## 📝 Objective
This project focuses on implementing Statistical Process Control (SPC) to monitor and maintain the quality of a manufacturing process by identifying products that fall outside the acceptable control limits.

## ❓ Key Questions
- Are the manufactured parts within the acceptable height limits defined by UCL (Upper Control Limit) and LCL (Lower Control Limit)?
- Which parts require adjustments based on height measurements?

## 📊 Data
- **manufacturing_parts table**: Contains data about item numbers, lengths, widths, heights, and operators.
  - **Fields**: item_no, length, width, height, operator.

## 🧠 Approach
1. **Statistical Process Control (SPC)**: Calculated the UCL and LCL using the average height and standard deviation of a rolling window of 5 items.
2. **Process Monitoring**: Flagged items with heights outside the control limits for review.

## 📈 Results
- **Alerts**: Items outside the UCL or LCL are flagged for corrective action.
- **Smooth Process**: Most items were within the acceptable range, ensuring quality control.

## 🚀 Conclusion
Implementing SPC helps ensure the manufacturing process remains consistent, allowing for proactive adjustments when parts deviate from control limits.

## 🛠️ Tools & Libraries
- **SQL**: For data extraction and calculations using window functions.
- **PostgreSQL**: Database management.
