# css-表单样式

/*======覆盖苹果手机input提交样式======*/
input[type="submit"],input[type="reset"],input[type="button"]{ -webkit-appearance:none;}
/*ios系统中元素被触摸时产生的半透明灰色遮罩去掉*/
a,button,input,textarea{
    -webkit-tap-highlight-color: rgba(0,0,0,0);
    /*-webkit-user-modify:read-write-plaintext-only; */
}
