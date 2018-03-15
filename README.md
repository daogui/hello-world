# hello-world
just a repository
x=int(input())
x=x+1
for t in list(range(x)):
	t=int(t)
	d=[]
	if  t==0:
		pass
	else:
		for r in list(range(t)):
			r=int(r)
			if r==0:
				d.append(1)
			else:
				a=1
				b=1
				h=t
				while r>0:
					h=h-1
					a=a*h
					b=b*r
					r=r-1
				c=a/b
				c=int(c)
				d.append(c)
		print(d)
