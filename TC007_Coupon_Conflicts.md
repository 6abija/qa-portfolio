# TC007 - Coupon Stackability and Expiry

**Title**: Apply Multiple Coupons with Conflicting Rules  
**Objective**: Test system logic for coupon validation  

## Steps
1. Add products totaling 100€  
2. Apply:  
   - Coupon A: -20€ (min 50€)  
   - Coupon B: -15% (cannot be stacked)  
   - Expired Coupon C  

## Expected Result
- Expired coupon rejected  
- Only one valid coupon applied (based on rules)  
- Correct discount shown  

**Type**: Business Logic, Negative Scenario  
**Priority**: High