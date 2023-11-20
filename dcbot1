import random
import string

def password_generator():
    letters = string.ascii_letters
    nums = string.digits
    special = string.punctuation
    
    characters = letters + nums + special
    
    pwd_length = int(input("Enter a password length: "))
    pwd = ""
    
    for i in range(pwd_length):
        pwd += random.choice(characters)
        
    return pwd

print(password_generator())
