# 8-digitPINs
---
A list of all possible 8-digit PIN combinations starting at 00000000 and ending at 99999999.

Compressed with 7-zip (https://www.7-zip.org/download.html)

<i> I do not condone, encourage, or support those who would use this information for malicious or illegal means.</i>


#Dabeersboys notes-
This is a big thanks to FullTang who put these lists together. I am super proud of your skillset and proud of the work you do and your accomplishments.

I forked these different repos of passcodes because on several occasions I have had the request or the need to find all passwords using the following digits, or use everything but these digits…. Here we bring in Inverse grep commands.

Here is a grep command for inverting grep to create a list of all passcodes not using what ever digits. These text files can be loaded into hash cat, Cellebrite Premium, Graykey, Password, ETC…..

Ie.

grep -E -v “any|number|that|you|don’t|want|used|” “8digitPIN.txt" > "modified_8digitPIN.txt"

grep -E -v "2|5|8|0" “8digit.txt" > “modified_8digitPIN.txt"

So the above command will search through all the 8 digit passcodes text file and create a list that isn’t using the digit 2, 5, 8, or 0 and puts it into a new text document called “modified_8digit.txt
