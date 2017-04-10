# Backlight Driver

Linux driver for Nimbusoft Vulcan keyboard backlight.

## Install

```
git clone https://github.com/nimbusoftltd/backlight-driver /usr/src/nimbusoft-0.1
dkms install nimbusoft/0.1
```

## Testing

```
modprobe nimbusoft
```

## Loading at boot

```
echo nimbusoft >> /etc/modules
```
