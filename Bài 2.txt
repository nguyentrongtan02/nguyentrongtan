a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 88]
b = [1, 3, 5, 4, 7, 88, 66, 59, 40, 54]
c = set(a) & set(b)
print("cac phan tu trung nhau la: ", c)
s = set(a) - set(b)
print("Mảng A sau khi set ", s)
z = set(b) - set(a)
print("Mảng b sau khi set ", z)