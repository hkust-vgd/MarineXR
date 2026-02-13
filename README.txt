URL: https://marinexr.hkustvgd.com/

Notes
- The site includes poster fallback images in imgs/ so it still looks good even if these files are missing.
- Keep filenames the same or update the <source> tags in index.html.
- The back looping video and trailer are kept in this folder: media/
- The images/GIFs in the galleries (Scene Screenshots, 3D Models, and BTS) are kept in the corresponding folder under imgs/
- If you are adding new images in galleries, please place the image into the correct folder. Then update the array [const galleries] in <script>. The displaying order will follow the order in array.
- Images/GIFs with resolution 1920x1080 (or ratio 16:9) are referred.
- Unlinked images will be replaced by a white placeholder: imgs/placeholder.png
- Avatar images are kept in this folder: imgs/Avatars, unlinked avatar images will be replaced by a white placeholder: imgs/Avatars/avatar_placeholder.png
- The custom style is editable in this file: css/site.css