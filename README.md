## System Requirements

- Record audio with four microphones placed outdoors
- Sensitive microphones that can be used mainly at night
- Record all year round, summer, winter, etc.
- Interval recording should be possible, for example, 10 minutes every hour.
- Playback of the recorded sound with four speakers (or more) indoors
- Playback happening with a delay up to 12 hours
- System that stores the recordings to create an archive.

## Data Flow Diagram

![[Sound Flow Diagram.svg]]

## System Specifications

### Outdoor (€12256)

#### Enclosures (€2800)

4 [Weatherproof enclosures](https://altelix.com/altelix-indoor-enclosure-for-sonos-amp-apple-tv-amazon-echo-link-amp-bluesound-powernode-roku-ultra-wiim-pro/) with rubber gasket and clasps to seal it shut. One opening for ethernet cable and power. (€300-400 each)

Each enclosure will hold:
- 1 phantom power source
- 1 Dante AVIO Adapter
- [Uninterruptable Power Supplies](https://www.power.fi/tietotekniikka/kaapelit-ja-adapterit/virtajohdot/apc-back-ups-650va-230v-1-usb-charging-port-offline-usv-valmiustila-ilman-yhteytta-400-w/p-1171103/?gclid=Cj0KCQiAjbagBhD3ARIsANRrqEs3lxoMDNXNG2LrFunaiaKIXZy8dx0z0QbjR43ynT0dhWGo0EoRA50aAnIFEALw_wcB&gclsrc=aw.ds) (€150)

#### Microphones (€9256)
##### 4x: 
- [Sennheiser MKH 416  ](https://en-fi.sennheiser.com/short-shotgun-tube-microphone-camera-films-mkh-416-p48u3) Short Shotgun Microphone ([€999 each](https://www.verkkokauppa.com/fi/product/581521/Sennheiser-MKH-416-RF-kondensaattorimikrofoni))
- [Dante AVIO Adapters](https://www.audinate.com/products/devices/dante-avio#) ([€210 each](https://www.algamnordic.com/product/e/536979/dante-analog-input-adaptor-1-channel/))
- [Blimp Windscreen Kit](https://www.bhphotovideo.com/c/product/478488-REG/Sennheiser_BS2_Blimp_System_f_ME.html/overview) ([€900 each](https://www.bhphotovideo.com/c/product/478488-REG/Sennheiser_BS2_Blimp_System_f_ME.html/overview))
- [RAINMAN](https://remoteaudio.com/products/microphone-solutions/rainman/) ([€100 each](https://remoteaudio.com/products/microphone-solutions/rainman/))
- [Microphone Stand or Mount](https://www.thomann.de/fi/airturn_gostand.htm?glp=1&gclid=Cj0KCQiAjbagBhD3ARIsANRrqEv4iXa1DVXeNOdEqz0R7s7dXAS3hlxf7rZooBFMK0Gd-MgrkxaPVl4aAg2fEALw_wcB) (€ 75 each)
- [Phantom Power Source 48V](https://www.thomann.de/intl/millenium_pocket_phantom.htm) (€30 each)

#### Wiring (€200)

[RJ45 Cable](https://www.clasohlson.com/fi/Verkkokaapeli-CAT6-100-metri%C3%A4,-Exibel/p/39-1188?gclid=Cj0KCQiAjbagBhD3ARIsANRrqEtw-327PskOil9chkh4tmJZmynBsbkf1Vgen370-OBKVueDvYLTo0kaAjSnEALw_wcB) 300 meters ±100 (€200)

#### Indoor (€17307)

#### Audio Interface (€8500)

[Sound Devices 888 Portable Production Mixer-Recorder](https://www.sounddevices.com/guides/888/) ([€8175](https://mediatrade.fi/tuote/portable-mixer-recorder-with-8-mic-line-inputs/))

OR

[Cantar Mini 16 track ultra portable mixer-recorder with Dante Package](https://www.aaton.com/cantarmini) (€8540)


### Storage (€1107)

#### Uncompressed WAV file at 44.1 kHz and 16-bit depth
| Duration | Storage Required | 
| --- | --- | 
| 1 hour | 635 MB |
| 12 hours | 7.62 GB |
| 1 year (12 hours/day) | 2.78 TB |
| 2 years (12 hours/day) | 5.56 TB |
| 3 years (12 hours/day) | 8.82 TB |


### Cloud Storage

The system can be configured to upload directly to an existing cloud storage solution or a new one can be set up. Prices vary, maybe there is already a solution.

### Network Attached Storage (€1107)

- Four [6 TB HDD](https://www.jimms.fi/fi/Product/Show/158240/st6000vx001/seagate-6tb-skyhawk-surveillance-3-5-sisainen-kiintolevy-sata-iii-256mb) (€163 each)  
- [Synology Disk Station](https://www.verkkokauppa.com/fi/product/441110/Synology-DiskStation-DS418-verkkolevypalvelin?gclid=Cj0KCQiAjbagBhD3ARIsANRrqEvDJhRqFmNspJaj6yKjOhq40feTsm4dRBxi178310qiKCeuCgZr1_IaAq8jEALw_wcB) (€455)
- RAID 6 configuration for redundancy in case of two drive failures
- Usable capacity of approximately 12 TB (after RAID overhead)
- Backup of 10 TB of data with room for expansion

### Computer (€600 - 1200)

Two [Apple Mac Mini](https://www.apple.com/mac-mini/) (€600 each)

### Software (€1500)

[Dante Virtual Soundcard](https://www.audinate.com/products/software/dante-virtual-soundcardb) (€50 permanent license)
	This soundcard will be used to access and route the recorded audio for playback.
[Dante Application Library](https://www.audinate.com/products/manufacturer-products/dante-application-library?) (About €500-1000 Developer Fee)
	An app can be written with the Dante Application Library to schedule recording and playback intervals as well as archiving the recordings.

### Speakers (€5000)

A Dante-capable speaker setup will allow the recorded and/or archived audio to be streamed losslessly to the powered speakers. The system can easily be configured for 4 speakers in any configuration.  The examples shown offer a low aesthetic profile, which may suit the installation. Other options are available.

[Active Audio R210+](https://www.audinate.com/products/dante-enabled/active-audio/active-audio-r210) (€6802 each)

[Yamaha VXL Series P](https://usa.yamaha.com/products/proaudio/speakers/vxl_pmodel/index.html) (€1175 each)

## Total Cost: €29563


