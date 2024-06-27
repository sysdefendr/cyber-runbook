![sysrunbook](https://github.com/sysdefendr/cyber-runbook/assets/71035808/32f81508-12ae-4148-8fe9-8e9ae1095226)
“Supreme excellence consists of breaking the enemy's resistance without fighting.”
― Sun Tzu, The Art of War 

Within this repository, I'll document my approach to internal, external and web application security testing. An approach comprised of techniques which I've used to compromise DA accounts internally, achieve entry from the internet and techniques I've used to successful execute XSS and SQLi.

I'm documenting these techniques, so others may take something from them to make them part of their approach. Copying the commands from this documentation is OK, but make sure to look up information about these techniques to gain a full understanding of why you're taking these actions. Enjoy and happy hacking :D

![external](https://github.com/sysdefendr/cyber-runbook/assets/71035808/4298b82d-18e9-4088-b201-1d870551c3ce)
# OSINT

### Google Dorks

#### Find files
Don't spend time manually Google dorking for files. 

- [PyMeta](https://github.com/m8sec/pymeta) (for Linux - created by [m8sec](https://www.twitter.com/m8sec))

  Install
  `git clone https:/github.com/m8sec/pymeta.git`
  
  Search Google and Bing for files and extra metadata
  `pymeta -d example.com`
  
- [PowerMeta](https://github.com/dafthack/PowerMeta) (Windows - created by [dafthack](https://twitter.com/dafthack))!
