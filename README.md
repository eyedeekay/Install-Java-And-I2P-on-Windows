Installing I2P, its dependencies, and recommended external software on Windows 10
=================================================================================

Getting I2P installed and configured on Windows has at times been a process which
left many of our potential participants confused. As power-users and developers, this
issue is sometimes invisible to us. So to get a better impression of what the
experience is for a new I2P participant, I installed an unfamiliar OS on an old laptop
and undertook the install process, from start to finish.

This is deliberately the most detailed version of this guide I could justify as 
in-scope, some steps might be redundant on computers that have already been in
use for some time.

What? An unfamiliar OS? How is that useful?
-------------------------------------------

Relax, it's Windows.

So what are we going to do here?
--------------------------------

We're going to finish four tasks. We are going to:

 1. [Install Java](#part-one-install-java)
 2. [Install I2P](#part-two-install-i2p)
 3. [Install a Real Browser(Firefox)](#part-three-install-a-real-browserfirefox)
 4. [Configure I2P Bandwidth](#part-four-configure-i2p-bandwidth)

### Part One: Install Java

In order to use I2P, you will need a suitable Java environment. On Windows, users should
probably choose Oracle's Java 8 implementation. Please install it by following the
instructions below:

If you already have Java installed, you may [Skip This Step](#part-two-install-i2p)

1. I2P requires Java to run, if you don't have Java installed, you will get an error
 that looks like this:
  - ![Uh oh, no Java yet](nojava.png)
2. We appreciate that you have a wide range of choices in Java software, but the Oracle
Java software is the easiest to install and use with I2P on Windows. Please use this
version.
  - ![You need Oracle Java for Windows](oraclejava.png)
3. Download it from here:
  - ![So download it](getjava.png)
4. Double-click the Java Installer you just downloaded. Don't set a custom path, just
use the default one.
  - ![Start installing Java](startjava.png)
5. Java will show you some information about what it is and where it runs while you
wait for it to finish installing.
  - ![Step one](installjava.png)
6. When you see this, Java is almost installed.
  - ![Step two](installjava2.png)
7. Java is now installed!
  - ![You're done!](installedjava.png)

### Part Two: Install I2P



1. Download I2P from [https://geti2p.net](https://geti2p.net)!
  - ![Download I2P](geti2p.png)
2. I2P is available in many languages. Select one that is familiar to you!
  - ![Select your Language](i2plang.png)
3. On the first screen, we introduce our software!
  - ![Introduction](i2pnext.png)
4. I2P is mostly public domain software, with permissive licenses and a small amount of GPL2'ed
Free Software!
  - ![Accept the License Agreement(or mostly lack thereof)](i2plicense.png)
6. You should probably leave I2P installed at the default path, as it is easiest to work with this
way!
  - ![Select the path to install to](i2ppath.png)
7. Check "Install Windows Service" to run I2P automatically on your computer!
  - ![Select Components](installbase.png)
8. I2P will copy it's files into the install location!
  - ![Wait a moment](installrun.png)
9. I2P is now installed! ![Finish it up](installed.png)

### Part Three: Install a Real Browser(Firefox)

Unfortunately for Windows users, Microsoft Edge does not have proxy settings that are safe to use with I2P. The browser
that is easiest to configure with I2P in a reasonably good way is Firefox(Although Chrome is possible, this procedure
is only recommended for experts). I2P participants who want to browse I2P Sites can follow these steps to install
and configure Firefox for I2P. 

If you already have Firefox installed, you may [Skip This Step](#install-the-i2p-firefox-profile)

1. Get Firefox from [htps://mozilla.org](https://mozilla.org)
  - ![Get Firefox](firefox.png)
2. Run the installer!
  - ![Run the installer](firefox-installer.png)

#### Install the I2P Firefox Profile

3. Download the Firefox Profile Bundle from the I2P Web Site!
  - ![Grab the Firefox Profile](profile.png)
4. Select the language you want to use for the install process!
  - ![Select your language](profilelang.png)
5. The Profile Bundle incorporates lots of external software, so it has a detailed license 
document!
  - ![Accpt the License Agreement](profilelicense.png)
6. You now have a browser ready for I2P! ![Now your browser is configured](profiledone.png)

### Part Four: Configure I2P Bandwidth

Want to re-run the welcome wizard after completing it, you can visit the page
on [your router console](http://localhost:7657/welcome).

1. When you visit the I2P router console for the first time, it will automatically direct you to the bandwidth
configuration wizard.
  - ![Start the bandwidth wizard](bwintro.png)
2. During the bandwidth test, we'll need to connect to the external M-Lab Service, which makes
  - ![Let the participant know what the bandwidth test entails](bwdisclaimer.png)
3. The bandwidth test takes about a minute to run completely.
  - ![Run the bandwidth test](bwtest.png)
4. Here we have an overview of the applications.
  - ![Suggest browser and application configuration](bwbrowser.png)
5. Now you have your bandwidth configured to efficiently contribute to I2P.
  - ![Welcome to the Invisible Internet](bwdone.png)
