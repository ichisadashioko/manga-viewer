# Introduction

This project is about creating a web server that allows us to read manga (view images) from our local drive in web browser.

# Why do we need to do that?

- When we downloaded some manga from some sites, its chapters are organized in folder and the actual images are in those chapter folders. We cannot forward to the next chapter without close the current _Image Viewer_ program, go to the next chapter folder, and open the first image of the next chapter.

- Most of the popular _Image Viewer_ programs are only allow us to view one image at a time. Their navigation may not be customizable.

- The __pinch__ function. On __Windows 10 laptop__ with a precision touchpad, you can use two-finger gestures to __pinch__ the web page in the __Chrome__ web browser and you also can move the web page around. I find it very useful to read some small _furigana_.

- I also want to able to preview the manga content instead of just staring at hundreds of folder icons with a little text.

# How it is going to be implemented?

- Dark mode: I am a night reader and light mode is already there without any `css`.
- [Django](https://www.djangoproject.com/) (Python): _"Django makes it easier to build better Web apps more quickly and with less code."_