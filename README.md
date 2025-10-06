# TJ-Tasks-2025--Anubhav_Mishra-
# DSA
## Beginner/Easy:
## Question 1->
Minimum Operations to Make Product Positive?
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
## Question 2->
Sum of Alternating Sequence? Code is in file.
## Algorithm

1. Read the number of test cases `t`.  
2. Repeat for each test case:  
3. Read the integers `x` and `n`.  
4. If `n` is even, set `sum = 0`; else set `sum = x`.  
5. Print `sum`. 
   - Output the minimum number of operations for the current test case.
## Question 3-> 
Trippi Troppi's world. Code is in file above.
## Algorithm
1. **Read Input.**
     -Read an integer `t` — the number of test cases.

2. **Loop Through Test Cases.**
   - Repeat the following steps `t` times.

3. **Read Words.**
   - For each test case, read three space-separated words.

4. **Form Modern Name.**
   - Take the first letter of each word.
   - Concatenate them to form the modern name.

5. **Print `Result.`**
   - Output the modern name.


# Vibe Coding
##Task 1: Tic Tac Toe Game in One Prompt (Easy)
**Prompt:**
 **Create a complete, fully functional Tic Tac Toe game for two players with a neat 3x3 grid using HTML, CSS, and JavaScript in a single file. Include game logic for turns, display the current player, detect win or draw, highlight the winning combination, and allow replay without refreshing the page. Provide only working code in one file, ready to open in a browser, with explanations or comments.**


