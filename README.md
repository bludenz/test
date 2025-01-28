# Awesome School Exploits Awesome

Pull Requests/Contributions are more than welcome, and we would love all the help we could get from those. When submitting an exploit, make sure to follow the [contribution guidelines](#contribution-guidelines)

- [Filter Bypasses](#Filter-Bypasses)
   - [Ranking](#Ranking)
   - [IStealYourDNS](#IStealYourDNS)
- [Program Blocker Bypassing](#Program-Blocker-Bypassing)
  - [Windows .exe Unblock](#Windows-exe-unblock)
- [Monitoring Software Disabling](#Monitoring-Software-Disabling)
  - [Disabling LanSchool Air](#Disable-LanSchool-Air)
- [Proxy Sources](#Proxy-Sources)
  - [Holy Unblocker](#Holy-Unblocker)
  - [Node Unblocker](#Node-Unblocker)
- [Game Hacks](#Game-Hacks)
  - [Blooket](#Blooket)
  - [Gimkit](#Gimkit)
- [Other](#Other)
  - [Add personal account](#Add-personal-account)

# Filter Bypasses

Tools that allow you to bypass filters, monitoring software, etc
### Ranking

This is a list of methods sorted by easiest to use/most working to hardest to use/least working. In some instances, you may need to combine a few methods to truly unblock everything.

  1. [IStealYourDNS](#IStealYourDNS)

### IStealYourDNS

This exploit involves changing your DNS settings to bypass network-wide filters. This will not work if your school uses extension-based blocking. Also, you'll have to do this for every network you connect to.

  1. Open your Wifi's DNS settings [chromebook howto](https://www.howtogeek.com/204672/how-to-change-the-dns-server-on-a-chromebook/)
  2. Set your primary DNS to `72.5.33.65` and your secondary DNS to `1.1.1.1`

# Program Blocker Bypassing
### Windows .exe Unblock

This only works if PowerShell is not blocked. Shoutout to `Citrik🗿#4600` on Discord.

1. Download the `.exe` file to your Downloads folder
2. Open `Windows PowerShell`
3. Run `cd Downloads` (or whichever folder your `.exe` file is located in)
4.  Run `Copy .\filename C:\Windows\Temp\filename` replacing `filename` with the name of your file.
5. Run `C:\Windows\Temp\filename` replacing `filename` with the name of your file.
6. The program will open.

# Monitoring Software Disabling
### Disable LanSchool Air

This is also possible using the "Disabling Extensions" exploit, however Ingot doesn't support apps, so you'll need to use the Basic GUI instead. Follow these steps each time you login:

  1. Forcibly close LanSchool by right clicking the app on the bottom appbar and pressing "Close"
  2. LanSchool will reopen, however, it won't be connected and will say "Not Connected" in bottom left corner

# Proxy Sources
### [Holy Unblocker](https://github.com/holy-unblocker/website-aio)

Holy Unblocker is a secure web proxy service supporting numerous sites while concentrating on detail with design, mechanics, and features. Bypass web filters regardless of whether it is an extension or network-based.
### [Node Unblocker](https://github.com/nfriedly/node-unblocker)

Web proxy for evading internet censorship, and general-purpose Node.js library for proxying and rewriting remote webpages
# Game Hacks
### [Blooket](https://github.com/therealgliz/blooket-hacks)

List of JavaScript scripts to run as a bookmarklets that'll enhance Blooket gameplay with cheats.
### [GimKit](https://github.com/rxzyx/GimKit-Hacks)

List of JavaScript scripts to run as a bookmarklets that'll enhance GimKit gameplay with cheats.
# Other
### Add personal account

Some people can actually add a personal account to websites like Gmail or YouTube even when their Chrome policies prevent adding personal accounts to the actual computer or browser.

1. First, you'll have to break the connection between your Chromebook and Chrome.
2.  This can be done by going to [https://myaccount.google.com/device-activity](http://web.archive.org/web/20241116225245/https://myaccount.google.com/device-activity) with your school account on another device, then finding your Chromebook on that page and clicking the sign out button, or by going to `chrome://settings/signOut` (if you can, do them both as it will increase your chances of this working)
3.  Then, you have to clear your cookies and site data from google.com, and all other google related domains.
4.  Finally, go to [this link](https://tinyurl.com/addsession) to add an account (you can even do this multiple times)

Note that this will not work for everybody (you may get a "this account is not allowed to sign in within your network" error) and you'll have to repeat the steps every time you sign out and back into your computer.
# Contribution Guidelines

    Exploits that require downgrading your software version are not permitted. We apologize, but these methods are risky, as administrators are notified when a chromebook is unenrolled.
    Make sure to use proper grammar and add your exploit to the navigation also
