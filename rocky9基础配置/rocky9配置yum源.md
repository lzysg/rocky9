cd /etc/yum.repos.d
mkdir -p /mnt
rm -rf *
vi mnt.repo
[a]
gpgcheck=0
baseurl=file:///mnt/BaseOS
[b]
gpgcheck=0
baseurl=file:///mnt/AppStream

mount /dev/cdrom /mnt/