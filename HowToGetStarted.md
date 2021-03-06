
#Authoritarianism Resistance Kit

This guide together with the USB drive you received will enable you to communicate securely and use the internet anonymously while living under the watch of an authoritarian government. It is designed for the computer novice and as such, does not go into any technical details. Its intended use is to provide digital safety while resisting an authoritarian government, but it might be of use to those who have "nothing to hide", who simply want to maximize their privacy. These are simple, effective, and tested methods. 

`I don't have a USB drive / I was just sent this link / I want to be super duper secure`

You can create your own USB drive by installing the TAILS operating system via [https://tails.boum.org/home/index.en.html](https://tails.boum.org/home/index.en.html). It's a bit laborious, but worth it. (If you go this route, be sure you verify the image before installing, as per the directions.)

This is also the safest possible method even if you received a USB drive, as you are guaranteeing a fresh drive with no possibility of tamper.



##Contents

1. [Disclaimers](#disclaimers)
2. [The Kit](#the-kit)
3. [About the Tools and How to Use Them](#about-the-tools-and-how-to-use-them)
4. [The Five Rules of Safety](#five-rules-of-safety)
5. [What Next? / Putting It All Together](#what-next--putting-it-all-together)

##Disclaimers

###A Note About Safety

The only 100% way to be safe under an authoritarian government is to not resist. Authoritarian governments set arbitrary rules for what is and is not considered a National Security Threat. Under some governments, even possession of an encrypted disk is sufficient probable cause to serve a warrant / drag you to an interrogation room. 

If you want to be 100% safe, throw away this disk or reformat it and use it for another purpose. Despite what others may tell you, you are always free to choose the path of least resistance if that means keeping yourself and your family safe. History is written by survivors. 

If you are curious and want to keep this kit handy, be prepared to keep it hidden. Via this guide you will be personalizing the USB drive. Though your drive will be encrypted, the most secure drive is one that is not found. 

###What This Kit Can Do / What It Can't

If used properly, this kit will allow you to browse the internet securely, communicate securely, and send and receive data securely. In this context, secure means "as good as possible for a novice", which is still fairly secure. 

This kit can not guarantee your safety, nor can it help you choose people to trust. Remember that humans are always the simplest exploit in a system. If you let a spy into the network of trust, your network is compromised. 

###If I'm Reading This, Can't Anybody?

Yes. This guide is open and available to anybody. The tools are open and available to anybody. Knowing the tools and methods will not help a third party break the security, and we should always assume they know what tools we're using and how we're using them. That is why we have strict protocols. 

It is also important to expose these tools and methods to a wide audience, so that they might be revised for maximum effectiveness over time. 

***


##The Kit

This kit has five main components:

1. The TAILS operating system (The Amnesiac Incognito Live System), which you are running right now via USB stick
2. The TOR browser / network, which allows you to bounce your computers IP Address (similar to a telephone number or postal address) off a series of relays to hide its origin
3. The JABBER instant messaging protocol with OTR (Off The Record) encryption for secure instant messaging
4. Secure and anonymous email
5. The Signal app for secure texting

The tools themselves are only part of the kit. You must also use them correctly and follow strict protocols, as outlined in the Five Rules of Safety. 

##About the Tools and How to Use Them

Below are descriptions of the tools as well as instructions on how to personalize them, if necessary. 

1. [Concerning TAILS](#1-tails-operating-system)
2. [Concerning TOR](#2-tor-browser--network)
3. [Concerning Jabber](#3-jabber-instant-messaging-protocol)
4. [Concerning Email](#4-anonymous-email)
5. [Concerning Texting](#5-signal-app-for-texting)

**---->** `RULES - Each tool has an associated rules, which is critical to its use. These are also collected at the bottom of this guide.`


###1. TAILS Operating System

TAILS allows you to operate any computer while leaving no trace. It is an open-source Linux distribution that is self-contained and designed for security. It will clear your system memory every time you exit. 

**---->** `RULE #1 - Never do any of these activities from your normal computing account. Always boot to TAILS via the USB drive.`

####DO THIS NOW - Enable a Persistent Drive 

The first thing you will want to do is enable a persistent volume for your TAILS drive. This means your information will be saved on the drive; otherwise TAILS wipes all information every time it restarts. 

1. Click the **Applications** menu in the upper left. 
2. Click **System Tools**. 
3. Click **Configure Persistent Volume**. 
4. For now select **Personal Data** and **Pidgin**. (You may want to select other options later, but these are good for a quick start.)
5. Enter your password for the persistent volume. NEVER WRITE DOWN PASSWORDS. Use a complex password that will be easy to remember. Two or three words will suffice (e.g. GiantStumblingPorcupine)
6. You're done. You will now be able to save files in the **Persistent** folder under **Home** as well as keep your Jabber IM credentials in the Pidgin chat program. 

###2. TOR Browser / Network

The Onion Relay (TOR) is a network of volunteer nodes that allow you to bounce your internet signal around the globe. A snooping third party would not be able to locate you based on your origin, since they would only be able to locate the final exit node. 

**NOTE** Because TOR operates via a relay, it is a bit slower than normal browsing. If your browsing seems sluggish, this is normal.

TOR is not 100% safe, but when used with TAILS it provides decent safety for a novice. 

**---->** `RULE #2 - Never log into any personalized service while using TOR. No facebook, amazon, gmail, etc. If you log in, your identity is compromised.`

###3. Jabber Instant Messaging Protocol

Jabber is an open-source instant messaging protocol that you can register anonymously. It supports OTR (Off the Record) encryption, which will allow you to talk with contacts such that a snooping third party will only see encrypted messages. 

####DO THIS NOW - Sign up for Jabber IM

1. Within TOR (always use TOR for any online step written here) go to [www.jabber.org](http://www.jabber.org).
2. Click **Public XMPP Services**. [link](https://xmpp.net/directory.php)
3. Select any service with a **AA** rating. Preferably one that is fairly recent (e.g. [im.koderoot.net](https://space.koderoot.net/))
4. Find the **Registration** or **Web Registration** link on the page (e.g. [https://im.koderoot.net/xmpp_register](https://im.koderoot.net/xmpp_register))
5. Register a new IM username and password. Your new username will be YOURNAME@RegisteringDomain.com (e.g. LargeSleepingOwl@im.koderoot.net)
6. Minimize the TOR browser. 
7. Launch Pidgin via the **Applications** menu in the upper left. 
8. Click **Add** to add your new account. 
9. For **Protocol** select **XMPP**.
10. Enter your new username (e.g. LargeSleepingOwl).
11. Enter your domain (e.g. im.koderoot.net).
12. Enter your new password. 
13. Click **Add**.
14. You're done!

####DO THIS NOW - establish a secure chat

1. In Pidgin click on your **Buddy List** window. (If you can't see it, click on the green circle chat icon at the top of the screen.)
2. Click **Buddies** and **New Instant Message**.
3. Enter the full address of your contact (e.g. SmallWakingRabbit@im.koderoot.net). 
4. Say hello.
5. Click **OTR** in the menu.
6. Click **Start Private Conversation**.
7. Click **OK**.
8. Click **OTR**.
9. Click **Authenticate Buddy** or **Re-Authenticate Buddy**.
10. Ask your question that only they will know the answer to. 
11. After they have authenticated, ask a follow-up second question in chat. This is the second layer of authentication. 
12. You're securely chatting!


**---->** `RULE #3 - Always re-authenticate your contact when you start speaking. This may seem like a hassle, but it is the only way to guarantee your contact has not been compromised.`

*Question: what if my contact is being coerced?* If for your secondary question your contact gives a wrong answer that is close to the right answer, they are sending a signal that they are being coerced. For instance, if you ask "Who is Marge's husband in the Simpsons?" and they answer "Gomer", you should play along and pretend to continue the chat. Give wrong information or be vague. This will guarantee their safety (at least immediately). 


###4. Anonymous email

Use [www.protonmail.com](http://www.protonmail.com) to establish anonymous email. This is a fairly simple process so I won't outline the steps. 

**---->** `RULE #4 - Never send mail to known identity emails (e.g. Gmail addresses) using anonymous email. If you absolutely must, enable encryption for the email by clicking the lock icon at the bottom of the Compose Email window.`

###5. Signal App for Texting

This app, available in the App Store or the Google Play Store, allows you to send encrypted text messages to contacts in your phone. Use it only to coordinate when on the ground or to plan conversations via IM. 

**---->** `Rule #5 - Always delete your texting conversations in Signal after you are done.`

##Five Rules of Safety


`RULE #1 - Never do any of these activities from your normal computing account. Always boot to TAILS via the USB drive.`
***
`RULE #2 - Never log into any personalized service while using TOR. No facebook, amazon, gmail, etc. If you log in, your identity is compromised.`
***
`RULE #3 - Always re-authenticate your contact when you start speaking. This may seem like a hassle, but it is the only way to guarantee your contact has not been compromised.`
***
`RULE #4 - Never send mail to known identity emails (e.g. Gmail addresses) using anonymous email. If you absolutely must, enable encryption for the email by clicking the lock icon at the bottom of the Compose Email window.` 
***
`RULE #5 - Always delete your texting conversations in Signal after you are done.`


##What Next? / Putting It All Together

Now that you have set up your USB Drive, your IM, your email, and your text, what next? Well, first let's cover what NOT to do next.

**DO NOT** send an email or text via an insecure line to whomever sent you this link or gave you this drive. Maybe you want to thank them, maybe you have questions, maybe you think this level of security is ludicrous and only proportionate to a grossly exaggerated imagined threat. Whatever you want to say, say it securely. Use Signal. Say it in person. Get their secure email or their secure IM (via Signal or in person) and say it that way. 

If you choose to participate in a circle of trust, you must fully participate. That means you abide by the rules. That means you do not talk, text, email, or IM about potentially compromising information unless you are using the tools and rules outlined in this guide. 

###Which Tool Should I Use When?

It's really up to you. The most secure option is talking via secure IM, since the conversation happens in real time and is not saved. Second to that is Signal. Third is email. Fourth is talking in person UNLESS you are positive the area is not bugged. 

###Who Can I Talk to About This?

You are welcome to invite anybody into the circle of trust, but be careful. Ask yourself, how well do I know this person? 

When you talk about this kit, do not use real names. Get in the habit of using usernames instead. The quickest way to compromise the network is to mix and mingle it with your existing social network, telling Bob about this kit you got from Susie and asking him what he thinks of it. 

###How Do I Make a USB Drive for a Friend?

1. Click **Applications**
2. Click **System Tools**
3. Click **Tails Installer**
4. Select **Install by Cloning**
5. Repeat your experience by giving them the drive with a printout of the URL for this guide. (You can use http://goo.gl or http://bit.ly or http://tinyurl.com to shorten it down)

###What Should I Do if I Have a Suggestion?

This is on Github, so learn to use Git, fork it, and make a pull request!


##That's It

You now have some simple, yet powerful tools to resist an authoritarian government, should you need them. Be wise, be focused, be safe. 
