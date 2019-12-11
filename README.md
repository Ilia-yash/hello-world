d={}
a=[]
count=1
while True:
    try:
        s=input()
    except:
        break
    a.append(s)
for i in range(len(a)):
    if(a[i]==-1):
        continue
    for j in range(i+1, len(a)):
        if a[j]==-1:
            continue
        if a[i]==a[j]:
            count+=1
            a[j]=-1
    d[a[i]]=count
    count=1
print(d)


d={}
a=[]
count=1
while True:
    try:
        s=input()
    except:
        break
    s=s.lower()
    a.append(s)
for i in range(len(a)):
    if(a[i]==-1):
        continue
    for j in range(i+1, len(a)):
        if a[j]==-1:
            continue
        if a[i]==a[j]:
            count+=1
            a[j]=-1
    d[a[i]]=count
    count=1
print(d)

