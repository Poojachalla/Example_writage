**Virtualization:**

-   Virtualization is technology that transforms hardware into software.

-   Virtualization allows to run multiple operating systems as virtual machines.

-   Virtual machine is an isolated guest OS installation within a normal host
    OS.

-   With Virtualization it is possible to run multiple operating systems and
    multiple applications on the same Server at the same time, increasing the
    utilization and flexibility of hardware.

-   ![](media/6e88e90cd9c8765893b2bca4f332008d.png)Each copy of an OS is
    installed into a virtual machine.

**Before Virtualization:**

-   Single OS image per machine.

-   Software and hardware tightly coupled.

-   Running multiple applications on same machine often creates conflict.

-   Inflexible and costly infrastructure.

![](media/37fa6f8555709926f01d9266a7d425da.png)**After Virtualization:**

-   Hardware- independence of OS and applications.

-   Virtual Machines can be provisioned to any system.

-   Can manage OS and application as a single unit by encapsulating

    them into virtual machines.

**Types of Operating systems:**

Host OS:

The operating system actually running on the hardware itself.

Guest OS:

The OS running in the simulated environment like VMware, virtual Box.

**Hypervisors:**

-   A hypervisor or virtual machine monitor (VMM) is a piece of computer
    software, firmware or hardware that creates and runs virtual machines.

-   A computer on which a hypervisor is running one or more virtual machines is
    defined as a host machine.

-   Each virtual machine is called a guest machine.

**Types of Hypervisors:**

**1) Type 1 Hypervisor:**

-   Type 1 Hypervisor is installed directly on the bare-metal hardware, it
    doesn’t require an additional OS, it is the OS.

    Ex: Xen, Microsoft Hyper-V.

-   System is thin, the hypervisor has direct access to the hardware.

![](media/7cca438f066e50e0d3d2366f0141d1d4.png)

**2)Type 2 Hypervisor:**

-   Type 2 hypervisor is also known as hosted hypervisor.

-   Type 2 hypervisor runs on a host OS that provides a virtualization service.

-   Type 2 hypervisor is installed on an OS and them it supports in other
    operating systems.

    Ex: VirtualBox and VMware workstation.

![](media/fbb739de199e1abc2cab9bf9304a1262.png)

**Virtualization working:**

-   A virtualization layer is installed. Uses bare-metal or hosted hypervisor
    architecture.

-   A bare-metal Hypervisor does not require OS. Hypervisor is OS.

-   Hosted based virtualization requires OS installed on the computer.

-   Virtualization layer installed as application on OS.

**VMware:**

-   VMware is a virtual machine software.

-   VMware provides cloud computing and platform virtualization software and
    services.

-   It has type 1 hypervisors that run directly on the server hardware without
    requiring an additional underlying OS.

-   Each virtual machine has its own set of virtual hardware.

-   Allows multiple virtual machines, operating systems to run in isolation and
    side-by-side on the physical machine.

**Working:**

-   Allows multiple OS instances to run concurrently with virtual machines on a
    single computer.

-   A virtualization layer is installed, which uses either a hosted or
    hypervisor architecture.

**Advantages:**

-   Reduces physical number of servers.

-   Reduce total cost of ownership.

-   Increases efficiency.

-   Security to each virtual machine.

**Hyper-V:**

-   Hyper-V is just a product from Microsoft that is based upon the generic tern
    “HyperVisor” (Microsoft’s hardware virtualization product.

-   Hyper-V runs each virtual machine in its own isolates space, which means you
    can run more than one virtual machine on the same hardware at the same time.

-   Each VM acts like a complete computer, running an OS programs.

-   You can have multiple operating systems on one physical compuetr and isolate
    the operating systems from each other.

-   When you need computing resources, virtual machines give you more
    flexibility, helps to save time and money, and are a more efficient way to
    use hardware than just running one OS on physical hardware.

**Advantages:**

-   Make development and test more efficient.

-   Establish or expand private cloud environment.

-   Use hardware more efficiently.

-   Establish or expand a virtual desktop infrastructure.

**VirtualBox:**

-   VirtualBox is a cross-platform virtualization application.

-   It installs on your existing Intel 0r AMD-based computers.

-   It has type 2 hypervisors that runs on a host OS that provides a
    virtualization service.

-   Developed by oracle organization.

-   Supports large number of guests operating systems.

-   Free ware, 3D virtualization supports, Multi Screen resolution support.

**Advantages:**

-   Running multiple operating systems simultaneously.

-   Easier software installations.

-   Testing and disaster recovery.

-   Infrastructure consolidation.

-   No hardware virtualization required.

-   Portability.
