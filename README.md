# Tasksumltionproject
combinations vs permutations
by ali gamal aziz permutations 
from itertools import permutations # import libery 
char = 'a'
p = [char, char*2, char.upper(), char.upper()*2]  # Char , Upper , 2 * Upper 
pp = []                         # stores the final list of permutations
for j in range(1,3):            # for loop 1 : 3 
    for i in permutations(p,j): # for loop list 
        p2 = ''.join(i)         # Join P2 in the for looop 
        if len(p2) < 3:         # for loop lenthe
            pp.append(p2)       # add in pp list 
print (pp)                      # print lsit 
