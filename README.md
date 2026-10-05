# fancygrep
fancygrep is a command which combines grep and wc. It searches through the file for a word, and displays the lines containing the word and the count. 
Syntax:
node fancygrep.js filename word
Example:
node fancygrep.js test.txt Hello

AI Assisted Programming:
I used AI to help me understand the commands that could be combined into a Fancy Command. It helped me understand what each command does such as 'tee' and helped me come up with edge cases for my program. I had to think independantly to come up with the Fancy Command and tested it myself. I tested it using a word that occurred in the file multiple times and one that didn't occur at all to match the edge cases AI came up with. One thing AI missed was while explaining the command 'tee' to me it failed to mention that it requires a new line at the end of the text file to append without adding on to the last line.
