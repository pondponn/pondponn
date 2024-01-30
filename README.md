n = int(input("กรุณากรอกจำนวนเต็ม: "))
print(f"ตารางสูตรคูณแม่ 5 ตั้งแต่ 5*1 จนถึง 5*12 ของ {n}:")
for i in range(1, 13):
    result = 5 * i
    print(f"5 x {i} = {result}")
