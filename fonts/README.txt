Samarkan is installed as samarkan.ttf and is wired up in index.html
(@font-face + the font-samarkan Tailwind token, used by the hero <h1>).

LICENCE - ACTION REQUIRED
Samarkan is shareware, (c) Titivillus Foundry. The author asks for $7.50 USD
registration if you intend to use it. This is a commercial site, so that
payment is owed. Details are in samarkan-LICENCE.txt (PayPal ethelrp@gmail.com).

OPTIONAL - make it smaller
The .ttf is 58 KB. Converting to .woff2 would roughly halve it:
  https://cloudconvert.com/ttf-to-woff2
Save the result here as samarkan.woff2, then in index.html change the
@font-face src line to:
  src: url('fonts/samarkan.woff2') format('woff2'),
       url('fonts/samarkan.ttf') format('truetype');
