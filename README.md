i=10
print(i)                            #returns 10

x1=22
y1=11
z1=x1/y1
print(z1)                           #retuns 2

name= 'avrajit'
len(name)                           #returns 7, (note: INDEX starts from '0')
name[2]                             #returns 'r'
name.upper                          #for upper-case
name[-3]                            #returns 'j', shows 3rd letter from the last

mylist = [30, 20, "avra"]           #list named as 'mylist' created
print(mylist)
mylist[1]                           #returns 20, as in python index starts from '0'                       
mylist[1] = 99                      #replace 20 by 99
print(mylist)                       #output: 30, 99, 'avra'
mylist.append(10)                   #adds '10' at the end of the list, if printed shows 30, 99, 'avra', 10
mylist.insert (2, 1000)             #inserts '1000' in the 3rd position
mylist.reverse()                    #to get mirror image of the list
