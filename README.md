# Awesome Networked Media [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a list of real-time software tools for routing audio and video streams between applications and for sending audio and video streams across the network.

## Contents

- [Audio Routing](#audio-routing)
- [Audio networking](#audio-networking)
- [Video Routing](#video-routing)
- [Video Networking](#video-networking)
- [Other](#other)


### Audio Routing

- [Audio Routes](https://maxforlive.com/library/device/5830/audio-routes) - m4l devices to help routing audio.
  - [[blog1](https://cycling74.com/articles/audio-routings-a-new-system-for-multi-channel-routing-in-ableton-live)] [[blog2](https://cycling74.com/articles/audio-routes-using-audio-routes-tooling-for-your-mfl-devices)]
- [Black Hole](https://github.com/ExistentialAudio/BlackHole) (mac-only) - virtual audio driver that allows applications to pass audio to other applications (16 ch).
- [cs.2click](https://github.com/delucis/cs.2click) - A Better Audio Router for a Modular System in Max MSP.
- [FlexASIO](https://github.com/dechamps/FlexASIO) (windows-only) - FlexASIO is a universal ASIO driver, that supports WASAPI (shared and exclusive), KS, DirectSound and MME.
- [Hi-Fi CABLE & ASIO Bridge](https://www.vb-audio.com/Cable/#DownloadASIOBridge) (windows-only) - similar to VB Cable (see below) but can interface with ASIO devices.
- [Jack](https://jackaudio.org/) - cross-platform API that enables device sharing and also inter-application audio routing.
  - [[JackRouter on Windows](https://jackaudio.org/faq/jack_on_windows.html)] [[Catalina support discussion](https://github.com/jackaudio/jackaudio.github.com/issues/92)]
- [JackBridge](https://github.com/madhatter68/JackRouter) (mac-only) - an alternative to jackrouter for MacOS which acts as virtual audio interface (currently 2in-4out) connected to Jackaudio server directly.
- [JackBridge (older version)](https://sourceforge.net/projects/jackbridge/) - JackBridge is an adapter library designed to allow legacy applications use the Jack Audio Connection Kit. It is also useful when a client application can't be easily adapted to Jack's requirements (callback API, sample rate and/or sample format).
- [Node.JS JACK-connector](https://github.com/unclechu/node-jack-connector) - Bindings JACK-Audio-Connection-Kit for Node.JS
- [Loopback](https://rogueamoeba.com/loopback/) (mac-only) - cable-free audio routing for Mac that creates virtual audio devices (up to 64ch).
- [OBSAudioRouter](https://github.com/lysdexic-audio/OBSAudioRouter) (mac-only) - A simple microphone + external audiodevices passthrough/rerouter for MacOS
- [ODeus ASIO Link Pro](https://give.academy/posts/2018/03/02/AsioLinkPro/) (windows-only) - driver level audio routing solution for windows
- [pd~](http://msp.ucsd.edu/software.htm) - max/msp external that allows Max to call a Pd subprocess.
- [simplejack](https://github.com/mildsunrise/simplejack) - This Nodejs module enables you to register simple JACK clients.
- [Sound Control](https://staticz.com/soundcontrol/) (mac only) - per app volume, eq, and device routing control.
- [Soundflower](https://github.com/mattingalls/Soundflower) (mac-only) - creates 2 loopback audio devices (2ch and 64ch).
- [VB Cable](https://www.vb-audio.com/Cable/) (windows-only) - VB-CABLE is a virtual audio device working as virtual audio cable.
- [Virtual Audio Capture Device](https://github.com/rdp/virtual-audio-capture-grabber-device) (windows-only) - free audio capture device to capture all the "wave out sound" that is playing on your speakers.

### Audio Networking

- [\_noisecrypt](https://low.show/noisecrypt/) - web based audio streamming app.
- [AOO](https://git.iem.at/cm/aoo) - Audio over OSC is aimed to be a message based audio system using Open Sound Control OSC_ as a syntax format.
- [Artsmesh](https://www.artsmesh.com/) (mac-only) - All-in-one app for networked music based on jacktrip allowing for P2P (up to 16 ch) and Broadcasting.
- [Cleanfeed](https://cleanfeed.net/) - multitrack, multi-party live audio and recording using only a browser.
- [EasyRTC](https://github.com/open-easyrtc/open-easyrtc) - WebRTC based implementation, originally forked from [priologic](https://github.com/priologic/).
  - [[website](https://easyrtc.com/products/easyrtc/)]
- [Fastmusic Box](http://symonics.com/fastmusic/) - hardware package with pre configured setup based on soundjack.eu
- [icecast](https://icecast.org/) - streaming media server which currently supports Ogg (Vorbis and Theora), Opus, WebM and MP3 streams.
  - [butt](https://danielnoethen.de/butt/) - butt (broadcast using this tool) is a streaming tool that supports SHOUTcast and Icecast.
  - [izicast](https://izicast.de/) - Icecast/Shoutcast client for iPhone and iPad
  - [pdogg](https://puredata.info/downloads/pdogg) - a library of objects for Pd for reading and writing Ogg/Vorbis streams and files.
  - [ŻyweRadio](https://github.com/kfirmanty/zywe-radio) - online radio using icecast to broadcast stream of music performed live.
- [High Fidelity](https://www.highfidelity.com/) - Spatialized audio for up to 150 people. No download required.
- [HQStreamer2](https://github.com/sauraen/HQStreamer2) - Stream audio between DAWs locally or across the internet using a standalone or audio plugin devices.
- [JackStreamer](http://www.networksound.com/index.php/products/jrpbox) - a HW+SW kit that allows you to play music with your friend/band/ensemble over the Internet.
- [Jacktrip](https://github.com/jacktrip/jacktrip) - multi-machine audio system used for network music performance over the Internet, that may offer the best latency using uncompressed audio.
  - resources: [[ccrma](https://ccrma.stanford.edu/software/jacktrip/)] [[kadenze](https://www.kadenze.com/courses/online-jamming-and-concert-technology-x/info)] [[chrischafe](http://chrischafe.net/online-jamming-and-concert-technology-online-course/)] [[mdessen](https://mdessen.com/portfolio/networked-music-performance-resources/)] [[dessen](https://docs.google.com/document/d/1YLX8NatB_Ktdr24LyVg7h_P3zwG1lh1D0A0e733mCYo/edit)] [[loveridge](https://docs.google.com/document/d/18pbu2xQRv521NKvHuYHjIVXRcLFqcDsqYnfKixyuyGg/edit)] [[jacktrip-users](https://groups.google.com/forum/#!forum/jacktrip-users)] [[och](https://github.com/omarcostahamido/One-Quick-Solution_Patches/tree/master/Other)] [[oconnor](https://www.haven2.com/index.php/archives/configuring-starting-and-running-a-multi-client-jacktrip-server)] [[synthia](https://www.youtube.com/watch?v=9yGQ23EbBTw&list=PL1PiOF-Vo5KA-xxBue6BjdrEQAXOzDlNM)] [[
jstoltenberg](https://www.youtube.com/playlist?list=PLOwImupx7XmMcUlDusRKLX6qGAKym28To)]
- [JackTrip WebRTC](https://github.com/jacktrip-webrtc/jacktrip-webrtc) (TBA) - JackTrip WebRTC is an HTML5 implementation of Jacktrip for the web browser.
- [JamKazam](https://www.jamkazam.com/products/platform) - live music platform and social network, enabling musicians to play music together in real time from different locations over the internet.
- [JamTaba 2](https://github.com/elieserdejesus/JamTaba/) - play online music jam sessions with musicians around the world using ninjam servers.
  - [[lines](https://llllllll.co/t/ninjam-network-jam-session/7767)]
- [Jamulus](https://github.com/corrados/jamulus) - software that enables musicians to perform real-time jam sessions over the internet, with clients connecting to a central server.
- [Listento](https://audiomovers.com/) - latency between 0.1 and 1 sec (PCM16 bit, PCM24 bit, PCM32 bit, AAC128, AAC192).
- [mediaXploration](https://mediax.stanford.edu/featured-events/mediaxploration/) - an experimental virtual and immersive environment.
- [Netty McNetface](http://msp.ucsd.edu/tools/quacktrip/) - a multi-user version of quacktrip~ that relies on a central repeater.
  - resources: [[mdessen](https://docs.google.com/document/d/1llld1vvYUPfsogMyPhUOIGb7ZYsUV8JA4i4yjyKWT78/edit)]
- [ninjam](https://www.cockos.com/ninjam/) - open source (GPL) software to allow people to make real music together via the Internet, NINJAM uses compressed audio, and Latency in NINJAM is measured in measures.
- [nodeJsVoip](https://github.com/cracker0dks/nodeJsVoip) - A simple nodeJs Websocket VOIP application without the use of WebRTC
- [ovbox](https://github.com/gisogrimm/ovbox) - remote collaboration box developed by the ensemble ORLANDOviols using open source software and open or standardized hardware.
- [photon](https://www.photonengine.com/en/Photon) - networking engine and multiplayer platform for Unity
  - [[https://assetstore.unity.com/packages/tools/network/photon-unity-networking-classic-free-1786#description](unity-asset)]
- [QJackTrip](https://www.psi-borg.org/QJackTrip.msi) - Aaron Wyatt compiled version of Jacktrip for running the client on Windows, which also includes his new GUI.
- [quacktrip~](http://msp.ucsd.edu/tools/quacktrip/) - a vanilla Pd jacktrip client and server (in the same object).
  - [[jacktrip-users](https://groups.google.com/forum/?utm_medium=email&utm_source=footer#!msg/jacktrip-users/KrhojQxYy_w/3W9vDtIpAAAJ)] [[old_v2](http://msp.ucsd.edu/tmp/quacktrip-test-2.tgz)] [[old_v1]((http://msp.ucsd.edu/tmp/quacktrip-2020.05.13.tgz))]
- [Quack4](https://github.com/fdch/Quack4) - A quacktrip v0.5 plugin that handles a 3 way connection.
- [QuaxTrip](https://github.com/damonholzborn/QuaxTrip) - Max patch encapsulating the Quack4, a VST version of Miller Puckette's QuackTrip, a Pd implementation of JackTrip.
- [raspberry-jam](https://github.com/rbultman/raspberry-jam) - Use a Raspberry Pi and audio shield to connect musicians, or poets, together from distant locations.
- [Sagora](https://www.sagora.org/index-por.html) - free software, designed and developed by artists/researchers from the School of Arts of the National University of Quilmes, Argentina. It allows to connect multiple users in a virtual room and transmit audio in real time.
- [Soundjack](https://soundjack.eu/) - Soundjack is a browser-based low-latency communication system using compressed audio (OPUS).
- [Source-Live](https://source-elements.com/products/source-live) (mac-only) - High quality, low latency, encrypted audio and video streaming, in sync from your DAW.
- [TPF](https://gitlab.zhdk.ch/TPF) - low-latency audio transmission software based on the jacktrip protocol and built in Pure Data.
- [Virtual Rehearsal Room](https://vrr.iem.sh/) - [Pd based] an Auditory Virtual Environment for musicians playing together @home , @studio and @stage.
- [VST Connect](https://new.steinberg.net/vst-connect/) - a fully-featured, remote recording solution that lets anybody record a musician or other performer in professional quality, regardless of where each of them is on the planet.

### Video Routing

- [CamTwist](http://camtwiststudio.com/) (mac-only) - broadcast live video switcher.
- [mmhmm](https://www.mmhmm.app/) (mac-only with other platforms coming soon) - dynamic virtual backgrounds, similar to camtwist.
- [jit.ndi](https://github.com/impsnldavid/jit.ndi) - Extensions for sending/receiving video and audio using the Newtek NDI® protocol in Cycling 74's Max.
- [NDI tools](https://ndi.tv/tools/) - free suite of Network Device Interface (NDI) tools for real time, ultra low latency video on existing IP video networks.
- [Spout](https://spout.zeal.co/) (windows-only) - Realtime video sharing framework for Windows (similar to Syphon).
- [Syphon](http://syphon.v002.info/) (mac-only) - Mac OS X technology that allows applications to share frames - full frame rate video or stills - with one another in realtime.

### Video Networking

- [Artsmesh](https://www.artsmesh.com/) (mac-only) - All-in-one app for networked music based on jacktrip allowing for P2P (up to 16 ch) and Broadcasting.
- [Digital Stage](https://digital-stage.org/) - multi platform implementation for audio-video conference call for art, music and theater companies to rehearse.
- [Google Hangouts](https://hangouts.google.com/)
- [Google Meet](https://meet.google.com/)
- [iWebVisit](https://www.iwebvisit.com/) - Inmate visitation online app.
- [Jitsi](https://jitsi.org/) - free video conferencing in the browser, similar to Zoom.
- [Live Lab](https://github.com/ojack/LiveLab)
  - [[culturehub](https://www.culturehub.org/livelab)] [[comparing2zoom](https://docs.google.com/spreadsheets/d/1jJNNtkoSH1FunCPHS2Z05MzdUMkU_KMe71uPimGF94Q/edit#gid=0)]
- [OBS Studio](https://obsproject.com/)
  - [[jitter](https://cycling74.com/articles/streaming-tips-the-jitter-edition)] [[msp](https://cycling74.com/articles/tips-for-streaming-your-max-patch)]
- [restream](https://restream.io/) - Restream allows you to stream live to 30+ social platforms at once.
- [Skype](https://www.skype.com/) - a telecommunications application that specializes in providing video chat and voice calls between computers, tablets, mobile devices, the Xbox One console, and smartwatches over the Internet. 
- [sococo](https://www.sococo.com/) - online workplace where distributed teams come to work together each day, side-by-side.
- [streamlabs](https://github.com/stream-labs/streamlabs-obs/) - open source streaming software built on OBS and Electron.
- [Streamyard](https://streamyard.com) - In-browser streaming studio, with basic free option and paid tiers.
- [Touchdesigner](https://derivative.ca/)
  - [[broadcasting](https://derivative.ca/community-post/broadcasting-social-media-touchdesigner/62737)] [[zoom](https://derivative.ca/community-post/tutorial/touchdesigner-zoom/62762)] [[2020.22080](https://forum.derivative.ca/t/official-build-2020-22080-posted/131128)] [[iglive](https://derivative.ca/community-post/tutorial/streaming-instagram-live/62828)]
- [UltraGrid](http://www.ultragrid.cz/)
  - [[Spout/Syphon](https://iaspace.zhdk.ch/wiki/ultragrid/)]
- [UpStage](https://upstage.org.nz/) - a platform for cyberformance: remote players combine digital media in real-time for an online audience. All you need is a web browser!
  - resources: [[github](https://github.com/upstage-org)] [[https://en.wikipedia.org/wiki/UpStage](wiki)]
- [VLC](https://www.videolan.org/vlc/) - cross-platform multimedia player and framework.
  - [[stream](https://forums.tomsguide.com/faq/how-to-stream-videos-over-the-internet-with-vlc.23235/)]
- [Whereby](https://whereby.com/)
- [Zoom](https://zoom.us/)
  - resources: [[LS-youtube](https://support.zoom.us/hc/en-us/articles/360028478292-Streaming-a-Meeting-or-Webinar-on-YouTube-Live)] [[LS-facebook](https://support.zoom.us/hc/en-us/articles/115000350406-Streaming-a-Meeting-or-Webinar-on-Facebook-Live)] [[LS-custom](https://support.zoom.us/hc/en-us/articles/115001777826-Live-Streaming-Meetings-or-Webinars-Using-a-Custom-Service)]

### Other

- [bf-pd](http://bf-collab.net/) -  Pure Data based software that allows musicians to share parameters and output data between instruments, to control each other’s instruments, to synchronize between instruments, to visualize each other’s activity, and to exchange messages
  - [[gitlab](https://gitlab.cristal.univ-lille.fr/boeuf/bf-pd)]
- [link](https://www.ableton.com/en/link/) - Ableton Link is a technology that keeps devices in time over a local network.


<p>
  <details><summary>Feel free to cite this:</summary> 
    

style | reference    
--- | ---
MLA 8th | Hamido, Omar Costa, and Michael Dessen. Awesome Networked Media. 2020. 2020. GitHub, https://github.com/omarcostahamido/awesome-networked-media.
APA 7th | Hamido, O. C., & Dessen, M. (2020). Awesome Networked Media. https://github.com/omarcostahamido/awesome-networked-media (Original work published 2020)
Chicago 17th | Hamido, Omar Costa, and Michael Dessen. Awesome Networked Media, 2020. https://github.com/omarcostahamido/awesome-networked-media.
IEEE | [1]O. C. Hamido and M. Dessen, Awesome Networked Media. 2020.

BibTeX | [here](https://github.com/omarcostahamido/awesome-networked-media/blob/master/awesome%20networked%20media.bib)


  </details>
</p>
