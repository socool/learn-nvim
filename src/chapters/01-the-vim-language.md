# ภาษา vim

## บัฟเฟอร์, สปลิต/วินโดว์ และ แท็บ

- **บัฟเฟอร์** - `บัฟเฟอร์` คือการเปิดไฟล์, ที่เราสามารถแก้ไขได้หลายๆ `สปลิต`
- **สปลิต/วินโดว์** - `สปลิต` หรือ `วินโดว์` คือหน้าต่างที่คุณย้ายไปมาได้
- **แท็บ** - `แท็บ` คือชุดของ `สปลิต`, ที่เหมือน `แท็บ` ใน `เทอร์มินอล`, คนไม่ค่อยใช้มันบ่อยมากนัก

##### ผูก

- `:e <file>` - จะเปิดไฟล์ใหม่ (บัฟเฟอร์)
- `:b <buffer>` - จะเปลี่ยนไปยังไฟล์ที่เปิดไว้แล้ว (บัฟเฟอร์)
- `:vsplit` - จะเปิดสปลิตหน้าจอเป็นแนวตั้ง
- `:split` - จะเปิดสปลิตหน้าจอเป็นแนวนอน
- ใช้ `:help tab-page` ในการอ่านรายละเอียดเกี่ยวกับแท็บ (ซึ่งไม่ค่อยจำเป็นเท่าไหร่)

## ผูกคีย์

บ่อยครั้งที่คุณน่าจะเคยเห็นการผูกคีย์ ประมาณ: `ggyG` - ซึ่งเป็นการคัดลอกทั้งหมดใน `บัฟเฟอร์`.\
สัญญลักษ์นั้นหมายถึงการผูกคีย์ นั่นหมายถึง การ กด เหมือนกับคุณ `พิมพ์` มัน. \
ในการเรียกใช้งานคีย์ที่ผูกไว้แล้ว มีขั้นตอนดังนี้:

- `gg` - เลื่อนเคอร์เซอร์ไปยังบนสุดของไฟล์
- `y` - เริ่มคัดลอก
- `shift+g` - สิ้นสุดการคัดลอดจากตำแหน่งเคอร์เซอร์ที่อยู่จุดสิ้นสุดของไฟล์

ใน vim คุณต้องไม่ต้องกดคีย์ค้างไว้ตามลำดับการกดของคีย์ที่คุณพิมพ์, และคุสามารถตั้งค่ามันได้ที่ `timeoutlent`
เพื่อให้ vim รอ มากขึ้น/น้อยลง ระว่างคีย์สโต้คได้.

### Keybinds naming

You don't need to memorize keybinds as the letter stands for its action.

- `y` - yank
- `p` - paste

Each time where I introduce an action in this guide, I'll mark the letter I use to remember the bind.

#### Special Keys

- `<cmd>` - is `:` which starts a cmd
- `<cr>` - is `enter`
- `<Esc>` - is `Escape`
- `<C-x>` - is Ctrl+x
- `<M-x>` - is alt+x
- `<M-X>` - is alt+shift+x
- `<A-x>` - is alt+x
- `<A-X>` - is alt+shift+x
- `<leader>` - is the leader key

You can type `:help <key>` to open a `help` `split` for that key, the key can be anything, it can be `G` and it can be `<cr>`

###### Leader

vim maps most of the keyboard by default, `<leader>` acts as a prefix for custom user binds. \
Leader is remappable, the default mapping is `,` most vim users change it to `<Space>`

## Help

There's a help page for everything, start using it as soon as possible, it's like `man` just better and for `vim`.

## Modes

There are a lot of modes in vim, I'll cover the important ones. \
To exit from each mode back to normal press `Escape`. I recommend remapping it to `capslock`, you're going to press it a lot and it will be much easier to use the pinky without moving your hands.

- Normal - This is where you will be usually, you can move, copy in this mode, and much more
- Insert (`i`) - Insert text to the buffer, you want to be in this mode **only** when you're actually inserting text, you don't want to move in this mode
- Visual (`v`) - Select and copy/replace text
- Visual Line (`V`) - Select and copy/replace text by lines
- Command (`:`,`/`) - Inserting a command

### How to map Capslock to Escape

- GNOME (Ubuntu) - Install `gnome-tweak-tool`, start `Tweaks` then `Keyboard & Mouse -> Additional Layout Options -> Caps Lock behavior`.
- [macOS](https://vim.fandom.com/wiki/Map_caps_lock_to_escape_in_macOS)
- Windows - Install [AutoHotKey](https://www.autohotkey.com/) and add `Capslock::Esc` to an `ahk` script.
