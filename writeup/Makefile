all:
	cd curling && pandoc readme.md -o curling.pdf && cd ..

merge:
	pdftk curling/curling.pdf  cat output merged.pdf
