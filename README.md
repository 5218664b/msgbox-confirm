# msgbox-confirm
自定义alert,confirm

### 如果你会handlebars，可以用模板写弹出的html，而不用在js里面拼接，这里的handlebars被我注释了
  

# example
  $.MsgBox.Alert("提示","请输入xxx");
  
  $.MsgBox.Confirm("提示","请输入xxx",function () {
      console.log('dddd');
  });

  $.MsgBox.CustomizeConfirm("提示","请输入xxx","button1","button2",function () {
    console.log('dddd');
  },function () {
    console.log(1231);
  });
