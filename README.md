# tscc
> Typescript to C compiler

## Support
> The compiler currently supports:

- [x] Function definitions
- [x] Data types (string, number)
- [x] Function calls
- [x] If
- [x] Else
- [x] Automatically detect requirements and inject #include tags
- [x] `==` - comparison
- [x] `!=` - comparison

## Installation & Usage
> To install tscc, first simply compile it:
```bash
    make
```
> Then you can move it to `/usr/local/bin`:
```bash
    sudo mv ./tscc.out /usr/local/bin/tscc
```
> Now you can use it like this:
```bash
    tscc <filename>.ts
```
