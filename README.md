# Writing Good Documentation

## Step - 1 Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues. 

- In order to create codeblocks in markdown you need to use three back-ticks (`)
- Not to be confused with quotations. (')

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Example usage:
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")

```

- When you can you should attempt to apply syntax highlighting to your codeblocks 

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Example usage:
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")

```

- Make note of where the back-tick character keyboard key is located.
- It should appear next to letter "Z" key on the keyboard.
- But may vary based on your keyboard.

<img width="200px" src="/assets/keyboard-backtick.jpg" />

Good cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash

NameError: name 'undefined_variable' is not defined 

```
> Here is an example of using a codeblock for an error that appears in bash.

When you can always provide a codeblock instead of a screenshot.
If you need to take a screenshot makesure it is not a photo from your phone

> There are certain cases where its okay to take photos with your phone. This is when you are showing something like a keyboard, which does not appear on a computer screen. 
If it render on your computer screen it should be a screenshot. 

## Step 2 - How to take Screenshots

A screen short is when you capture a part of your screen from your laptop or desktop.

This is not to be confused with taking a photo with your phone.

***DON'T DO THIS***

![A photo with your phone ](assets/phone-photo.jpg)

***DO THIS INSTEAD***

![Screenshot example ](assets/screenshot.png)

Taking screenshots on both macOS and Windows is relatively simple, and both operating systems offer built-in tools to capture screenshots. Here's how to do it on each platform:

### On macOS:

1. **Capture Entire Screen**:
   - Press `Command (⌘) + Shift + 3`. The screenshot will be saved to your desktop by default.

2. **Capture a Selected Portion of the Screen**:
   - Press `Command (⌘) + Shift + 4`. You'll see a crosshair cursor. Click and drag to select the area you want to capture. The screenshot will be saved to your desktop.

3. **Capture a Specific Window**:
   - Press `Command (⌘) + Shift + 4`, followed by the `Spacebar`. Your cursor will turn into a camera icon. Click on the window you want to capture. The screenshot will be saved to your desktop.

### On Windows:

1. **Capture Entire Screen**:
   - Press `PrtScn` (Print Screen) on your keyboard. This will capture the entire screen and copy it to your clipboard.

2. **Capture Entire Screen (Windows 10 and later)**:
   - Press `Windows + Shift + S`. This will dim the screen, and you can select the area you want to capture. The screenshot will be copied to your clipboard.

3. **Capture a Specific Window**:
   - Press `Alt + PrtScn`. This will capture the active window and copy it to your clipboard.

4. **Capture a Specific Window (Windows 10 and later)**:
   - Press `Windows + Shift + S`, then select "Snip & Sketch" or "Snip Now" to capture a specific window or region. The screenshot will be copied to your clipboard.

After taking a screenshot on both macOS and Windows, you can paste it into an image editing program (like Paint or Preview) or directly into a document or image editing application.

Keep in mind that the specific key combinations and features might vary slightly depending on your version of macOS or Windows, so it's a good idea to check your system's documentation or online resources for any variations.

## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items[^1].

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji short-codes.

| Name | Short-code | Emoji |
| --- | ---| --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |

## Step 5 - How to create Table

You can use the following markdown format to create tables:

```md
| Name | Short-code | Emoji |
| --- | ---| --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud | `:cloud_with_lightning:` | :cloud_with_lightning: |
```
 
Github extends the functionality of markdown tables to provide more alignment and table cell formatting options[^2].

- Make note of where the pipe character keyboard key is located.
- It should appear above "Right Shift" key on the keyboard.
- But may vary based on your keyboard.

![Photo of the pipe character on the keyboard](assets/key-pipe.jpg)

![Hiden Garden scret window](secret-garden/hidden-garden.md) 

## External References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

- [BFM - Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/)

[^1]: [BFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)
[^2]: [BFM - Table (with extension) Sheet](https://github.github.com/gfm/#tables-extension-)

