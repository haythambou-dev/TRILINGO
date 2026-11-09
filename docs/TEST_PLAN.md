# Test plan

Record only tests that were actually performed. Add date, hardware revision, firmware commit and results.

## Test 1 — controller detection

- [ ] Exact ESP32 board identified
- [ ] Board powers from USB
- [ ] Computer detects serial port
- [ ] Test sketch uploads
- [ ] Serial Monitor output verified

## Test 2 — button inputs

- [ ] One button tested
- [ ] All nine buttons tested individually
- [ ] No false/repeated presses during a 5-minute test
- [ ] Button-to-message mapping recorded

## Test 3 — language selection

- [ ] Darija selection verified
- [ ] French selection verified
- [ ] English selection verified
- [ ] Switching language does not trigger a button accidentally

## Test 4 — audio

- [ ] Exact audio module identified
- [ ] Speaker wiring checked against module documentation
- [ ] Each message plays correctly
- [ ] Volume is appropriate
- [ ] No unexpected resets during playback

## Test 5 — usability

Only test with appropriate consent and adult supervision. Do not claim clinical effectiveness from informal testing.

- [ ] Picture labels are understandable
- [ ] Buttons are easy to reach and press
- [ ] A user can select a message without step-by-step prompting
- [ ] Feedback and observed difficulties documented
