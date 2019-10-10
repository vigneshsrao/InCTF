# ateles

### Description

The attachment contain 2 files. `ateles_handout.zip` contains only the patch file. For the fully built binaries and the remote environment, download `ateles_handout_large.zip` (165MB)

The aim is to execute `/usr/bin/xcalc` on the remote server. 

### Short Writeup

2 element overflow in Array, as initialized length is compared with (initialized length + 2) when jit'ed. Use this to overwrite the shape and group for the following object (say a Uint8Array) to that of Uint32Array, thus attaining a larger overflow in a typed array.

### Handout's

Since the handout is quite large, here are the google drive links for the same.

[https://drive.google.com/drive/folders/1bLUPugg3LXu8OxauG53VZnIs1x8ZVgtF?usp=sharing](https://drive.google.com/drive/folders/1bLUPugg3LXu8OxauG53VZnIs1x8ZVgtF?usp=sharing)

### Flag

inctf{r3sh4ping_th3_ateles_for_sh4ping_up_a_pr0t3le$}

@sherl0ck__

