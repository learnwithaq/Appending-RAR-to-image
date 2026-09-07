# Appending-RAR-to-image

Command: copy /b image.jpg + secret.rar output.jpg

Where:
image.jpg = cover image
secret.rar = RAR archive you want to hide
output.jpg = resulting JPEG

Example:
copy /b photo.jpg + secret.rar hidden.jpg

The resulting hidden.jpg will still open as an image, while the RAR data is appended to the file.
