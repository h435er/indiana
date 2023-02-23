
print("---------------")
print("| Indiana Tom |")
print("---------------")
start=input("starten?(J/N)")
if start =="N":
  print("dann bist du wohl noch nicht so weit")
  quit()
elif start=="J":
  print("ok dann geht es jetzt los:")
  print("-----------------------------------------------------------------------------------------------------")
  print("| die geschichte erzaehlt von einem Tom(du) der mit seinem bestem Freund Tim  auf schatzjagt war    |")
  print("| eines tages hoerten sie von einem gewaltigem Schatz, der so viel wert hat wie alles Geld der Welt |")
  print("| die Polizei hoerte auch davon und so begann ein ewig langer wettstreit...                         |")
  print("-----------------------------------------------------------------------------------------------------")
start2=input("Tim: sollen wir in den Wald gehen(wald) oder in einer Hoele suchen(hoele)?")
if start2=="wald":
  print("Tom: wir gehen in den Wald, weil ich glaube dass wir dort einen Hinweis finden")
  print("30 minuten spaeter:\nTim: Tom,weisst du dass wir schon seit 30 minuten im Kreis laufen?")
  print("Tom:ja, das weiss ich aber hier muss doch ein schatz sein!")
  print("Tim:jajaja...aber warte! da glaenzt ja was! komm schnell hin!")
  print("Tom: das ist ja eine Flasche mit einem brief drinnen!")
  flasche=input("Tim,soll ich die oeffnen?(ja/nein)")
  if flasche=="ja":
    print("'plop'...Tim:na guck mal! das ist eine Schatzkarte! eine waschechte Schatzkarte!")
    quit()
  elif flasche=="nein":
    print("Tom:ok, die ist eh schon dreckig...ich glaube nicht dass dort ein Hinweiss drinnen ist")
    quit()
elif start2=="hoele":
  print("Tom: komm wir gehen in diese neue entdeckte hoele die wir gefunden haben!")
  print("Tim:da ist sie!")
  rein=input("Tim:sollen wir hineingehen?(ja/nein)")
if rein=="ja":
 print("Tom:das ist aber gruselig!")
 quit()
elif rein=="nein":
  print("dann lass uns mal aussen herum gucken ob da was ist!")
  quit()
    
