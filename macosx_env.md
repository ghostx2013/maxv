##### setup zsh env
	curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh

	vi .zshrc "philips"

###### setup homebrw and rbenv
	ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"

	git clone git://github.com/sstephenson/rbenv.git ~/.rbenv

	echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.zshrc

	echo 'eval "$(rbenv init -)"' >> ~/.zshrc

	exec $SHELL -l

	rbenv install 1.9.3-p392

	rbenv rehash

	$ brew update
	$ brew install rbenv
	$ brew install ruby-build

	brew install wget
	brew install mysql
	brew install node
	brew install nmap
	brew install tree

##### Setup package
	import urllib2,os;pf='Package Control.sublime-package';ipp=sublime.installed_packages_path();os.makedirs(ipp) if not os.path.exists(ipp) else None;open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read())

##### Setup plugins
	Theme - Flatland
	Alignment 
	ZendGarden
	git
	Prefixr
	SublimeLinter
	Placeholders
	Clipboard History
	Nettuts Fetch
	JsMinifier
	Sublime CodeIntel
	Bracket Highlighter
	GBK
	Nginx
	Puppet
	puppetSyntax Checking
	Nodejs
	nodejs module helper

#####add setting user
	"theme": "Flatland Dark.sublime-theme",
	"color_scheme": "Packages/Theme - Flatland/Flatland Dark.tmTheme"

##### ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" ~/bin/subl
