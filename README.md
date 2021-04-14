# Template projects for Network Lab

In the readme of figures can see description and pre-configured data.

## How to use

You can download last `.gns3p` [release](https://github.com/UT-Network-Lab/gns3-figures/releases/latest) or **clone** this repository in your system and use at one of this instruction:

1) generate `.gns3p` by running `./build-gns3p.sh` in bash (**warning**: build only on linux for correct file permission)
2) open `Fig-*` with `GNS3` application
3) copy figures folder to your GNS3 project directory

## TODO

* [ ] add and set delay for delayed figures
* [ ] add default gw for pre-configured figures (set gw in `/etc/network/interfaces`)
* [X] change figure name `.` to `_`
* [ ] align topology item with grid lines
* [ ] figure 8.7, 5.5
* [X] figure gui(1)/server(2)/router(1) with ip and route
* [X] change type of h2, h7 to gui for figure 7.14
