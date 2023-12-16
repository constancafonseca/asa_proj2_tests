## asa_proj2_tests
Testes para o segundo projeto de ASA

## Dependencies

- Makefile - You probably already have it

### On MacOS
If you want to run this on MacOS you will need to install GNU's diff command for this to work properly. I recommend using a package manager like brew:
```bash
brew install diffutils
```

## How to run
Clone the repo
```bash
git clone https://github.com/constancafonseca/asa_proj2_tests.git
```
Provide the file [config.txt](config.txt) with the path to your source code.

Followed by
```bash
make
```
You can also run a specific test or a group of tests. But you should run make clean first. E.g:
```bash
make clean tests/1.in tests/1.in
```
You can then check out the respective output, on the same folder with the extension `.outhyp` and the diff `.diff`.
