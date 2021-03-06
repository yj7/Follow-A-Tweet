Follow-A-Tweet
==============

This script allows you to follow particular tweets of interest, even if you are not on twitter.

AUTHOR: Priyans Murarka
======
###How To:

To use this script, you will need a tweet link. To obtain tweet link, click on the tweet you would want to follow. Click on the small option 'Details'. It will redirect you to the tweet's link. You can copy paste the address from the browser and use the same.
Also, please pick up the 'root' tweet for best results.

###Usage:
 
    $ sh follow-a-tweet.sh https://twitter.com/priyansm/status/371531619103805440 20m
======

##Features:

1. Works perfectly well with simple text based replies to the tweets.
2. Responds in user-specific time.
3. Sends proper notifications on the desktop.
4. Since it is shell-based, there is no need to install any extra features.

##TODOs:

1. Add 'Original Tweet' when notifying the user about the replies to the tweets.
2. Optimize the code.
3. Repair the tweet format when it contains hashtags or links.
4. Add additional flexibilities like mailing a compiled list of responses to a particular mail address.
5. Make it platform independent.
6. Add the functionality to follow 'multiple' tweets.
