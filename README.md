# argsort ; Returns indices that would sort an array

z = np.array([12,45,23,19,90,5,3])
print(np.argsort(z))                             # will return [6 5 0 3 2 1 4]
print(np.argsort(z)[-2:])           # indices of 1st two highest values arranged in ascending order
print(np.argsort(z)[-2:][::-1])     # sort the the higheest two indices in descending order

print(z[np.argsort(z)[-2:]])
print(z[np.argsort(z)[-2:][::-1]])   #prints the highest two "values" in descending order
