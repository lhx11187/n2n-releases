
�Ѿ���openwrt-18.06.2-x86-64��֤ͨ�������۶����øð汾ǰ���openwrt_x64�澵��


--n2n������Դopenwrt_x64��leno��
  20190213-0032-openwrt-x64-R9.1.1-squashfs.img


--ȱ��libcrypto.so.1.0.0��
  ���Ƶ�openwrt-18.06.2-x86-64-combined-ext4.img����edge������ʾȱ��libcrypto.so.1.0.0�⣬����leno����������




--ȱtun�豸
  ����edge������ʾERROR: ioctl() [No such file or directory][2]��

����
opkg update��
opkg list |grep kmod |grep tunȷ��tun����
opkg install kmod-tun
insmod /lib/modules/4.14.95/tun.ko

----- by QQȺ�� ����� 78599998*
