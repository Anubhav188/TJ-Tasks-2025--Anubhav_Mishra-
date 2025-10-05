# TJ-Tasks-2025--Anubhav_Mishra-
# DSA - Beginner/Easy: Minimum Operations to Make Product Positive

## Question 1->
Code is in file.

## Algorithm:

1. **Count zeros and -1s:**  
   - Loop through the array.  
   - Let `zeros` = number of 0s, `neg` = number of -1s.  

2. **Handle zeros:**  
   - Each zero must become 1 → `zeros` operations.  

3. **Check negative count:**  
   - If `neg` is **even**, the product of negatives is already positive.  
   - If `neg` is **odd**, flip **one -1** to make the product positive.  

4. **Calculate total operations:**  
   - `ops = zeros + neg` (each -1 requires 1 operation to flip partially)  
   - If `neg` is odd → add 1 extra operation to handle the odd negative.  

5. **Print result:**  
   - Output the minimum number of operations for the current test case.  

