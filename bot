import google.generativeai as genia
from termcolor import colored as color
import os 

os.system('figlet AI BY MNHACKER| lolcat')
api = "" # add google ai api here
genia.configure(api_key=api)
model = genia.GenerativeModel('gemini-1.5-flash')
while True:
        inp = input(color("YOU : ",'green'))
        if inp in ['exit','break']:
                print(color("THANK YOU FOR USING OUR AI",'red'))
                break
        elif inp in ['clear','CLEAR']:
                os.system('clear')
        else:
                response = model.generate_content(inp)
                print(color("AI : "+response.text,'yellow'))
