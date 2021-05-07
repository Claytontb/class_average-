# class_average-
"""
input: the test score 
intiate a iterator (counter) and accumulator and set it to zero 
loop through the list test scores 
add all the test scores 
increment the computer by one 
once the loop ends there are no more words to add 
divide the accumulator (sum) by the counter
display the output to the user 
output: print the average of the class scores
"""


"""
scores 
iterator, accumulator=0
loop through scores 
  accumulator = accumulator + scores 
  iterator = iterator + 1
output = accumulator / total score 
print average
"""

def calculate_average(scores):
  iterator = 0
  accumulator = 0
  student_count = len(scores)
  print("Length is: ", len(scores))

  while iterator < len(scores):
      # print("within while loop iterator: ". iterator)
      print(f"'item at index ${iterator} is: ", scores(iterator)
      accumulator = accumulator + scores(iterator)
      iterator = itertor = 1 

  print("sum is: ", accumulator)
  average = accumulator / student_count 
  print("the average total scores in the class is: ", average)
  return average 

output = calculate_average(100, 90, 50, 40, 60, 70)

print("The average of the total socres in the class is: ", output" , output)