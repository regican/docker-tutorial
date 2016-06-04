Node.js Docker Tutorial
===============

So you have Node apps, and you want to use them with Docker. This repository is designed for helping you follow along with our [blog post](https://nodesource.com/blog/dockerizing-your-nodejs-applications/). It will take you from 0 to 60 with Docker and Node.js!


## Installation Guide (Mac OS X)

1. Install [VirtualBox](https://www.virtualbox.org/)
2. Install [Docker Toolbox](https://docs.docker.com/engine/installation/mac/)
3. Do the following in your terminal
  1. Create a new Docker VirtualBox
    * docker-machine create --driver "virtualbox" dockerMe
  2. Power on thew new Docker VitrualBox
    * docker-machine start dockerMe
  3. Configure your Docker env
    * eval "$(docker-machine env dockerMe)"
  4. Now lets add it to your bash profile at (~/.bash_profile)
    * eval "$(docker-machine env dockerMe)"


## Docker Tutorials

Basics & Setup [https://www.youtube.com/watch?v=pGYAg7TMmp0&list=PLoYCgNOIyGAAzevEST2qm2Xbe3aeLFvLc](https://www.youtube.com/watch?v=pGYAg7TMmp0&list=PLoYCgNOIyGAAzevEST2qm2Xbe3aeLFvLc)

## Authors and Contributors

<table><tbody>
<tr><th align="left">William Blankenship</th><td><a href="https://github.com/hughsk">GitHub/retrohacker</a></td><td><a href="http://twitter.com/retrohack3r">Twitter/@retrohack3r</a></td></tr>
</tbody></table>

## License & Copyright

This material is Copyright (c) 2015 NodeSource and licensed under the MIT license. All rights not explicitly granted in the MIT license are reserved. See the included [LICENSE.md](./LICENSE.md) file for more details.
