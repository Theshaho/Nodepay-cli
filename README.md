# Nodepay-cli

you can use my referral link to register on Nodepay: [Link](https://app.nodepay.ai/register?ref=QQ51zuerWUH82iS)

1. Update:

    ```bash
    sudo apt update && sudo apt upgrade -y
    ```

2. curlInstall the package:

    ```bash
    sudo apt install curl -y
    ```

3. Download the script `nodepay_setup.sh`:

    ```bash
    curl -O https://gist.githubusercontent.com/Bo0tstrap/479627be43db165b4016291ff76ea2f1/raw/eed5ade7f5aee685db1fd50ddbe60c324e209cf8/nodepay_setup.sh
    ```

4. Give execution permission to the downloaded script:

    ```bash
    chmod +x nodepay_setup.sh
    ```

5. Start a new `screen`:

    ```bash
    screen -S nodepay
    ```

6. Run the script:

    ```bash
    ./nodepay_setup.sh
    ```

In the last command, it will ask you for np token, go to the Nodepay dashboard, press F12 and get it from the place I marked in red (unfortunately, the np token limit is 14 days, so you need to renew it every 14 days).
    ![np](https://github.com/user-attachments/assets/731dd642-46f2-41f4-9de5-60df7e34a1bf)
    
7. Grant the necessary permission:

    ```bash
    chmod +X Nodepay-cli/nodepay.py
    ```

8. Run the script:

    ```bash
    python3 Nodepay-cli/nodepay.py
    ```


Detach from screen by Ctl + A + D

## if you get error forLoguru or something like: no module named loguru

use this command to install loguru

```bash
apt install python3-loguru
```
Then run command on step 8

```bash
python3 Nodepay-cli/nodepay.py
```
    
  [source](https://github.com/ruesandora/Rivalz/blob/main/Nodepay-cli.md)
