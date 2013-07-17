ssl-certificate-tools
=====================

OpenSSL wrappers for easy and convenient certificate management

certtool
========

Tool to manage a certificate store

	Client Creation
	---------------
	newclient    (creates a new client directory)

	Certificates Creation & Renewal
	-------------------------------
	genkey       (generate a new key)
	genreq       (generate a new request for an existing key)

	Certificate Verification
	------------------------
	certinfo     (show certificate infos)
	verify       (checks certificate validity, match, and displays expiration info)
	verifycert   (verifies a certificate against system CA + chain)
	verifymatch  (check that private key + certificate + request are matching)
	expiration   (show certificate validity dates)

	Certificates alternate exports formats
	--------------------------------------
	pkcs12       (exports key+crt to pkcs12 format, .p12 extension)
	p12info      (show certificate .p12 bundle content)
	pfx          (exports key+crt to pkcs12 format, .pfx extension, for IIS)
	pfxinfo      (show certificate .pfx bundle content)

catool
======

Tool to manage a simple local certification authority

	Certificates Creation & Renewal
	-------------------------------
	gencert      (generate certificate and signs it with CA)
	renewcert    (re-generate a certificate for an existing key/req)
	showcert     (show certificate infos)

	Certificates alternate exports formats
	--------------------------------------
	pkcs12       (exports key+crt to pkcs12 format)
	der          (exports key+crt to der format)
	pem          (exports key+crt to pem format)

	CA Creation
	-----------
	newca        (creates a new CA)
	showca       (show current CA infos)

