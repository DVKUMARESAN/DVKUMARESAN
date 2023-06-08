- 👋 Hi, I’m @DVKUMARESAN
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
DVKUMARESAN/DVKUMARESAN is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import re 
2	def validate_password(password):
3	    
4	    if len(password) < 8:  
5	        return False  
6	    if not re.search("[a-z,A-Z,0-9,@!#%&*]", password):
7	        
8	        return False 
9	    return True
10	password =input("Enter the Password: ")
11	if validate_password(password):  
12	    print("Valid password")  
13	else:  
14	    print("Invalid password")
