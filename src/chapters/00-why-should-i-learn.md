# ทำไมต้องรู้ nvim

ในฐานะมืออาชีพ, คุณต้องใช้เวลามากมายกับคอมพิวเตอร์ของคุณ,โดยเฉพาะการแก้ไขโค้ด.คุณต้องทำมันด้วยความสนุกและมีประสิทธิภาพที่สุด.
nvim มันสนุก: สนุกในการเรียนรู้,สนุกในการเขียน,ในการปรับปรุงและสุดท้าย - มันมีประสิทธิภาพมากมาย.

#### คุณสามารถใช้ vim ด้วยตีย์บอร์ดอะไรก็ได้

vim ให้ตัวเลือกคุณในการเลือกใช้คีย์ง่ายๆ บนคีย์บอร์ด: คีย์ตัวอักษร, ctrl, alt, shift, escape, enter. \
คุณไม่ต้องห่วงว่า end มันอยู่ตรงไหน,pageup/down และ home เพื่อเปลี่ยนระหว่าง keyboard และ laptop.

ถ้าคุณเคยพิมพ์บนคีย์บอร์ด,คุณสามารถใช้ vim ในแนวทางที่คุณคุ้นเคย.

#### ให้มือของคุณอยู่บนคีย์บอร์ด

vim สามารถใช้งานโดยปราศจากเม้าส์,และที่ควรจะเป็นก็คือให้ใช้งานแบบนั้นแหละแบบไม่มีเม้าส์.ให้เหมือนกับว่ามี "พลังงาน" บังคับให้มือของคุณอยู่บนคีย์บอร์ด.
และคุณอยู่กับ "คลื่น" ในขณะโปรแกรมโดยไม่ต้องการให้มือของคุณขยับไปใช้งานเม้าส์และกลับไปที่คีย์บอร์ด.

vim ถูกออกแบบมาให้ใช้งานกับ [type touching](https://www.ratatype.com/static/i/learn/keyboard/en/keyboard.webp).\
ส่วนสำคัญคือให้มือของคุณอยู่นแป้นพิมพ์: `asdf jkl;`. \
และมันไม่จำเป็นต้องใช้งาน touch type (ฉันไม่ใช้ touch type 100%) แต่แนะนำให้ลองใช้งานก็ได้.

##### คำชี้แจง

คุณใช้เม้าส์ได้. \
ผมตั้งค่าเม้าส์เพื่อให้ "เดา" แสดงสิ่งต่างๆในเครื่องของผม. \
ผมใช้เม้าส์ในการ "อ่าน" โค้ด,และส่วนตัวพบว่ามันสะดวกทีเดียว. \
ผมใช้เม้าส์เพื่อแสดงให้คนอื่นเห็นในเครื่องของผมเพื่อเค้าจะได้ทำตามได้.

#### หนทางที่ถูกต้องในการโปรแกรม

ผมพูดได้ว่า `nvim` คือหนทางที่ถูกต้องในการโปรแกรม.

เมื่อคุณใช้งาน vim, คุณ"คุย" กับมันไม่ใช่ "เคลื่อน" มัน.\
จินตนาการตามน่ะ, แทนที่คุณจะถามเพื่อนคุณให้เทน้ำลงแก้ว,คุณกับให้คำสั่งแก่เพื่อนคุณคือ วิธีการในการเทน้ำลงแก้วซึ่งหน้าตาเป็นแบบนี้:

1. เปิดขวด
2. หยิบแก้วมา
3. หยิบขวดมา
4. ทำให้มุมของขวดตรงกับแก้ว
5. วางขวด
6. ปิดขวด

มันไม่ง่ายกว่าหรือในการที่จะพูดว่า "เฮ้,เทน้ำให้ฉันซักแก้วหน่อย?"
อืม, ก็เป็นความรู้สึกในการใช้อิดิเตอร์ตัวอื่นหลังจากใช้งาน vim, vim ให้คุณ "คุย" กับมัน.

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
