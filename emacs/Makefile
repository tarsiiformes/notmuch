# See Makefile.local for the list of files to be compiled in this
# directory.
all:
	$(MAKE) -C .. all

.DEFAULT:
	$(MAKE) -C .. $@

lisp:
	$(MAKE) -C .. lisp

compile-elisp-tests:
	$(MAKE) -C ../test compile-elisp-tests

clean:
	$(MAKE) -C .. clean-lisp
