# ejabberd @ wunderfitzig.net - A privacy respecting XMPP Server Project inspired by trashserver.net

XMPP protocol based Chat Server hosted by Strato.
Server runs on Debian 10 Buster.
Ejabberd version 20.07. from buster-backports.
Used installation tutorials added as links at the end of the README file.

So far the server is still at beta-stage and in private use only but will serve for future public use trying to meet high privacy standards guaranteeing high anonymousity. Standards defined according to XMPP compliance test and Lynis security audit.

## Packages installed:

  - Anti-Spam/Bot: Captchas at registration: 
      - <code> imagemagick </code> 
      - <code> gsfonts </code> 

## To do list:

  - [ ] Include STUN/TURN Video/Audio Chat
  - [ ] meet highest security standards for private user data
      - [ ] Meet Lynis Security Audit Score >80%
      - [ ] see trashserver.net and Mike Kuketz
      - [ ] XMPP Compliance test
        - [ ] XEP-0363: HTTP File Upload (CORS Headers)
        - [ ] XEP-0156: Discovering Alternative XMPP Connection Methods (HTTP)
        - [ ] XEP-0368: SRV records for XMPP over TLS
  - [ ] Create public website for users with Server information

## Links:

  * https://www.process-one.net/blog/how-to-move-the-office-to-real-time-im-on-ejabberd/
  * https://www.process-one.net/blog/how-to-set-up-ejabberd-video-voice-calling/
  * https://www.kuketz-blog.de/ejabberd-installation-und-betrieb-eines-xmpp-servers/
  * https://github.com/ThomasLeister/trashserver.net-xmpp
  * https://cisofy.com/lynis/
