cmake_minimum_required(VERSION 2.6)

add_library("pure64-core"
	"dap.c"
	"dir.c"
	"error.c"
	"file.c"
	"fs.c"
	"gpt.c"
	"mbr.c"
	"misc.c"
	"partition.c"
	"path.c"
	"stream.c"
	"string.c"
	"uuid.c")
