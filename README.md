
# EncryptoFile

EncryptoFile is a simple command-line tool for encrypting and decrypting files using a password-based encryption algorithm. It allows you to securely protect the contents of your files from prying eyes, and can be used to protect sensitive information such as personal or financial data.



## Installation

To use EncryptoFile, you'll need to compile it from source. Here's how:


1.Clone the EncryptoFile repository:
```bash
  git clone https://github.com/AkhilAndroid/EncryptoFile.git
  cd EncryptoFile
```
2.Compile the source code using g++: 
```bash
  g++ main.cpp -o EncryptoFile.exe
```
## Release
If you don't want to compile EncryptoFile yourself, you can download the latest release from the EncryptoFile repository. The release version includes the compiled executable file for Windows, Linux, Mac.


## Usage/Examples


The syntax for using EncryptoFile is as follows:
```bash
EncryptoFile <-e | -d> <key filename> <input filename> <output filename>

```

    -e : encrypt the input file
    -d : decrypt the input file
    <key filename> : the name of the file containing the password key
    <input filename> : the name of the input file to be encrypted or decrypted
    <output filename> : the name of the output file to be generated

Here are some examples of how to use EncryptoFile:


### Encryption
To encrypt a file, use the following command:
```bash 
EncryptoFile -e password.txt image.jpg encrp_img.jpg
```

This command will encrypt the image.jpg file using the password key stored in the password.txt file, and save the encrypted output to a new file named encrp_img.jpg.

### Decryption

To decrypt a file, use the following command:

```bash
EncryptoFile -d password.txt image-enc.jpg decrp_img.jpg
```
Make sure you replace password.txt with the name of your key file, image.jpg with the name of your input file, and encrp_img.jpg with the name you want to give your encrypted file or decrp_img.jpg with the name you want to give your decrypted file.




## Contributing

Contributions are always welcome!

If you find any issues with EncryptoFile, or would like to contribute to its development, please feel free to open an issue or submit a pull request on the GitHub repository. We welcome all contributions, big or small!




## License

EncryptoFile is licensed under the MIT License. See the LICENSE file in the repository for more details.

