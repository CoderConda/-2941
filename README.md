# 백준 2941(replace)

c_list = ['c=', 'c-', 'dz=', 'd-', 'lj', 'nj', 's=', 'z=']

word = input()

for i in c_list:
    word = word.replace(i, "a")
print(len(word))    
