import os
import pyttsx3
pyttsx3.speak("welcome to artificial searching chatroom")
while True:	
	print("\n\n")
	print("				WELCOME TO ARTIFICIAL SEARCHING CHATROOM")
	print("				________________________________________")
	print("\n")
	print("				Following applications can be searched: ")
	print("")
	print("					Internet Surfing App                 ")
	print("				               Notepad                  ")
	print("				          Windows Media Player          ")
	print("				               VS Code                  ")
	print("						Wordpad                  ")
	print("						 Excel                 ")
	print("						 Paint                ")
	print("\n")
	print("				*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_")
	print("\n")
	print("			    Chat with me,which application you want to open?")
	print("\n")
	p=input("                       Type here:")  
	print("\n\n")
	if ("don't" in p) or ("Don't" in p) or ("DON'T" in p)or("DO NOT" in p) or ("Do not" in p) or ("do not" in p)or("didn't" in p)or("Didn't" in p)or("DIDN'T" in p)or("DID NOT" in p)or("Did not" in p)or("did not" in p):	
		print("                     As you directed,not opening your suggested app")
		print("                     ______________________________________________")
	else:
		if (("run" in p) or ("Run" in p) or ("RUN" in p)or("open" in p) or ("Open" in p) or ("OPEN" in p)or("start" in p) or ("Start" in p) or ("START" in p)or("LAUNCH" in p) or ("Launch" in p) or ("launch" in p)) and (("notepad" in p)or("Notepad" in p)or("NOTEPAD" in p)or("editor" in p)or("Editor" in p)or("EDITOR" in p)):
			pyttsx3.speak("opening notepad")	
			print("                           Notepad has been opened")
			os.system("notepad")
		elif (("run" in p) or ("Run" in p) or ("RUN" in p)or("open" in p) or ("Open" in p) or ("OPEN" in p)or("start" in p) or ("Start" in p) or ("START" in p)or("LAUNCH" in p) or ("Launch" in p) or ("launch" in p))and(("internet surfing app" in p) or ("Internet surfing app" in p) or ("Internet Surfing App" in p)or("INTERNET SURFING APP" in p)):
			print("          Choose the internet surfing application from the list given below:")
			print("                                     Chrome                       ")
			print("                                     Firefox                       ")
			print("                                 Internet Explorer                      ")
			q=input("               Type here:")	
			if (("run" in q) or ("Run" in q) or ("RUN" in q)or("open" in q) or ("Open" in q) or ("OPEN" in q)or("start" in q) or ("Start" in q) or ("START" in q)or("LAUNCH" in q) or ("Launch" in q) or ("launch" in q)) and (("chrome" in q)or("Chrome" in q)or("CHROME" in q)):
				pyttsx3.speak("opening chrome")	
				print("                      Chrome has been opened")		
				os.system("chrome")
			elif (("run" in q) or ("Run" in q) or ("RUN" in q)or("open" in q) or ("Open" in q) or ("OPEN" in q)or("start" in q) or ("Start" in q) or ("START" in q)or("LAUNCH" in q) or ("Launch" in q) or ("launch" in q)) and (("firefox" in q)or("Firefox" in q) or ("FIREFOX" in q)):	
				pyttsx3.speak("opening mozilla firefox")	
				print("                   Mozilla firefox has been opened")
				os.system("firefox")
			elif (("run" in q) or ("Run" in q) or ("RUN" in q)or("open" in q) or ("Open" in q) or ("OPEN" in q)or("start" in q) or ("Start" in q) or ("START" in q)or("LAUNCH" in q) or ("Launch" in q) or ("launch" in q))and(("internet explorer" in q) or ("Internet explorer" in q) or ("Internet Explorer" in q)or("INTERNET EXPLORER" in q)):
				pyttsx3.speak("opening internet explorer")	
				print("                   Internet explorer has been opened")
				os.system("iexplore")
		elif (("run" in p) or ("Run" in p) or ("RUN" in p)or("open" in p) or ("Open" in p) or ("OPEN" in p)or("start" in p) or ("Start" in p) or ("START" in p)or("LAUNCH" in p) or ("Launch" in p) or ("launch" in p))and(("vs code" in p)or("Vs code" in p)or("VS CODE" in p)or("Vs Code" in p)or("VS Code" in p)):
			pyttsx3.speak("opening V s code")	
			print("                                VScode has been opened")
			os.system("Code")
		elif (("run" in p) or ("Run" in p) or ("RUN" in p)or("open" in p) or ("Open" in p) or ("OPEN" in p)or("start" in p) or ("Start" in p) or ("START" in p)or("LAUNCH" in p) or ("Launch" in p) or ("launch" in p)) and (("wordpad" in p)or("Wordpad" in p)or("WORDPAD" in p)):
			pyttsx3.speak("opening wordpad")	
			print("                                Wordpad has been opened")
			os.system("wordpad")
		elif (("run" in p) or ("Run" in p) or ("RUN" in p)or("open" in p) or ("Open" in p) or ("OPEN" in p)or("PLAY" in p)or("Play" in p) or ("play" in p)or("start" in p) or ("Start" in p) or ("START" in p)or("LAUNCH" in p) or ("Launch" in p) or ("launch" in p))and(("wmplayer" in p) or ("Wmplayer" in p) or ("WMPLAYER" in p)or("PLAYER" in p)or("Player" in p) or ("player" in p) or ("song" in p)or("Song" in p) or ("SONG" in p)):
			pyttsx3.speak("opening windows media player")	
			print("                             Windows media player has been opened")
			os.system("wmplayer")
		elif (("run" in p) or ("Run" in p) or ("RUN" in p)or("open" in p) or ("Open" in p) or ("OPEN" in p)or("start" in p) or ("Start" in p) or ("START" in p)or("LAUNCH" in p) or ("Launch" in p) or ("launch" in p)) and (("excel" in p)or("Excel" in p)or("EXCEL" in p)):
			pyttsx3.speak("opening excel")	
			print("                                    Excel has been opened")
			os.system("excel")
		elif (("run" in p) or ("Run" in p) or ("RUN" in p)or("open" in p) or ("Open" in p) or ("OPEN" in p)or("start" in p) or ("Start" in p) or ("START" in p)or("LAUNCH" in p) or ("Launch" in p) or ("launch" in p)) and (("paint" in p)or("Paint" in p)or("PAINT" in p)):
			pyttsx3.speak("opening paint")	
			print("                                     Paint has been opened")
			os.system("mspaint")
		elif ("exit" in p) or ("Exit" in p) or ("EXIT" in p)or("end" in p) or ("End" in p) or ("END" in p) or ("quit" in p) or ("Quit" in p) or ("QUIT" in p):
			pyttsx3.speak("Thankyou for chatting with us")
			print("                                 Thankyou for chatting with us        ")
			break
		else:
			pyttsx3.speak("SORRY! no such application available")
