# automated-decision
#REQUEST FOR USER INCOME AND CREDIT SCORE
def loan_approval_system(income, credit_score):
    if income >500000 and credit_score > 700:
        return "Loan Approved"
    else:
        return "Loan Denied" 
    
    #example display
user_income = float(input("Enter your income: "))
user_credit_score = int(input("Enter your credit score: "))
#print result
result = loan_approval_system(user_income, user_credit_score)
print(result) 
