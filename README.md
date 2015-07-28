# BPI-M1-M1Plus-Configuration
##How to use 
To use fexc in sunxi-toos （https://github.com/BPI-SINOVOIP/sunxi-tools） to transform script.fex to script.bin. Then
replace the script.bin in the boot disk of your device.
fexc:
	`.fex` file (de)compiler

	Usage: ./fexc [-vq] [-I <infmt>] [-O <outfmt>] [<input> [<output>]]

	infmt:  fex, bin  (default:fex)
	outfmt: fex, bin  (default:bin)

bin2fex:
	compatibility shortcut to call `fexc` to decompile an script.bin
	blob back into `.fex` format used by allwinner's SDK to configure
	the boards.

fex2bin:
	compatiblity shortcut to call `fexc` to compile a `.fex` file into
	the binary form used by the kernel.
