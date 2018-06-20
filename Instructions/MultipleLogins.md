# Multiple logins

- You can simply create the public rsa key on each computer you intend to use for accessing the NMTUET server and send those keys to us. We are happy to add them into the NMTUET server. :smiley:
- If you can not do so due to your own reasons, you have to use your private key. Check the file id_rsa in your .ssh folder and use this command to login: `ssh -i /your_path_to_the_id_rsa_file/id_rsa -p 2222 your_account@nmtuet.ddns.net`

    For example: _ssh -i /home/hien-v/.ssh/id_rsa -p 2222 hien-v@nmtuet.ddns.net_
    Remember that using private key is **DANGEROUS** for security issues. We **DONOT** recommend you to store same private key in many computers. You can simply bring your private key to the computers you intend to use for accessing the NMTUET server via the **USB drive** :simley:
