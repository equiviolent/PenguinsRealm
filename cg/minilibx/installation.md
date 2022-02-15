# Installation

Mlx is a library and it is written in C therefore it has to somehow be compiled.

Because of we don't have right permission to install mlx globally we just going to have it locally included within our project. However if you are on your computer and wish to install it, if you are on Linux, checkout [the official repository](https://github.com/42Paris/minilibx-linux), otherwise if you're on MacOS, honestly, I don't how to do it x).

{% hint style="info" %}
Tip:

If you are on ArchLinux, minilibx-git has been added into their [developer repository](https://aur.archlinux.org/packages/minilibx-git).
{% endhint %}

First, download [mlx](https://projects.intra.42.fr/uploads/document/document/5828/minilibx\_opengl.tgz) and put it into your project directory. I call it mlx\_macos however feel free to name it as you wish. Actually, we are going to create a project with a valid Makefile and by the end of this section, you would have a project ready to go, with the possibility of compiling it on Linux as well as MacOS.

Our project should look something like that:

```
+------------+
|project name|
+------+-----+
       |
       +--> mlx_macos
       |
       +--> Makefile
       |
       +--> main.c
```

