.PHONY: all
all:
	ansible-playbook -i hosts.ini site.yml

.PHONY: test
test:
	ansible-playbook -i hosts.ini --syntax-check site.yml
