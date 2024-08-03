# TLM-Tool
This is "Text Lines Modifier Tool".

This tool contains 4 modify modules to modify lines in text files:
1. add_i()
2. add_name()
3. edit_i()
4. edit_name()

To use this tool, you need to have small knowledge in Python language, but I can explain how these 4 modules work and which variables you need to use, while creating auto-scripts, I didn't release this tool, but these modules are used in my first project "RS SDM Tool" (from my repository "Rolling-Sky-Cheating-Legends").

If you want to educate how this tool works, then read tutorial lessons.
# Lesson 1: Variables
I have no idea how to explain variables without examples, but I think this way is better to understand

Example of using "range_from" and "range_to":
range_from = 1
range_to = 21
(Their value means: "from 1 to 20" or on python it's "for i in range(1, 21)")

Example of using "range_list" and "range_list_finder":
range_list = "Example_One, Example_Two, Example_Three, Example_Four".split(', ')
range_list_finder = "Mutual_key_{name}"
(In this example range_list contains 4 names, they are also splitted by .split() (you can set another split, if you want))
(In this example range_list_finder using mutual name to find key phrases in text file, I added {name} to range_list_finder to use 4 find key phrases with range_list, it means, range_list_finder contains phrases:
Mutual_key_Example_One
Mutual_key_Example_Two
Mutual_key_Example_Three
Mutual_key_Example_Four)

Example of using "line_from" and "line_to":
line_from = 2
line_to = 3
(their value means a line from variables "phrase_i" or "phrase_name" will be generated between line 2 and line 3 (in text file))
