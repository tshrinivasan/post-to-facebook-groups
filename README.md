# post-to-facebook-groups - Not working

# Note : This code worked at 2015. But not in 2020. This is too old. Facebook changed all its API and does not allow posting to groups in bulk. Dont use this repo. Keeping here for archive purpose only.

Author: T Shrinivasan <tshrinivasan@gmail.com>


This is a python script to post some content to multiple facebook groups automatically.

Edit the file post_to_fb_groups.py

1. get api from here  https://developers.facebook.com/tools/explorer
and fill the variable api at line 8

2. After line 18, in the variable message, add your content

3. Find the ids of your desired groups from http://lookup-id.com/
and add this in this array groups at line 32

4. open terminal and run the command 
python post_to_fb_groups.py


Note that you have to be a member ith posting permission to the groups, you add in this file.


License : GPL V3

