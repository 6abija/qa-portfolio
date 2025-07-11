# TC004 - Rapid Cart Update Race Condition

**Title**: Simultaneous Quantity Update From Two Tabs  
**Objective**: Test race condition in cart item quantity update  

## Steps
1. Open the cart in two separate browser tabs  
2. In Tab 1: change quantity of product X to 5  
3. In Tab 2: change quantity of product X to 2  
4. Quickly submit both tabs  

## Expected Result
- Server correctly handles latest request  
- Cart total is updated correctly  
- No duplicate or inconsistent values  

**Type**: Concurrency, Data Integrity  
**Priority**: Critical