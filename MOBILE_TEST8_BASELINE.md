# Preferred mobile fallback — Test 8

Chosen by the user on 2026-11-07 for the smoothest overall experience. Continue fine-tuning separately; retain this exact fallback.

- Source: mobile-test-timing.html at commit b9054f67552551a39fcb41886ad9f6b6073930b4.
- Source blob: aeb7a11b5cde841fdbff62c287d8c0d9d84a83ee.
- dev_mode=false; 30 FPS maximum; mobile longest edge capped at 1440; mobile WebRTC ceiling 4000 kbps, minimum 0.
- Explicit Start Test button; sustained-playback startup gate; corrected timer binding and protected curtain dismissal.
- No Test 7 map cleanup. Server originally reported MaxQP 32. No experimental MaxQP 40 override.
- Best Test 8 report: 19.2 seconds to reveal, gameplay 29.5 FPS average, no browser-reported gameplay drops or long freezes, average gameplay jitter buffer 66 ms. Some brief FPS dips remained. User reported very smooth playback.
- Main index was intentionally still Test 6 when this checkpoint was made. Restoring the preferred Test 8 means using mobile-test-timing.html, not this branch's index.html.

Do not package or upload Unreal builds automatically. Ask before further paid live tests. Preserve camera motion and use at most 30 FPS on every platform.
