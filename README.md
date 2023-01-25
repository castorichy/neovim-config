# How to customize nvim for better experience.

I like customizing my nvim because it provides the best experience to mi desire. Lots of people have asked me to create a tutorial showing how to customize neovim. In this article i will elaborate how to do so in detail.

So now lets dive into it and start learning one by one. Neovim comes with no plugins to customize your nvim experience it only gives you ways on how you can do it your self. I like that because you will learn how to do it your self. there are two way you can customize (lua language and vimScript). I will use vimScript to explain because i am not experienced with lua language.

# Setting up nvim environment

All vim Configurations are stored in “.config/nvim/init.vim” file. I will assume that you know linux commands on how to create directories and file. nvim has two ways to configure, one way is by command mode. lets try and opening a file and enter into a command mode and type “set number” then hit enter button. Here you will see numbers appearing on your screen.

The second method is by creating a vim file inside .config/nvim directory. After creation update the file content by opening it using nvim editor the write this comment “set number”.

Open a new file and you will see number appearing. this method is much advisable since command mode is used only when its open.

# Adding configuration into init.vim file

Adding a new config IS A EAZY WAY
