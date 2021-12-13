index: index.o
	ld -macosx_version_min 11.0.0 -o index index.o -lSystem -syslibroot `xcrun -sdk macosx --show-sdk-path` -e _start -arch arm64

index.o: index.s
	as -o index.o index.s
