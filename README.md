def sumlist(list,myresult)
  for i in list 
    myresult = myresult + i
  end 
  return myresult

end

list =[1,2,1,3]

result = sumlist(list,0)

puts result
