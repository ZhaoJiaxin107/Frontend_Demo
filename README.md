# Frontend_Demo
Interesting cases of frontend development

### Key Priciples for magnifiers
- When the mouse moves on the small picture, it can locate the corresponding position of the large picture by capturing the 
 position of the mouse on the small picture.

- The moving direction of magnifying glass is opposite to that of large picture horizontally and vertically

### How to design
* Page elements
* Technical points: event capture and location
* Difficulty: Calculation

### Technologies
* onmouseover: occurs when the mouse pointer moves over the specifed object
* onmouseout: occurs when the mouse pointer moves out the specified object 
* onmousemove: occurs when the mouse pointer move 
* offsetLeft | offsetTop | offsetWidth | offsetHeight
* event.clientX | event.clientY

### Comparision between offsetLeft and style.left
- style.left returns string, for example, 30px, while offsetLeft returns number 30.
- style.left can be read and written, and offsetLeft is read only. If we want to change the position of div, we can modify style.left.
- style.left should be defined in advance otherwise the value is null.

### Important
How to make the magnifying glass on the small picture move synchronously with the large picture.

