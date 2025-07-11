# TC005 - Undo After Delete in Wishlist

**Title**: Undo Feature Behavior After Deleting Item from Wishlist  
**Objective**: Test the ability to recover deleted wishlist item within timeout  

## Steps
1. Add a product to wishlist  
2. Click "Remove"  
3. Click "Undo" within 5 seconds  
4. Refresh the page  

## Expected Result
- Item is restored to wishlist  
- Undo is available for exactly 5 seconds  
- No duplication on refresh  

**Type**: Usability, Edge Case  
**Priority**: Medium