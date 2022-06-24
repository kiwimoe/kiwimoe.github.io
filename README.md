> A fork version of parchment jekyll theme

How to use it?
To run it locally you need to install ruby gems first.
On Debian (Ubuntu, Mint, etc)
sudo apt install zlib1g-dev ruby-full build-essential

On Arch (Arco, Endevour, etc)
sudo pacman -S zlib1g-dev ruby-full build-essential

After this all done, follow the steps, provided below

Install these dependencies
sudo gem install jekyll bundler jekyll-paginate

Now run
bundle exec jekyll serve
Jekyll should serve your blog at localhost:4000