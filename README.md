elements = [1, 2, 2, 3, 4, 4, 4, 5, 5]

duplicates = [elements]

for x in elements:

    if elements.count(x) > 1 and x not in duplicates:
print(duplicates)
