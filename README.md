Customized version of Google's Chromium power_LoadTest app/extension ([code](https://chromium.googlesource.com/chromiumos/third_party/autotest/+/HEAD/client/site_tests/power_LoadTest), [homepage](http://www.chromium.org/chromium-os/testing/power-testing)) that runs for 20 hours instead of just one.

To change number of loops (hours of testing), change value of "loop_hours" at the top of test.js
Log into Facebook and Gmail before starting test. Enable plug-ins automatically if you have them disabled (for streaming audio)

To-dos:
+ ~~Make extension keep Chromebook always awake, no screen-off/sleep (possible?).~~
+ Have extension "log" battery life every x amount of time (to where? localhost webpage? local storage? synced storage?)
