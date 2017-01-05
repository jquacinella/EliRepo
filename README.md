# As of Jan 4th

- **HW** Continue wokring on getting Cisco IOS images into GNS3
- **HW** Follow https://www.csd.uoc.gr/%7Ehy435/material/GNS3-0.5-tutorial.pdf, starting with page 17
- **HW** Attempt this python project: http://www.cse.msu.edu/~cse231/PracticeOfComputingUsingPython/03_Strings/CaesarCypher/project04.pdf
- **HW** 

- **Project** get social networking tool on raspberry pi, get it to arp spoof using mitmf a victim on same network


# As of Wed Dec 21st

- **HW** Attempt this python project: http://www.cse.msu.edu/~cse231/PracticeOfComputingUsingPython/03_Strings/CaesarCypher/project04.pdf
- GNS3
  - https://www.csd.uoc.gr/~hy435/material/GNS3-0.5-tutorial.pdf
  - http://commonerrors.blogspot.com/2015/08/gns3-tutorials-for-beginners-how-to.html
  - http://gns3-tutorials.blogspot.com/2015/01/router-basic-command-and-static-route.html
- SS7
  - http://www.dslreports.com/forum/r30710693-Getting-access-to-SS7
  - http://resources.infosecinstitute.com/ss7-protocol-how-hackers-might-find-you/#gref (interesting)
  - http://axicom.com/en/blog/The-One-Weird-Network-That-Hackers-Use-to-Get-Your-Data
  - https://www.blackhat.com/presentations/bh-europe-07/Langlois/Presentation/bh-eu-07-langlois-ppt-apr19.pdf (great overview of SS7, maybe try to find the video associated with this presentation)
  - https://news.ycombinator.com/item?id=8804916
  - https://blog.c22.cc/2009/12/28/26c3-sccp-hacking-attacking-ss7-sigtran-applications/
  - http://www.hackitoergosum.org/2010/HES2010-planglois-Attacking-SS7.pdf
  - http://arstechnica.com/security/2016/04/how-hackers-eavesdropped-on-a-us-congressman-using-only-his-phone-number/
  - https://insinuator.net/2016/02/ss7maper-a-ss7-pen-testing-toolkit/
  - https://www.quora.com/How-can-one-get-access-to-an-SS7-network
  
# As of Wed Dec 7th

We got the virtual machines to communicate by adding two adapters, and setting the first one to NAT and the other one to internal. The internal network adapters need manual ip addresses and the other ones need DHCP to auto configure their ip address.

Used http://www.khromozome.com/how-to-hack-windows-10-using-kali-linux/ to setup an attack

- **HW** Attempt this python project: http://www.cse.msu.edu/~cse231/PracticeOfComputingUsingPython/03_Strings/CaesarCypher/project04.pdf
- **HW** Continue meterpreter attack from kali to windows
- **HW** Lookup projects with RaspPi to see if youre interested below
- **HW** Watch the SS7 video: http://www.technob.net/2016/12/hack-any-social-media-account-in-less.html?m=1
- **HW** CC Attack: https://fossbytes.com/distributed-guessing-attack-credit-card-six-seconds/
- **HW** How to find exploit code: https://medium.com/@securitystreak/finding-the-right-exploit-code-968ad454824f#.lh3b2rodq

# As of Sun Nov 27th

- **TODO**: Lookup projects with RaspPi to see if youre interested
  - http://www.itpro.co.uk/mobile/21862/raspberry-pi-top-22-projects-to-try-yourself
    - "Stratux is a project devised to tell you information about the various aircraft in the sky around you, and it’s wonderfully simply to build"
    - "Using the RetroPie emulation software, he was able to make a retro games console that's entirely contained in the controller"
    - "This project turns the Raspberry Pi into a router to send all your network traffic through Tor, rather than just browser sessions"
    - "Using a spare PC monitor and his Raspberry Pi, Piney set up the OS to always open Google Calendar over his home Wi-Fi with some clever scripting"
    - "Turns out the Raspberry Pi can do more that just computing. It can send out signals over FM airwaves. It’s perfect for users who’ve dreamt about starting their own pirate radio station"
  - http://www.pcworld.com/article/2895874/10-insanely-innovative-incredibly-cool-raspberry-pi-projects.html#slide5
    - "This isn’t something you’d want to stick in your pocket, but it’s amazing to think you can take a Raspberry Pi and combine it with a GSM module, battery, and TFT touch screen to create a homegrown cell phone"
  - https://github.com/pwnieexpress/raspberry_pwn
    - Penetration testing with RaspPi
  - http://makezine.com/2016/12/08/5-raspberry-pi-projects-wil-wheaton/

- **TODAY**: Went over git, created new repo and added as collaborator
- **TODAY**: Go over chap 5 on linux booting
- **TODAY**: spend time creating a lab using virtualbox; got Kali and Win10


- **HW**: Configure kali box
- **HW**: Configure windows box
- **HW**: Make them pingable to each other
- **HW** Attempt this python project: http://www.cse.msu.edu/~cse231/PracticeOfComputingUsingPython/03_Strings/CaesarCypher/project04.pdf

## Links
  - http://askubuntu.com/questions/760671/could-not-load-vboxdrv-after-upgrade-to-ubuntu-16-04-and-i-want-to-keep-secur

## Commands
  - dmesg
  - cat /proc/cmdline
  - git clone url
  - git status
  - git pull origin master
