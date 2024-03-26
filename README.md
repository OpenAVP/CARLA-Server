# CARLA Server

> The original README for CARLA is stored at: [./CARLA_README.md](./CARLA_README.md)

This repository is used to store optimized and modified versions of [CARLA](https://carla.org/) for the [OpenAVP project](https://github.com/OpenAVP). 

For usage issues, please refer to the [official CARLA documentation](https://carla.readthedocs.io/en/latest/).

<img width="1814" alt="image" src="https://github.com/OpenAVP/CARLA-Server/assets/51916543/45abdd3c-3c6b-4920-93a3-42c430322b7c">


> [!IMPORTANT]  
> Matching Content Version: **AVP3.0**
> 
> Content Repo: [https://github.com/OpenAVP/CARAL-Server-Content](https://github.com/OpenAVP/CARAL-Server-Content)

### RELEASE

- **0.9.15-B4-AVP3.0**
    - Windows - Download -> [Dropbox](https://www.dropbox.com/scl/fi/ffoltedl8bsh53cefodia/CARLA-Server-0.9.15-B4-AVP3.0-Win64.zip?rlkey=0hvb35vgneegp2r6xsch0fhi7&dl=0) | [BaiduNetDisk](https://pan.baidu.com/s/1OxBo3x_6F80tewSuraShkQ?pwd=ixn3) - 2023/03/26
    - Linux - Download -> [Dropbox](https://www.dropbox.com/scl/fi/pncy6p4tls7n72bpkiswu/CARLA-Server-0.9.15-B4-AVP3.0-Linux64.tar.gz?rlkey=pumx1e73ftpf5bwyk1s5wvc6w&dl=0) | [BaiduNetDisk](https://pan.baidu.com/s/1Fr4kkAzKbPR2RnGuwtWdRw?pwd=ntfs) - 2023/03/26

- **0.9.15-B3-AVP2.2**
    - Windows - Download -> [Dropbox](https://www.dropbox.com/scl/fi/tk67jt86yu41pg5ohtemq/CARLA-Server-0.9.15-B2-AVP2.1-WIN64.zip?rlkey=zg787j2rdvo1w4yi04xumz8lk&dl=0) | [BaiduNetDisk](https://pan.baidu.com/s/172gPbsxXxg66ie6ql14jqQ?pwd=gt9m) - 2023/03/04
    - Linux - Download -> [Dropbox](https://www.dropbox.com/scl/fi/gyviugsl3xl2pyaq89qna/CARLA-Server-0.9.15-B3-AVP2.2-Linux64.tar.gz?rlkey=sutj84f2sn62qdhv6gbcqxr0n&dl=0) | [BaiduNetDisk](https://pan.baidu.com/s/1ai1r0-JosxbGvP0OLKF95g?pwd=fcnq) - 2023/03/24

- **0.9.15-B2-AVP2.1**
    - Windows - Download -> [Dropbox](https://www.dropbox.com/scl/fi/tk67jt86yu41pg5ohtemq/CARLA-Server-0.9.15-AVP2.1-WIN64.zip?rlkey=zg787j2rdvo1w4yi04xumz8lk&dl=0) | [BaiduNetDisk](https://pan.baidu.com/s/1vQ2PwvtS5B28QrTYBFIGzQ?pwd=kgi5) - 2023/02/29
    - Linux - _Not Supported_

### CHANGELOG

- **0.9.15-B3-AVP3.0**
    - Use AVP3.0 content package ([details](https://github.com/OpenAVP/CARAL-Server-Content/releases/tag/0.9.15-AVP3.0))
      > Add custom vehicle `vehicle.byd.qinpro` about BYD QinPro EV (SUSTech Modified)
      > Update the shadows on the ceiling in the `SUSTech_COE_ParkingLot` scene
      > Update the ground texture in the `Playground` scene, now is 1m x 1m checkerboard

- **0.9.15-B3-AVP2.2**
    - Use AVP2.2 content package ([details](https://github.com/OpenAVP/CARAL-Server-Content/releases/tag/0.9.15-AVP2.2))
    - Fix collider bug in AVP2.1 content package
    - Update parking area color to be more visible, use `111, 246, 162` now
    - Update carla version tag to mach this release

- **0.9.15-B2-AVP2.1**
    - Use AVP2.1 content package ([details](https://github.com/OpenAVP/CARAL-Server-Content/releases/tag/0.9.15-AVP2.1))
    - Adding map `SUSTech_COE_ParkingLot`
    - Adding map `Playground`
    - Adding semantic segmentation lables `Parking Area` and `Parking Lane`


