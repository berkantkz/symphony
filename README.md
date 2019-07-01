# symphony
like a love song on the radio

## Usage:
As it is set as default [here](https://github.com/berkantkz/symphony/blob/master/index.html#L162), you will see "_Symphony, like a love song on the radio_" when you visit [https://berkantkz.github.io/symphony/](https://berkantkz.github.io/symphony/).

To change this text containing of 3 lines, add ```?``` (quetion mark) right after ```index.html``` and add your first string right after ```string1``` parameter, add your second string with ```string2``` parameter, and add your third string with ```string3``` parameter.
> *Don't forget to seperate the parameters with ```&``` (ampersand)!*

See the example below:

> [https://berkantkz.github.io/symphony/```?string1=Move&string2=along with&string3=the truth.```](https://berkantkz.github.io/symphony/index.html?string1=Move&string2=along%20with&string3=the%20truth.) will print:
**media deleted from the server**

To change background image, add the url of the image that you want to set as background right after ```bg``` parameter. See example below:
> [https://berkantkz.github.io/symphony/index.html?bg=https://i.ytimg.com/vi/vR0PHuWHzSQ/maxresdefault.jpg](https://berkantkz.github.io/symphony/index.html?bg=https://i.ytimg.com/vi/vR0PHuWHzSQ/maxresdefault.jpg) will print:
**media deleted from the server**

If we combine all of them together:
> [https://berkantkz.github.io/symphony/```?string1=Move&string2=along with&string3=the truth.&bg=https://i.ytimg.com/vi/vR0PHuWHzSQ/maxresdefault.jpg```](https://berkantkz.github.io/symphony/index.html?string1=Move&string2=along%20with&string3=the%20truth.&bg=https://i.ytimg.com/vi/vR0PHuWHzSQ/maxresdefault.jpg) will print:
**media deleted from the server**

### Notes:
* You don't need to mind the special characters as Javascript will parse them. This is valid for the characters like ```?, !, -, #, and space ( )``` and some characters that are available in my own language such as ```ö, ç, ü, ğ, ş``` etc. I didn't test and I also don't know if it would work for the special characters that are from any other language.

### Questions:
  - Q: Why such a page exists?
  - A: I have no idea. I made it just because I wanted to deal with something when I had some free time.

>

  - Q: How about the background?
  - A: ~~Can't be changed. Perhaps I will add an option for it too later. if I find some time for sure.~~ **I added an option for it too!**
 
--- 
> *I made this thing for landscape & desktop devices. How about mobile view? - Eww, I hate it.*
