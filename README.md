# pythoncode-demo
python code 
code p = int(input('Please enter the pricinpal amount: ')) t = int(input('Please enter the number of years: ')) r = int(input('Please enter interest rate: '))

si = (p * t * r) / 100 print(si) num1 = int(input('Please enter the bigger num: ')) num2 = int(input('Please enter the smaller num: '))

for i in range(1,num2+1): if(num1%i==0 and num2%i==0): GCD = i print(GCD)

for i in range(2000, 3201): if (i%7==0) and (i%5!=0): print(i,end=",")
input_string = input("Enter a list element separated by space : ") a_list = input_string.split() tot = 0 count = 0 for val in a_list: tot = tot + int(val) count = count + 1 print(tot / count) input_string = input("Enter your list separated by spaces") a_list = input_string.split() not_sorted_flag=False for idx in range(len(a_list) - 1): if int(a_list[idx]) > int(a_list[idx + 1]): not_sorted_flag = True break

if(not_sorted_flag): print('List is not sorted') else: print('List is sorted') input_string = input("Enter a list element separated by space : ") a_list = input_string.split() largest = -float("inf") for val in a_list: if int(val) > largest: largest = int(val) print(largest) strn = input("Enter a string : ") sub_s = input("Enter a search string : ") found = False for i in range(len(strn)-len(sub_s)+1): if(strn[i:i+len(sub_s)] == sub_s): found=True break if(found): print(sub_s, 'is a substring of', strn) else: print(sub_s, 'is not a substring of', strn)

About
code

Topics
Resources
 Readme
Stars
 0 stars
Watchers
 1 watching
