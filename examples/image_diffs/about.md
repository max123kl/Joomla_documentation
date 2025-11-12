# What has been done

There are two raw files (both are download from Jeff's PR #77):
- create-new-folder.png (first try)
- create-new-folder2.png (new screenhot afterwards)

I cropped both files and then applied the ‘unsharp mask’ filter:
- 304-create-new-folder-en.png
- 304-create-new-folder2-en.png

### What are the differences?
* The **raw files** have a different number of pixels. Without loss of quality, the first cropped file (1447x832 px) could allow a display width of 20 inches in **a pure web environment** on a standard screen with 72 dpi. Today, however, screens with a higher pixel density are used in the majority of cases (e.g. 120 dpi).
In this case, the displayed image width is reduced to 12 inches.
For the second cropped image (2894x1652 px), the corresponding image widths are 40 and 24 inches. </br>
However, if the image is to be **prepared for printing**, 300 dpi is a generally accepted reference value. The achievable image size (without loss of quality) is now 4.8 or 9.6 inches.

**For the next test it is important that the image is displayed in 100% image size!**

* The images were processed with the ‘unsharp mask’ filter. The difference can best be seen in the text passages. See also the screenshot in my comment on PR #77.