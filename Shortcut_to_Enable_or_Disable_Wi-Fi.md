# Shortcut to Enable or Disable Wi-Fi

---
### To find the name of Wi-Fi Connection
+ _**Step 1 :**_ Go to **`Control Panel`** from **Start Menu** or Press `Windows + R`, then type _**'control panel'**_ and press **Enter**.
+ _**Step 2 :**_ Then go to **`Network and Sharing Center`**.
+ _**Step 3 :**_ On the left menu bar find and click **`Change adapter settings`**.
+ _**Step 4 :**_ Now, find the name of your **Wi-Fi Connection**. In this case it is _**"Wi-Fi"**_.

    ![Wi-Fi Connection Image](https://user-images.githubusercontent.com/66966012/158032195-4edf24b9-5189-48e9-98ac-24889b3d737c.png)

---
### Create Shortcut
+ _**Step 1 :**_ Go to Desktop and then **_Right-click > New > Shortcut_**.
+ _**Step 2 :**_ In the field *__Type the loction of the item:__* paste the following line -
    ```
    netsh interface set interface name="Wi-Fi" admin = disabled
    ```
    and replace the *Wi-Fi* word with your *Wi-Fi Connection name*.
+ _**Step 3 :**_ Then click `Next`.
+ _**Step 4 :**_ Give the shortcut a name like *'Disable Wi-Fi'* or any other name you like.
+ _**Step 5 :**_ Finally click `Finish`.
+ _**Step 6 :**_ Repeat these steps to create another shortcut to enable Wi-Fi. Just replace the code given in _**Step 2**_ with this one -
    ```
    netsh interface set interface name="Wi-Fi" admin = enabled
    ```

---
### Configure Properties
+ _**Step 1 :**_ Right click on one of the two shortcuts(created above).
+ _**Step 2 :**_ Click on `Properties`.
+ _**Step 3 :**_ In the *Shortcut* tab, click on `Advanced`.
+ _**Step 4 :**_ Check the `Run as Administrator` box.
+ _**Step 5 :**_ Then click on `Ok`.
+ _**Step 6 :**_ If you want to give it a keyboard shortcut, then click on *Shortcut Key* and press the keyboard shortcut button(s).
+ _**Step 7 :**_ Finally click `Apply` and then `Ok`.
+ _**Step 8 :**_ Repeat these steps for other shortcut also.
