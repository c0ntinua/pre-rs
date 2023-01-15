
# pre-wasi

This is the Rust version of the Pre symmetric crypto system (which uses prefix or instantaneous codes when writing ciphertext). It's aimed at WebAssembly runtimes in the terminal in particular. There's a separate key-generator program in another repo. The images below show how it works. Basically you need a key.txt and either a plain.txt or cipher.txt file in the working directory. The program will encrypt or decrypt as appropriate. The colorful output is a representation of the key.

![wasi-pre-1](https://user-images.githubusercontent.com/90075803/212541665-64473fdc-f528-48c1-ac00-c15f1c85a0d8.png)

![wasi-pre-2](https://user-images.githubusercontent.com/90075803/212541675-912f0fcb-2e2b-4609-8eb2-9f204f0d5463.png)
