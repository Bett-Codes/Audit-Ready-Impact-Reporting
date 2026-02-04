# Impact Metrics Definition

# Core Indicators
1. Total Households Supported(Cumulative)
   - Definition: Sum of households_supported across all partners
   - Unit: Number of households
   - Calculation: SUM(households_supported)

2. Total Amount Disbursed
   - Definition: Sum of amount_disbursed_usd across all partners
   - Unit: USD
   - Calculation: SUM(amount_disbursed_usd)

3. Average Households per Partner
   - Definition: Mean households supported per partner
   - Unit: Number of households
   - Calculation: MEAN(households_supported) by partner

4. Regional Distribution
   - Definition: Households supported by region
   - Unit: Number of households
   - Calculation: SUM(households_supported) GROUP BY region

# Reporting Dimensions
- By Month
- By Partner
- By Region
- By Partner + Region