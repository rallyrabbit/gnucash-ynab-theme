# GNUCash YNAB Theme

I've tried GNUCash many times through the years and finally made the switch.  But I found that it was hard to read and the color schemes are like a checkbook in the 1980s.  So, I tried to mimic the YNAB theme as much as I could.

This is a work in progress.  Keep in mind, I am trying to make the theme target only GNUCash components.  Making a clean theme like that means that not all of the windows and diaglogs can be targeted.  If the theme gets too broad, then it starts affecting programs that also use GTK (like gimp).

By: Adam Oldham (RallyRabbit)

# Feature

- Account register uses Segoe UI at 20px like YABN (not 18px Arial that is stock in GNUCash)
- Account register colors are like YNAB register (white/light blue with grey header and footers)
- Account list uses the YNAB light blue
- Splits are the ynab yellow
- Highlight row is ynab yellow

# Wants

- Iwant teh css in one file but the theme won't work the the css in GNUCash and Fonts won't work in the theme file and I can't figure out why yet
- Summary row simpler (less data) with balance highlighted
- Change position of deposit and withdrawl columns by default
- Keep working to find ways to do oter dialogs and windows
- 

# Directions

- gtk-3.0.css - Put in %APPDATA%\Roaming\GnuCash
- gtk.css - Put in %APPDATA%\Local\gtk-3.0


