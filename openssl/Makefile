.PHONY: 1.0.0 1.0.1 1.1.0 1.2.0

all: 1.0.0 1.0.1 1.1.0 1.2.0

1.0.0:
	ds importpdb assets/openssl.flirt 1.0.0/x86/openssl.exe 1.0.0/x86/openssl.pdb openssl 1.0.0
	ds importpdb assets/openssl.flirt 1.0.0/x86/libcrypto-1_1.dll 1.0.0/x86/libcrypto-1_1.pdb openssl 1.0.0
	ds importpdb assets/openssl.flirt 1.0.0/x86/libssl-1_1.dll 1.0.0/x86/libssl-1_1.pdb openssl 1.0.0

1.0.1:
	ds importpdb assets/openssl.flirt 1.0.1/x86/openssl.exe 1.0.1/x86/openssl.pdb openssl 1.0.1
	ds importpdb assets/openssl.flirt 1.0.1/x86/libcrypto-1_1.dll 1.0.1/x86/libcrypto-1_1.pdb openssl 1.0.1
	ds importpdb assets/openssl.flirt 1.0.1/x86/libssl-1_1.dll 1.0.1/x86/libssl-1_1.pdb openssl 1.0.1

1.1.0:
	ds importpdb assets/openssl.flirt 1.1.0/x86/openssl.exe 1.1.0/x86/openssl.pdb openssl 1.1.0
	ds importpdb assets/openssl.flirt 1.1.0/x86/libcrypto-1_1.dll 1.1.0/x86/libcrypto-1_1.pdb openssl 1.1.0
	ds importpdb assets/openssl.flirt 1.1.0/x86/libssl-1_1.dll 1.1.0/x86/libssl-1_1.pdb openssl 1.1.0

1.2.0:
	ds importpdb assets/openssl.flirt 1.2.0/x86/openssl.exe 1.2.0/x86/openssl.pdb openssl 1.2.0
	ds importpdb assets/openssl.flirt 1.2.0/x86/libcrypto-1_1.dll 1.2.0/x86/libcrypto-1_1.pdb openssl 1.2.0
	ds importpdb assets/openssl.flirt 1.2.0/x86/libssl-1_1.dll 1.2.0/x86/libssl-1_1.pdb openssl 1.2.0

clean:
	rm -f assets/*.flirt*
