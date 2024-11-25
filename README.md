# Keybox checker on python!
This code is purely made for education and research purposes. (And also because I have too much free time.)
# First time setup
First step is to have python already installed in your computer.\
Second step is to clone the repository into your directory.
```bash
git clone https://github.com/SenyxLois/KeyboxCheckerPython
```
Third step is to install all required dependencies :-

> [!TIP]
> Python virtual environment is highly recommended!
```bash
pip install -r requirements.txt

```
> [!WARNING]
> For termux user, I don't know what with the cryptography and pip on there so please install all the packages using this command :
```bash
pkg install openssl
pkg install rust
export RUSTFLAGS=" -C lto=no" && export CARGO_BUILD_TARGET="$(rustc -vV | sed -n 's|host: ||p')" && pip install cryptography aiohttp colorama
```
That's it! I mean its a python file.
# Usage
*Checking a single keybox*
```bash
python main.py path/to/keybox.xml
```
*Bulk checking a folder full of keybox*
```bash
python main.py path/to/keyboxs
```

#### Example picture
*Example of a single keybox*
![aosp-example](https://github.com/user-attachments/assets/fad99171-677b-458a-8eb7-299c05519827)
*Example of bulk checking keyboxes*
![cuh](https://github.com/user-attachments/assets/88ae7f19-6e73-478c-8385-2b5492cc7178)

# Special thanks to!
- [KimmyXYC](https://github.com/KimmyXYC/KeyboxChecker) | For his Keybox checker logic
- [Me](https://github.com/senyxlois) | For her stupidly alot of free time
- Hollowed Citra | Providing keybox to fix an error that I didn't even know exist.

# Todo List
- [ ] Re-Code every single shit I've done since it look like a mess
- [ ] Better bulk system
- [ ] idk self-sign certificate gen?

