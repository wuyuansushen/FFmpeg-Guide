# FFmpeg-Guide
Guide of FFmpeg on CentOS 8

## 1. Install dependencies

Install epel-release and rpmfusion, enable PowerTools repo
```
dnf install -y epel-release
dnf install --nogpgcheck https://mirrors.rpmfusion.org/free/el/rpmfusion-free-release-8.noarch.rpm https://mirrors.rpmfusion.org/nonfree/el/rpmfusion-nonfree-release-8.noarch.rpm
dnf config-manager --enable PowerTools
```

## 2.Install ffmpeg

```
dnf install -y ffmpeg
```
