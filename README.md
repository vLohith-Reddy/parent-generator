# parent-generator
class parent:
    def_init_(self,name):
    self.name=name
    def display(self):
        print(self.name)
class child(parent):
    def_init_(self,name,cname):
    super()._init_(name)
    self.cname=cname
    def display1(self):
        print(self.cname)
        print(self.name)
c1=child("abc","bcd")
print(c1.name)
c1.display()
c1.display1()
