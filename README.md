# ITS140
week_day = int(input('Welcome! Please enter a number between 1 & 7:  '))
if week_day > 7:
  output = 'Uh oh! Please enter a number between 1 & 7 '

if week_day == 1:
  output = "You've chosen Sunday!"
elif week_day == 2:
  output = "You've chosen Monday!" 
elif week_day == 3:
  output = "You've chosen Tuesday!"
elif week_day == 4:
  output = "You've chose Wednesday!"
elif week_day == 5:
  output = "You've chosen Thursday!"
elif week_day == 6:
  output = "You've chosen Friday!"
elif week_day == 7:
  output = "You've chosen Saturday!"

print(output)
