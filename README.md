# Ubuntu Samba Server for macOS Time Machine Backups
This is a collaborative post to make examples and easily create a  time machine disk for your macOS.

Turn an Ubuntu machine into a network backup server for macOS Time Machine using this Samba configuration.  
**Tested on macOS Catalina (10.15.7) and Ubuntu 22.04 LTS.**  

## Features  
- Simple setup for macOS Catalina users.  
- Secure user authentication.  
- Customizable backup size limits.  

## Compatibility Notes  
- **macOS**: Officially tested on **Catalina (10.15.7)**. Untested on newer versions (Ventura/Sonoma), but may work.  
- **Ubuntu**: Verified on **22.04 LTS (Jammy Jellyfish)**.  
- **Samba**: Requires `vfs_fruit` module (included in Ubuntu 22.04’s default Samba).  

## Prerequisites  
- Ubuntu 22.04 LTS (Jammy Jellyfish).  
- Samba installed (`sudo apt install samba`).  
- macOS Catalina (or later) on the same network.  

##  FAQs  
**Q: Does this work on macOS Ventura/Sonoma?**  
A: This setup was tested **only on Catalina (10.15.7)**. Newer macOS versions may work, but adjustments might be needed. Contributions welcome!  

**Q: What Ubuntu versions are supported?**  
A: Tested on **22.04 LTS (Jammy)**. For newer releases (e.g., 24.04), check Samba’s `vfs_fruit` compatibility.  

---
