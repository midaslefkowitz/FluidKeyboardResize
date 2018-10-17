![Fluid resize](https://github.com/saket/FluidResize/blob/master/images/fluid_resize.gif)

This is a java fork of the [original Kotlin version of this project](https://github.com/saket/FluidKeyboardResize).

Details can be found in the original authors blog post, [Smoothly reacting to keyboard visibility changes](https://saket.me/smoothly-reacting-to-keyboard/).

The implementation for detecting keyboard visibility and animating size change can be found in [FluidContentResizer](https://github.com/midaslefkowitz/FluidKeyboardResize/blob/java/fluidresizelayout/src/main/java/me/saket/fluidresize/FluidContentResizer.java#L16) and its usage [here](https://github.com/midaslefkowitz/FluidKeyboardResize/blob/java/sample/src/main/java/me/saket/fluidresize/sample/FluidResizeActivity.java#L16). It's a tiny project so feel free to simply copy over the necessary files to your project.

### License

```
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

Full license can be read [here](https://github.com/midaslefkowitz/FluidKeyboardResize/blob/java/LICENSE).
```
