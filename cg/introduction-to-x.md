# Introduction to X

#### What is X anyway?

The grandpa of the Unix-like operation systems graphic system often reffered to X, is really one of the oldest windowing system.

#### Server/Client

The Linux graphic works in the server/client model, a server is a program that coordinates input and output of its client. And it happens over the server display protocol. There are various display server protocols available in Linux. X11 and Wayland are two of them.

Display server is an important key component of an operation system. whenever you click somewhere on your screen, the screen is the client and who does the job under the hood is the server, (opening an image for example) the client click on it and the server command the hardware to open it.

#### X.org

The X.Org project provides an open source implementation of the X Window System. It is basically an open-source display server that interacts with client applications via the X11 protocol to draw things on a display and to send input events like mouse movements, clicks, and keystrokes.

#### X11

Is a display protocol. It defines how messages are exchanged between with a client and a server.

#### Wayland

I won't go into real details about Wayland, just know that wayland is a new generation, a modern protocol made to replace X-window, but though it's still too young to do its job and would probably take a bit more time to do it.

#### Opengl

Is an API to render 2d and 3d vector graphics. The API is typically used to interact with a graphics processing unit (GPU), to achieve hardware-accelerated rendering.

