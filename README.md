# Hell & Heaven Names List

A single-file, offline-capable web app that stores your logins in an
encrypted vault inside your own browser.

## How it works
- Open the page and choose a code (master password) of 12+ characters.
- Your entries are encrypted with AES-256-GCM, with a key derived from
  your code using PBKDF2 (600,000 rounds). All of this happens in your
  browser using the built-in Web Crypto tools.
- Nothing is sent to any server. There are no accounts and no tracking.
- The vault locks itself after 2 idle minutes.

## Sharing
Use "Share and back up" to make an encrypted copy. Send it to someone,
tell them your code in person or by phone, and they can merge it into
their own vault.

## Important
- Your vault exists only in the browser you use it in. Clearing site
  data erases it, so keep an encrypted copy somewhere safe.
- A forgotten code cannot be recovered.
- This is a personal project and has not had an independent security
  audit. Don't make it the only copy of critical passwords.

## Use it
Open the hosted page, or download `index.html` and open it in a browser.
