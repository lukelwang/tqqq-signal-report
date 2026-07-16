# tqqq-signal · Distance-to-BUY (auto-published, encrypted)

Live diagnostic page, regenerated every US market weekday by the `tqqq-signal`
cron (`scripts/post_daily.sh`). Read-only; never affects a trading decision.

**Live page:** https://lukelwang.github.io/tqqq-signal-report/ (password-protected)

The page is AES-256 encrypted with
[StatiCrypt](https://github.com/robinmoisson/staticrypt) before it is pushed,
so this repo and the hosted site only ever contain ciphertext. The strategy
code, data, signal logs — and the decryption password — live outside this repo.
