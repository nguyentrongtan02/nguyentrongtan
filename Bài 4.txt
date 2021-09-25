def tongSoX(x):
    total = 0;
    while (x > 0):
        total = total + x % 10;
        x = int(x / 10);
    return total;

x = int(input("Nhập số nguyên dương x = "));
print("Tổng các chữ số của", x, "là", tongSoX(x));