
for x in range(5):
    for y in range(5):
        pydle(x, y, "", "red")
    for z in range(3,5):
        pydle(0,z,"","white")
        pydle(4,z,"","white")
    for z in range(2):
        pydle(1, 3, "", "orange")
        pydle(2, 3, "", "orange")
        pydle(3, 3, "", "orange")
