# ![logo](/images/logo.jpg) Chickyboo
Solution to Chickyboo crypto riddle

![logo](/images/logo.jpg)

###1st Clue: Youtube Video https://www.youtube.com/watch?v=kRg18QLi_XY

I was like wtf is this video when i saw the video for the first time, but then reading the comments someone told something about a encrypted text at the end of the video. So i checked and it was true!

This is the encrypted message:

`pjhpf oyvpm ytpad idsaa`

I tried with many combinations and many ciphers, but i wasn't getting any plaintext, after reading more comments, someone posted the it was QWERTY related.

Oks, QWERTY for those who doesn't know is just the organization of the keys in our keyboard. So checking the possible combinations i found one that worked:

QWERTY (English Keyboard), left key (alphabet chars only)

`ohgod itcon trols usall --> oh god it controls us all`

###2nd Clue: The QR image.

So... this was posted in the rocketjump twitter: https://twitter.com/rocketjumptweet/status/670349946160214016

![qr](/images/qrimage.jpg)

First we scan the QR Code. The QR code sends us to the following url: http://imgur.com/a/Z41xK

![mask](/images/image2enc.jpg)

Its another image with the following caption:

`YOUHAVE EVERYTHINGTHAT YOUNEED`

I believe the image is using Gmask, lets try it, im using OS X, there is a Windows program called Gmask,
just run it with wine, normal unmasking doesn't work so i supposed there was some password or something.

Download Gmask: http://homepage3.nifty.com/furumizo/gmaskd_e.htm

I tried many combinations 'til i achieved, the trick was using what we got in the 1st clue!:

There were 3 masks, each one with a password: `ohgod`, `itcontrols` and `usall`. It doesn't matter if its uppercase or lowercase.

![mask1](/images/gmask1.jpg)

![mask2](/images/gmask2.jpg)

![mask3](/images/gmask3.jpg)

![mask4](/images/gmask4.jpg)

And finally the decrypted one!

![mask5](/images/gmaskDecrypted.jpg)


Oh my god! there is another ciphered message in the image! It was time to use CrypTool which is very cool to break ciphered messages or just analyse them.

Download CryptTool: https://www.cryptool.org/en/

`gigng tilxf igter ndlpk gxxte larpm zefte phoeq pekhx lbhit bkmre wmzws umpxu wrrhi mewdg ayefs hveel njeft ixehr bfiom msnxp`

I did many tests after analysing it, i was 80% sure it was a Vigenère cipher. So i started analysing it again, so after that i got the following password:

`TASANPE`

But it wasn't decrypting the ciphered message.

![crypto1](/images/crypto1.jpg)

So i had to try shifting the keys, til' one combinations worked (there was a little trick, oh my...)

![crypto2](/images/crypto2.jpg)

And we got it!!

![decrypted](/images/decrypted.jpg)

![decryptedyeah](/images/decryptedyeah.jpg)


And this is the clear text:

`UP ON THE ZENITH A FULL CYCLE BEYOND THE SHADOWED DAY OF LOVE HIS MESSAGE SHALL BE REVEALED TO US MA HIS AZURE SHELL PROTECT US ALL`

### 3rd and final clue. A new youtube video: https://www.youtube.com/watch?v=SUo2ZbjURms

Oh my god! All of this was awesome, hehe, cyber monday, shadowed day, LOL

[@fwong](https://twitter.com/fwong) cool stuff man :)


