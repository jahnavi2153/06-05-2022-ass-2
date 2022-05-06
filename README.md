# 06-05-2022-ass-2
#prepare dictionary for employee with the fields
#empno,empname,doj,empdesgin,empsal,city
a={1:[1,'Raju','3/1/2022','Manager',25000,'Delhi'],
2:[2,'Deepak','3/1/2022','Manager',30000,'Hyderabad'],
3:[3,'Ravi','10/2/2022','Asst Manager',18500,'Kolkata'],
4:[4,'Ramu','22/2/2022','Store Manager',16500,'Delhi'],
5:[5,'Teja','13/3/2022','General Manager',15000,'Hyderabad']}
x=int(input('Enter a number:'))
print('Enter EMPNO:',a[x][0])
print('Enter EMPNAME:',a[x][1])
print('Date of joining:',a[x][2])
print('EMPDESIGN:',a[x][3])
print('EMPSAL:',a[x][4])
print('City:',a[x][5])

output:
Enterr a number:4
Enter EMPNO:4
Enter EMPNAME:Ramu
Date of joining:22/2/2022
EMPDESIGN:Store Manager
EMPSAL:16500
City:Delhi
