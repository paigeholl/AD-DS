# 3. Install AD Domain Services and Create a Domain Controller

This section walks you through installing Active Directory Domain Services and configuring your server as a domain controller.

## Install AD Domain Services

1. In **Server Manager**, select **Add roles and features**
<img src=https://ik.imagekit.io/typeai/tr:w-1200,c-at_max/img_kK5uCus4Kqz9pVuhiB.png width=550px >

2. Click **Next** through the wizard until you reach the server selection screen

3. Verify the correct server is selected, then click **Next**
<img src=https://ik.imagekit.io/typeai/tr:w-1200,c-at_max/img_yw0LRgqlLdftkdFlpj.png width=550px>

4. Select **Active Directory Domain Services** checkbox

5. When the pop-up appears, select **Add Features**

6. Continue clicking **Next** through the remaining screens until you reach the **Install** button

7. Click **Install** and wait for the installation to complete

8. Click **Close** when finished

## Promote Server to Domain Controller

> **Note:** Even though AD Domain Services is now installed, you still need to create and configure the domain.

1. Look for the yellow triangle notification next to the flag icon in the top-right corner
2. Click on this notification and select **Promote this server to a domain controller**
3. In the deployment configuration window:
   - Select **Add a new forest**
   - Enter your desired root domain name
   - Click **Next**
4. Set the Directory Services Restore Mode (DSRM) password
5. Click **Next** through the remaining configuration screens
6. Review the configuration and click **Install**
7. The server will automatically restart after the installation completes

## Verification

After the restart, you should see the domain name displayed on the login screen, confirming successful domain controller configuration.

<img src=https://ik.imagekit.io/typeai/tr:w-1200,c-at_max/img_FUgLTMVNQ7y46UWbuT.png width=500px >

