def talip_table():
    i = 1
    j = 1
    while i <= 9:
        while j <= i:
            print("%d*%d=%d" % (i, j, i * j), end="\t")
            j += 1
        print("")
        j = 1
        i += 1

