# day-14
def vowel_links(txt):
    a = txt.split()
    vowels = "aeiou"
    for i in range (len(a)-1):
        if a[i][-1] in vowels and a[i+1][0] in vowels :
            print (True)
        else:
            print (False)
txt=input()
vowel_links(txt)
