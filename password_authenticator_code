#The title of the program
print("Password Authentication Program")

#Variable that holds the password
magic_password = "magic_pass123"

#The for loop runs the program 3 times as the user has 3 
for i in range(3):
    attempts = 2-i
    enter_pass = input("Enter Your Password: ")
    #this is for the number of attempts, if 0 attempts then access denied
    if enter_pass != magic_password:  
        if int(attempts) > 1:
            print("Incorrect password. You have " +  str(attempts) + " attempts left. Please try again.")
        elif int(attempts) == 1:
            print("Incorrect password. You have " +  str(attempts) + " attempt left. Please try again.")
        else:
            print("Incorrect password. Maximum number of attempts reached. Access denied.")
    elif enter_pass == magic_password:
        print("Correct password! Access granted.")
        break
        #breaks out of the loop
