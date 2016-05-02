# Cslcast
A way of mirroring one screen onto another

For example, let's say you have a Raspberry Pi connected to a TV, and you wish to cast your desktop computer's screen to this TV.

On the Raspberry Pi run
```bash
./cast -s
```

And on the desktop computer run
```bash
./cast [Hostname]
```
Where `[Hostname]` is the hostname of the Raspberry Pi

You can also run `./cast -h` for help
