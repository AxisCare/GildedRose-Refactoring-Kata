MAKEFLAGS += --no-print-directory

test:
	php fixtures/texttest_fixture.php 30 > actual
	diff expected actual && echo "Test passed"

test.watch:
	npx onchange '**/*.php' -- make test
