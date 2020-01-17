### Intall

- https://docs.mongodb.com/manual/tutorial/install-mongodb-on-amazon/

# Error
#### libc.so.6(GLIBC_2.18)(64bit)

    Error: Package: mongodb-org-shell-4.2.2-1.amzn2.x86_64 (mongodb-org-4.2)
           Requires: libc.so.6(GLIBC_2.18)(64bit)
	Error: Package: mongodb-org-mongos-4.2.2-1.amzn2.x86_64 (mongodb-org-4.2)
			   Requires: libc.so.6(GLIBC_2.18)(64bit)
	Error: Package: mongodb-org-server-4.2.2-1.amzn2.x86_64 (mongodb-org-4.2)
			   Requires: libc.so.6(GLIBC_2.18)(64bit)
	 You could try using --skip-broken to work around the problem
	 You could try running: rpm -Va --nofiles --nodigest
    
