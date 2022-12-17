# 12-17-coding-


for i in range(10):


    def main ():
        math = int (input("請輸入您的數學成績"))
        if (isPass(math)):
            print("123")
        
        english = int (input("請輸入您的英文成績"))
        isPass(english)
        chinese = int (input("請輸入您的中文成績"))
        isPass(chinese)

        sum=math+english+chinese
        average = sum / 3
        print("總平均", average)
        isPass(average)


    def isPass(score):
        if score >= 60:
            print("恭喜你及格了")
            return True 
        elif score < 60:
            print("重修")
            return False

    main()
