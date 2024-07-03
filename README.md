# edgeEngine-SE-NXP

edgeEngine Linux-ARM aarch64 for NXP S32G Vehicle Integration Platform (GoldVIP) S32G2.

NXP GoldVIP deliverable includes Xen hypervisor and by default, GoldVIP starts a privileged Linux virtual machine named 
(Dom0 or Domain-0). This version of edgeEngine-SE-NXP runs on Domain-0 VM Linux

## Before you start  

edgeEngine-SE-NXP needs a special license(mimikEdge.lic) to run the edgeEngine binary.
To get mimikEdge.lic, please get in touch with mimik at [mimik-support](https://developer.mimik.com/support/)
or email support.sdk@mimik.com

 [explore the developer resources & documentation](https://developer.mimik.com)
 
 [sign up and create a mimik developer console account](https://developer.mimik.com/console/create_account)


## Installation Guide
1. Download latest release for edgeEngine-SE-NXP  [HERE](https://github.com/edgeEngine/edgeEngine-SE-NXP)
2. Create a new directory
3. Move the package to the newly created directory 
4. Open a terminal and navigate to the newly created directory that now has the downloaded .tar file
5. *Untar package (ex:)

For edgeEngine-SE-NXP
```
tar xvf edgeEngine-SE-NXP-v3.10.30.tar
```


6. Run the start script to start edgeEngine
```
./start.sh
```
7. Please visit [Developer Console](https://developer.mimik.com/console/create_account) to create an account and get started with your projects


## Notes:
* A directory may be made after untaring. Navigate into that directory to find  the `start.sh` script.
- Do not close the terminal window where edgeEngine is running. Closing this window will terminate the edgeEngine process.
- To stop edgeEngine, simply close or use the keyboard shortcut CTRL + C in the terminal window where edgeEngine is running.


