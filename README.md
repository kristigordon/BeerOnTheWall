# BeerOnTheWall

I am working on for and while loops and learning the range function. 

I used the classic sailors song of beer on the wall to iterate through 100 lines with both the range function in a for loop and with a while loop. 

The for loop with range was much cleaner, easier to understand when reading, and I didn't have to more forcefully decrement a variable 100 times. 

```
for i in range(100, 1, -1):
    print(f"{i} bottles of beer on the wall.\n{i} bottles of beer.\nTake one down, pass it around, {i} bottles of beer on the wall")
    print("*****************************************")
```
```
num = 100
while num > 0:
    print(f"{num} bottles of beer on the wall.\n{num} bottles of beer.\nTake one down, pass it around, {num} bottles of beer on the wall")
    num -= 1 
```

<img width="567" alt="Screen Shot 2022-07-29 at 8 39 39 PM" src="https://user-images.githubusercontent.com/66803124/181863442-4f3e8ca0-5df3-40b4-ba4b-3cc1ef646bf5.png">

<img width="550" alt="Screen Shot 2022-07-29 at 8 39 03 PM" src="https://user-images.githubusercontent.com/66803124/181863417-a02f9a64-f355-441f-b4b7-4e4b6d67be55.png">
