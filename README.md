# DS-Stack-25S-0183
Step 1: Process '6'
  → Push 6
  → Stack: [6]

Step 2: Process '2'
  → Push 2
  → Stack: [6, 2]

Step 3: Process '3'
  → Push 3
  → Stack: [6, 2, 3]

Step 4: Process '+'
  → Pop 3 and 2
  → Calculate: 2 + 3 = 5
  → Push 5
  → Stack: [6, 5]

Step 5: Process '*'
  → Pop 5 and 6
  → Calculate: 6 * 5 = 30
  → Push 30
  → Stack: [30]

RESULT: 30
