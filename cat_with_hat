list_cat = []

for i in range(100): list_cat.append(False)

def cat_in_hat(list1, num):
    count = 0
    for i in range(len(list1)):
        count += 1
        if (count%num) == 0:
            if list1[i] == False:
                list1[i] = True
            else:
                list1[i] = False
                
def num_hats(list1, num):
    count = 0
    for i in range(num): cat_in_hat(list1, i+1)
    for i in list1:
        if i == True: count+=1
    return count

print(f'Number cats with hats: {num_hats(list_cat, 100)}')
