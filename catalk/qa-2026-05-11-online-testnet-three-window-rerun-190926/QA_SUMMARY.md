# Catalk Online TestNet three-window QA rerun — issue evidence

- Target: https://chat-testnet.opcatlabs.io
- Run artifacts: `/Users/aibot/.openclaw/workspace/screenshots/catalk-online-rerun-20260511-190926`
- Existing QA profiles reused: Alice / Bob / Charlie
- Visible windows: three headed Chrome-for-Testing windows open simultaneously
- Issue-only screenshots copied here: full-window chat captures for failing flows only

## Results

### Persisting failures
1. Public group text propagation: `Alice reused public depth reuse-mp1zsunu` did not appear within 240000ms.
2. Private group member propagation: `private group reuse Bob private-dm-mp205n95` did not appear within 150000ms.
3. Direct message propagation: `dm alice to bob private-dm-mp205n95` did not appear within 150000ms.

### Passed in this rerun
- Public group mention picker/send, reply/quote, image message, and refresh flow.
- Meow feed/compose, Reward tabs, Profile edit modal validation/cancel, Settings logout/language controls.
- DM third-user non-visibility guard remained valid during the private/DM run.
