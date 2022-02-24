# How to Convert a Markdown File to a Word File

This guide will show you how to convert a markdown file, file.md, to a word file, file.docx.  The requirements and steps are below, if you have read the word file to markdown file this should be very similar.

## Requirements

- A markdown file
- Pandoc installed
- Opened terminal

## Steps

1. Open a terminal.
2. Remember where your word file is stored at.
3. Use the `cd` command to navigate to your word file's parent directory.
   > If your file is stored at /home/user/Documents/file.docx an example command would be `cd /home/user/Documents/`
   > **NOTE:** If you are not sure you are in the right directory type `ls` and check if the file name is listed, if is you are in the correct directory.
4. Run the following command, but make sure to replace the paths that start with `REPLACE_ME`.
   `pandoc -s REPLACE_ME.docx -o REPLACE_ME.md`
   > **NOTE:** If your word file does not contain images `--extract-media=images` is not necessary
   > **NOTE:** If there is output please read the message and correct the mistakes, most likely you have not specified a valid path to a word file.

Congratulations you have converted a markdown file to a word file.  Now that your content is converted you should certainly ensure that it was converted correctly.

{% include footer.md %}
