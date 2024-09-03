# apnacollage-dmo
my first repository.
<br>
auther=Bhagwat Gatwe
import datetime # pip install datetime 

import pyttsx3 # pip install pyttsx3

import speech_recognition as sr # pip install speechRecognition

import webbrowser # pip install webbrowser

import pyautogui # pip install pyautogui

import time # pip install time

def speech():

    pass

    

        

    

while True:

    try:

        r = sr.Recognizer()

        with sr.Microphone() as source:

            print("Listening...")

            r.adjust_for_ambient_noise(source)

        

            

            audio = r.listen(source)



        

            print("Recognizing...")

            query1 = r.recognize_google(audio, language='en-in')

            print(query1)

            if 'hello' in query1:

                engine=pyttsx3.init()

                engine.say('launching version 1.o sattelite x111010111011 command me sir')

                engine.runAndWait()

                print("launching version 1.o sattelite x111010111011")

                while True:

                    try:

                        r = sr.Recognizer()

                        with sr.Microphone() as source:

                            print("Listening...")

                            r.adjust_for_ambient_noise(source)

                        

                            

                            audio = r.listen(source)



                        

                            print("Recognizing...")

                            query1 = r.recognize_google(audio, language='en-in')

                            print(query1)

                            if '1.0' in query1:

                            

                                a=datetime.datetime.now().hour

                                b=datetime.datetime.now().minute

                                engine=pyttsx3.init()

                                engine.say('yes boss executing command 1.0')

                                engine.runAndWait()

                                print("alarm ringing")

                                engine=pyttsx3.init()

                                engine.say('the time is {a1} {b1}'.format(a1=a,b1=b))

                                engine.runAndWait()

                                engine=pyttsx3.init()

                                engine.say('when do you want to set the alarm for')

                                engine.runAndWait()

                                query1=int(input('hours'))

                                query2=int(input('minutes'))

                                try:

                                    try:

                                        while (datetime.datetime.now().hour<=query1 and datetime.datetime.now().minute<query2):

                                            print("nap...")

                                        i=1

                                        while(i<100):

                                            engine=pyttsx3.init()

                                            engine.say('wake up sir')

                                            engine.runAndWait()

                                            print("alarm ringing")

                                            i=i+1

                                    except:

                                        continue

                                except:

                                    continue

                               

                                

                               

                            if '1.1' in query1:

                                engine=pyttsx3.init()

                                engine.say('yes boss executing command 1.1')

                                engine.runAndWait()

                                try:

                                    engine=pyttsx3.init()

                                    engine.say('what do you want to search Sir')

                                    engine.runAndWait()

                                    

                                    r = sr.Recognizer()

                                    with sr.Microphone() as source:

                                        print("Listening...")

                                        r.adjust_for_ambient_noise(source)

                                    

                                        

                                        audio = r.listen(source)



                                    

                                        print("Recognizing...")

                                        query1 = r.recognize_google(audio, language='en-in')

                                        print(query1)

                                    

                                    

                                    webbrowser.open("https://www.google.com/search?q={a}&oq={a}&aqs=chrome..69i57j69i59j69i60j5l3j69i60l2.843j1j7&sourceid=chrome&ie=UTF-8".format(a=query1))

                                except:

                                    engine=pyttsx3.init()

                                    engine.say('Sir speak again')

                                    engine.runAndWait()

                                    continue

                            if '1.2' in query1:

                                engine=pyttsx3.init()

                                engine.say('yes boss executing command 1.2')

                                engine.runAndWait()

                                engine=pyttsx3.init()

                                engine.say('contacting Google')

                                engine.runAndWait()

                                webbrowser.open("https://www.google.com/search?q=a&oq=a&aqs=chrome..69i57j69i59j69i60j5l3j69i60l2.843j1j7&sourceid=chrome&ie=UTF-8")

                                time.sleep(4)

                                pyautogui.click(1176,163)

                                continue

                            if '1.3' in query1:

                                engine=pyttsx3.init()

                                engine.say('yes boss executing command 1.3')

                                engine.runAndWait()

                                engine=pyttsx3.init()

                                engine.say('opening gmail')

                                engine.runAndWait()

                                webbrowser.open("https://www.google.com/search?q=a&oq=a&aqs=chrome..69i57j69i59j69i60j5l3j69i60l2.843j1j7&sourceid=chrome&ie=UTF-8")

                                time.sleep(4)

                                pyautogui.click(1758,163)

                                time.sleep(1)

                                pyautogui.click(1642,262)

                                time.sleep(2)

                                pyautogui.click(1790,63)

                                time.sleep(1)

                                pyautogui.click(1498,296)

                                time.sleep(1)

                                pyautogui.click(1498,164)

                                

                                

                            if '1.5' in query1:

                                pyautogui.click(788,578)

                                

                                

                                

                    except:

                        pass

    except:

        continue

                    

    

        

       



        
