include prorab.mk

$(eval $(call prorab-config, ../../config))

this_name := curlydoc

this_soname := $(shell cat $(d)soname.txt)

this_srcs := $(call prorab-src-dir, .)

$(eval $(prorab-build-lib))
