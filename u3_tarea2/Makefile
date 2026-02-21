help:
	@echo "Targets disponibles:"
	@echo "  lint"
	@echo "  build"
	@echo "  unit-tests"
	@echo "  validate"
	@echo "  integration-tests"
	@echo "  package"

lint:
	@echo "Running lint..."
	@echo "Lint OK"

build:
	@echo "Building project..."
	@mkdir -p dist
	@echo "<h1>Awesome Website</h1>" > dist/index.html
	@echo "#!/usr/bin/env bash" > awesome-api
	@echo "echo 'Awesome API running'" >> awesome-api
	@chmod +x awesome-api
	@echo "Build OK (dist/ y awesome-api creados)"

unit-tests:
	@echo "Running unit tests..."
	@echo "Unit tests OK"

validate:
	@echo "Validating project..."
	@echo "Validation OK"

integration-tests:
	@echo "Running integration tests..."
	@echo "Integration tests OK"

package: build
	@echo "Empaquetando awesome-website.zip..."
	@zip -r awesome-website.zip awesome-api dist
	@echo "Package OK (awesome-website.zip creado)"

.DEFAULT_GOAL := help
