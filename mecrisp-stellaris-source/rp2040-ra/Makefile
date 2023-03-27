
all:
	./assemble > ./thislog 2>&1

clean:
	rm mecrisp-stellaris-pico-core.list
	rm mecrisp-stellaris-pico-core.o
	rm mecrisp-stellaris-pico-core.bin
	rm mecrisp-stellaris-pico-core.elf

distclean:
	@rm -f mecrisp-stellaris-pico-core.list
	@rm -f mecrisp-stellaris-pico-core.o
	@rm -f mecrisp-stellaris-pico-core.bin
	@rm -f mecrisp-stellaris-pico-core.elf
	@rm -f thislog
	./distclean.sh

# end
