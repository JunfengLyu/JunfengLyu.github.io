TEX := Alan_Lyu_CV.tex
BUILD_DIR := build
BUILD_PDF := $(BUILD_DIR)/Alan_Lyu_CV.pdf
PUBLIC_PDF := ../../assets/pdf/Alan_Lyu_CV.pdf

.PHONY: build publish clean

build:
	mkdir -p $(BUILD_DIR)
	tectonic -X compile $(TEX) --outdir $(BUILD_DIR)

publish: build
	cp $(BUILD_PDF) $(PUBLIC_PDF)
	@echo "Updated $(PUBLIC_PDF)"

clean:
	rm -rf $(BUILD_DIR)
