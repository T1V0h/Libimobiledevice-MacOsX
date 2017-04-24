# Libimobiledevice-MacOsX
libimobiledevice for Mac (updated 4/23/2017)

open terminal
$ cd Libimobiledevice-MacOsX
$ ls
then choose any option listed

----------------------------------------------------------------------------------------------------------------------------

no credit towards me whatsoever.
all i did was compile a bunch of projects and took every executable file and placed them into a single folder. hope this might organize things better for you as it does with me :) 

you can find a compiled version of libimobiledevice for windows @ https://mega.nz/#!BgsCEDQK!ho1vd8J_F0tBMdvpsTGRwQlA_2DDFAHRwVNY0eIlP5E <<<< compiled by FCE 365 GeoSn0w

----------------------------------------------------------------------------------------------------------------------------

EXAMPLE 

run Terminal:

ti-vo's-mac:>thompson$ cd libimobiledevice-MacOsX

ti-vo's-mac:libimobiledevice-MacOsX>thompson$ ls

futurerestore			        idevicenotificationproxy
iDeviceReRestore	      	idevicepair
idevice_id			          ideviceprovision
ideviceactivation		      idevicerestore
idevicebackup			        idevicerestore2
idevicebackup2			      idevicescreenshot
idevicecrashreport	      idevicesyslog
idevicedate			          img4tool
idevicedebug			        iproxy
idevicedebugserverproxy		irecovery
idevicediagnostics	     	libtool
ideviceenterrecovery	   	nonceEnabler
ideviceimagemounter	     	noncestatistics
ideviceinfo		            tsschecker
idevicename

tivo-Mac:LibiMobileDevice-MacOX>thompson$ ./futurerestore

  -t, --apticket PATH		        Apticket used for restoring
  -b, --baseband PATH		        Baseband to be flashed
  -p, --baseband-manifest PATH	Buildmanifest for requesting baseband ticket
  -s, --sep PATH		            Sep to be flashed
  -m, --sep-manifest PATH	      Buildmanifest for requesting sep ticket
  -w, --wait			              keep rebooting until nonce matches APTicket
  -u, --update			            update instead of erase install
      --latest-sep		          use latest signed sep instead of manually specifying one(may cause bad restore)
      --latest-baseband		      se latest signed baseband instead of manually specifying one(may cause bad restore)
      --no-baseband		          skip checks and don't flash baseband.
                   		          WARNING: only use this for device without baseband (eg iPod or some wifi only iPads)
----------------------------------------------------------------------------------------------------------------------------

when choosing any executable file, some options must be started with "./" and some without.
for and example, "futurerestore" needs to be run like "./futurerestore" and some like "irecovery" and not "./irecovery"

----------------------------------------------------------------------------------------------------------------------------

last: if using "iDeviceReRestore" you will need to make a "shsh" folder in this same directory
