### Ubuntu编译

```
tar -xzvf .gz

cd unpv13e
./configure
cd lib
sudo cp libunp.a /usr/lib64/
```

```
gcc -o tcpservselect01 tcpservselect01.c -lunp
```