---
title: Running ArcGIS Pro on a Mac
category: ArcGIS
order: 5
---

> Note: ArcGIS applications require a licensed installation of Microsoft Windows.

> Note: Installing Windows on macOS using Boot Camp requires a Mac with an
> Intel processor.

> Note: Running ArcGIS software on [Apple silicon][10] may introduce stability,
> feature, and performance degradation and is not recommended until Microsoft
> Windows is fully supported on Apple's M-series and later processors.

Both ArcGIS Desktop and [ArcGIS Pro][9] require Microsoft Windows. Running
ArcGIS software on a Mac is made possible by installing Windows using one of
two methods:

1. **Install Windows natively on your Mac's hard drive using Apple's [Boot
   Camp][1].** This option involves creating a dual-boot environment on your Mac
   which will require choosing which operating system you want to use when you
   start you computer. Switching from one operating system to another will
   require restarting your Mac.

   See Apple's [Install Windows 10 on your Mac with Boot Camp Assistant][2] to
   get started.

2. **Install Windows as a virtual machine on your Mac using a third-party
   application such as [VMware Fusion][3], [Parallels][4], or [Oracle VM
   VirtualBox][5].** This option enables running Windows inside your Mac's host
   operating system without the need to restart your Mac to boot into Windows.
   Please reference the [minimum system requirements][8] for installing ArcGIS
   Pro in a virtual machine on macOS.

   See ESRI's [Run ArcGIS Pro on a Mac][7] to get started.

Please note that ESRI does NOT support running ArcGIS on a Mac, and that you
can only use ArcGIS on a Mac using one of the Windows platform installation
options described above.

If you have an incompatible Apple device and are unable to run Windows
using either of steps outlined above, consider using [OWLab][8], a cloud-hosted
Windows Virtual Desktop, to access ArcGIS Pro.



[1]: http://www.apple.com/support/bootcamp/
[2]: https://support.apple.com/en-us/HT201468
[3]: http://www.vmware.com/products/fusion/
[4]: http://www.parallels.com/products/desktop/
[5]: https://www.oracle.com/virtualization/virtualbox/
[6]: https://www.esri.com/arcgis-blog/products/3d-gis/3d-gis/arcgis-pro-in-mac-os-x/
[7]: https://pro.arcgis.com/en/pro-app/latest/get-started/run-pro-on-a-mac.htm
[8]: https://cla.temple.edu/tech-notes/remote-access/owlab/
[9]: https://cla.temple.edu/tech-notes/arcgis/arcgis-pro/
[10]: https://en.wikipedia.org/wiki/Apple_silicon
