# Awesome Real Time Communications [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Protocols and methodology for near simultaneous exchange of media and data.


## Contents

- [Server Software](#server-software)
  - [General Purpose](#general-purpose)
  - [SIP Servers](#sip-servers)
  - [Media Servers](#media-servers)
  - [STUN/TURN](#stunturn)
- [Clients](#clients)
- [Operations](#operations)
  - [Monitoring](#monitoring)
  - [Testing](#testing)
  - [Web/API Interfaces](#webapi-interfaces)
  - [Billing](#billing)
- [Developer Resources](#developer-resources)
  - [Tutorials](#tutorials)
  - [JavaScript Libraries](#javascript-libraries)
  - [C/C++ Libraries](#cc-libraries)
  - [Go Libraries](#go-libraries)
  - [PHP Libraries](#php-libraries)
  - [Python Libraries](#python-libraries)
  - [Erlang Libraries](#erlang-libraries)
  - [Rust Libraries](#rust-libraries)
  - [Dart Libraries](#dart-libraries)
  - [Media over QUIC](#media-over-quic)
- [Blogs](#blogs)
- [Discussion](#discussion)
- [Events and Talks](#events-and-talks)
- [Contribute](#contribute)


## Server Software

### General Purpose

- [FreeSWITCH](https://github.com/signalwire/freeswitch) - Open source communications server for voice, video, messaging and conferencing.
- [Asterisk](https://www.asterisk.org/) - PBX framework supporting multiple protocols and platforms.

### SIP Servers

- [Kamailio](https://www.kamailio.org/w/) - Open source SIP server for routing, registration, presence and large-scale deployments.
- [OpenSIPS](https://opensips.org/) - Open source SIP proxy and application server for VoIP platforms.
- [Routr](https://routr.io) - Cloud-native SIP proxy, registrar and location service.
- [Sippy B2BUA](https://github.com/sippy/b2bua) - Back-to-back user agent server written in Python.
- [Flexisip](https://github.com/BelledonneCommunications/flexisip) - SIP server suite comprising proxy, presence and group chat functions.
- [FreeSBC](https://github.com/rasonyang/freesbc) - Open source SIP/WebRTC edge proxy with an embedded RTP relay for FreeSWITCH and Asterisk.
- [P-KISS-SBC](https://github.com/mwolff44/pk-sbc) - Kamailio and rtpengine-based session border controller for connecting SIP trunks and PBXs.

### Media Servers

- [Janus](https://janus.conf.meetecho.com) - Lightweight open source, general purpose, WebRTC gateway.
- [LiveKit](https://github.com/livekit/livekit) - Open source WebRTC server and SDK ecosystem for real-time audio, video and data.
- [RTPProxy](https://www.rtpproxy.org) - General purpose high performance RTP proxy.
- [rtpengine](https://github.com/sipwise/rtpengine) - RTP and UDP based media traffic proxy, usable as a kernel module.
- [mediasoup](https://mediasoup.org) - Specialized WebRTC conferencing system.
- [SEMS](https://github.com/sems-server/sems) - Open source media and application server for SIP based VoIP services.
- [Jitsi](https://jitsi.org/projects) - A collection of RTC open source projects, with a focus on conferencing software.

### STUN/TURN

- [coturn](https://github.com/coturn/coturn) - Fully featured TURN/STUN server supporting multiple platforms.
- [eturnal](https://eturnal.net/) - Modern and scalable STUN/TURN server written in Erlang.
- [STUNner](https://github.com/l7mp/stunner) - Kubernetes-native STUN/TURN gateway for WebRTC media.
- [STUNTMAN](https://github.com/jselbie/stunserver) - RFC compliant open source STUN implementation.


## Clients

- [Web SIP Phone](https://github.com/rasonyang/web-sip-phone) - Chrome extension maintaining SIP/WebRTC audio for server-controlled call center agents.


## Operations

### Monitoring

- [sngrep](https://github.com/irontec/sngrep) - Terminal based SIP flow viewer.
- [sipgrep](https://github.com/sipcapture/sipgrep) - Console tool for sniffing, capturing and exploring SIP traffic.
- [HOMER](https://github.com/sipcapture/homer) - Multi-protocol capturing and monitoring framework for RTC.
- [Trickle ICE](https://webrtc.github.io/samples/src/content/peerconnection/trickle-ice) - Exposes client-side NAT traversal debug data.
- [rtcStats](https://github.com/rtcstats/rtcstats) - WebRTC API trace and getStats collection, storage and feature extraction tooling.
- [SIP3 Community Edition](https://sip3.io/docs/InstallationGuide.html) - Open source SIP/RTP capture, analysis and monitoring components with community deployment tooling.

### Testing

- [SIPp](https://github.com/SIPp/sipp) - Traffic generator and scenario-based test tool for the SIP protocol.
- [SIPVicious](https://github.com/EnableSecurity/sipvicious) - Suite of security tools that can be used to audit SIP based VoIP systems.
- [sipsak](https://github.com/nils-ohlmeier/sipsak) - SIP stress and diagnostics utility.
- [sipexer](https://github.com/miconda/sipexer) - Modern and flexible SIP command line tool.
- [natcheck](https://github.com/1mb-dev/natcheck) - NAT diagnosis CLI that probes STUN servers and reports mapping behaviour and a WebRTC P2P forecast.

### Web/API Interfaces

- [Eqivo](https://eqivo.org) - Open source programmable-voice/telephony API platform.
- [Kazoo](https://github.com/2600hz/kazoo/tree/4.3) - Legacy open source VoIP API platform built on FreeSWITCH and Kamailio, available in the public 4.3 branch.
- [FusionPBX](https://www.fusionpbx.com) - Multitenant system built on top of FreeSWITCH.
- [FreePBX](https://www.freepbx.org) - Web Manager for Asterisk.
- [Fonoster](https://github.com/fonoster/fonoster) - Open source platform for programmable voice and voice AI applications.
- [Wazo](https://wazo-platform.org) - VoIP API platform built on top of Asterisk, Kamailio and RTPEngine.
- [jambonz](https://www.jambonz.org) - Open source CPaaS built for communications service providers.
- [IVOZ Provider](https://github.com/irontec/ivozprovider) - Multitenant solution for VoIP telephony providers.
- [Sayna](https://github.com/SaynaAI/sayna) - Real-time speech infrastructure for voice AI with WebSocket streaming, SIP telephony and pluggable STT/TTS providers.
- [AI Native Call Center](https://github.com/rasonyang/ai-native-callcenter) - FreeSWITCH-based call center with speech-to-speech AI, agent queues and a web interface/API.

### Billing

- [CGRateS](https://github.com/cgrates/cgrates) - Open source rating, charging and billing engine for telecom and ISP services.


## Developer Resources

### Tutorials

- [WebRTC.org](https://webrtc.org/) - Official WebRTC guides, APIs and project resources.
- [Getting Started With WebRTC](https://webrtc.org/getting-started/overview) - Official introduction to media capture and peer-to-peer connectivity APIs.
- [WebRTC Samples](https://webrtc.github.io/samples) - Collection of samples demonstrating various parts of the WebRTC APIs.

### JavaScript Libraries

- [drachtio](https://drachtio.org) - Node.js SIP server framework.
- [adapter.js](https://github.com/webrtcHacks/adapter) - JavaScript shim for abstracting WebRTC spec changes and inconsistencies.
- [JsSIP](https://jssip.net/) - Open source JavaScript SIP library with WebRTC media support.
- [simple-peer](https://github.com/feross/simple-peer) - WebRTC wrapper for browser media streams and data channels.
- [Peerix](https://github.com/meefik/peerix) - TypeScript WebRTC library for peer-to-peer media and data with pluggable signalling drivers.
- [PeerJS](https://peerjs.com) - Data and media peer-to-peer connection API implemented over WebRTC.

### C/C++ Libraries

- [libre](https://github.com/baresip/re) - Portable SIP, SDP, RTP, SRTP and ICE/STUN/TURN library with asynchronous I/O.
- [PJSIP](https://www.pjsip.org) - Multi-protocol RTC library written in C.
- [eXosip](http://savannah.nongnu.org/projects/exosip) - eXtended osip is a mature C library for abstracting the SIP protocol.
- [libdatachannel](https://github.com/paullouisageneau/libdatachannel) - Standalone C/C++ library for WebRTC data channels, media transport and WebSockets.
- [icey](https://github.com/auscaster/icey) - C++20 media toolkit combining WebRTC, FFmpeg, asynchronous networking and signalling.
- [libSRTP](https://github.com/cisco/libsrtp) - Secure Real-time Transport Protocol (SRTP) library for C.
- [usrsctp](https://github.com/sctplab/usrsctp) - Portable Stream Control Transmission Protocol (SCTP) user-land stack.
- [Sofia-SIP](https://github.com/freeswitch/sofia-sip) - Open source SIP library used by FreeSWITCH.

### Go Libraries

- [Pion](https://pion.ly) - Extensive software stack for WebRTC written in Go.
- [go-diameter](https://github.com/fiorix/go-diameter) - RFC compliant Diameter protocol library.

### PHP Libraries

- [RTCKit/SIP](https://github.com/rtckit/php-sip) - SIP message parsing and rendering library for PHP.

### Python Libraries

- [aiortc](https://github.com/aiortc/aiortc) - WebRTC and ORTC implementation for Python using asyncio.

### Erlang Libraries

- [ersip](https://github.com/poroh/ersip) - Library comprising building blocks for SIP applications.

### Rust Libraries

- [WebRTC.rs](https://github.com/webrtc-rs/webrtc) - Asynchronous WebRTC implementation in Rust with SDP, RTP, RTCP and SRTP support.

### Dart Libraries

- [dart-sip-ua](https://github.com/flutter-webrtc/dart-sip-ua) - Dart SIP user-agent stack with SIP over WebSocket and WebRTC media support.

### Media over QUIC

Experimental implementations for live media over QUIC and WebTransport. Supported draft versions and protocol variants differ; check compatibility before combining implementations.

- [moq-rs](https://github.com/cloudflare/moq-rs) - Rust implementation of Media over QUIC Transport with a relay and sample publishers.
- [moq](https://github.com/moq-dev/moq) - Rust and TypeScript libraries, relay and browser player implementing moq-lite.
- [moqtail](https://github.com/moqtail/moqtail) - Rust and TypeScript Media over QUIC Transport libraries with a relay and example clients.
- [moxygen](https://github.com/facebookexperimental/moxygen) - C++ Media over QUIC Transport library with a relay, sample applications and interoperability tools.
- [libquicr](https://github.com/Quicr/libquicr) - C++ Media over QUIC Transport library with publish, subscribe, capture and replay tools.
- [imquic](https://github.com/meetecho/imquic) - Experimental C library for QUIC and WebTransport with RTP over QUIC and Media over QUIC Transport support.


## Blogs

- [BlogGeekMe](https://bloggeek.me/blog) - Blog by Tsahi Levent-Levi with a strong focus on WebRTC.
- [WebRTC For Developers](https://www.webrtc-developers.com/) - Articles, examples and tools for WebRTC application developers.
- [WebRTCHacks](https://webrtchacks.com) - WebRTC blog by independent technologists.


## Discussion

- [FreeSWITCH Community](https://signalwire.community) - Discord community for FreeSWITCH and SignalWire users and developers.
- [discuss-webrtc](https://groups.google.com/g/discuss-webrtc) - Developer discussion group for WebRTC APIs, implementations and interoperability.


## Events and Talks

- [ClueCon](https://www.cluecon.com/) - Conference for communications and voice AI developers.
- [Kamailio World](https://www.kamailio.org/w/category/kamailio-world/) - Conference announcements and technical sessions covering Kamailio and open source RTC systems.
- [AstriCon](https://www.asterisk.org/astricon/) - Conference for Asterisk and FreePBX developers and users.
- [CommCon](https://commcon.xyz/) - RTC and open-media community events with a technical talk archive.
- [OpenSIPS Summit](https://www.opensips.org/Community/Summits) - OpenSIPS community conferences with technical presentations and proceedings.
- [FOSDEM](https://fosdem.org) - Free event for software developers, with a RTC component, held every year in Europe.
- [JanusCon](https://www.januscon.it/2024/) - Conference proceedings and technical talks for Janus and WebRTC developers.
- [TADHack](https://blog.tadhack.com/) - Telecom application hackathons, demos and event announcements.


## Related Lists

- [Awesome RTC Hacking](https://github.com/EnableSecurity/awesome-rtc-hacking) - Real Time Communications hacking and penetration testing resources.
- [Awesome 5G](https://github.com/calee0219/awesome-5g) - 5G frameworks, libraries, software and resources.
- [Awesome Cellular Hacking](https://github.com/W00t3k/Awesome-Cellular-Hacking) - Research resources in the 3G/4G/5G Cellular security space.
- [Awesome Telco](https://github.com/ravens/awesome-telco) - Telco resources and projects.
- [Awesome Asterisk](https://github.com/ictinnovations/awesome-asterisk) - Asterisk tooling: ARI, AMI and AGI libraries, call audio streaming, voice AI and testing.
- [Awesome FreeSWITCH](https://github.com/ictinnovations/awesome-freeswitch) - FreeSWITCH tooling: Event Socket libraries, call audio streaming, distributions and monitoring.
- [SIP Resources](https://github.com/miconda/sip-resources) - Useful SIP resources curated by Kamailio's head developer.


## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
