def main():
  intro()
  try: 
    miles_needed = int(input('Enter the number of miles: '))
    miles_to_kilometers(miles_needed)
  except:
    print('An exception occurred, try again entering only a number.')
    print()
    main()

def intro():
  print("This program converts measurements")
  print('in miles to kilometers. For your')
  print('reference the formula is: ')
  print(' 1 mile = 1.609 kilometers')
  print()

def miles_to_kilometers(miles):
  kilometers = miles * 1.609
  print('That converts to', kilometers, 'kilometers.')

main() 
