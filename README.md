# UltraStar-WorldParty-DepLibs
## Description
Because the latest stable version of Ultrastar World Party [21.04](https://github.com/ultrastares/ultrastar-worldparty/releases/tag/21.02) [released in Feb 7, 2021] uses a pretty old version of ffmpeg library which nowdays is only avaliable via oldstable branch from Debian 12 Bookworm (which deprection is quite near) and I don't like snaps (and they are Ubuntu-centric).  
I am going to upload the depedencies required for run USWP, they are gathered from my current installation of Debian 12 and tested running in a Gentoo in stable mode (in 2024/12/14)
Keep in mind, These are only x86_64 Binaries Compatible and they are using the .deb build version.  
<https://github.com/ultrastares/ultrastar-worldparty/releases/download/21.02/ultrastar-worldparty_21.02-1_amd64.deb>
## How To Use
    - just run `LD_LIBRARY_PATH=$PATH_OF_THE_DOWNLOAD_LIBS:$LD_LIBRARY_PATH $ROUTE_OF_THE_BINARY/ultrastar-worldparty`
## Improvements
I think It doesn't worth because the new release is relatibly close <https://ultrastar-es.org/foro/viewtopic.php?p=80262#p80262> & <https://github.com/ultrastares/ultrastar-worldparty/commits/alfa/>
but It would be ideal, make a build of the same version of ffmpeg without some unused dependencies libraries like "libbluray.so.2", AV1 and maybe x265
FYI: It's ffmpeg 5.1.6-0

