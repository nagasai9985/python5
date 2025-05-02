#dictionary operations
person={'name':'nagasai',"age":23,'city':'vijayawada'}
print(person)
print("accessing and modify the person age :")
person ["age"]=21
print(person)
print("adding and removing items")
person['email']= 'nagasai1532002@gmail.com'
print(person)
del person ['city']
print(person)
print("All keys & values")
print(person.keys())
print(person.values())
print(person.items())
print(person.get("age"))
