In this question, they want the input to be true if the word is same when Reverse ignoring the cases and considering alpha numeric characters only.
All the spaces to be removed, not considering special characters and upper cases to lower cases then reverse it will get the output.
Now we have to use pointer left pointer L and right pointer R.
We will compare left character and right character and check if it is same.
If not same then we apply return.
We will keep incrementing left pointer and decrementing right pointer until the left pointer passes the right pointer that is they meet each other.
That is when, they have to stop.
When on left or right there is non alpha numeric ignore it and compare next one with the right or left pointer character.
To do that we will create while loop that is while our characters is non alpha numeric L += 1 then we go ahead if at right pointer R -= 1
then when they reach or meet at middle we stop the algorithm we detect it is true.
