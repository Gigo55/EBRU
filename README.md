
#PYTHON EXAMPLE
note=int(input("sayı giriniz:"))
if 0<=note<=100:
    if note>=80:
        note1=note+10
        print(note1)
    elif note>=60:
        note2=note+5
        print(note2)
    elif note<45:
        note3=note-5
        print(note3)
    else:
        print(note)
else:
    print("hatalı not.")
