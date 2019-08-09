# OCR File Extractor for the Bash Bunny

* Author: Jiagi
* Version: Version 1.0
* Target: Windows

## Description

Displays a file's contents encoded in base64, using a browser.

## Configuration

**FONT_SIZE:** The size of the font used by the web browser.

**PADDING_X:** The horizontal distance between each character.

**PADDING_Y:** The vertical distance between each line.

**MARGIN_TOP:** The distance between the top of the browser window and the first line.

**MARGIN_LEFT:** The distance between the left side of the browser window and the start of each line.

**MARGIN_BOTTOM:** The distance between the bottom of the browser window and the last line.

**MARGIN_RIGHT:** The distance between the right side of the browser window and the end of each line.

**FRAME_TIME:** The time for which every frame will stay on the screen, before changing to the next one.

**FONT:** The font used by the web browser to display text.

**BG_COLOR:** The background color of the browser window.

**FG_COLOR:** The text color.

**WAIT_TIME:** The time to wait before displaying the file's content.

**TARGET_FILE:** The variable to extract from the target's computer.

All variables are in pixels, except for FRAME_TIME and WAIT_TIME which are in milliseconds, and FG_COLOR and BG_COLOR which are colors.

## STATUS

| LED                | Status                                       |
| ------------------ | -------------------------------------------- |
| SETUP              | Start the server                             |
| ATTACK             | Load the file and display their content      |
| CLEANUP            | Remove log file created by the server        |
| FINISH             | The script is done                           |
