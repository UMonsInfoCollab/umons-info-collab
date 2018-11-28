################################################################################
############################ Variables to changes ##############################
##### Sources directory
SRC_DIR		= src

##### file to compile, without tex extension
##### It compiles the resume and rapport by default
RESUME		= resume
RAPPORT		= rapport

##### Executable/output to use: PDFLATEX, DVILUATEX
CC			= $(PDFLATEX)
################################################################################

################################################################################
############################# Constant variables ###############################
##### Build name file
SRC_RESUME	= $(RESUME).tex
SRC_RAPPORT	= $(RAPPORT).tex

NAME		= Compilation

##### Compilators
PDFLATEX	= pdflatex
DVILUATEX	= dviluatex
################################################################################

################################################################################
############################### Rules ##########################################
all: resume rapport

resume:
	cd $(SRC_DIR) && $(CC) -output-directory ../ $(SRC_RESUME)
	cd $(SRC_DIR) && $(CC) -output-directory ../ $(SRC_RESUME)

rapport:
	cd $(SRC_DIR) && $(CC) -output-directory ../ $(SRC_RAPPORT)
	cd $(SRC_DIR) && $(CC) -output-directory ../ $(SRC_RAPPORT)

zip: fclean all
	$(MAKE) clean
	zip -r $(NAME).zip . -x *.git*

clean:
	rm -f $(RESUME).out $(RESUME).aux $(RESUME).toc $(RESUME).log $(RESUME).tex.backup $(RESUME).nav $(RESUME).snm
	rm -f $(RAPPORT).out $(RAPPORT).aux $(RAPPORT).toc $(RAPPORT).log $(RAPPORT).tex.backup $(RAPPORT).nav $(RAPPORT).snm

fclean: clean
	rm -f $(RAPPORT).pdf
	rm -f $(RESUME).pdf
	rm -f $(NAME).zip
################################################################################
