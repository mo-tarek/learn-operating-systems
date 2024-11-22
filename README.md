 1. **Understand the basics of operating systems**
    - OS concepts
      - Understand the key concepts of OS  
        - Process
        - Memory management
        - Input/Output (I/O)
        - Scheduling
        - Security 
    - Computer architecture
      - Learn how computer works at the hardware level
        - CPU
        - Memory: RAM
        - Storage: HD
        - Device interfaces (interrupts, I/O ports)
    - Programming language
      - Main: C programming language + Assembly 
      - For certain task: C++ 
2. **Setup a development environment**
  - Compiler and linker
  - Emulator
    - QEMU or Bochs
  - Assembler
  - Make utility
  - Version control
3. **Create a bootloader**
  - Basic bootloader
  - GRUB
4. **Develop the kernel**
  - Key concepts of the kernel
    - Bootstrapping
    - Memory management
    - Process management
    - Interrupt handling
    - System calls
5. **Implement file system**
6. **Implement device drivers**
  - Implement device drivers for various HW devices, including:
    - Keyboard: capture key presses 
    - Screen/Display: draw text and graphics to the screen (usually via VGA or framebuffer)
    - Mouse: handle input from a mouse 
    - Storage: interface with hard drives or SSDs
  - Device drivers typically involve writing low-level code to communicate with the HW through I/O ports or memory-mapped registers.
7. **Creat a shell and a user interface**
  - Command-line shell
  - Graphical user interface (GUI)
8. **Implement process and memory management**
  - Process control
  - Memory Management
9. **Networking (Opitional)**
10. **Security and protection**
    - User permissions
    - System calls security
    - Sandboxing 
11. **Testing and debugging**
  - Unit testing: develop Unit testing for individual components 
  - System testing: run integration testing on the full OS. test its stability, performance and its compatibility with the HW
  - Debugging tools: use debugging tools like gdb to step through your code and diagnose issues 
12. **Documenting the OS**
- As you develop, maintain detailed documentation of your design decisions, codebase, and how to use the OS.

### Tools and resources
  - **Books**
    - Operating systems design and implementation, Andrew Tanenbaum
    - The linux programming interface, Michael Kerrisk
  - **Online resource**
    - OSDev.org  (an extensive community and resource for OS development)
    - Tutorials on building a simple kernel (e.g., Creating an OS:  simple kernel)
### Example of a simple OS flow
  - Bootloader loads the kernel (from disk into memory)
  - Kernel sets up the hardware (intializes the processor, memory, interrupt handling)
  - Kernel runs process scheduler (to manage processes)
  - Process execute (user programs or background services)
  - User interacts with the OS via a shell or GUI
