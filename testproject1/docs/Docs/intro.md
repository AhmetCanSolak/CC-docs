## What is ClearControl?

It is a software to control your custom microscopes.

## Motivation

There were only vendor specific software pieces to control microscopes and those
were not satisfying for especially researchers of this field. Hence, we come up
with ClearControl to address this issue.

## Fundamental Features

- It has an intuitive GUI to increase accessibility among people with different
backgrounds.

[GUI Picture here]()

- It is modular and extendable. If ClearControl does not support a hardware you
have you can easily wrap vendor drivers and use it within ClearControl.
- It is performant in a very unexpected way. It uses `coremem` and `OpenCL` under
the hood.
- There is also a version for lightsheet microscopes. Check [ClearControl-Lightsheet](https://github.com/ClearControl/clearcontrol-lightsheet) for details.
