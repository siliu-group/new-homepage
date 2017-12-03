## S-Lab ##
- \_pages contains some tabs
- \_posts contains all news. you can post latest news here.

### Run this theme on your local machine ###
To serve this jekyll theme make sure your computer meets the [following requirements](https://jekyllrb.com/docs/installation/#requirements), then run this command.

```
git clone https://github.com/siliu-group/new-homepage
cd new-homepage
sudo apt-get install ruby-full rubygems
sudo gem install bundler
bundle install
bundle exec jekyll s
http://127.0.0.1:4000/
```

### Post news ###
- 在_posts中复制一份template.md，按时间-标题修改文件名
- 修改文件中的标题日期，缩略图，摘要，然后将刚刚拷贝的link放到href中

You can change the site configuration in the [_config.yml](https://github.com/rmsubekti/nangka/blob/master/_config.yml) file.

License : [MIT](https://github.com/rmsubekti/nangka/blob/master/LICENSE.md)
Feel free to fork, change, modify and re-use it.
