# Download the necessary things
1. Để làm việc với Git cần phải tải Git [tại đây 👈🏻](https://git-scm.com/downloads)

2. Extensions Visual Studio Code:
    - Live Server
    - Live Previews:
    - HTML to CSS autocompletion
    - Prettier - Code formatter
    - Auto Rename Tag 

3. Extensions Chrome:
    - ColorZilla
    - Page Ruler Redux
    - Viewport Resizer


### Cách dùng Git:
```markdown
git init
```
```markdown
git add .
```
```markdown
git commit -m "comment"
```
```markdown
git branch
```
```markdown
git checkout
```
```markdown
git remote add origin https://github.com/BuiQuangVinh66/Learn-The-Basics-Of-Front-End.git
```
```markdown
git push origin master
```
```markdown
git pull origin master
```
```markdown
git clone
```

---

# **Learn-The-Basics-Of-Front-End**
- Chúng ta sẽ bắt đầu bằng HTML trước, sau đó sẽ tới CSS và JAVASCRIPT.

# Introduction
### Front-End là gì?
- Là thứ người dùng có thể nhìn thấy trên web.
    #### HTML là gì?
    - Là ngôn ngữ đánh dấu siêu văn bản cực vip max pro, là ngôi nhà mới xây.
    #### CSS là gì?
    - Nếu **HTML** là ngôi nhà mới xây thì **CSS** là nội thất và sơn tường.
    #### JAVASCRIPT là gì?
    - Nếu đã có ngôi nhà và đồ trang trí thì **JAVASCRIPT** là đường ống nước, đường điện.

# Start
### HTML có những khái niệm gì?
1. **Tag**: là một dấu ngoặc nhọn dùng để bao quanh nội dung muốn hiển thị ví dụ: (hình ảnh, văn bản, bảng,...).
2. **Attribute**: là một thuộc tính của các thẻ **Tag** dùng để định dạng cho các thẻ **Tag** ví dụ: (màu sắc, kích thước,...).
3. **Element**: là một phần tử của một file HTML, nó được tạo từ các thẻ **Tag** và **Attribute**.
4. **Document**: là một trang web, nó có thể chứa nhiều **Element**.

## **Cấu tạo cơ bản file HTML?**
- Gồm các thẻ như sau:
<table width="100%">
    <tr>
        <th>Thẻ</th>
        <th>Giải thích</th>
    </tr>
    <tr>
        <td>doctype</td>
        <td>Xác định phiên bản HTML</td>
    </tr>
    <tr>
        <td>html</td>
        <td>Là thẻ gốc cảu các thẻ khác</td>
    </tr>
    <tr>
        <td>head</td>
        <td>Chứa thông tin về tài liệu</td>
    </tr>
    <tr>
        <td>body</td>
        <td>Chứa nội dung của trang web</td>
    </tr>
</table>

#### Example:
```html
<!DOCTYPE html>
<html>

<head>
</head>

<body>

</body>

</html>
```

## *Thẻ Head chứ thẻ gì trong đó?*
- Nó dùng để chứa các thẻ như meta, title, link

#### Example:
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style.css">
    <title>Document</title>
</head>
```

### Meta có cộng dụng gì?
- Meta có công dụng cung cấp thông tin về trang web cho công cụ tìm kiếm như viewports, keywords, author, description,..

- Một số thẻ đã bị google bỏ qua và trở thành thẻ vô dụng:
    - keywords: vì quá nhiều người lạm dụng nhồi nhét quá nhiều từ khóa làm trang web mất đi sự đang tin cậy
    - author thẻ này cũng không cần thiết

#### Example:
```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="keywords" content="Hentai, Biến thái, súc vật, bệnh hoạn">
<meta name="description" content="Bán tượng nami khỏa thân">
<meta name="author" content="Không ai cả">
```

## *Thẻ body chứ thẻ gì trong đó?*
- Vì body chứa các nội dung của trang web cho nên nó có rất là nhiều thẻ:
### Heading, Comment, Spacing:
<table width="100%">
    <tr>
        <td>h1</td>
        <td><h1>This is h1 text</h1></td>
    </tr>
    <tr>
        <td>h2</td>
        <td><h2>This is h2 text</h2></td>
    </tr>
    <tr>
        <td>h3</td>
        <td><h3>This is h3 text</h3></td>
    </tr>
    <tr>
        <td>h4</td>
        <td><h4>This is h4 text</h4></td>
    </tr>
    <tr>
        <td>h5</td>
        <td><h5>This is h5 text</h5></td>
    </tr>
    <tr>
        <td>h6</td>
        <td><h6>This is h6 text</h6></td>
    </tr>
    <tr>
        <td>p</td>
        <td><p>This is p text</p></td>
    </tr>
    <tr>
        <td>& nbsp</td>
        <td></td>
    </tr>
</table>

#### Example:
```html
<h2>This is h2 text</h2>
<h3>This is h3 text</h3>
<h4>This is h4 text</h4>
<h5>This is h5 text</h5>
<h6>This is h6 text</h6>
<p>This is p text</p>

<h2>Latinh</h2>
<p>
    &nbsp;&nbsp;
    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Commodi qui, omnis id sunt nobis sit cumque nulla,
    eligendi
    adipisci, aperiam dolores voluptatum ratione suscipit? Beatae repellat architecto ducimus blanditiis maiores.
</p>

<h2>English</h2>
<p>
    &nbsp;&nbsp;&nbsp;
    The company itself is a very successful company. It will never be a just consequence to assume the softness of his
    flattery; Wherefore, because it is an exercise, it is bound for us to avoid any.
</p>
```
- - -

### Text formatting:
<table width="100%">
    <tr>
        <th>Tab</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>br</td>
        <td>This is normal text</td>
    </tr>
    <tr>
        <td><b>b</b></td>
        <td>This is <b>bold</b> text</td>
    </tr>
    <tr>
        <td><i>i</i></td>
        <td>This is <i>italic</i> text</td>
    </tr>
    <tr>
        <td><sub>sub</sub></td>
        <td>This is <sub>subscript</sub> text</td>
    </tr>
    <tr>
        <td><sup>sup</sup></td>
        <td>This is <sup>superscript</sup> text</td>
    </tr>
    <tr>
        <td><small>small</small></td>
        <td>This is <small>small</small> text</td>
    </tr>
    <tr>
        <td><big>big</big></td>
        <td>This is <big>big</big> text</td>
    </tr>
    <tr>
        <td><ins>ins</ins></td>
        <td>This is <ins>inserted</ins> text</td>
    </tr>
    <tr>
        <td><del>del</del></td>
        <td>This is <del>deleted</del> text</td>
    </tr>
    <tr>
        <td><mark>mark</mark></td>
        <td>This is <mark>marked</mark> text</td>
    </tr>
</table>

#### Example:
```html
<h2>This is normal text</h2>
<h2>This is <b>bold</b> text</h2>
<h2>This is <i>italic</i> text</h2>
<h2>This is <sub>subscript</sub> text</h2>
<h2>This is <sup>superscript</sup> text</h2>
<h2>This is <small>small</small> text</h2>
<h2>This is <big>big</big> text</h2>
<h2>This is <ins>inserted</ins> text</h2>
<h2>This is <del>deleted</del> text</h2>
<h2>This is <mark>marked</mark> text</h2>
```

- - -

### Link & images:
<table width="100%">
    <tr>
        <th>Tab</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>a</td>
        <td>Dùng thuộc tính href để dẫn đường liên kết</td>
    </tr>
    <tr>
        <td>img</td>
        <td>Dùng thuộc tính src để dẫn đường ảnh</td>
    </tr>
</table>

#### Example:
```html
<a href="https://www.example.com" target="_blank">Here is the link</a>

<img 
src="https://www.example.com" 
alt="This is an example and it works when the image fails"
>
```

- - -

### Lists
<table width="100%">
    <tr>
        <th>Tab</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>ul</td>
        <td>Dùng để chỉ định danh sách đánh thứ tự bằng số</td>
    </tr>
    <tr>
        <td>ol</td>
        <td>Dùng để chỉ định danh sách đánh thứ tự bằng gạch đầu dòng, có thể dùng thuộc tính type='A'</td>
    </tr>
    <tr>
        <td>li</td>
        <td>Dùng để viết thành danh sách</td>
    </tr>
    <tr>
        <td>dl</td>
        <td>Dùng để viết danh sách thông tin</td>
    </tr>
    <tr>
        <td>dt</td>
        <td>Dùng để viết tiêu đề trong thông tin danh sách</td>
    <tr>
        <td>dd</td>
        <td>Dùng để viết nội dung trong tiêu đề danh sách</td>
    </tr>
</table>

#### Example:
```html
<ul>
    <li>This is the list</li>
    <li>This is the list</li>
    <li>This is the list</li>
</ul>

<ol>
    <li>This is the list</li>
    <li>This is the list</li>
    <li>This is the list</li>
</ol>

<dl>
    <dt>HTML</dt>
    <dd>Add structure to webpage</dd>

    <dt>CSS</dt>
    <dd>Add style to webpage</dd>

    <dt>JAVASCRIPT</dt>
    <dd>Add functionality to webpage</dd>
</dl>
```

- - - 

### Table:

<table width="100%">
    <tr>
        <th>Tab</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>table</td>
        <td>Dùng để tạo khung bảng</td>
    </tr>
    <tr>
        <td>tr</td>
        <td>Dùng để tạo hàng của bảng</td>
    </tr>
    <tr>
        <td>th</td>
        <td>Dùng để tạo tiêu đề</td>
    </tr>
    <tr>
        <td>td</td>
        <td>Dùng để tạo nội dung</td>
    </tr>
</table>

#### Example:
```html
<table border="2px">
    <tr>
        <th width="70px">Top</th>
        <th>Hentai Name</th>
    </tr>
    <tr>
        <td align="center">1</td>
        <td>Shooting sperm into the beautiful and lustful sister's pussy</td>
    </tr>
    <tr>
        <td align="center">2</td>
        <td>Fucking her beautiful, seductive cousin</td>
    </tr>
    <tr>
        <td align="center">3</td>
        <td>Orgy with beautiful and delicious sisters</td>
    </tr>
</table>
```

- - -

### Audio:
<table width="100%">
    <tr>
        <th>Tab</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>audio</td>
        <td>Dùng tạo thanh điều khiển audio</td>
    </tr>
    <tr>
        <td>source</td>
        <td>Dùng để link tới file audio</td>
    </tr>
</table>

#### Example:
```html
<audio src="tieng-ren-cua-em-ho.mp3" controls muted loop autoplay></audio>
```

- - -

### Video:
<table width="100%">
    <tr>
        <th>Tab</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>video</td>
        <td>Dùng tạo thanh điều khiển video</td>
    </tr>
    <tr>
        <td>source</td>
        <td>Dùng để link tới file audio</td>
    </tr>
</table>

#### Example:
```html
<video src="bo-me-di-vang-phai-o-nha-cung-em-ho.mp4" controls muted autoplay loop></video>
```

- - -

### Button:

#### Example:
```html
<button onclick="doSomeThing()">Click me!</button>
```

- - -

### Label:

#### Example:
```html
<label for="id-name"></label>
```

- - -

### Input:

#### Example:
```html
<input type="text" id="myInputText">
<input type="email" id="myInputEmail" required>
<input type="tel" id="myInputtel" required>
<input type="password" id="myInputpassword" required>
<input type="checkbox" id="myInputcheckbox" required>
<input type="date" id="myInputdate">
<input type="number" id="number" min="1" max="99" value="1">
<input type="range" id="myInputrange">
<input type="file" id="myInputfile">
<input type="reset" id="myInputText">
<input type="submit" id="myInputText">
```

- - -

### Select:

#### Example:
```html
<select name="Hentai" id="hentai-list">
    <option value="TOP-10">Amakano</option>
    <option value="TOP-9">Tamashii Insert</option>
    <option value="TOP-8">Kyonyuu Hitozuma Onna Kyoushi Saimin</option>
    <option value="TOP-7">Baka Dakedo Chinchin Shaburu no dake wa Jouzu na Chii-chan♡</option>
    <option value="TOP-6">Tsumamigui 3 the Animation (Wife Eater 3)</option>
    <option value="TOP-5">Dropout</option>
    <option value="TOP-4">Amakano</option>
    <option value="TOP-3">Pretty x Cation the Animation</option>
    <option value="TOP-2">Shoujo Ramune</option>
    <option value="TOP-1">Yokosou! Sukebe Elf no Mori e</option>
</select>
```

- - -


