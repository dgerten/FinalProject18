  For my final Project I made a game of tic-tac-toe. The rules of this game are just like the normal rules of tic-tac-toe; there are nine boxes and whoever gets three x’s or o’s in a row wins. These winning combinations can be horizontal, vertical, and diagonal. The way you input which box you want correlates to specific numbers for each box, with 0 on the top left and 8 at the bottom right. The computer chooses its box by seeing which boxes are left and which ones are the best. It does this by knowing the order of the best boxes, which are: 4, 0, 2, 6, 8, 1, 3, 5, 6. The reason for this order is that 4 is the centerbox, so it automatically gives you a square that could be in four winning combinations. The next four numbers are each corner squares, which can each have three winning combinations. The last four numbers are each middle-side squares, which each only have two winning combinations. The computer can also block the user’s tic-tac-toe once the user has two out of the three squares needed to win.

Link to code:
https://repl.it/@dgerten/Final-Code-from-pythonanywhere

Flowchart:
https://drive.google.com/file/d/1diWVE2xysyRB_3VwbmJwVL9m0SqUE8ju/view?usp=sharing

Visuals:
https://docs.google.com/presentation/d/1ZsOZEnRCPI2M4nd1yWxy28D0cHX6yzWl4Okbl4ypzQI/edit?usp=sharing

Sources:
https://www.programiz.com/python-programming/methods/list/append
https://inventwithpython.com/tictactoe.py
  -The board from lines 9-19
