#QUESTION 1
def calculate_discount(price, discount_percent):
    if discount_percent >= 20 and discount_percent<100 :
        price = price-(discount_percent/100 * price)
        return price
    else:
        return price
#QUESTION 2
price= int(input("Enter original price: "))
discount_percent= float(input("Enter discount percentage: ")) 
print(calculate_discount(price,discount_percent))
