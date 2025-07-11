# TC009 - Currency Rounding Precision

**Title**: Price Rounding Logic with Currency Conversions  
**Objective**: Ensure price remains accurate across conversions  

## Steps
1. Set currency to USD, then EUR  
2. Add product priced at 9.99  
3. Go to checkout and review total with tax  

## Expected Result
- Rounded correctly (e.g., 9.99 becomes 10.00 with tax)  
- No floating point errors like 9.989999  

**Type**: Precision, Currency Logic  
**Priority**: Medium