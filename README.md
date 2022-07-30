- 👋 Hi, I’m @170Zheng
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
170Zheng/170Zheng is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def talip_table():
    # 如果不使用乘法
    i = 1
    j = 1
    while i <= 9:
        while j <= i:
            print("%d*%d=%d" % (i, j, i * j), end="\t")
            j += 1
        print("")
        j = 1
        i += 1

