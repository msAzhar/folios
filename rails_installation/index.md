#   Ruby on Rails (Kurulum)

.fx: first

 Aжar [M...]

`<azhar.murzaeva@bil.omu.edu.tr>`


http://www.omu.edu.tr/

Temmuz 2015

 
---
###Rails Nedir ?

- `Ruby on Rails`, kısaca `Rails` Ruby dilini temel alan bir web geliştirme framework'üdür. 

###Rails Kurulum Aşamaları
- Ruby için gerekli paketlerin Kurulumu
- Rbenv Kurulumu
- Ruby Kurulumu
- Rails Kurulumu
- MySQL Kurulumu
- +Sublime Text Kurulumu
- Kurulum Testi

###Gerekli Paketlerin Kurulumu

- Ruby için gerekli paketlerin kurulması için aşağıdaki kod satırlarının çalıştırılması gerekmektedir.

> $sudo apt-get update

> $sudo apt-get install git-core curl zlib1g-dev build-essential \ 

> $libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 \

> $libxml2-dev libxslt1-dev libcurl4-openssl-dev \

> $python-software-properties libffi-dev

###Rbenv Kurulumu

- `Rbenv`, Ruby için bir versiiyon yönetim sistemidir. Birden fazla Ruby versiyonlarını kullanmamızı sağlamakta.

> $cd ~

> $git clone https://github.com/rbenv/rbenv.git ~/.rbenv

> $echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc

> $echo 'eval "$(rbenv init -)"' >> ~/.bashrc

> $exec $SHELL

> $git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build

> $echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.bashrc

> $exec $SHELL

###Ruby Kurulumu

- `Ruby`, nesneye yönelik, dinamik, reflektif bir programlama dilidir. Ruby dili, Yukihiro Matsumoto tarafından Japonya'da tasarlanmaya ve geliştirilmeye başlanmıştır. Ruby kurulumu için aşağıdaki komutların çalıştırılması gerekmektedir.

> $rbenv install 2.3.1

> $rbenv global 2.3.1

> $ruby -v

- `Bundler`, gereken gem'leri ve gereken versiyonları kurarak Ruby için kalıcı bir ortam oluşturmaktadır. Bunlder aşağıdaki kod ile kurulabilir:

> $gem install bundler

Bu kurulumdan sonra aşağıdaki kodun çalıştırılması gerekmektedir:

> $rbenv rehash


###Rails Kurulumu

- `Ruby on Rails`, Ruby dilini temel alan bir web geliştirme framework’üdür. Ruby on Rails, kısaca Rails, iki temel yazılım geliştirme felsefesi üzerine kuruludur: Convention over Configuration (`CoC`) ve Dont't Repeat Yourself (`DRY`). Bir de Model View Controller (`MVC`) var...
Rails de bir gem'dir. Onu kurmadan önce nodejs kurulmalıdır.

> $curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -

> $sudo apt-get install -y nodejs

- nodejs kurulumundan sonra da Rails'i artık kurabiliriz:

> $gem install rails -v 4.2.6

- ve kurulup kurulmadığını kontrol edelim ve rbenv'imizi rehash edelim:

> $rails -v

> $rbenv rehash

###MySQL Kurulumu

- `MySQL`, hızlı ve sağlam bir veritaban yönetim sistemidir. Onun kurulumu için aşağıdaki kod satırını çalıştırmamız gerekmektedir.
!NOT: Kurulum esnasında root kullanıcısı için bir şifre oluşturmanız istenecektir. Bu şifre uygulamalar geliştirilirken kullanılacaktır.

> $sudo apt-get install mysql-server mysql-client libmysqlclient-dev


###Sublime Text Kurulumu

- `Sublime Text`, içinde birçok programlama dili arayüzü barındıran, çapraz platform bir kaynak kod düzenleme ve metin editörüdür. Arayüzü Vim'den ilham alınarak tasarlanmıştır. Kurulumu için console'a aşağıdaki kodların çalıştırılması gerekmektedir:

> $sudo add-apt-repository ppa:webupd8team/sublime-text-3

> $sudo apt-get update

> $sudo apt-get install sublime-text-installer

###Kurulum Testi

- Bu aşamaya kadar yazdığımız ve çalıştırdığımız komutları Rails uygulamalarını geliştirebilmek için Rails'i kurmaya çalıştık. Şimdi de Rails uygulamayı oluşturmaya çalışalım:

> $rails new myRailsapp

- Uygulamamızın dizinine girelim:

> $cd myRailsapp

- Uygulamamızı çalıştıralım ve belirtilen porttan uygulamamızı görebiliriz :)

> $rails server
