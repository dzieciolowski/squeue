# Simple queue implementation based on Screen command

## Usage

Run command using queue:
~~~
squeue cp /mnt/dir1/file.dat /mnt/dir2
squeue --name myqueue cp /mnt/dir1/file.dat /mnt/dir2
~~~

Show queue (attach to screen session):
~~~
squeue -s
squeue -n myqueue -s
~~~

Display version and usage:
~~~
squeue -v
squeue -u
squeue -h
~~~

## How to install

### Installing on Arch Linux

`squeue` package is available on Arch Linux through AUR:

~~~~
yaourt -S squeue
~~~~

### Other installation

Install `squeue` in your current working directory:

~~~~
curl -s https://raw.githubusercontent.com/dzieciolowski/squeue/master/squeue
~~~~

## License

Licensed under the [MIT License](LICENSE.txt).
