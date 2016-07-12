# haskell-libui
Haskell bindings to the [`libui`](https://github.com/andlabs/libui) C library.

- [x] Raw FFI available in `Graphics.LibUI.FFI`
  * [x] All functions from the FFI mirror their `libui` names prefixed with `c_`
  * [ ] Document the FFI
- [ ] Haskell callback based API in `Graphics.LibUI.Types`
  * [x] Data-wrappers for `uiControl` type
  * [ ] Callback based API
