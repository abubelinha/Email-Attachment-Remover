# Links Email Parsing

- https://tools.ietf.org/html/rfc2060.html # IMAP Protocol
- https://docs.python.org/3.6/library/imaplib.html
- https://docs.python.org/3.6/library/email.message.html
- https://yuji.wordpress.com/2011/06/22/python-imaplib-imap-example-with-gmail/
- https://gist.github.com/baali/2633554
- http://stackoverflow.com/questions/32885661/python-imap-locate-emails-with-attachments-in-inbox-and-move-them-to-a-folder
- http://code.activestate.com/recipes/302086-strip-attachments-from-an-email-message/
- https://github.com/izderadicka/imap_detach/blob/master/src/imap_detach/mail_info.py
- http://code.activestate.com/recipes/498189-imap-mail-server-attachment-handler/
- http://bruno.im/2009/dec/18/decoding-emails-python/

# Usage

- Use Python 3
- Adjust config.ini sample, rename to config.ini and copy into env folder
	- Set IMAP mailbox login configuration
	- Decide to run single folder or all folders
	- Activate test mode with enhanced logging if needed
- Run email_attachment_remover.py

# Hint

Run it on a fast internet connection as it has to download all mails and attachments and partly upload it again

# Related projects (Gmail attachments removal):

https://support.google.com/mail/thread/33445561/how-can-i-detach-attachments-in-gmail
https://www.broobles.com/imapsize/imap-delete-attachments.php

https://www.reddit.com/r/GMail/comments/lygc56/imapsize_alternative/
Java cmd line: https://github.com/vadimkim/imapsize

https://www.quora.com/Is-there-an-alternative-to-IMAP-size-that-works-with-Gmail-IMAPsize-has-the-unique-feature-where-it-can-edit-emails-via-IMAP-and-it-will-keep-the-email-and-headers-but-remove-the-file-attachments-it-leaves-a-message
Python cmd line: http://lacinato.com/cm/blog/27-imapsizereducer
http://lacinato.com/pub/email/imap_size_reducer.py
https://gist.github.com/paloha/a5dc2843a342b1f8b814c92a098ca2a2
