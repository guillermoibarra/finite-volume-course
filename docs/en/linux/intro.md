# Introduction to Linux

This course, titled **"Fundamentals of Finite Volume Methods in CFD: Theory, Practice, and Implementation in Python,"** focuses on the tools used in computational fluid dynamics (CFD). If we were to summarize the essence of this course in one line, it might be something like **"Introduction to Tools for the Multi-Physics Analysis of Engineering Systems."** Here, we use the term "tool" broadly—not just as a physical device but as anything that aids in accomplishing a goal, solving a problem, or facilitating a process. This broader interpretation includes not only physical devices but also software, methodologies, techniques, and algorithms.

For example, the finite volume method—a technique we will explore in this course—is a tool for solving differential equations, which in turn helps us represent physical processes. In this sense, it’s a tool used within another tool. As we progress through this course, you’ll encounter a variety of such tools, each with its strengths and limitations. Understanding these aspects is crucial to effectively using them in engineering.

Now, let’s turn our attention to Linux. Often described as a family of open-source, Unix-like operating systems, Linux is a quintessential software tool. Just as physical tools enable us to manipulate our environment, Linux allows us to control and interact with our computational environment. Like other operating systems such as Windows or macOS, Linux manages a computer’s memory and processor, facilitating communication between hardware and software through its core component, the kernel.

In the context of this course, Linux is more than just an operating system; it is the foundation upon which we will build and run the various tools necessary for multi-physics analysis. Its open-source nature, flexibility, and extensive support for scientific computing make it an ideal environment for the complex simulations and analyses we will undertake. As you delve into this course, you will see how Linux, along with other tools, plays a critical role in enabling the rigorous analysis and innovative problem-solving that define modern engineering.

## Distros and the Many Flavors of Linux

If you’re ready to explore Linux, your first step will be choosing a Linux distribution, or distro. Linux itself is essentially the kernel, the core part of the operating system, while a distro combines the kernel with supporting libraries and tools to create a complete operating system. As of February 2024, there are over 400 active Linux distros, according to Tecmint. Rather than suggesting a specific distro, it’s more useful to understand the key factors that differentiate them: package management, graphical interface, and release cycle.

### Repository and Package Management

The backbone of any Linux distribution is its repository and package management system, which determines how software is installed, updated, and managed. Different distros use different package managers and repositories, influencing software availability, ease of installation, and how up-to-date your system is.

#### Debian-based Systems

Debian-based distros, such as Ubuntu, Linux Mint, and Kali Linux, use the APT (Advanced Package Tool) package manager. APT is known for its large repository of packages and stability, making it suitable for both desktop and server environments. This balance between the latest software and stability makes it a great choice for beginners and those looking to run a server.

#### Arch-based Systems

Distros like EndeavourOS and Manjaro use the Pacman Package Manager. Arch-based systems, particularly when installed from scratch, allow users to control every detail of the installation process and package selection. While distros like EndeavourOS and Manjaro provide an easier installation experience, they still offer the benefits of Arch’s rolling-release model and user control. These systems are recommended for users who desire full control over their system, though they come with a steep learning curve.

#### RPM-based Systems

RPM-based systems, such as Fedora and Red Hat Enterprise Linux (RHEL), are geared more towards enterprise environments, prioritizing stability and security. These systems are ideal for users who prioritize stability, particularly in professional or production settings.

### Graphical Interface

The desktop environment (DE) defines the visual and interactive experience of using your Linux system. It dictates the look, feel, and performance, as well as how much customization is possible. Choosing the right DE can significantly enhance your user experience.

#### GNOME

GNOME offers a polished, cohesive interface with a focus on simplicity and efficiency. However, it can be resource-intensive, making it less ideal for older hardware. It’s suitable for users who prefer a modern, feature-rich environment with less emphasis on customization.

#### XFCE

XFCE is designed to be resource-efficient while still providing a full desktop experience. It’s an excellent choice for users with older hardware or those who prefer a minimalistic approach. XFCE is ideal for those who prioritize speed and simplicity, especially on older hardware.

#### KDE Plasma

KDE Plasma is known for its flexibility and aesthetic appeal. It offers a wide range of customization options, allowing users to tailor the interface to their preferences without sacrificing performance. It’s perfect for users who value customization and visual appeal.

#### Tiling Window Managers (e.g., i3, Sway, Awesome)

Tiling window managers (TWMs) provide a minimalist and highly efficient workspace by organizing windows in a grid-like pattern without overlapping. They are designed for users who prefer keyboard-driven navigation and a distraction-free environment. TWMs are incredibly lightweight and highly customizable, though they often come with a steeper learning curve. They’re ideal for users who prioritize efficiency, minimalism, and keyboard-centric workflows.

### Release Cycle

The release cycle of a distribution defines how often updates are delivered and how major system changes are handled. This can impact the system’s stability and the freshness of its software.

#### Rolling Release

Rolling release distros provide the latest software updates as soon as they are available, eliminating the need for major system upgrades. While this ensures you always have the newest features, it can sometimes lead to instability. Rolling release distros are ideal for users who prefer having the latest software and are comfortable managing potential risks associated with frequent updates.

#### Point Release

Point release distros follow a fixed release schedule, offering major updates periodically. These systems often come with long-term support (LTS) options, ensuring stability over an extended period. Point release distros are beneficial for users who prioritize system stability and predictability, particularly in professional or production environments.


