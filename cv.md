# Oleksij RODIN
*******
## Contacts:
+  **Discord:** oleksij (rlexus90)#7382
+  **Phone:** +380669166194
+  **Email:** (rlexus90@gmail.com)
****
## About myself:
I want to change my profession, so I started studying JavaScript. Studied independently. Now joined the study in RSSchool.
## Code example:
```
function doneOrNot(board) {
  const row = '0123456789';
  for (let i = 0; i < 9; i++) {
    let rowg = row;
    let rowv = row;
    for (let j = 0; j < 9; j++) {
      rowg = rowg.replace(board[i][j], '');
      rowv = rowv.replace(board[j][i], '');
    }
    if (rowg.length > 1 || rowv.length > 1) { return "Try again!" }
  }
  let sq1 = '123456789';
  let sq2 = '123456789';
  let sq3 = '123456789';
  for (let i = 0; i < 3; i++) {

    for (let j = 0; j < 3; j++) {
      sq1 = sq1.replace(board[i][j], '');
      sq2 = sq2.replace(board[i + 3][j + 3], '');
      sq3 = sq3.replace(board[i + 6][j + 6], '');
    }
  }
  if (sq1.length > 0 || sq2.length > 0 || sq3.length > 0) { return "Try again!" }
    return "Finished!"
}
```
## Work experience:
I have no experience as a developer, but I want to get it.
## Education and courses:
+ **2012** SEVASTOPOL NATIONAL UNIVERSITY OF NUCLEAR ENERGY AND INDUSTRY.
+ **now** Self-study from open resources.
## Language:
**English level** Pre-Intermediate (A2).
