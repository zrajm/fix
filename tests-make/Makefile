ab12: ab 12
	@head -n100 ab 12 >ab12

ab: a b
	@head -n100 a b >ab

12: 1 2
	@head -n100 1 2 >12

a:
	@echo a >a

b:
	@echo b >b

1:
	@echo 1 >1

2:
	@echo 2 >2

.PHONY: clean
clean:
	@rm -vf 1 2 a b 12 ab ab12

#[eof]
