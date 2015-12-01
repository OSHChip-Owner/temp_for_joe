Go to developer.mbed.org and sign up for an account.

Login

We need to choose a platform.  This is because the compiler compiles differently for different devices ("platforms").
For now, we will use the HRM1017 from Switch Sciences.  This is the closest we can get among the registered platforms to our platform, the OSHchip.

Click the link (upper right) for **Compiler**.

Click on the words "no device selected" in the upper right.

In the Select a Platform window, click on **Add Platform**, at the bottom. This brings up the Platforms page.

On the Platforms page, check the box for **Switch Science Inc.**, under Platform Vendor.

This reduces the list of platforms to only three.  Click on the **mbed HRM 1017**. This will bring up a page devoted to that device.

On the right, click on **Add to your mbed Compiler**.  After a pause, you will see a confirmation: Platform 'mbed HRM1017' is now added to your account!

Return to the mbed Compiler page. Click again on the words "**no device selected**".  This time, the HRM1017 will be listed at the bottom.   Click on it, then click on the **Select Platform** at the top.

Now your compiler should show the HRM1017 in place of the "no device selected".

Next we will select a program.  
On the mbed home page, click **Code**.  Many programs are listed.

In the Search box, key in **BLE_HeartRate**, and click Go.
Click on the words BLE_HeartRate indicating the program from Bluetooth Low Energy, which is marked Featured.

On the Bluetooth Low Energy / BLE_HeartRate page, note the explanation and code walkthrough.  Click the button **Import this program**, on the right.

Click to import the program in the resulting popup.  This will take you back to the compiler, and BLE_HeartRate will be listed under your programs in the Program Workspace.

Open the program main.cpp.  Observe that it contains a loop that broadcasts a heart rate from 100 to 175.

Connect (USB) the device that will run the program and send the BLE information.  On Windows, it should occupy a particular device letter (M?).

Power up the device.  Compile the program by clicking **Compile** at the top.  Save the result to the device.

On an Android device that supports BLE, install and run the program **BLE Heart Rate Monitor**.

**Reset** the device under test. 

The Android device will presently begin showing the heart rate from 100 to 175.




