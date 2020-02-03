```
╭───╮╭─╮  
│   ││ │╭─╮╭──┬──┬─╮╭───╮╭───╮   
│   ││ │├─┤│ ╭╮ ╭╮ ││ ─ ││╭╮ │  ╭────────┬─────────────────────╮
╰╮  ╰╯╭╯│ ││ ││ ││ ││  ─┤│╰╯ │  | UPLOAD │ ▒▒▒▒▒▒▒▒▒▒▒░░░░ %75 |                    
 ╰────╯ ╰─╯╰─╯╰─╯╰─╯╰───╯╰───╯  ╰────────┴─────────────────────╯                    
```

## Install

Using Bower
```
bower install https://github.com/KimCalvin/vimeo-upload
```

Or npm

```
npm install https://github.com/KimCalvin/vimeo-upload
```

## Usage

Include `vimeo-upload.js` in your index.html.

```
<script src="bower_components/vimeo-upload/vimeo-upload.js"></script>
```

Create a new `VimeoUpload` initialized with a Blob or File and Vimeo Access Token then call `upload()` to start the upload process.

```javascript
var uploader = new VimeoUpload({
  file: file,
  token: accessToken,
});

uploader.upload();
```

Your access token need to be authorized by Vimeo. Create new Vimeo access token [here](https://developer.vimeo.com/apps).

Check `index.html` for details and additional parameters you can include when initializing `VimeoUpload`.

## Credits

Sample code for uploading files directly with XHR/CORS: [cors-upload-sample](https://github.com/googledrive/cors-upload-sample)
