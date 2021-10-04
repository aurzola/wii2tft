set(srcs "station_example_main.c"
	"ili9340.c"
	"fontx.c"
	"decode_png.c"
	"pngle.c"
	)

idf_component_register(SRCS ${srcs}
					INCLUDE_DIRS ".")


