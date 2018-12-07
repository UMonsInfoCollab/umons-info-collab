################################################################################
############################ Variables to change ###############################
##### Sources directory
SRC_DIR		= src

##### file to compile, without tex extension;
NAME		= resume

##### Executable/output to use: PDFLATEX, DVILUATEX
CC			= $(PDFLATEX)
################################################################################

################################################################################
############################# Constant variables ###############################
##### Build name file
SRC			= $(NAME).tex

##### Compilers
PDFLATEX	= pdflatex
DVILUATEX	= dviluatex
################################################################################

################################################################################
############################### Rules ##########################################
$(NAME):
	cd $(SRC_DIR) && $(CC) -output-directory ../ $(SRC)
	cd $(SRC_DIR) && $(CC) -output-directory ../ $(SRC)

zip: fclean $(NAME)
	$(MAKE) clean
	zip -r $(NAME).zip . -x *.git*

clean:
	$(RM) -f $(NAME).out $(NAME).aux $(NAME).toc $(NAME).log $(NAME).tex.backup $(NAME).nav $(NAME).snm

fclean: clean
	$(RM) -f $(NAME).pdf $(NAME).zip $(NAME).dvi
################################################################################
