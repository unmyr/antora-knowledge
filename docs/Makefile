BASE_DIR=..
DOC_ROOT=.

DIST_DIR=$(BASE_DIR)/dist

adoc:
	npx antora --to-dir $(DIST_DIR) --fetch ../antora-playbook.yml
	ls -l $(DIST_DIR)/index.html
