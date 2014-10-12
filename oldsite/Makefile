SOURCEFILES = $(patsubst %.otl,%,$(wildcard *.otl))
all:
	for file in $(SOURCEFILES); do \
	  echo $$file.otl;\
	  otl2html -s webpage.css -D $$file.otl > $$file.html ;\
	done

clean: 
	rm *.otl *.html
