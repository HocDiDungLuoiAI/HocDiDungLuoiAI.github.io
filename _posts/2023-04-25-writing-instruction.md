---
layout:       post
title:        " Instruction for Writing Blog by Markdown"
author:       "w4rf0t"
header-img: "https://bell-sw.com/static/832cce1960961652a92bf2c618fb5d27/ae3a9/20-part-2.png"
header-mask: 0.2
catalog:      true
tags:
    - Instruction
---

> This is an instruction for Hocdidungluoi AI members's writing a sample markdown file for this blog。

I will use [This Page](https://hocdidungluoiai.github.io/2023/04/25/hello-world-python/) for example.
The above markdown code contains information about writing and executing a "Hello, World!" program in Python. It is written using the markdown language which allows the user to format text in a simple and easy-to-read manner. The structure of the markdown code can be analyzed as follows:

### First of All

- Go to [hocdidungluoiai Repo](https://github.com/hocdidungluoiai/hocdidungluoiai.github.io)
- Type `.` in order go to **Github editing page**
- At `_posts` folder -> create a new file in `year-month-date-title.md`

    ![image](https://user-images.githubusercontent.com/61643034/234245308-1195116a-37c3-4217-b871-ef4cc3d17872.png)

### Header of File
```bash
---
layout:       post
title:        "《Hello World》in Python"
author:       "w4rf0t"
header-img: "link_to_image_header"
header-mask: 0.2
catalog:      true
tags:
    - Code
    - Python
---
```

- The first line `---` indicates the beginning of the markdown document.
- The `layout` property specifies the layout of the document.
- The `title` property specifies the title of the document.
- The `author` property specifies the author of the document.
- The `header-img` property specifies the URL of the header image for the document.
- The `header-mask` property specifies the opacity level of the header image.
- The `catalog` property specifies whether or not to include the document in the site's catalog.
- The `tags` property specifies the tags associated with the document.

### Main Body

The main body of the markdown code contains the following sections:

- **Download and Install:** This section provides instructions on how to download and install Python on a computer.
    + Download: This sub-section provides a hyperlink to the Python website and instructions on how to download the latest version of Python for the user's operating system.
    + Open a text Editor: This sub-section provides instructions on how to open a plain text editor.
    + Write the code: This sub-section provides instructions on how to write a simple Python program that prints the phrase "Hello, World!" to the console.
    + Save the file: This sub-section provides instructions on how to save the Python code file.
    + Run the program: This sub-section provides instructions on how to run the "Hello, World!" program in Python.
- **Note:** if you want to write as command lines, use this:

```bash
'''python
print('Hello World!')
'''
```