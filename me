#!/bin/bash
# Copyright (c) 2019 Sssssystem
# https://github.com/Ssssystem/Sssssystem.github.io
# https://sssssystem.github.io
# sh -c "$(curl -fsSL https://sssssystem.github.io/me/me/install.sh)"
clear
function logo(){
echo -e "\033[31m
\n\n\n\n\n\n
   +++++++++++     +++++++
   +    +    +     +
   +    +    +     +++++++
   +    +    +     +
   +    +    +     +++++++
\033[0m"
}
function home(){
cd $HOME
echo -e "
\n
01)  好van的东西
02)  修复底部小键盘
03)  切换清华源
04)  使用atilo安装linux发行版
05)  安装hexo博客(作者的库)
06)  刷流量/测网速
07)  安装命令行版百度云
08)  安装aria2下载工具
09)  切换为zsh终端
10)  配置python环境
11)  配置java环境
00)  退出
---------------------------------------------
"
read -p "[when]# 你选择的序号是：" xuanze
case $xuanze in
01)
	clear
	logo
	sleep 1s
	game
	;;
02)
	sleep 0.5s
	rm -rf $HOME/.termux
	mkdir $HOME/.termux
	echo -e "extra-keys = [['>','-',',','\"','.','/','*'],['ESC','(','HOME','UP','END',')','PGUP'],['CTRL','[','LEFT','DOWN','RIGHT',']','PGDN']]" >> $HOME/.termux/termux.properties
	echo -e "\033[31m进度 [100%]\n请重启 termux\033[0m"
	home
	;;
03)
	sleep 0.5s
	sed -i 's@^\(deb.*stable main\)$@#\1\ndeb https://mirrors.tuna.tsinghua.edu.cn/termux stable main@' $PREFIX/etc/apt/sources.list
	apt update && apt upgrade
	echo -e "\033[31m进度 [100%]\n请重启 termux\033[0m"
	home
	;;
04)
	sleep 0.5s
	echo -e "deb [trusted=yes] https://yadominjinta.github.io/files/ termux    extras" >> $PREFIX/etc/apt/sources.list
	pkg in atilo-cn
	echo -e "\033[31m进度 [100%]\033[0m"
	home
	;;
05)
	sleep 0.5s
	pkg install -y unzip
	pkg install -y wget
	pkg install -y vim
	pkg install -y git
	pkg install -y nodejs-lts
	pkg install -y openssh
	rm -rf $HOME/博客
	mkdir $HOME/博客	
	wget -O $HOME/博客/02.zip https://github.com/NibaZShab/NibaZShab.github.io/releases/download/02/02.zip
	unzip $HOME/博客/02.zip
	rm -rf $HOME/博客/02.zip
	cd $HOME/博客
	npm install -g hexo-cli
	npm install --save hexo
	mkdir $HOME/博客/404
	cd $HOME/博客/404
	hexo init
	rm -rf $HOME/博客/404/_config.yml
	mv $HOME/博客/_config.yml $HOME/博客/404
	mv $HOME/博客/up.sh $HOME/博客/404
	chmod 777 $HOME/博客/404/up.sh
	cd $HOME/博客/404/themes
	mv $HOME/博客/inside $HOME/博客/404/themes
	cd $HOME/博客/404
	git config --global user.name "NibaZShab"
	git config --global user.email "nibazshab@gmail.com"
	git init
	git remote add origin git@github.com:NibaZShab/NibaZShab.github.io.git
	ssh-keygen -t rsa -C "nibazshab@gmail.com"
	cd $HOME/博客
	git clone https://github.com/NibaZShab/NibaZShab.github.io.git
	cd /sdcard
	mkdir /sdcard/$
	cd $HOME
	ln -s /sdcard/$ $HOME/404
	cd $HOME/博客/NibaZShab.github.io
	mv $HOME/博客/NibaZShab.github.io/404 $HOME/404/$
	cd $HOME/博客
	rm -rf NibaZShab.github.io
	cd $HOME/博客/404/source
	mkdir $HOME/博客/404/source/about
	mkdir $HOME/博客/404/source/links
	cd $HOME/博客/404/source/_posts
	rm -rf $HOME/博客/404/source/_posts/*
	cp $HOME/404/$/markdown/page/* $HOME/博客/404/source/_posts
	cd $HOME/博客/404/source/about
	cp $HOME/404/$/markdown/about.md $HOME/博客/404/source/about/index.md
	cd $HOME/博客/404/source/links
	cp $HOME/404/$/markdown/links.md $HOME/博客/404/source/links/index.md
	cd $HOME/博客/404
	cp $HOME/404/$/markdown/book.md $HOME/博客/404
	chmod 777 $HOME/博客/404/book.md
	npm install --save hexo-deployer-git
	echo -e "\033[31m进度 [100%]\n读取ssh密钥请输入 cat $HOME/.ssh/id_rsa.pub\n检测ssh连接状况请输入 ssh -T git@github.com\n\n注: 此为作者个人的博客，部分文件和操作逻辑较为难以理解\n建议前往 https://nibazshab.github.io/post/04\n可按照小白教程搭建自己的博客\033[0m"
	home
	;;
06)
	sleep 0.5s
	i=0
	while [ $((i++)) -le 999 ]
	do
	wget -O /dev/null http://dlied5.myapp.com/myapp/1104466820/sgame/2017_com.tencent.tmgp.sgame_h8218_1.43.1.15_fc9dc4.apk
	done
	;;
07)
	sleep 0.5s
	echo "deb [trusted=yes] http://termux.iikira.com stable main" >> /data/data/com.termux/files/usr/etc/apt/sources.list
	apt update
	apt install baidupcs-go
	home
	;;
08)
	sleep 0.5s
	pkg install -y aria2
	pkg install -y wget
	cd /sdcard/Download
	rm -rf /sdcard/Download/aria2
	mkdir /sdcard/Download/aria2
	echo -e "" >> /sdcard/Download/aria2/aria2.session
	cd $HOME
	wget -O $PREFIX/etc/aria2.conf https://github.com/NibaZShab/NibaZShab.github.io/releases/download/09/09.conf
	rm -rf $HOME/启动aria2
	echo -e "echo \"rpc-key: 123456\"\nsleep 2s\nam start -a android.intent.action.VIEW -d http://aria2.net\naria2c --conf-path=$PREFIX/etc/aria2.conf" >> $HOME/启动aria2
	chmod 777 $HOME/aria2
	echo -e "\033[31m进度 [100%]\033[0m"
	home
	;;
09)
	sleep 0.5s
	pkg install -y wget
	rm -rf $HOME/install.sh
	wget https://github.com/Cabbagec/termux-ohmyzsh/raw/master/install.sh
	echo -e "\033[31m\n推荐配色值 → 19\n\033[0m"
	sleep 3s
	sh install.sh
	echo -e "\033[31m进度 [100%]\n请重启 termux\033[0m"
	rm -rf storage
	home
	;;
10)
	sleep 0.5s
	pkg install -y vim-python
	pkg install -y python
	pkg install -y python2
	pkg install -y clang
	pip install ipython
	pip3 install ipython
	echo -e "\033[31m输入 ipython 进入 python2 控制台\n输入 ipython2 进入 python3 控制台\033[0m"
	;;
11)
	sleep 0.5s
	pkg install -y wget
	wget -O $HOME/jdk.deb https://github.com/NibaZShab/NibaZShab.github.io/releases/download/08/08.deb
	dpkg -i $HOME/jdk.deb
	rm -rf $HOME/jdk.deb
	echo -e "\033[31m进度 [100%]\033[0m"
	home
	;;
00)
	clear
	cat $PREFIX/etc/motd
	exit
	;;
*)
	clear
	logo
	echo -e "\n\n\n[when]# 你正确输入了一个错误序号！"
	sleep 2s
	home
esac
}
function game(){
cd $HOME
echo -e "
\n
01)  小火车
02)  彩虹猫
03)  screenfetch
04)  neofetch
05)  奶牛说话
06)  打开王者荣耀
07)  当前时间
00)  返回
---------------------------------------------
"
read -p "[when]# 你选择的序号是：" haixuanze
case $haixuanze in
01)
	sleep 0.5s
	pkg install -y sl
	echo -e "\033[31m输入 sl 开始\033[0m"
	game
	;;
02)
	sleep 0.5s
	pkg install -y nyancat
	echo -e "\033[31m输入 nyancat 开始\033[0m"
	game
	;;
03)
	sleep 0.5s
	pkg install -y screenfetch
	echo -e "\033[31m输入 screenfetch 开始\033[0m"
	game
	;;
04)
	sleep 0.5s
	pkg install -y neofetch
	echo -e "\033[31m输入 neofetch 开始\033[0m"
	game
	;;
05)
	sleep 0.5s
	pkg install -y cowsay
	echo -e "\033[31m输入 cowsay 要说的话 开始\033[0m"
	game
	;;
06)
	sleep 0.5s
	am start -n com.tencent.tmgp.sgame/com.tencent.tmgp.sgame.SGameActivity
	exit
	;;
07)
	sleep 0.5s
	echo -e "#!/bin/bash\necho -e \"\\n\\n 现在是北京时间   \$(date +%Y年%m月%d日) \$(date +%H:%M:%S)\\n\"" > $PREFIX/bin/时间
	chmod 777 $PREFIX/bin/时间
	echo -e "\033[31m输入 时间 开始\033[0m"
	game
	;;
00)
	clear
	logo
	sleep 1s
	home
	;;
*)
	clear
	logo
	echo -e "\n\n\n[when]# 你正确输入了一个错误序号！"
	sleep 2s
	game
	;;
esac
}
logo
sleep 1s
home
