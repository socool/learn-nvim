# ทำไมต้องรู้ nvim

ในฐานะมืออาชีพ, คุณต้องใช้เวลามากมายกับคอมพิวเตอร์ของคุณ,โดยเฉพาะการแก้ไขโค้ด.คุณต้องทำมันด้วยความสนุกและมีประสิทธิภาพที่สุด.
nvim มันสนุก: สนุกในการเรียนรู้,สนุกในการเขียน,ในการปรับปรุงและสุดท้าย - มันมีประสิทธิภาพมากมาย.

#### You can use vim with any keyboard

vim gives you the option to use only the basic keyboard keys: the alphabetical keys, ctrl, alt, shift, escape, enter. \
You don't need to find where is end, pageup/down and home each time you switch a keyboard/laptop.

If you can type on a keyboard, you can use vim the way you're used to.

#### Keep your hands on the keyboard

vim can be used without a mouse at all, and it's even recommended to use it this way, as it will "force" you to stay in the "flow" while programming without needing to move your hand over to the mouse and back to the keyboard.

vim is designed to be used with [type touching](https://www.ratatype.com/static/i/learn/keyboard/en/keyboard.webp).\
The important binds are on/next to the keys your hands should always be on: `asdf jkl;`. \
It isn't a must to touch type (I don't touch type 100%) but I recommend trying to switch anyways.

##### Disclaimer

You can use a mouse. \
I configured a mouse to allow "guests" to show me stuff in my workstation. \
I use a mouse to **read** code, personally I find it more convenient. \
I use a mouse when showing someone in my workstation so they can follow along.

#### The right way to program

It's a strong saying but I'm convinced that `nvim` is the right way to program.

When you're using vim, you "talk" to the editor rather than "move" it. \
Imagine, instead of asking your friend to pour you a glass of water, you would give instructions to your friend on how to pour you a glass of water, which would look like something like this:

1. Open the bottle
1. Grab the glass
1. Grab the bottle
1. Make an angle with the bottle towards the glass
1. Put down the bottle
1. Close the bottle

Wouldn't it be easier to just say "Hey, can you pour me glass of water?"
Well, that how it feels to use other editors after you're using vim, vim lets you "talk" to the editor.

#### Feel "at home" everywhere

Most TUIs programs support `vim` binds which will make you feel fast in any program that you usually use, `less`, `man`, `tmux` and many more.

You can feel "at home" in browsers too, with the [vimium extension](https://addons.mozilla.org/he/firefox/addon/vimium-ff/)

Edit files through `ssh` with ease

#### Lightweight and Native

nvim is lightweight, starts up fast, renders fast and a lot of the plugins tend to use a strong native binary to run the heavyweight tasks. \
For example, to search for text across the project [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) runs [ripgrep](https://github.com/BurntSushi/ripgrep).

#### Rich plugin ecosystem

nvim has a huge community that develops plugins for everything you can and can't imagine. \
nvim doesn't miss on any IDE feature that other IDEs have to offer. \
nvim plugins are the first to "evolve" when a new tech is coming to the IDE world, the nvim community is the first to adapt it, e.g: ripgrep

You can take a look at the [awesome nvim plugin list](https://github.com/rockerBOO/awesome-neovim). I recommend to "watch" to get updates about new plugins.

#### Be comfortable

nvim is basically a framework for an editor, it can't do much without plugins but it gives the user the ability to configure the editor in a way they're most comfortable with.

Imagine sitting on a chair you built exactly to your size. The back rest covers all of your back, the head rest is exactly in the right height and has the perfect shape to support your head and neck. The arm rests match exactly the height of your desk, and the chair is at the perfect height for your legs. \
This is how I feel when I code in nvim, I sit in a chair I build exactly for my needs, and I can keep improve the way I code because I can improve the way my editor works.

---

# How should I start use nvim?

nvim has a steep learning curve - it takes time and patience to master, you will find that you need to invest time so you can **start** using nvim as your daily driver.

If you are a professional programmer I recommend to start using it in your personal projects and integrate it slowly to your professional workflow. I did it by having my previous editor (Sublime Text) open while nvim was open too.

I started by trying to do simple actions with nvim and moving to sublime when I needed to do complicated stuff that I struggled to do with nvim. After I got comfortable with basic functionality, I started trying to do more complex actions with nvim, sometimes I managed to yet sometimes I also failed and went back to sublime. Eventually I felt more comfortable with nvim and stuck with it all day long.

The bottom line is that it'll take time and effort but eventually it will be worth it, for me it sparked the old feeling of learning how to edit your code, and I still feel it every day.

---

# Neovim Requires Time

Neovim requires a lot of time learning additional to the learning curve you will have to make bunch of configurations other than the nvim config itself, terminal, nerdfont, plugins, etc, it might be not for you.

If you are 100% dedicated to learn and use neovim. I strongly recommend to start backing up your work environment config with some kind of dotfiles framework. I use [dotbot](https://github.com/anishathalye/dotbot).
