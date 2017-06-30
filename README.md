# SMWallet
SMWallet动画波浪球(http://www.itssh.cn/)

SMWallet动画波浪球，依赖Jquery，有问题请发邮件：sm0210@qq.com

## 实例化SMWallet动画波浪球

## 效果

![](https://github.com/sm0210/SMWallet/blob/master/SMWallet.jpg "SMWallet")

## 实例化组件
````
  //配置信息
  var config = {
    //可配置参数：剩余额度标题，默认[剩余额度 (元)]
    amountTitle:'剩余额度 (元)',
    //必须参数：剩余额度，默认0.00
    amount:'3945.26',
    //必须参数：本月总额度，默认0.00
    total:'5000.00'
  };
  //实例化1
  var wa = $('#walletEl').initSMWallet(config);

  //实例化2
  config.amount = '2500.00';
  $('#walletEl2').initSMWallet(config);

  //实例化3
  config.amount = '1500.00';
  $('#walletEl3').initSMWallet(config);
 ````
 
 ## 重新渲染时间轴
````
    //reload 重新渲染
		var config2 = {};
		config2.amount = '4500.00';
		config2.amountTitle = 'reload渲染';
		wa.reload(config2);

 ````
 
 ###如果您觉得此文有帮助，可以打赏点钱给我支付宝sm0210@qq.com ，或扫描二维码
![](https://github.com/sm0210/SMCalendar/blob/master/sm0210%40qq.com.jpg "sm0210@qq.com")


