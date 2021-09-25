def  tinhGt(n):
    gt = 1;
    if (n == 0 or n == 1):
        return gt;
    else:
        for i in range(2, n + 1):
            gt = gt * i;
        return gt;

n = int(input("Nhập số nguyên dương n = "));
if (n<0):
         print("Yêu cầu nhập lại số nguyên dương")
         n = int(input("Nhập số nguyên dương n = "));
         print("Giai thừa của", n, "là", tinhGt(n));
else:
     print("Giai thừa của", n, "là", tinhGt(n));