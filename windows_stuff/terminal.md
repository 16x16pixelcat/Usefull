# TOS

[fixes](#fixes)

[winget](#winget)

## fixes

Scans for and repairs corrupted system files

```
sfc /scannow
```

---

Fix Windows Master Record

```
bootrec /fixmbr
```

---

Clears your computer's DNS Resolver Cache

```
ipconfig /flushdns
```

---

Check and Fix Disk Errors

```
chkdsk /f C:
```

---

scans and repairs system image files

```
DISM /Online /Cleanup-Image /RestoreHealth
```

## Winget

search for packages (apps)

```
winget search
```

install and uninstall apps

```
winget install\uninstall
```

---