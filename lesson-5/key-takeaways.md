## anonymus fuction
- những hàm không tên thường được sử dụng một lần, gán cho biến, hàm ẩn danh
format: function(parameters){};
//function nameFUc(){};

## lambda function (arrorw fuction)
cú pháp viết ngắn ngọn hàm - cũng là một dạng hàm ẩn danh - dùng tính toán một hàm duy nhất - hàm tính toán từ một hàm khác và tính lại
thay vì dùng "function" thì sử dụng "=>"


//hàm có mộ tham số
let dup = x => {
    return x * 2;
}

// hàm có một biểu thức return
let dup2 = x => x*2;

// hàm không có tham số 
() => {
    console.log("");
}

## DOM
Document Object Model
tab Element - contain DOM 
in DOM - have node - element in this page
<option>HomePage</option>
<br> - thẻ xuống dòng tự đóng không có giá trị
thêm thuộc tính cho thẻ - cách ra và thêm thuộc tính
<option value="usa">HomePage</option>


## selectors
Xpath --> open dev tool --> ctrl+F 
- thêm chỉ số * xpath tuyệt đối * : sẽ có bất tiện là phải nắm phần tử trên DOM khi dev thay đổi thứ tự phảii tìm lại từ dầu mất thời gian
    ex:/html[1]/body[1]/div[1]
** Note:với nhưngx thẻ <iframe> --> để khỏi nhầm lẫn
    * xpath tương đối *: 
    //input[@id='username']
    //input[@type='text']

    *tìm theo text*
    //a[text()="User Registrator"]

    *dài thì tìm theo dạng contain text*
    //a[contain(text()="Bài học: Register Page")]

## PLAYWRIGHT synctax cơ bản 
- tenfile-syntax.spec.ts
- cú pháp:
        import {test-đưa dưới dạng object} from '@playwright/test';
        test("Tên testcase", async () =>{
                await test.step("Teen step", async () => {

                });
                await test.step("Teen step", async () => {

                });
                ....
        });

- basic action on webpage:
    navigatte: 
    test("Tên testcase", async (page) =>{
                await test.step("Teen step", async () => {

                });
                await test.step("Teen step", async () => {

                });
                ....
        });


