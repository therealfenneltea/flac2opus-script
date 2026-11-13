.PHONY: install
install_dir := $(HOME)/.local/bin
install_path := $(install_dir)/flac2opus

install:
	@mkdir -p $(install_dir)
	@echo "Installing to $(install_path)"
	@cp -v flac2opus "$(install_path)"
	@chmod -v +x "$(install_path)"
	@echo "Done"
