pwd命令，显示目前所在目录，显示当前工

作目录 ( 显示当前， 文件夹，或文件所在路径 )

cd命令，是目录切换命令，是shell内置命令，(切换并进入目录中)

ls命令，列出目标目录中所有的子目录和文件


$pwd


/data/data/com.termux/files/home/downloads

$ pwd
/data/data/com.termux/files/home
~ $ ls $home

5555        downloads    storage         yay
Arch_arm64  dump.rdb     vld-0.14.0
CONFIG      package.xml  vld-0.14.0.tgz
EVAL        ping         www99

~ $ cd $home

~ $ cd  vld-0.14.0

~/vld-0.14.0 $  cd


~ $ ls $PREFIX


0000  bin  include  libexec  share  var
6666  etc  lib      opt      tmp

~ $ cd $PREFIX

.../files/usr $ pwd

/data/data/com.termux/files/usr
.../files/usr $
