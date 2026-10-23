# How to use
1. Download all the files
2. Unzip the foods2.zip folder, take out the foods2.db file and delete the folder
3. Now you should have Anleitung.txt, Mappe1.xlsm, foods2.db and lookup_food_caching.exe in one folder
4. !!Important!! I would heavily recommend to copy the Mappe1.xlsm file and only work in copies and leave the original file as is, because this way you can just
   always create a new file without needing to delete the data inside
5. After following all the previous steps you can open your copy of Mappe1.xlsm
6. Now simply enter the name (in english) of the food you want to track and the amount of it in gramms
7. wait for a short time and you should see the rest of the columns be filled in
8. You can continue this for as many rows as you'd like

# for who is this useful
- fitness coaches who already use excel sheets and don't want to switch to other software, but still want their work to be more efficient
- people in general who prefer excel over other apps/websites, but don't want to manually enter everything

# how it works
1. The excel sheet is extended with makros, with a self written script
2. it recognizes changes it the selected columns (A and B)
3. after recognizing it sends the values to a python programm which searches through the database for the food item
4. if something was found the exact calories, proteins, ... get calculated based on the gramm amount the user put in
5. after all the data is collected excel inputs it in the corresponding columns of the specific row
6. if the food doesn't get found it shows you what similar words you could have meant
7. the software "learns" from you, basically if you use something more often the response should be faster

(The software currently runs mostly in german, though the input is entirely in englisch, which was mainly done to keep performance higher due to various reasons)
