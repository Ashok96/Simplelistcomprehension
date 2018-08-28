# Simplelistcomprehension
List comprehension in python practice



#print first 25 fibonacci series by list comprehension

l=[]
l.append(1)
l.append(1)
[l.append(l[n-2]+l[n-1])for n in range(2,25)]
print(l)

