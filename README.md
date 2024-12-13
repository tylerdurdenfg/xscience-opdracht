# xscience-opdracht


def chatbot():
    print("Hallo! Ik ben uw dokter-chatbot over gezondsheidsklachten. welke vragen kan ik voor u beantwoorden?")
    print("-------------------------------------------------------")
    print("dit zijn dingen die u kunt vragen:")
    print("-wat kan ik doen tegen hoofdpijn?")
    print("-wat kan ik doen tegen buikpijn?")
    print("-wat kan ik doen tegen spierpijn?")
    print("-wat kan ik doen tegen rugpijn?")
    print("-wat kan ik doen als ik niet kan slapen?")
    print("-wat kan ik doen tegen hooikoorts?")
    print("-wat kan ik doen tegen duizeligheid?")
    print("-wat moet ik doen als er een mes in mijn buik zit?")
    print("-------------------------------------------------------")
    print("Typ 'stop' als u zich weer beter voelt :)")
    print("-------------------------------------------------------")

    while True:
        # Vraag om input van de gebruiker
        user_input = input("YOU: ").lower()

        #stoppen
        if user_input == "stop":
            print("Chatbot: Bedankt voor het praten! Tot ziens!")
            break

        # Antwoorden 
        elif "hallo" in user_input or "0" in user_input:
            print("Chatbot: hallo, wat voor vragen kan ik beantwoorden?")
        elif "wat kan ik doen tegen hoofdpijn?" in user_input or "1" in user_input:
            print("Chatbot: Heeft u vandaag al water gedronken? Veel mensen vergeten om water te drinken dus drink wat water en neem een paracetamol.")
        elif "wat kan ik doen tegen buikpijn?" in user_input or "2" in user_input:
            print("Chatbot: Ga even liggen en relax om je beter te voelen stop ook even met wat eten en drink wat water en/of neem een paracetamol.")
        elif "wat kan ik doen tegen spierpijn?" in user_input or "3" in user_input:
            print("Chatbot: Stop met intensiefe bewegingen en eet eiwitten voor een sneller herstel.")
        elif "wat kan ik doen tegen rugpijn?" in user_input or "4" in user_input:
            print("Chatbot: Neem een paracetamol en ga liggen, als u zich weer iets beter voelt kunt u yoga proberen. Yoga is heel goed voor je rug en je hele lichaam.")
        elif "wat kan ik doen als ik niet kan slapen?" in user_input or "5" in user_input:
            print("Chatbot: Neem een slaapmiddel en ga overdag bewegen/sporten om beter te kunnen slapen.")
        elif "wat kan ik doen tegen hooikoorts?" in user_input or "6" in user_input:
            print("Chatbot: Voor veel hooikoorts zijn er pilletjes voor, het is dus handig om pilletjes mee te en zakdoekjes op zak te hebben.")
        elif "-wat kan ik doen tegen duizeligheid?" in user_input or "7" in user_input:
            print("Chatbot: Duizeligheid komt vaak door te weinig slaap, te veel werk, en te weinig water gedronken. Probeer wat rust te nemen misschien wat frisse lucht in ademen en beter slapen.")
        elif "wat moet ik doen als er een mes in mijn buik zit?" in user_input or "8" in user_input:
            print("Chatbot: BEL GELIJK 112 SNEL!!!!!")
        else:
            print("Chatbot: Sorry maar dat begrijp ik niet, misschien heeft u een hoofdletter gebruikt, geen vraagteken gebruikt of een woord verkeerd gespeld. Kan ik u met iets anders helpen?")


chatbot()
