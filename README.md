# Search-app-
#this is searching app for pc , only those app available in your pc can be search by it.
#My app contain some of the most used app which you can search.
#you can add your requirement app by adding some code.

#import pyttsx3 
#this is a module which you can install using pip command(pip install pyttsx3)

#import os 
#this module can install using pip command (pip install os) 

#print() this is a python print command which include "\n" in its end so you get new line after running this command
#printed the list of available app which client can access.

#while true ( infinite loop which can be breaken by ) break command.

#if-elif-else statement in which if given condition is true then it run its block code otherwise jump to other elif  statement till condition break true or else statement come.
#else statement is like default statement which is executed if other statement are wrong.

#or & and operator used as 
#if any one condition in or operator is true then it will return ture otherwise false.
#in and operator if any condition is false then it will return false.

#os.system() is command to access our pysical syatem files or apps where system is program file of os module

#pyttsx3.speak()is command in which your speaker will speak the string you have written between it .
#where speak() is program file and pyttsx3 is module in which it is present.

#you can use this code using twilio api to send whatsapp messages
	#to run on your firstly run this command 
  	#make amount on twilio where you can get your twilio account sid and auth token (do not share this credential with others)
  	#setput environment variable for twilio_accound_sid and twilio_auth_token
  	#enable virtual env as
  	#python -m venv pywhatsapp
  	#virtualenv pywhatsapp
  	#activate pywhatsapp by going to its directory in which you will find scripts for that diretory you can activate pywhatsapp
  	#write the below code in any texteditor 
  	#try out twilio whatsapp to activate sandbox in its brower
  	#then you can run this code in python to send messages
		#import os
		#from twilio.rest import Client

		#client = Client(os.environ['TWILIO_ACCOUNT_SID'],os.environ['TWILIO_AUTH_TOKEN'])

		#from_whatsapp_number = 'whatsapp:+14155238886'

		#to_whatsapp_number = 'whatsapp:+8775615200'

		#message =client.messages.create(body=' i am happy' , from_=from_whatsapp_number,to=to_whatsapp_number)

		#print("send successfully")
