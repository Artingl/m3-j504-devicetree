# WARNING
I probably don't know what am i doing, but it works. These DTs will not work with generic linux kernel, nor with asahi kernel as it requires patched kernel. But there's a patched version by Janne Grunau, which fixes the AIC v3: https://github.com/jannau/linux/tree/t8122-j504
They also provided DT, which will work, but the keyboard functionality is broken in their DT, which i fixed, as well as some other things.

My DT has some hardcoded values, like FB base, which might be different on your device
# Things that do work
Currently these things work: aic v3, only single cpu core (no smp), dart, mtp and keyboard, simple drm framebuffer, usb2 support
