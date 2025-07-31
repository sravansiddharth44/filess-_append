# filess-_append
with open('line.txt','a+')as file:
    text=input("enter a line to append data")
    file.write(text+'\n')
    file.seek(0)
    print("\n cueernt contentin the file")
    print(file.read())
