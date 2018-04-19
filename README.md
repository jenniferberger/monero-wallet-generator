# monero-wallet-generator
Monero (XMR) offline wallet generator

This page generates a new Monero or Aeon address. It is self contained and does all the necessary calculations locally, so is suitable for generating a new wallet on a machine that is not connected to the network, and may even never be. This way, you can create a Monero or Aeon wallet without risking the keys.

It contains all the resources in a single HTML file.
The bundled resources are

 JavaScript BigInteger library version 0.9
 http://silentmatt.com/biginteger/

 * Waves v0.6.0
 * http://fian.my.id/Waves

// QRCode for JavaScript
//
// Copyright (c) 2009 Kazuhiko Arase
//
// URL: http://www.d-project.com/

 js-sha3 v0.5.1
 * https://github.com/emn178/js-sha3
 *
normalize.css v3.0.2 | MIT License | git.io/normalize */
http://polymer.github.io/LICENSE.txt (css)

emcrypten asm (assumably for really big integers)

mnemonic.js : Converts between 4-byte aligned strings and a human-readable
 sequence of words. Uses 1626 common words taken from wikipedia article
