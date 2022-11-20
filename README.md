# WhatsApp-Group-Chat-Analysis

## Getting Started
You need to export the group chat without media and put that text file into your project folder where you are working.Then use ipynb file in that you can see all type of analysis that I have made.WhatsApp provides an option to export the chat which we can use it for analysis purpose. It is recommended to export any group chat for analyzing since it tends to be larger.

You will find the “Export chat” option in your WhatsApp chat (group/individual). Find the vertical ellipsis symbol > More > Export chat. Note: This feature isn’t supported in Germany.


### Installing

* while using colab

```
pip install emojis
```
* I found this emoji.UNICODE_EMOJI and emoji.UNICODE_EMOJI['en] as an error.
So, I got it solved using emoji.distinct_emoji_list(test)
where, test is a string.
```
emojis = emoji.distinct_emoji_list(word)
  new_line_list.extend([emoji.demojize(is_emoji) for is_emoji in emojis])
```



## Acknowledgments

* https://stackoverflow.com/
* https://medium.com/analytics-vidhya/whatsapp-group-chat-analysis-8f184d3b4586
* https://about.meta.com/technologies/
* https://stackoverflow.com/

