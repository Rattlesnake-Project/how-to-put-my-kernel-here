# HOW TO PUT MY KERNEL HERE?

## What is needed in the kernel for me to put it here?

* The kernel needs to be cleaned of additional extra features
* You are allowed to use commits for compilers such as clang, gcc, linaro among others
* You need to be aware of what you do in your kernel, we can not stop our time to teach anything
* You are allowed to make upstream of your linux version (I recommend you use [android-linux-stable](https://github.com/android-linux-stable))
* Follow the simple bringup that I'll leave below
* We do not allow commits without keeping the real developer's authorship

## Simple BringUp

* Change your `CONFIG_LOCALVERSIO` from defconfig file (-x.x is version kernel, initial use 0.1)
  ```bash
  CONFIG_LOCALVERSION="•Rattlesnake-x.x"
  ```

## What is the purpose of this team?

We are from the [ViperOS](https://github.com/Viper-Project) team and our intention was just a kernel of the maintainers team, so we decided that it would be legal to open the opportunity to more people who would like to participate as well.
Our goal is to just have a clean kernel with no unnecessary extra features and keep it up to date with its base and linux.

## How to then put my kernel here?

* Enter [this link](https://github.com/Rattlesnake-Project/how-to-put-my-kernel-here/blob/master/document.md) and just register the following questions (make a pull request).

  ```bash
  Username github:
  Link of your kernel from github:
  ```
