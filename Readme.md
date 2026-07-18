for x in range(5):
    for y in range(5):
        c = "red"
        if (y == 1 and x in (0, 2, 4)) or (y > 2 and x in (0, 4)):
            c = "white"
        elif y == 3 and x in (1, 3):
            c = "black"
        elif y > 2 and x in (1, 2, 3):
            c = "orange"
        pydle(x, y, "", c)

