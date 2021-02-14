# UMS Interface
This program allows you to chose a block device or disk image as a 'disk',and communicate with PC through usb mass storage (just as usb disk do).Root permission is needed.

 * [download latest version](https://raw.githubusercontent.com/outofmemo/UMS-Interface/master/update/app-release.apk)

![](https://raw.githubusercontent.com/outofmemo/UMS-Interface/master/screenshots/p1.png)

## introduction
<h4 style="color:#0F0">quick start</h4>
<b style="color:#009;">usb connection:</b>
set current data source as U disk<br/>
<b style="color:#009;">mount to:</b>
mount current data source<br/>
<b style="color:#009;">quick create:</b>
create a image with the given size,format as vfat,mount it,and use it as U disk<br/><br/>
<b style="color:#900;">
    *If the file you just copied can not be displayed immediately, try click 'close'/'launch' and 'umount'/'mount' continuously.</b><br/>
<h4 style="color:#0F0">U disk</h4>
<b style="color:#009;">block device:</b>
Representing a disk or partition, usually located in /dev/block or /dev.<br/>
<b style="color:#009;">image file:</b>
 Usually named as *.img .An image file with a file system can be mounted like normal disk.<br/>
<b style="color:#009;">data source:</b>
source of the data in U disk,an image file or a block device is available .<br/>
<b style="color:#009;">config path:</b>
path this software relied.Like  /sys/class/android_usb/android0 or  /sys/devices/virtual/android_usb/android0.<br/>
<b style="color:#009;">readonly:</b>may have no effect for some phone
<br/>
<h4 style="color:#0F0">mount</h4>
<b style="color:#009;">data source:</b>
source of the data to mount,an image file or a block device is available .<br/>
<b style="color:#009;">mount point:</b>
chose a directory to mount.<br/>
<b style="color:#009;">file system:</b>
will be automatically chose if not specified.<br/>
<b style="color:#009;">mask:</b>
used to set dmask and fmask.<br/><br/>
<b style="color:#900;">
    *You must disable 'mount namespace separation' in SuperSu, or it won't work.</b><br/>
<h4 style="color:#0F0">create image</h4>
<b style="color:#009;">format:</b>
create file system for image file.<br/><br/>
It can be used as a boot disk for PC when select a solved image.<br/>

## screen shots
![](https://raw.githubusercontent.com/outofmemo/UMS-Interface/master/screenshots/p2.png)

![](https://raw.githubusercontent.com/outofmemo/UMS-Interface/master/screenshots/p3.png)

![](https://raw.githubusercontent.com/outofmemo/UMS-Interface/master/screenshots/p4.png)

![](https://raw.githubusercontent.com/outofmemo/UMS-Interface/master/screenshots/p5.png)

## see more
 * [android6.0.1 usb mass storage](http://blog.csdn.net/outofmemo/article/details/53348552)
 * [coolapk](http://www.coolapk.com/apk/com.sjj.echo.umsinterface)
 * [boot disk image(PE),password: er8y](http://pan.baidu.com/s/1gfa9GbD)

## ���
<h4 style="color:#0F0">�������</h4>
<b style="color:#009;">U������:</b>
����ǰ����Դ��ΪU��,���'��ֹ'ȡ�� <br/>
<b style="color:#009;">���ص�:</b>
�Զ����ص�ǰ����Դ,���'��ֹ'ȡ��<br/>
<b style="color:#009;">һ������:</b>
�������,����ָ����С�����ļ�,��ʽ��vfat,���������,ͬʱ��ΪU��ʹ��<br/><br/>
<b style="color:#900;">  
    *����ո��Ƶ��ļ��޷�������ʾ,�����������'�ر�'/'����','ж��'/'����'.</b><br/>
<h4 style="color:#0F0">U��</h4>
<b style="color:#009;">���豸:</b>
����һ���洢�������,ͨ��λ��/dev/block �� /dev.<br/>
<b style="color:#009;">�����ļ�:</b>
ͨ������Ϊ*.img .һ���ں��ļ�ϵͳ�ľ����ļ��ɱ�����,����ͨ�洢��һ��ʹ��.<br/>
<b style="color:#009;">����Դ:</b>
��ѡ���⾵���ļ�����豸.��ѡ����豸,���������,�������ݶ�ʧ.<br/>
<b style="color:#009;">����Ŀ¼:</b>
ͨ�����Զ�Ѱ��,�ɵ��"ѡ��"���ֶ�ָ��.�����ֻ��ϴ�Ŀ¼Ϊ  /sys/class/android_usb/android0 ��  /sys/devices/virtual/android_usb/android0.<br/>
<b style="color:#009;">ֻ��:</b>
U��ֻ��,�ܶ��ֻ��Ͽ�����Ч<br/><br/>
<b style="color:#900;">
    *�����ں�ԭ��,ʹ������оƬ��һЩ�ֻ�ʹ�ô˹��ܻᱻ��Ϊ�ãġ��ңϣ�</b><br/>
<h4 style="color:#0F0">����</h4>
<b style="color:#009;">����Դ:</b>
����ָ���ں��ļ�ϵͳ�ľ����ļ�����豸.<br/>
<b style="color:#009;">���ص�:</b>
ָ��һ��Ŀ¼,"����"�е��ļ��ᱻ�ŵ�����.<br/>
<b style="color:#009;">�ļ�ϵͳ:</b>
����,���Զ��ж�.<br/>
<b style="color:#009;">Ȩ������:</b>
���ڹ���vfatʱָ���ļ�����Ȩ��.<br/><br/>
<b style="color:#900;"> 
    *SuperSU �е�"���ؿռ����"���ܻ�Ӱ�챾����,�ɳ�����SuperSu��ȡ��.</b><br/>
<h4 style="color:#0F0">��������</h4>
<b style="color:#009;">��ʽ��:</b>
Ϊ�ļ������ļ�ϵͳ,�Ա���������.<br/>
<b style="color:#900;"></b>
�ɽ������̵Ĵ��̾�����ΪU�̵�����Դ,������ɷ���Ľ��ֻ���Ϊ����������.<br/>
 
## ָ��
 * [��׿4.4���ϰ汾���ֻ���ΪU��ʹ��](http://jingyan.baidu.com/article/a3f121e4be8e7ffc9052bb19.html)
