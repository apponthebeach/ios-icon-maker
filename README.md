# ios-icon-maker
Easy scripts to generate icon for iPhone, iPad & Apple Watch

You will find here for script to execute in order to generate iOS app icons on a Mac.
Those scripts use the command 'sips' in order to generate the icons.

It supposed you have the image that will be used and transform to the targeted formats. This image should be 2048x2048px, which will be the format ask on iTunesConnect in order to submit your app.

## How to use the scripts?
### iPhone
In order to generate iPhone icons, use the script iPhone-icon-maker followed by the name of the image file used.
For example, for a source name icon2048.png, you should execute the following command :
<pre>
./iPhone-icon-maker icon2048.png
</pre>

### iPad
In order to generate iPad icons, use the script iPad-icon-maker followed by the name of the image file used.
ex:
<pre>
./iPad-icon-maker icon2048.png
</pre>

### Apple Watch
In order to generate Apple Watch icons, use the script AppleWatch-icon-maker followed by the name of the image file used.
ex:
<pre>
./AppleWatch-icon-maker icon2048.png
</pre>

### All formats
Finaly if you have exactly the same icon for iPhone, iPad and Apple Watch, you can generate all icons in one command, using the script all-format-icon-maker. Be aware that this last script will work only if you have the three other ones in the same folder.
ex:
<pre>
./all-format-icon-maker icon2048.png
</pre>

## History
### 1.0
* Generate all icons needed for iPhone, iPad and Apple Watch

## License
This script follow MIT license.

## Contact
If you have any question with using it, you can email to me. My email is: appnotie@gmail.com
