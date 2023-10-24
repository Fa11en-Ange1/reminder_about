words = "interesting book"
letters = "aioue"
count = 0 

for i in words.lower():
    if i in letters:
        count +=1
print(count)
