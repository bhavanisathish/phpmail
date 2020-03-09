# phpmail
changes in php.ini
[mail function]
; XAMPP: Comment out this if you want to work with an SMTP Server like Mercury
SMTP = smtp.gmail.com
smtp_port = 25    //465

; For Win32 only.
; http://php.net/sendmail-from
sendmail_from = phpflow@gmail.com
sendmail_path = "\"D:\xampp\sendmail\sendmail.exe\" -t"

Changes in sendmail

[mail function]
smtp_server=smtp.gmail.com
smtp_port=25    //465
auth_username=yourmail@gmail.com
auth_password=XXXXXXX
force_sender=yourmail@gmail.com
