
class test:
    x=10
    def m1(self):
        self.y=20
        print(test.x)
        print(self.y)
class demo(test):
    a=1
    def m2(self):
        self.b=2
        print(demo.a)
        print(self.b)
        print(demo.x)
        print(self.y)
d1=demo()
d1.m1()
d1.m2()
