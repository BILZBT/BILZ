student_rec=['John','Don','Jake','Bilal','Mayank','Shihan','Dave','Azneef']
student_rec.sort()
name=str(input('Enter the name of the Student You want To search for:'))
#function starting
def search_student(list,value):
  first=0
  last=len(list)-1
  while first<=last:
    center=(first+last)//2
    if list[center]==value:
      a=print('Your Value {} Is Present At {} Position'.format(list[center],center))
      return center
    elif list[center]<value:
      first=center+1
    else:
      last=center-1
  return 0

#calling function

print(search_student(student_rec,name))
