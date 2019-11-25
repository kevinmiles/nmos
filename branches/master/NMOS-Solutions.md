# NMOS Solutions
This page lists open source, free and commercial implementations of NMOS specifications.

This list is unlikely to be complete, and AMWA does not make any guarantees of conformance.

To have an implementation added, please submit a GitHub issue to the [NMOS repo](https://github.com/AMWA-TV/nmos), including the information required in the table. The implementation must be available, and a link to a repo, download page or product page must be provided.

# Open Source & Freeware

| Name | Language | License | Description |
| ---- | -------- | ------- | ----------- |
| [AMWA NMOS Testing Tool](https://github.com/AMWA-TV/nmos-testing/) | Python | Apache 2.0 | Testing of all current NMOS specifications |
| [BBC R&D NMOS Joint RI](https://github.com/bbc/nmos-joint-ri) |  Python | Apache 2.0  | IS-04 and IS-05 registry and APIs (used as reference in AMWA workshops). |
| [BBC R&D NMOS Web Router](https://github.com/bbc/nmos-web-router) | Javascript | Apache 2.0 | IS-04 and IS-05 web-based client application |
| [BBC R&D Authorisation Server](https://github.com/bbc/nmos-auth-server) | Python | Apache 2.0 | OAuth2 Authorisation Server based on AMWA NMOS BCP-003-02 / IS-10 |
| [Mellanox NMOS Docker](https://dockr.ly/2K046pJ) | N/A | Apache 2.0 | Docker container IS-04/05/07/09, BCP-003-02 |
| [Riedel NMOS Explorer](https://myriedel.riedel.net/en/downloads/) | N/A | Freeware | IS-04 and IS-05 client application for Windows and Linux |
| [Sony nmos-cpp](https://github.com/sony/nmos-cpp) | C++  | Apache 2.0 | IS-04 and IS-05 API implementations, registry and node applications |
| [Sony nmos-js](https://github.com/sony/nmos-js) | Javascript | Apache 2.0 | IS-04 and IS-05 web-based client application |
| [Streampunk Media Ledger](https://github.com/Streampunk/ledger) | Javascript (NodeJS)  | Apache 2.0 | IS-04 v1.0 APIs |

Note that inclusion in this list is not an endorsement by AMWA or a guarantee of conformance to the specifications.

# Commercial Hardware & Software ![buy NMOS here](images/buy_NMOS_here_100w.png)

This section lists commercial implementations of the NMOS specifications. It includes information about which NMOS specifications, versions and features are supported, and provide links to the manufacturers' product pages. (Note to manufacurers: the linked product page must include information about NMOS support!)

Note that inclusion in this list is not an endorsement by AMWA or a guarantee of conformance to the specifications.

Many of these products have participated in the JT-NM Tested programme, with results available [here](http://jt-nm.org/jt-nm_tested/). Note that the JT-NM Tested badge does not constitute a 'pass', but is simply an indication that testing results are available to download.


## Controllers & Registries

| Company | Product | Supported Specifications | Comments |
| ------- | -------------- | ------------------------ | -------- |
| Axon | [Cerebrum](https://www.axon.tv/productgroup/cerebrum/ip-control-monitoring/) | IS-04 v1.2 <br/> IS-05 v1.0 | Broadcast Control and Monitoring Solution |
| BFE | [SILKNET](https://bfe.tv/en/solutions-products/control-monitoring-systems/ksc-silknet/) | IS-04 v1.2 <br/> IS-05 v1.0 | Broadcast SDN Controller |
| EVS | [SCORE MASTER](https://evs.com/en/product/score-master) | IS-04 v1.2 <br/> IS-05 v1.0 | SDN Controller for IP Routing |
| Mellanox | [SN2000 Series](http://www.mellanox.com/page/products_dyn?product_family=251&mtag=sn2000) <br/> [SN3000 Series](http://www.mellanox.com/page/products_dyn?product_family=280&mtag=sn3000_label) | IS-04 v1.3 <br/> IS-05 v1.1 <br/> IS-07 v1.0 | Spectrum and Spectrum-2 Ethernet Switches <br/> Including on-switch IS-04 registry |
| Nevion | [VideoIPath](https://nevion.com/videoipath/) | IS-04 v1.2 <br/> IS-05 v1.0 | Broadcast Controller & IS-04 Registry |

## Media Nodes

| Company | Product | Supported Specifications | Comments |
| ------- | -------------- | ------------------------ | -------- |
| AJA | [IPR-10G2-HDMI](https://www.aja.com/products/mini-converters/ipr-10g2-hdmi) <br/> [IPR-10G2-SDI](https://www.aja.com/products/mini-converters/ipr-10g2-sdi) <br/> [IPR-10G-HDMI](https://www.aja.com/products/mini-converters/ipr-10g-hdmi) <br/> [IPT-10G2-HDMI](https://www.aja.com/products/ipt-10g2-hdmi) <br/> [IPT-10G2-SDI](https://www.aja.com/products/ipt-10g2-sdi) <br/> [IoIP](https://www.aja.com/products/io-ip) <br/> [KONA-IP](https://www.aja.com/products/kona-ip) | IS-04 v1.2 <br/> IS-05 v1.0 | IP Converters and Interfaces |
| Bridge Technologies | [VB440](https://bridgetech.tv/products/vb440/) | IS-04 v1.2 <br/> IS-05 v1.0 | High Performance IP Probe |
| Dalet | [Brio]( https://www.dalet.com/fr/platforms/brio) | IS-04 v1.2 <br/> IS-05 v1.0 | Ingest and Playout Server |
| EEG | [HD492 Alta](https://eegent.com/products/X6KO3ARIL9X1VEIU/altaTM-ip-video-captioning) | IS-04 v1.2 <br/> IS-05 v1.0 | Caption Encoder for Live Broadcasting |
| Embrionix | [emFUSION](https://www.embrionix.com/product/emFUSION-6) <br/> [emVIEW](https://www.embrionix.com/product/emVIEW-7-DMI%20-%20Standalone%20IP%20Gateway%20(HDMI%20out)) <br/> [emSFP ST.2110 Encapsulator](https://www.embrionix.com/product/ST2110%20Dual%20Encapsulator%20(HD-SDI)) <br/> [emSFP ST.2110 Decapsulator](https://www.embrionix.com/product/ST2110%20Dual%20De-Encapsulator%20(HD-SDI)) | IS-04 v1.2 <br/> IS-05 v1.0 <br/> IS-08 v1.0 | IP Gateway converters |
| EVS | [XT-VIA](https://evs.com/en/product/xt-via) <br/> [XS-VIA](https://evs.com/en/product/xs-via) <br/> [XT-4K](https://evs.com/en/product/xt4k) <br/> [XS-4K](https://evs.com/en/product/xs4k) <br/> [XS-NEO](https://evs.com/en/solutions/ingest2post) | IS-04 v1.2 <br/> IS-05 v1.0 | IP/SDI Production Servers |
| Grass Valley | [XIP-3901](https://www.grassvalley.com/products/xip-3901/) <br/>[Kaleido IP](https://www.grassvalley.com/products/kaleido-ip/) | IS-04 v1.2 <br/> IS-05 v1.0 | SDI/IP Processing Platform<br/>IP Video Multiviewer |
| Harmonic | [Spectrum X](https://www.harmonicinc.com/video-appliances-software/portfolio/spectrum-x/) | IS-04 v1.2 <br/> IS-05 v1.0 | Ingest and Playout Server |
| Imagine Communications | [Selenio Network Processor](https://www.imaginecommunications.com/products/networking-infrastructure/processing/selenio-network-processor) <br/> [EPIC Multiviewer](https://www.imaginecommunications.com/products/networking-infrastructure/multiviewers/epic-mv) | IS-04 v1.2 <br/> IS-05 v1.0 | Network-based audio/video processor and gateway device <br/> IP-enabled Multiviewer |
| Leader | [LV5600](https://www.leader.co.jp/en/products/broadcast/waveform/lv5600/) <br/> [LV7600](https://www.leader.co.jp/en/products/broadcast/waveform/lv7600/) | IS-04 v1.2 <br/> IS-05 v1.0 | IP and SDI Hybrid Waveform / Rasterizer Monitor |
| Macnica | [VIPA](https://www.macnicatech.com/products/VIPA_PCIeCard) | IS-04 v1.2 <br/> IS-05 v1.0 | General purpose Video IP Accelerator.<br/> IP Gateway,  Multi-channel capture processing and playout of ST2110 streams. |
| Matrox | [X.mio5 Q25](https://www.matrox.com/video/en/products/developer/hardware/xmio5_Q25/) <br/> [DSX LE5 Q25/D25](https://www.matrox.com/video/en/products/developer/hardware/dsx_le5_Q25_D25/) <br/> [X.mio3 IP](https://www.matrox.com/video/en/products/developer/hardware/xmio3_ip/) | IS-04 v1.2 <br/> IS-05 v1.0 | ST.2110 & ST.2022-6 Network Cards |
| Net Insight | [N600 Series](https://netinsight.net/products-and-services/nimbra/nimbra-product-specifications/#fusion-tab-nimbra600) | IS-04 v1.2 <br/> IS-05 v1.0 <br/> IS-08 v1.0 | Media transport and edge processing solution |
| Nevion | [Virtuoso MI](https://nevion.com/products/nevion-virtuoso/) | IS-04 v1.2 <br/> IS-05 v1.0 | Software defined media virtualization platform |
| Nextera Video | [NMOS Software Core](http://www.nexteravideo.com/nmos) | IS-04 v1.2 <br/> IS-05 v1.0 <br/> IS-08 v1.0 | Software core for  FPGA embedded or standalone processor |
| Pebble Beach Systems | [Dolphin](https://www.pebble.tv/products/dolphin/) | IS-04 v1.2 <br/> IS-05 v1.0 | Software-defined integrated channel solution |
| Phabrix | [Qx](https://phabrix.com/products/qx/qx-series/) <br/> [SxTAG](https://phabrix.com/products/sx/tag/) | IS-04 v1.2 <br/> IS-05 v1.0 | IP/SDI generation, analysis and monitoring |
| Riedel | [Artist 32/64/128 G2](https://www.riedel.net/en/products/intercom/artist/hardware/) <br/> [MicroN IP App](https://www.riedel.net/en/products/media-networks/mn-micron/ip-app/) | IS-04 v1.2 <br/> IS-05 v1.0 | IP intercom and gateway devices |
| Ross | [Raptor](https://www.rossvideo.com/raptor) <br/> [Newt](https://www.rossvideo.com/newt) <br/> [Iggy](https://www.rossvideo.com/products-services/infrastructure/signal-processing/iggy-madi-aes67-st2110-to-madi-audio-converter/) | IS-04 v1.2 <br/> IS-05 v1.0 | IP/SDI Gateway <br/> IP/SDI/HDMI Gateway <br/> AES67 / MADI gateway |
| Sony | [HDCU Series](https://pro.sony/en_GB/products/camera-control-unit/hdcu-3500) | IS-04 v1.2 <br/> IS-05 v1.0 | IP Ready Camera Control Units |
| Telestream | [PRISM](https://www.telestream.net/video/prism.htm) | IS-04 v1.2 <br/> IS-05 v1.0 | Hybrid IP/SDI Monitoring Instrument. |
| Vizrt | [VizEngine 3.14](https://www.vizrt.com/products/viz-engine) | IS-04 v1.2 <br/> IS-05 v1.0 | Real Time Rendering Engine |

# Incubator Participants

Alongside those working on implementations of the finished specifications, many organisations actively participate in the specification development process including workshop events. The latest list of participating companies can be found at [nmos.tv](https://nmos.tv/NMI_participants.html).