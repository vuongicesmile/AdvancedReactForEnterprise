
-- yarn add normalize - scss

B2 : ở global.scss 

tạo thêm base/_reset.scss : sau đó import vào

@import "node_modules/normalize-scss/sass/normalize/import-now" 

--------------------

default css that normalizes all browsers

--- sau đó ở thư mục global.css:
<p style="color:red;">Dòng 17 -21 </p>

/*==============================================
 =                   Base                      =
 =============================================*/

@import "base/reset";
