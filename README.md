class Vyshu:
    def __init__(self):
        self.balance=0
        print("Welcome to vyshu")
    def deposit(self):
        amount=float(input("Enter amount to be deposited:"))
        self.balance+=amount
        print("\n Deposited amount :", amount)
    def withdraw(self):
        amount =float(input("Enter the amount to be withdraw:"))
        if self.balace>=amount:
            self.balance-= amount
            print("\n Withdraw :",amount)
        else:
            print("\n Insufficient balance")
    def checkbal(self):
        print("\n Net avalible balance:",self.balance)
        
        
s=Vyshu()
s.deposit()
s.withdraw()
s.checkbal()
