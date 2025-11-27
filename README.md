# ExifTool
---
The objective of this activity is to study and understand how files (specifically images) can carry hidden information (metadata) and how command-line tools can be used to protect privacy and prevent unnecessary data exposure.

---
## Tools

* ExifTool
* Kali Linux

---

## Installing ExifTool
ExifTool is a cross-platform tool. Installation varies depending on the operating system:

```
sudo apt update
sudo apt install libimage-exiftool-perl
```

---

## Practical Steps Perfomed

```
exiftool image.jpeg
```

```
exiftool -all= image.jpeg
```

```
exiftool image.jpeg
```

**Expected Result:** The output should now show only minimal, essential JPEG format information, without the sensitive data (like camera name, author, or GPS coordinates) that was present in the first step. This confirmation ensures the cleanup was successful.
