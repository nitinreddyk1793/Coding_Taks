def revrev(to_rev):
  if len(to_rev)==0:
      return "Please enter the value wit length more then 2"
  elif len(to_rev)==1:
      return to_rev
  else:
       original=to_rev.split()
       string_join=""
       Reversed=[]
       try:       
          for i in original:
             j=len(i)-1
             while j>=0:
                string_join=string_join+i[j]
                j=j-1
             Reversed.append(string_join)
             string_join=""
       except IndexError:
            print("An Index Error have occurred")
  return " ".join(Reversed)
            
print(revrev("The quick brown fox"))
