![Screenshot_2024-09-19_17_45_09](https://github.com/user-attachments/assets/873ef98a-48e0-445b-b5dc-eb5959ad5b34)

<div align="center">

# $${\color{orange}Burpsuite-Professional-v2026-latest}$$
</div>

<p align="center"> Burp Suite Professional is the web security tester's toolkit of choice. Use it to automate repetitive testing tasks - then dig deeper with its expert-designed manual and semi-automated security testing tools. Burp Suite Professional can help you to test for OWASP Top 10 vulnerabilities - as well as the very latest hacking techniques. Advanced manual and automated features empower users to find lurking vulnerabilities more quickly. Burp Suite is designed and used by the industry's best.</p>

<h3 align="center">

[Overview](https://portswigger.net/burp/pro)
</h3>
 
<br>
<br>

#  $${\color{magenta}BlackArch-Installation}$$
```sh
sudo pacman -Sy --needed wget && wget -qO- https://raw.githubusercontent.com/Rickidevs/Burpsuite-Professional-BlackArch/main/install.sh | sudo bash
```
<details><summary></summary>

## Update
> optional
```
cd && sudo rm -rf Burpsuite-Professional && wget -qO- https://raw.githubusercontent.com/Rickidevs/Burpsuite-Professional-BlackArch/main/update.sh | sudo bash
```
 
## Java Version
> select the default openjdk runtime
```
sudo update-alternatives --config java
```               
</details>

## Setup Licenses

<div align="center">
 
https://github.com/xiv3r/Burpsuite-Professional/assets/117867334/c25831a4-68a2-44ee-b6dd-5ff18165f340
</div>
 
Note: Copy the license from loader to the burpsuite > manual activation > copy burpsuite request key to loader request >  copy response key to the burpsuite.

<br>

## Shortcut Launcher - (xfce)
right click the desktop -> create a launcher name it Burpsuite Professional, add command `burpsuitepro` and select burpsuite community icon.

<div align="center">
 <img width="500" height="500" src="https://github.com/xiv3r/Burpsuite-Professional/blob/main/Launcher.jpg">
</div>

<br>
<br>

---------


## Step 3: Install the `burp` Shortcut
Make the `burp` script executable and install it globally.

```bash
chmod +x burp
sudo cp burp /usr/local/bin/burp
```

**Explanation**:
- The `installmacos.sh` script creates a `burp` script to run Burp Suite with required Java options.
- Uses `$(pwd)` to reference JAR files in the current directory.
- Makes the script executable and copies it to `/usr/local/bin` for global access.


## Notes
- **Running the Shortcut**: Run `burp` from the `Burpsuite-Professional` directory containing `loader.jar` and `burpsuite_pro_v2025.5.6.jar`. For global use, replace `$(pwd)` with absolute paths.

## Contributors 

<a href="https://github.com/xiv3r/Burpsuite-Professional/graphs/contributors">
  <img src="https://contrib.rocks/image?&columns=25&max=10000&&repo=xiv3r/Burpsuite-Professional" alt="contributors"/>
</a>


<details><summary>

## Credits
</summary>

* Loader.jar 👉 [h3110w0r1d-y](https://github.com/h3110w0r1d-y/BurpLoaderKeygen)
* Script 👉 [cyb3rzest](https://github.com/cyb3rzest/Burp-Suite-Pro)

</details>
