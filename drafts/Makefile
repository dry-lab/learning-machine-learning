RELATIVE:=../../..
include $(RELATIVE)/_config.mk

ifndef RELATIVE
RELATIVE:=$(shell echo "$(patsubst $(BLOG)/%, %, $(CURDIR))" | sed 's/[^/][^/]*/../g')
$(warning RELATIVE location of blog directory is not specified. Assuming "$(RELATIVE)")
endif

YEAR:=2018
DIR:=
SRC:=$(wildcard $(DIR)*.Rmd)
CSS:=$(wildcard $(DIR)*.css)

include $(BLOG)/_slides/slides.mk
