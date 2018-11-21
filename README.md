# new-
存储程序
#递归
lis = [3,5,8,6,9,4]
def sum_xue(list):
    if len(list) ==0:
        return 0
    else:
        return list.pop()+sum_xue(list)
print(sum_xue(lis))
熟悉python函数
