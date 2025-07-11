# TC010 - Timeout Session Edge

**Title**: User Tries Checkout Right After Session Timeout  
**Objective**: Ensure graceful session expiry  

## Steps
1. Log in and add items to cart  
2. Wait until session expires (simulate via dev tools or cookies)  
3. Try to go to checkout  

## Expected Result
- Redirect to login  
- No loss of cart state  
- Clear message: “Session expired, please log in again”  

**Type**: Session Handling  
**Priority**: High