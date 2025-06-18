# openwrt-x86-64-generic-ext4-combined-efi

目标平台 X86/64</br>
内核版本：6.1.141</br>
默认IP地址：192.168.1.235</br>
账号：root  密码：password</br>
文本编辑器，我选择的是nano-full（纯粹个人习惯）</br>

针对ext4系统烧录后，修改设置不能保存的问题，</br>
烧录到实体机上，插电进入后，</br>
先通过SSH链接openwrt，</br>
然后输入：mount -o remount rw /</br>
以上命令是 可以重新挂载根文件系统为可读写模式。</br>

![image](https://github.com/user-attachments/assets/02ad7bbb-8539-4131-ac65-108122775675)
![image](https://github.com/user-attachments/assets/64fa337b-b62b-476f-8956-e1f19ed0a419)
![image](https://github.com/user-attachments/assets/c0de59b7-f733-4b0b-85af-dba08020cc0d)
![image](https://github.com/user-attachments/assets/03560803-a020-49c3-9530-cc82b185c2ca)
