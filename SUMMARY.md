# Table of contents

* [Offensive Security Notes](README.md)
  * [Linux/Unix](linux-unix/README.md)
    * [Checklist - PrivEsc](linux-unix/checklist-privesc/README.md)
      * [Related Links](linux-unix/checklist-privesc/related-links.md)
      * [Kernel Exploits](linux-unix/checklist-privesc/kernel-exploits.md)
      * [MYSQL](linux-unix/checklist-privesc/mysql/README.md)
        * [HEX](linux-unix/checklist-privesc/mysql/hex.md)
      * [SUID](linux-unix/checklist-privesc/suid.md)
      * [Relative Path in SUID Program](linux-unix/checklist-privesc/relative-path-in-suid-program.md)
      * [Writable /etc/passwd file](linux-unix/checklist-privesc/writable-etc-passwd-file.md)
      * [Writable script in /etc/crontab](linux-unix/checklist-privesc/writable-script-in-etc-crontab.md)
      * [Writable services](linux-unix/checklist-privesc/writable-services.md)
      * [Sudo <=1.8.14](linux-unix/checklist-privesc/sudo-less-than-1.8.14.md)
      * [Debian OpenSSL Predictable PRNG Bruteforce SSH Exploit](linux-unix/checklist-privesc/debian-openssl-predictable-prng-bruteforce-ssh-exploit.md)
      * [Docker](linux-unix/checklist-privesc/docker/README.md)
        * [Docker Escape](linux-unix/checklist-privesc/docker/docker-escape.md)
      * [davfs2](linux-unix/checklist-privesc/davfs2.md)
      * [gcore](linux-unix/checklist-privesc/gcore.md)
      * [Exiftool](linux-unix/checklist-privesc/exiftool.md)
    * [Limited Shell Escape](linux-unix/limited-shell-escape.md)
    * [Wordpress](linux-unix/wordpress.md)
    * [Apache Tomcat](linux-unix/apache-tomcat.md)
    * [Werkzeug Console PIN bypass](readme/linux-unix/werkzeug-console-pin-bypass/README.md)
      * [get\_flask\_pin.py](readme/linux-unix/werkzeug-console-pin-bypass/get\_flask\_pin.py.md)
    * [Java Object Deserialization](linux-unix/java-object-deserialization.md)
    * [Redis RCE](linux-unix/redis-rce.md)
    * [Postgres](linux-unix/postgres.md)
    * [Erlang - 4369](linux-unix/erlang-4369.md)
    * [Sendmail ClamAV](linux-unix/sendmail-clamav.md)
    * [VNC Password Decryptor](linux-unix/vnc-password-decryptor.md)
  * [Windows](windows/README.md)
    * [Checklist - PrivEsc](windows/privesc/README.md)
      * [MSSQL](windows/privesc/mssql.md)
      * [PsExec.exe](windows/privesc/psexec.exe.md)
      * [Build Exploits](windows/privesc/build-exploits.md)
      * [Unquoted Service Paths](windows/privesc/unquoted-service-paths.md)
      * [SeImpersonateToken](windows/privesc/seimpersonatetoken.md)
      * [Job with editable file](windows/privesc/job-with-editable-file.md)
      * [AlwaysInstallElevated](readme/windows/privesc/alwaysinstallelevated.md)
      * [Misconfigured LDAP](windows/privesc/misconfigured-ldap.md)
    * [Useful PS Scripts](windows/useful-ps-scripts/README.md)
      * [GetUserSPNs.ps1](windows/useful-ps-scripts/getuserspns.ps1.md)
      * [Master MDF Hash Extraction](windows/useful-ps-scripts/master-mdf-hash-extraction.md)
      * [Spray-Passwords.ps1](windows/useful-ps-scripts/spray-passwords.ps1.md)
    * [MS17-010](windows/ms17-010.md)
    * [Password Extraction](windows/password-extraction.md)
    * [Office Macro](windows/office-macro.md)
    * [Reverse Shells](readme/windows/reverse-shells.md)
    * [Shellter](readme/windows/shellter.md)
  * [Web](readme/web/README.md)
    * [SQL Injection](readme/web/sql-injection/README.md)
      * [mongodb 2.2.3](readme/web/sql-injection/mongodb-2.2.3.md)
      * [UNION BASED](readme/web/sql-injection/union-based/README.md)
        * [MSSQL](readme/web/sql-injection/union-based/mssql.md)
        * [Oracle](readme/web/sql-injection/union-based/oracle.md)
      * [ERROR BASED](readme/web/sql-injection/error-based.md)
      * [node.js](readme/web/sql-injection/node.js.md)
  * [Nmap samples](readme/nmap-samples.md)
  * [msfvenom samples](readme/msfvenom-samples.md)
  * [Enumeration](readme/enumeration/README.md)
    * [SMB](readme/enumeration/smb.md)
    * [RPC](readme/enumeration/rpc.md)
    * [LDAP](readme/enumeration/ldap.md)
  * [Buffer Overflow](readme/buffer-overflow/README.md)
    * [mona](readme/buffer-overflow/mona.md)
    * [fuzzer.py](readme/buffer-overflow/fuzzer.py.md)
    * [exploit.py](readme/buffer-overflow/exploit.py.md)
    * [bytearray.py](readme/buffer-overflow/bytearray.py.md)
    * [pattern\_offset.rb](readme/buffer-overflow/pattern\_offset.rb.md)
    * [pattern\_create.rb](readme/buffer-overflow/pattern\_create.rb.md)
  * [Password Cracking](readme/password-cracking.md)
  * [File Download](readme/file-download/README.md)
    * [FTP](readme/file-download/ftp.md)
  * [Port Forwarding](readme/port-forwarding/README.md)
    * [Dynamic Forwarding](readme/port-forwarding/dynamic-forwarding.md)
  * [Useful links](readme/useful-links.md)
* [PortSwigger Academy](portswigger-academy/README.md)
  * [Server-side topics](portswigger-academy/server-side-topics/README.md)
    * [Authentication vulnerabilities](portswigger-academy/server-side-topics/authentication-vulnerabilities.md)
    * [OS Command Injection](portswigger-academy/server-side-topics/os-command-injection.md)
    * [File Path Traversal](portswigger-academy/server-side-topics/file-path-traversal.md)
    * [Business logic vulnerabilities](portswigger-academy/server-side-topics/business-logic-vulnerabilities.md)
    * [Information disclosure vulnerabilities](portswigger-academy/server-side-topics/information-disclosure-vulnerabilities.md)
    * [Access control vulnerabilities and privilege escalation](portswigger-academy/server-side-topics/access-control-vulnerabilities-and-privilege-escalation.md)
    * [File upload vulnerabilities](portswigger-academy/server-side-topics/file-upload-vulnerabilities.md)
    * [Server-side request forgery (SSRF)](portswigger-academy/server-side-topics/server-side-request-forgery-ssrf.md)
    * [XML external entity (XXE) injection](portswigger-academy/server-side-topics/xml-external-entity-xxe-injection.md)
  * [Client-side topics](portswigger-academy/client-side-topics/README.md)
    * [Cross-site scripting](portswigger-academy/client-side-topics/cross-site-scripting.md)
    * [Cross-origin resource sharing (CORS)](portswigger-academy/client-side-topics/cross-origin-resource-sharing-cors.md)
    * [Cross-site request forgery (CSRF)](portswigger-academy/client-side-topics/cross-site-request-forgery-csrf.md)
    * [Clickjacking (UI redressing)](portswigger-academy/client-side-topics/clickjacking-ui-redressing.md)
    * [DOM-based vulnerabilities](portswigger-academy/client-side-topics/dom-based-vulnerabilities.md)
    * [Testing for WebSockets security vulnerabilities](portswigger-academy/client-side-topics/testing-for-websockets-security-vulnerabilities.md)
  * [Advanced topics](portswigger-academy/advanced-topics/README.md)
    * [Insecure deserialization](portswigger-academy/advanced-topics/insecure-deserialization.md)
    * [Server-side template injection](portswigger-academy/advanced-topics/server-side-template-injection.md)
    * [Web cache poisoning](portswigger-academy/advanced-topics/web-cache-poisoning.md)
    * [HTTP Host header attacks](portswigger-academy/advanced-topics/http-host-header-attacks.md)
    * [HTTP request smuggling](portswigger-academy/advanced-topics/http-request-smuggling.md)
    * [OAuth 2.0 authentication vulnerabilities](portswigger-academy/advanced-topics/oauth-2.0-authentication-vulnerabilities.md)
* [Walkthroughs](walkthroughs/README.md)
  * [PG Practice](walkthroughs/pg-practice/README.md)
    * [Linux](walkthroughs/pg-practice/linux/README.md)
      * [WARM UP](walkthroughs/pg-practice/linux/warm-up/README.md)
        * [Bratarina](walkthroughs/pg-practice/linux/warm-up/bratarina.md)
        * [ClamAV](walkthroughs/pg-practice/linux/warm-up/clamav.md)
        * [Exfiltrated](walkthroughs/pg-practice/linux/warm-up/exfiltrated.md)
        * [Hawat](walkthroughs/pg-practice/linux/warm-up/hawat.md)
        * [Interface](walkthroughs/pg-practice/linux/warm-up/interface.md)
        * [Muddy](walkthroughs/pg-practice/linux/warm-up/muddy.md)
        * [Pebbles](walkthroughs/pg-practice/linux/warm-up/pebbles.md)
        * [Twiggy](walkthroughs/pg-practice/linux/warm-up/twiggy.md)
        * [Wombo](walkthroughs/pg-practice/linux/warm-up/wombo.md)
      * [GET TO WORK](walkthroughs/pg-practice/linux/get-to-work/README.md)
        * [Banzai](walkthroughs/pg-practice/linux/get-to-work/banzai.md)
        * [Cassios](walkthroughs/pg-practice/linux/get-to-work/cassios.md)
        * [Dibble](walkthroughs/pg-practice/linux/get-to-work/dibble.md)
        * [Fail](walkthroughs/pg-practice/linux/get-to-work/fail.md)
        * [G00g](walkthroughs/pg-practice/linux/get-to-work/g00g.md)
        * [Hetemit](walkthroughs/pg-practice/linux/get-to-work/hetemit.md)
        * [Hunit](walkthroughs/pg-practice/linux/get-to-work/hunit.md)
        * [Pelican](walkthroughs/pg-practice/linux/get-to-work/pelican.md)
        * [Maria](walkthroughs/pg-practice/linux/get-to-work/maria.md)
        * [Nappa](walkthroughs/pg-practice/linux/get-to-work/nappa.md)
        * [Nibbels](walkthroughs/pg-practice/linux/get-to-work/nibbels.md)
        * [Nukem](walkthroughs/pg-practice/linux/get-to-work/nukem.md)
        * [Payday](walkthroughs/pg-practice/linux/get-to-work/payday.md)
        * [Readys](walkthroughs/pg-practice/linux/get-to-work/readys.md)
        * [Reconstruction](walkthroughs/pg-practice/linux/get-to-work/reconstruction.md)
        * [Roquefort](walkthroughs/pg-practice/linux/get-to-work/roquefort.md)
        * [Snookums](walkthroughs/pg-practice/linux/get-to-work/snookums.md)
        * [Sorcerer](walkthroughs/pg-practice/linux/get-to-work/sorcerer.md)
        * [Splodge](walkthroughs/pg-practice/linux/get-to-work/splodge.md)
        * [Sybaris](walkthroughs/pg-practice/linux/get-to-work/sybaris.md)
        * [UC404](walkthroughs/pg-practice/linux/get-to-work/uc404.md)
        * [Walla](walkthroughs/pg-practice/linux/get-to-work/walla.md)
        * [Webcal](walkthroughs/pg-practice/linux/get-to-work/webcal.md)
        * [XposedAPI](walkthroughs/pg-practice/linux/get-to-work/xposedapi.md)
        * [ZenPhoto](walkthroughs/pg-practice/linux/get-to-work/zenphoto.md)
        * [Zino](walkthroughs/pg-practice/linux/get-to-work/zino.md)
        * [QuackerJack](walkthroughs/pg-practice/linux/get-to-work/quackerjack.md)
      * [TRY HARDER](walkthroughs/pg-practice/linux/try-harder/README.md)
        * [Clyde](walkthroughs/pg-practice/linux/try-harder/clyde.md)
        * [Peppo](walkthroughs/pg-practice/linux/try-harder/peppo.md)
        * [Sirol](walkthroughs/pg-practice/linux/try-harder/sirol.md)
    * [Windows](walkthroughs/pg-practice/windows/README.md)
      * [WARM UP](walkthroughs/pg-practice/windows/warm-up/README.md)
        * [Algernon](walkthroughs/pg-practice/windows/warm-up/algernon.md)
        * [Compromised](walkthroughs/pg-practice/windows/warm-up/compromised.md)
        * [Helpdesk](walkthroughs/pg-practice/windows/warm-up/helpdesk.md)
        * [Internal](walkthroughs/pg-practice/windows/warm-up/internal.md)
        * [Kevin](walkthroughs/pg-practice/windows/warm-up/kevin.md)
        * [Metallus](walkthroughs/pg-practice/windows/warm-up/metallus.md)
      * [GET TO WORK](walkthroughs/pg-practice/windows/get-to-work/README.md)
        * [AuthBy](walkthroughs/pg-practice/windows/get-to-work/authby.md)
        * [Billyboss](walkthroughs/pg-practice/windows/get-to-work/billyboss.md)
        * [Craft](walkthroughs/pg-practice/windows/get-to-work/craft.md)
        * [Fish](walkthroughs/pg-practice/windows/get-to-work/fish.md)
        * [Hepet](walkthroughs/pg-practice/windows/get-to-work/hepet.md)
        * [Hutch](walkthroughs/pg-practice/windows/get-to-work/hutch.md)
        * [Jacko](walkthroughs/pg-practice/windows/get-to-work/jacko.md)
        * [Medjed](walkthroughs/pg-practice/windows/get-to-work/medjed.md)
        * [Nickel](walkthroughs/pg-practice/windows/get-to-work/nickel.md)
        * [Shenzi](walkthroughs/pg-practice/windows/get-to-work/shenzi.md)
        * [Slort](walkthroughs/pg-practice/windows/get-to-work/slort.md)
        * [UT99](walkthroughs/pg-practice/windows/get-to-work/ut99.md)
      * [TRY HARDER](walkthroughs/pg-practice/windows/try-harder/README.md)
        * [Heist](walkthroughs/pg-practice/windows/try-harder/heist.md)
        * [Meathead](walkthroughs/pg-practice/windows/try-harder/meathead.md)
        * [Vault](walkthroughs/pg-practice/windows/try-harder/vault.md)
    * [Template](walkthroughs/pg-practice/template.md)
* [About the author](offensive-security-notes/about-the-author.md)
