# haskell-libui
- - -

Haskell bindings to the [`libui`](https://github.com/andlabs/libui) C library.

- [x] Raw FFI available in `Graphics.LibUI.FFI`
  * [x] All functions from the FFI mirror their `libui` names prefixed with `c_`
  * [x] Document the FFI
- [x] Haskell callback based API in `Graphics.LibUI.FFI.Wrapped`
  * [x] Data-wrappers for `uiControl` type
  * [x] Callback based API

- - -

Tested on OSX and Ubuntu 14.04. A Vagrantfile is available.
