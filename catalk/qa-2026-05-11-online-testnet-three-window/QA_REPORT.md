# Catalk Online TestNet three-window QA — issue evidence only

Target: https://chat-testnet.opcatlabs.io

Visible QA profiles: Alice, Bob, Charlie. OP_CAT Layer testnet. Existing QA wallets/profiles reused.

## Findings

1. Public group three-user roundtrip failure: Alice message `Alice reused public depth reuse-mp1xx311` did not appear on the other user windows within 240 seconds.
2. Private group propagation failure: Bob message `private group reuse Bob private-dm-mp1yb7fh` did not appear for Alice within 150 seconds.
3. Direct message propagation failure: Alice→Bob DM `dm alice to bob private-dm-mp1yb7fh` did not appear for Bob within 150 seconds.

## Passed online checks

- Public group open on all 3 profiles.
- Public mention picker/send, reply/quote, image send, and refresh all passed online.
- Meow feed, Meow compose, Reward tabs, Profile edit/cancel, Settings language/logout all passed online.
- DM third-user non-visibility passed online.

## Evidence

- PDF: `Catalk_Online_TestNet_Three_Window_Issue_Evidence_2026-05-11.pdf`
- PNGs in this directory are full-window issue screenshots only.
