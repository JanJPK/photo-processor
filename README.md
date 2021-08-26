# PhotoProcessor

I was frustrated with how every device has a different filename format, so I wrote a small program that organizes and renames files. Metadata is used to pull actual date taken (in case of files with different creation/modification dates) and device name.

Example:
```
GOPR3564.jpg                -> IMG--2021-12-01--21-30-00--GoPro7.jpg
GH013592.mp4                -> VID--2021-12-01--21-45-00--GoPro7.mp4
IMG_20210408_194108.JPEG    -> IMG--2021-04-08--19-41-08--Mi4C.jpg
IMG_20210408_203040.jpg     -> IMG--2021-04-08--20-30-40--A41--001.jpg
IMG_20210408_203040(1).jpg  -> IMG--2021-04-08--20-30-40--A41--002.jpg
IMG_20210408_203040(2).jpg  -> IMG--2021-04-08--20-30-40--A41--003.jpg
```

I'm redoing the program, since code is rather old and uploading it soon.
