- 👋 Hi, I’m @Rksing3
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Rksing3/Rksing3 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
n = 8



for i in range(1, n+1):
    # to print (n-i) spaces before printing the number
    # Solution 1: - using the string multiplication
    # print(" "*(n-i), end="")

    # Solution 2: - using loops
    for j in range(n-i):
        print("  ", end="")

    # j-loop prints the numbers in the row
    for j in range(1, i+1):
        print(j,end=' ')

    # new line
    print() 
    
    
    n = 5



for i in range(1, n+1):
    for j in range(1, i+1):
        # print(j, end=" ")
        print(i,j,sep=",",end="    ")

    print() 
		
    
