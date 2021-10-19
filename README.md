# fibonacci-in-python
int_0=0
int_1=1
count=0
n=int(input("number of ele 'n': "))
for i in range(0,n+1):
    print(int_0,end=',')
    nth=int_0+int_1
    int_0=int_1
    int_1=nth
    count+=1
