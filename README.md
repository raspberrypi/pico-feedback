# Feedback on Raspberry Pi Pico and RP2040

* Issues relating only to the Pico C/C++ SDK should be filed against the [`pico-sdk`](https://github.com/raspberrypi/pico-sdk) repo.
* Issues relating to the C example code should be filed against the [`pico-examples`](https://github.com/raspberrypi/pico-examples) repo.
* Issues relating to the to [`pico-extras`](https://github.com/raspberrypi/pico-extras) or [`pico-playground`](https://github.com/raspberrypi/pico-playground) should also be filed against those repos.
* ~Issues relating only to the MicroPython port should be filed against the `micropython` repo.~
* Issues relating to the Python example code should be filed against the [`pico-micropython-examples`](https://github.com/raspberrypi/pico-micropython-examples) repo.

In general if there is a specific repo for the thing you have an issue around, you should file the issue on that repo. However all other issues, including documentation, other user-facing issues like IDE problems, should be filed [here](https://github.com/raspberrypi/pico-feedback/issues).

Issues relating to the MicroPython port should now be filed against the upstream [`micropython`](https://github.com/micropython/micropython) repo as there is now a [pull request](https://github.com/micropython/micropython/pull/6791) to integrate the RP2040 into the main MicroPython distribution.

Issues relating to the CircuitPython port should be filed against the main [`circuitpython`](https://github.com/adafruit/circuitpython) repo as CircuitPython is maintained by Adafruit, and initial RP2040 support has [already been integrated](https://github.com/adafruit/circuitpython/pull/4031) into the main CircuitPython distribution. CircuitPython binaries can be found [here](https://circuitpython.org/board/raspberry_pi_pico/).
