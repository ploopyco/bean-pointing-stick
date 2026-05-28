The firmware that ships on all Beans is `bean.uf2`.

## MacOS scrolling issues

Certain operating systems, like MacOS, don't play well with the high-res scrolling implementation. For more details, see: https://github.com/qmk/qmk_firmware/issues/17585#issuecomment-2325248167

This issue causes the drag scroll function to go much too fast on MacOS. The current fix is to use the `bean_no_high_res_scroll.uf2` firmware, which reduces scrolling to a usable speed.

Flashing the new firmware is easy; just hold down the bottom-left button while plugging the Bean in. Your computer should recognize a USB mass storage device was just plugged in. After that, copy and paste the firmware onto the device, and you're done.