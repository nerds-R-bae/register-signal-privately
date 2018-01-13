# register-signal-privately


COOKBOOK GUIDE:

Setting up Signal without using your number
(and getting more people to use Signal).

#For threats of domestic agency interference:
Prep:

Use Linux ...or Mac.
Change your MAC address. Prevent ipv6 and webRTC in settings.
Use a VPN that does not leak DNS. Test at dnsleaktest.com, use the full test. Set the VPN to obfuscate. This means the connection to the VPN will not have a header telling your ISP and any state snoopers you are connecting to the ip address of a vpn, and trying to be sneaky.

Method:

Download Bluestacks, and set it aside without setting it up. Bluestacks is a sandbox android emulator.
Download via the browser method a copy of TextPlus.apk (or equivalent). Do not sign in. Google has reasonable secure encryption, so it is best to download it from there. Playstore will verify the .apk.
Download Bitdefender trial, and use it to scan. Bitdefender is very good at inspecting files for trojan droppers.
Run Bluestacks, and refuse installing or setting up Google Playstore.
Run Textplus from within Blustacks, make sure you use a throwaway email address service.
You will be given a free, no credit card USA phone number, and you can select the state/location furthest from you; if you are stateside. Some sister apps within the TextPlus Company stable of apps allow you to select UK, Australian, or Canadian numbers, so check them out before selecting your .apk. They are generally all from the same company, but with different offers.
Load the number into Signal on an ios device or via Signal Web version, bon appetit.
If someone else had been issued that number before you, and registered the number with Signal, just try to switch your TextPlus number; or use a different app to obtain another number.
Scrub your disks of the .apk and Bluestacks.

For International Agency and Well Funded State Threats

In addition to the above:

a. Download the .apk from public wifi using your bulletproof vpn on a throwaway android phone that has been encrypted with 20+ (or max allowable) random digits.
b. Remove the sim and battery, place it in a ziplock bag and then several wraps of cooking foil. This will stop any chance of any rogue cellular network pings. You can always destroy the phone by losing it in a river. It's hard to find and the water ruins the phone. The processor would have to be taken off the board to extract the data and decrypt. There is a 10% chance that the chip will be destroyed in the chip-off process. Generally running it over, you have to crush the processor but there is a risk you may be caught red handed prior to destroying it. Flinging the phone into a body of water, or in a flask of salty water and throwing it from a moving vehicle is better. If its a nano phone, you may be okay swallowing it without the battery, and inside a **nd*m depending on your risk factor of being incarcerated and being required to pass it out, or internally scanned with an airport type scanner in a abdomen scan chair.
b. Go home and extract the .apk, trusting that there has not been any triggers on your haven sensors scattered throughout the house. Keep the wrapping on the phone when connecting it to your computer.
c. You should not use TOR when dealing with .apk files, as there may be a leak disclosing your use of TOR.
d. Your computer should have iptables locked down to harden your system from outgoing os leaks. If you need to use Mac, then you can download a gui for iptables called 'Little Snitch" spend some weeks gradually blocking leaky apps. The only app you let transmit essentially is your VPN. Disable the analytics app inside the VPN GUI. Preferably use Tunnelblick instead of a VPN GUI.
e. Use Bitdefender to scan for RATs (remote access trojans), or if the risk is too high, ask someone else or access someone else's computer to go through this process to run the TextPlus.apk to get that free nonidentifiable phone number for Signal.
f. Sit behind a well managed pfSense firewall.
g. Run a Whonix instance inside a virtual machine, being careful to not install the whonix workstation because the workstation module would run the .apk module over TOR and increase the risk of detection. Instead bridge an openillinois or debian workstation through the whonix gateway. The whonix gateway is simply a hard firewall that needs no tweaking. For ultimate control, use two bridged pfSense firewalls bridged to the openillinois/debian virtual machine. This should achieve null leaks and very hard for adversaries to RAT your o.i/debian vm. Likewise, sitting behind a pfSense firewall and using a VPN that has virus and intrusion blocking at the VPN's back end may make sense.
h. Use Signal on ios. It's less buggy, and presently very hard to invoke a remote access trojan onto. This is essential because if your adversary has ratted your android, then they have access to everything you type into Signal, all audio, video etc etc etc.
i. Use an iPod or iPad without cellular sim card. Just use wifi. You don't want to be tracked by network pings geographically, or have an iPhone that can be electromagnetically induced to ping a signal to the network (roughly). You don't want to have your adversary to set up a man-in-the-middle spoofed cell-site to capture your data. Just use a wifi only ios device and go blank from the number one real time tracking system in the world - cellphone networks. 'Country A' can track your every movement merely from network pings, when you are in 'Country B, C, D...or Z'.
j. Download Signal onto ios in a different country with nonidentifying credentials.
k. Buy a pfSense portable firewall and connect your iPod/Pad to the pfS firewall, and pfS to the VPN. This allows you to block all leaky apple apps and if the VPN fails, then you can set pfS to close all connections and stop the use of Signal, or any other data, such as leaky apple beacon daemon data that may pinpoint you, such as risky mDNSrespondr, touristd, App Store, apsd, com.appl.GEO.xpc and the various other apple and ios variant chattering daemons.
l. In your openillinois/debian vm, run the .apk inside a vm of android.

What this will do is obfuscate which phone number you are using, or it is you that is using a TextPlus disposable number to set up Signal. TextPlus and it's wholesalers will be able to tell that Signal has been linked to that TextPlus number. Signal app should be secure enough to prevent connecting you to the use of Signal, as long as you have researched well all the risks that could uncloak your use or location.

If you are in any country, you can still use a USA, UK TextPlus number to receive the Signal registration text.

This is not a list of all possible risks. I do not proclaim to give qualified advice. Research all other vulnerabilities related to use of radio frequency and digtal communications.
Others should add to this, or correct. If this is of any use, and may save the life of a Freedom Fighter in a tricky country; then feel free to redistribute.
Buy a dark phone already set up from the father of PGP, Phil Zimmerman, and his company, Silent Circle. Secure agents located world wide.

Try the app compared to Signal, it may be easier to set up.
@nerds-R-bae
nerds-R-bae commented an hour ago



Comments on email in life threatening situations:

If you use a PGP email, use a very rare provider that strips the unencrypted header off the email.

The issue if you use an email with a header, is that it will contain your ip address, or if your phone/computer is compromised, then your real ip can be forced to to be included in all your encrypted emails.

The adversary just sends you an email and you respond, and the header unmasks you instantly.

No ratting, and can be done via malicious website images or pixels. A caveat.

Check out mailhops to see how it works for yourself.

If you use email without header stripped, all of your recipients will have your location, the name of the isp, what os you used, and can google map you.

The adversary doesn't even need to break into your home to set off a Haven trigger and compromise your systems. They whip your mask off at lightspeed just by raiding your family's computers, hacking them, filing a security letter with ISPs, and UK hs the capacity to record all web traffic worldwide and hand it to any bedbuddy.

Generally, email is deprecated in regards to security. Even an adversary can weasel your private key out your browser if you use p'mail. If you're overseas, they only have to get any machine you have used p'mail on, or hack it, or the machine you're currently using.

Mr Zimmerman stated that email is deprecated. That is why Signal and his offering under the Silent Circle brand is much more secure as it has forward secrecy and keys that frequently change etc etc. The main risk is in setting up Signal. Then you're fine. Mr Snowden uses Signal.

With Signal and Silent Circle, you can send flattened images of docs.

It is not widely used. It may save your life rightly.

Email is handy. Its ok against domestic snooping, but a pgp key can be cracked from an intercepted email in a few weeks, if they really want you.

The header is the dead give away. Thats why Obama assured the public he only ever wanted metadata (headers) and you are free to encrypt. Well, the emperor seemed to have some nice new clothes on...but low and behold he was duped. He's actually naked, and everyones laughing at him. Believe me, Mr. Snowden is right. 'They' can read everything when emails are 99% in the clear, and always know where we are just from headers / metadata.

Google and freemail are great consumer free items that can allow consumers to maximise the amount of unsolicited ecommerce opportnities sent to them. The level of tracking with email trackers, stickylinks, beacon pixels and so forth sent to your email inbox, and with the providers raking up all the key words, well, they have all the words and hand them to our governments to share out.

For the technically pure, I would use PGP emails, from a clean account and tightly managed server and sparingly as long as metadata was stripped... and Signal & Silent Circle if a life rightly depends on it.
