A single board computer, As the name suggests, is a computing unit that's fitted into a circuit board, very often we call these circuit boards as printed circuit board (PCB). They are used in a variety of applications like drone, robotics, automotives and edge computing. These boards cater everything that is commonly expected from a regular computer but, in a small and streamlined design.



There are other siblings to single board computers as well, called System on Module (SoM). A SoM has everything a SBC has (processor, storage, power management and DRAM) except the peripherals. The reason is modular connectivity to different carrier boards having different peripherals to serve different applications. The other sibling is a mini PC. A mini PC is a type of SBC which provides you with a desktop PC experience in a small size and with similar computing power.



Now, coming to our main topic of discussion on how to select a SBC for your application. To keep this guide sweet and simple, let us first see the different components that a SBC is usually composed of:



The Processor: A processor is the most important part of your computer; it's the brain that efficiently handles your computing tasks to give you unparalleled results. A processor is selected based on several factors, but the most basic are its performance capabilities, clock frequency, data handling capabilities and available OS support. One more factor that many people select their SBC is based on the number of cores in their processor, howver only cores do not matter but architecture too so make sure to carry out a thorough comparison on that too. Most of these factors are listed in the benchmark scores of your respective processor. You can select your SBC based on the processor it has using these CPU benchmark scores. You can see stats like CPU cores and their architecture, clock speed, maximum allowed memory, storage bandwidth and their respective data/transfer speed, number of peripheral ports.



The RAM: The RAM is an accelerator for your SBC. It stores data from storage device for running applications for short period of time and provide this data to the CPU when needed. It acts as a high-speed "workspace" so the CPU doesn't have to wait for the slow storage, giving the processor a fast read/write speed. Your RAM is the reason your games, browser, and music apps run smoothly. Your usual selection criteria for RAM consist of version, the voltage they work on, their transfer speed, and latency. DDR4, DDR5, LPDDR4/4X, LPDDR5/5X are some good examples.



Storage: The storage is the you non-volatile memory which retains data even after the power supply is cut. SDCard, eMMC, SSD, and UFS are some good examples of storage devices. Typically, you might want larger storage options for your application, so it is generally a better idea to select a SBC which has larger storage inherently and even allows options to expand storage. Most SBCs do so by providing a NVMe port or SATA port to connect with the external hard drives.



Networks: The number of networking options enables you not only to use the internet but also enables you to access your board from a distance without physically being near to it. A single board computer should ideally have Ethernet ( 1000 Mbps/1 Gbps/ 2.5 Gbps or greater), Wi-fi ( 5/6/6E or even better, 7!), Bluetooth (5.0 and greater)



Peripherals: Your application might want you to access input and output devices, or some interfaces for configuration and debugging or a typical sensor interfacing. Some good-to-go interfaces are I2C, UART, USB, SPI, JTAG, and I2S ( some boards also provide an on-board audio jack to access a digital audio interface). If your board provides an external PCIe interface to allow you to attach external NVMe SSDs or perform some expansion, it's a serious green flag!



Power Consumption: Though single-board computers are not very power-hungry devices, their usual consumption is somewhere between 3W and 15W. Some specialized boards like Nvidia Jetson AGX Orin can also consume power up to 100 watts! The importance of this information is to help you select a correct power supply unit for your board, in case your supplier doesn't provide you with one, which is quite a common case. Boards these days usually have USB-C PD for power supply to provide some ease to their consumers although some boards can also come with a dumb USB-C connector which accepts 5V/3A power, you can easily find a suitable adapter for them.



Expandability, Upgradability and available accessories: When you talk about upgradability and available accessories, you would want some external adapters or HATs to use some devices which are not supported in your favourable format but can be accessed natively in your processor. An example of this can be a PCIe or camera adapter. If your board provider designs HATs and other accessories, consider that a green flag!



Software support: Enough about hardware, let's not forget that software is also a necessary component of a single board computer to run your task efficiently, requiring less human touch and longer run. But what if you get stuck somewhere? Let's say the board is not booting or the image is not getting flashed properly. Who would you ask for help? That's where software support plays a vital role. A good hardware company also provides good software support. The more OS images your SBC is supported with, the merrier! Another sign is community. Sometimes when software support is busy somewhere, the community guys can run to your help. They may provide good guidance to you to resolve any issue. The other part is mainline linux support, you would never want to run your applications on ancient vendor kernels. Good hardware companies strive to provide best linux support for your board at any stage.



Once you have compared all these specs stated above, you can create a small checklist of your own and easily come to a conclusion on how to select your next (or first!) SBC for your needs. 
