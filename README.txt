Quanser HIL SDK 2021 (4.1.3390)
-----------------------------------

The Quanser HIL SDK for the macOS operating system running on a Macintosh platform. The Quanser Hardware-in-the-loop (HIL) SDK, also known as the Quanser HIL SDK, provides device drivers and a set of C functions (API) for accessing Quanser hardware (devices and data acquisition cards).  

The Quanser HIL SDK for the macOS operating system running on Macintosh hardware provides access to the following devices:
- Quanser QUBE Servo 2 - USB 
- Quanser Q2-USB (normal mode only)
- Quanser Q8-USB (normal mode only)
- Quanser QArm

To install the Quanser HIL SDK on macOS:
- Copy all the files in the desired target directory onto the target.
- On the target system, uninstall previous versions of the Quanser HIL SDK on the target by running the following command:
    sudo uninstall_hil_sdk
- On the target system, go to the directory where you copied the files and run the following commands:
    chmod a+x setup uninstall_hil_sdk
    sudo ./setup
- Type "yes" (without quotes) in reponse to the license agreement prompt if you agree with the license.

The Quanser HIL SDK examples on macOS can be found under /opt/quanser/hil_sdk/examples

It is recommended to make a copy of the /opt/quanser/hil_sdk/examples folder to a location where the user has Write permission (e.g., ~/Documents) before editing the source files and compiling executables.

The Quanser HIL SDK documentation is available online: 
https://docs.quanser.com/hil_sdk/documentation

To uninstall the Quanser HIL SDK on macOS, run the following command:
    sudo uninstall_hil_sdk


THIS IS BETA SOFTWARE. IF YOU ARE USING THIS SOFTWARE, WE WOULD APPRECIATE ANY FEEDBACK.


The full version of this product is 4.1.3390. The build date was 2021/4/22.
