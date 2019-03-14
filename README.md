# osdev_tools
Operating system development tools

这是一组用于操作系统开发的工具链，而且全都需要在 DOS 下使用，原本是在 ulios2 的开发过程中逐渐配套起来的，现提取出来，以供单独使用。

## WINBOOT.IMG
WINBOOT.IMG 是 Win98 的引导软盘镜像，可用于启动新创键的虚拟机。

软盘启动后可用 format c:/s 命令格式化 C 盘并使 C 盘可引导。可将 A 盘中的命令复制到 C 盘使用。

## CPQ6C
CPQ6C.zip 是 pqmagic 分区大师的 DOS 版。可方便得用于磁盘分区调整和格式化。

建议解压到 C:\CPQ6C 目录下使用。使用 pqmagic 命令打开。

## UCDOS
UCDOS.zip 是著名的中文 DOS 环境。

请解压到 C:\UCDOS 目录下使用。使用 ucdos 命令打开。使用 quit 命令退出。

## DJGPP
DJGPP 是 GNU 编译工具的 DOS 版。这里包含了 as, gcc, ld, make 等重要的编译工具。

请创建 C:\DJGPP 目录，并将该目录内的压缩包全部解压到 C:\DJGPP 目录中使用。

## NASM
nasm-2.12.02rc9-dos.zip 是 NASM 汇编器的 DOS 版。

请解压到 C:\DJGPP\BIN 目录下，即可借助 DJGPP 的环境使用。

## TC
TC.zip 是著名的 Turbo C 2.0 编译器，已包含了中文版的命令行编译工具 TCC.EXE 和 汇编器 TASM.EXE。

请解压到 C:\TC 目录下使用。已设置了优化的编译参数。

## GRUB
GRUB.zip 是 GRUB引导工具的 DOS 版。用于在 DOS 环境下引导系统。

建议解压到 C:\GRUB 目录下使用。已配置了选项，可以从 IDE0:0 的第二个主分区引导 ulios2。使用 grub 命令打开。
