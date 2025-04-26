# Assignment-5
# Test - 1
my_dict={'Devendra':97,'Pragnay':98,'Dharti':55,'Shakti':90}
b=input("Enter the student's Name :" )
a=(my_dict.get(b,'student not found'))
print(b,"'s Marks :",a)
print('Thank You')


# Test - 2
number=[1,2,3,4,5,6,7,8,9,10]
print('Orignal list:',number)
c=number[0:5]
print('Extrected First Five eliments:',c)
c.reverse()
print('Reversed extrected eliments:',c)
