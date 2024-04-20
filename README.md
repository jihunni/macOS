# macOS
## basic installation and setting
- Developer tool
	```
	xcode-select --install # to install clang, gcc and git.
	```
- HomeBrew and zsh  
	HomeBrew : https://brew.sh/    
	zsh terminal installation
	```
	# zsh install
	brew install zsh
	
	# oh-my-zsh install
	sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
	```

  Installation Collection
	```
	brew upgrade llvm
	brew upgrade gcc
	brew install tree
 	brew install wget
 	```

	Environmental variable path for `brew`
	```
	#For compilers to find curl you may need to set:
	export LDFLAGS="-L/opt/homebrew/opt/curl/lib"
	export CPPFLAGS="-I/opt/homebrew/opt/curl/include"
	
	#For pkg-config to find curl you may need to set:
	export PKG_CONFIG_PATH="/opt/homebrew/opt/curl/lib/pkgconfig
 	```
- iTerm2
  - theme setting : https://ooeunz.tistory.com/21 
- anaconda
- docker

# Install Window11 Arm
- Youtube link: https://www.youtube.com/watch?v=KGZMV8IuUtA
- Window11 Arm download : https://www.microsoft.com/en-us/software-download/windowsinsiderpreviewarm64
