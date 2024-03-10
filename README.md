# change-integer
交換兩個數字
def swapnumber(a,b):

  print('交換前')
  print("a:", a, "b:", b)

  a, b = b, a  #交換兩個變數
  print("交換後")
  print("a:", a, "b:", b)

print(swapnumber(2,3))

