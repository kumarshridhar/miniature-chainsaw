# miniature-chainsaw
def sortedinsert(x,n): 
  x.sort()
  for i in range(len(x)):
    if(n<x[i]):
      x.insert(i,n)
      break
  return(x)
