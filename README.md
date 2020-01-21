# My CVEs
List of my CVE published

* **CVE-2019-19589** The Lever PDF Embedder plugin 4.4 for WordPress does not block the distribution of polyglot PDF documents that are valid JAR archives. https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-19589

* **CVE-2019-19889** An issue was discovered on Humax Wireless Voice Gateway HGB10R-2 20160817_1855 devices. The attacker can discover admin credentials in the backup file, aka backupsettings.conf. https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-19889

* **CVE-2019-19890** An issue was discovered on Humax Wireless Voice Gateway HGB10R-2 20160817_1855 devices. Admin credentials are sent over cleartext HTTP. https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-19890

* **CVE-2019-19916** In Midori Browser 0.5.11 (on Windows 10), Content Security Policy (CSP) is not applied correctly to all parts of multipart content sent with the multipart/x-mixed-replace MIME type. This could result in script running where CSP should have blocked it, allowing for cross-site scripting (XSS) and other attacks when the product renders the content as HTML. Remediating this would also need to consider the polyglot case, e.g., a file that is a valid GIF image and also valid JavaScript. https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-19916

* **CVE-2019-20203** The Authorized Addresses feature in the Postie plugin 1.9.40 for WordPress allows remote attackers to publish posts by spoofing the From information of an email message. https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-20203

* **CVE-2019-20204** The Postie plugin 1.9.40 for WordPress allows XSS, as demonstrated by a certain payload with jaVasCript:/* at the beginning and a crafted SVG element. https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-20204

* **CVE-2020-7241** The WP Database Backup plugin through 5.5 for WordPress stores downloads by default locally in the directory wp-content/uploads/db-backup/. This might allow attackers to read ZIP archives by guessing random ID numbers, guessing date strings with a 2020_{0..1}{0..2}_{0..3}{0..9} format, guessing UNIX timestamps, and making HTTPS requests with the complete guessed URL. https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-7241

* In Internet Explorer 11, Content Security Policy (CSP) is not applied correctly to all parts of multipart content sent with the multipart/x-mixed-replace MIME type. This could result in script running where CSP should have blocked it, allowing for cross-site scripting (XSS) and other attacks when the product renders the content as HTML. Remediating this would also need to consider the polyglot case, e.g., a file that is a valid GIF image and also valid JavaScript. [awaiting]

* Bypass the Wordpress 5.3.1 Upload restrictions by using polymorphic files. [awaiting]
