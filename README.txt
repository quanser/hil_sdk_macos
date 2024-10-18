Quanser HIL SDK 2024 SP1 (24.1.4682)
-----------------------------------

The Quanser HIL SDK for the MacOS operating system running on Mac hardware. The Quanser Hardware-in-the-loop (HIL) SDK, also known as the Quanser HIL SDK, provides device drivers and a set of C functions (API) for accessing Quanser hardware (devices and data acquisition cards).  

The Quanser HIL SDK for the MacOS operating system running on Mac hardware provides access to the following devices:
- Quanser Qube-Servo 3
- Quanser QUBE Servo 2 - USB
- Quanser Q2-USB (normal mode only)
- Quanser Q8-USB (normal mode only)
- Quanser AERO
- Quanser Aero 2
- Quanser QArm

To install the Quanser HIL SDK on macOS:
- Copy all the files in the desired target directory onto the target.
- On the target system, uninstall previous versions of the Quanser HIL SDK on the target by running the following command:
    sudo uninstall_hil_sdk
- On the target system, go to the directory where you copied the files and run the following commands:
    chmod a+x setup_hil_sdk uninstall_hil_sdk
    sudo ./setup_hil_sdk
- Type "yes" (without quotes) in reponse to the license agreement prompt if you agree with the license.

The Quanser HIL SDK examples on macOS can be found under /opt/quanser/hil_sdk/examples

It is recommended to make a copy of the /opt/quanser/hil_sdk/examples folder to a location where the user has Write permission (e.g., ~/Documents) before editing the source files and compiling executables.

The Quanser HIL SDK documentation is available online: 
https://docs.quanser.com/hil_sdk/documentation

To uninstall the Quanser HIL SDK on macOS, run the following command:
    sudo uninstall_hil_sdk


THIS IS BETA SOFTWARE. IF YOU ARE USING THIS SOFTWARE, WE WOULD APPRECIATE ANY FEEDBACK.


The full version of this product is 24.1.4682. The build date was 2024/10/17.
