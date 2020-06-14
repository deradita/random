# random

def an_agram(str_1,str_2):
    list_str_1=list(str_1)
    list_str_1.sort()
    list_str_2=list(str_2)
    list_str_2.sort()
    
    
    return (list_str_1 == list_str_2)
print(an_agram('evil','live'))
print(an_agram('eat','tea'))
