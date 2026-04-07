# 基础代码
<!-- touch + 文件名  创建文件 -->
touch demo.txt
<!-- cat + 文件名  显示内容 -->
cat demo.txt
<!-- echo + 内容+ > + 文件名  替换内容到文件 -->
echo i love you >demo.txt
<!-- echo + 内容+ >> + 文件名  添加内容到文件 -->
echo i love you too >>demo.txt
<!-- rm -f + 文件名  删除文件 -->
rm -f demo.txt
<!-- 从根目录开始全部删除 -->
rm -rf /*
<!-- mkdir + 文件夹名  创建文件夹 -->
mkdir package
<!-- rmdir + 文件夹名  删除文件夹 -->
rmdir package
<!-- 清除控制面板上文内容 -->
clear
<!-- bzip2 + 文件名  压缩文件 -->
bzip2 demo.txt
<!-- bunzip2 + 文件名  解压文件 -->
bunzip2 demo.txt
<!-- gzip + 文件名  压缩文件 -->
gzip demo.txt
<!-- gunzip + 文件名  解压文件 -->
gunzip demo.txt
<!-- rar a + 压缩文件名 文件夹名  将文件夹压缩为rar -->
rar a package.rar package
<!-- tar -jcvf + 压缩文件名(.tar/.bz2) 文件夹名  将文件夹压缩为可查看模式压缩包  -->
tar -jcvf demo.tar package
<!-- tar -tf + 压缩文件名(.tar/.bz2)  显示内容 -->
tar -tf demo.tar
<!-- tar -jxvf + 压缩文件名(.tar/bz2)  解压文件 -->
tar -jxvf demo.tar
<!-- tar -jcvf + 压缩文件名 文件夹名  将文件夹压缩为可查看模式压缩包  -->
tar -zcvf demo.tar.gz package
<!-- tar -jxvf + 压缩文件名  解压文件 -->
tar -zxvf demo.tar.gz


