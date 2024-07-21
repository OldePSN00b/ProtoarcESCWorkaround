# ProtoarcESCWorkaround
  Do you have a Protoarc XK03 bluetooth keyboard and play games? Well, I do. I've noticed that, unfortunately, the ESC key does not only double but triple duty. It acts as the tilde key, the backtick and ESC depending on the combination of keyboard presses you do. If you game on a laptop or the Lenovo Legion Go, like I do, you'll quickly realise that having ESC mapped as anything other than ESC makes it hard to exit some games or even pull up menus (I'm looking at you, Once Human). Well do I have the workaround for you! Strap in, this is going to get slightly wordy and just as slighly difficult. 

What you'll need:

One of those bluetooth wireless keyboards (Using the ProtoArc XK03, https://www.protoarc.com/products/xk03-foldable-keyboard, myself but this method should work with most things)

Microsoft PowerToys (As of this guide, current version is 0.82.1. Check here for your preferred installed method https://learn.microsoft.com/en-us/windows/powertoys/install)

I'll preface this set of directions with YMMV, I'm doing this on a Lenovo Legion Go but this should work generally on any Windows 10/11 machine.

First things first, install Microsoft PowerToys as it does all the heavy lifting for this workaround and launch it from the lovely icon that looks like:


![Screenshot 2024-07-21 182825](https://github.com/user-attachments/assets/572d3939-dba7-4a8b-8821-76cc83d170b7)

Now PowerToys does a lot of pretty freaking amazing things but the section we're looking for to make this workaround happen is called Keyboard Manager. Pick it from the list on the left side of PowerToys.

![Screenshot 2024-07-21 183109](https://github.com/user-attachments/assets/c5ae3614-0720-48d2-8570-cfa235dea255)

For Keyboard Manager to do anything, we need to enable it. Slide the toggle to the right and that'll get this party started!

![Screenshot 2024-07-21 183330](https://github.com/user-attachments/assets/b89e56f7-7bab-4693-b0d3-8ba409d58830)

Now the meat and potatoes to this whole workaround is the Remap a Key section. You'll want to click on it to get things started.

![Screenshot 2024-07-21 183700](https://github.com/user-attachments/assets/e5a19e43-f5cc-499d-a48f-9687a44b84a6)

So here we'll have PowerToys do the key translation. Click the left Select button, it'll pop up a dialog that lets you define the key you want to remap. You'll get this dialog box.

![Screenshot 2024-07-21 184028](https://github.com/user-attachments/assets/8f445738-d0ce-462e-9716-d137862206a0)

The key I needed to remap is the backtick key, which is the default character that the XK03 will output when pressed without any of the combination keys to change it to another one. So that was easy to get into that dialog box. I clicked ok and the first section looked like this.

![Screenshot 2024-07-21 184625](https://github.com/user-attachments/assets/ea79f76c-752e-4a8b-9e24-7ef66fa73285)

We want PowerToys to send an ESC key. We'll leave the pulldown on Send Key/Shortcut and click the Select button. Now,
for me, this is where it got complicated. In order for me to hit ESC on my XK03, i need to press FN+Shift+ESC to get the character to appear. If you attempt to do this in that dialog box, it will input both the Shift key and ESC, which is not what we want. So there are two ways around this, you can use another wired/wireless keyboard to just get the ESC key OR you can use Micrsoft's virtual keyboard.









