all-tests tests:	test-artype \
			test-basic \
			test-compress \
			test-port \
		
	echo Tests passed.

test-artype:
	cd artype && for i in *.sh; do echo Running test artype/$$i; $(SHELL) $$i; done
test-basic:
	cd basic && for i in *.sh; do echo Running test basic/$$i; $(SHELL) $$i; done
test-compress:
	cd compress && for i in *.sh; do echo Running test compress/$$i; $(SHELL) $$i; done
test-port:
	cd port && for i in *.sh; do echo Running test port/$$i; $(SHELL) $$i; done
