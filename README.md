# IBM-Project-45323-1660729401
Smart Solutions For Railways


import random
def temp():
    temp=random.randint(20,40)
    return temp
def humidity():
    humidity=random.randint(30,70)
    return humidity
temp=temp()
humidity=humidity()
print("temperature is:",temp)
print("humidity is:",humidity)
if(temp>30):
    if(humidity>60):
        print("alert detected")
    else:
        print("high temperature detected")
elif(temp==30):
    print("threshold reached")
else:
    print("all good")
