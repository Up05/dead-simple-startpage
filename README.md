# dead-simple-startpage

# Installation

## Not Firefox (based) browsers

1. `git clone github.com/Up05/dead-simple-startpage`
2. Open browser settings, "Homepage"/"Startpage", choose to use a specific page.
3. in the `url` box, add: `file:///C:/path/to/startpage/index.html` or open the `index.html` with your browser, press `ctrl + l` and copy-paste link in to the url box.
4. That's that.

## Firefox 

1. Realize, that you do not need a start page.
2. That's that.

# Usage

You can switch mode keys `0-9` (either keypad, or normal ones).  
You can go to links in mode `0` by pressing letters.
If you enter modes with an iframe(another page), it auto focuses.

To add your own crap, edit the index.html.  
For mode 0, it's enough to add `id=<letter>` to any `<a>` elements.  
For modes, add both to `#mode` `<div>` and to `pmodes` array (keep the order the same). *also 0th element is different, because it has different logic.*

![image](https://github.com/user-attachments/assets/600bcc03-47a9-471e-82ee-91571d521b63)

