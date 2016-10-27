# 天工收银 SDK
#####  天工收银目前支持 alipay  wxpay  wxpay_jsapi  chinapay_b2c  chinapay alipay_wap
#####  其中alipay_wap 没有return_url  这个受限于支付宝  wxpay_jsapi 使用curl方式提交交易数据 详情在相应代码中

#### 支付回调参数

```php
amount=0.01                         //金额
bank=                               //银行
buyer=134%2A%2A%2A%2A0087           //账号所有人
buyer_openid=                       //账号所有人open_id
channel=alipay_pinganpay            //支付方式
charge_id=s3jrnfdvgwagn35mvvkdmo7c  //订单唯一标识
code=123                            //
device_info=                        //
is_success=true                     //是否支付成功
metadata=                           //备注信息
order_no=7baf7cd34f71733ba1946fc6   //
pay_time=1477580832                 //支付时间
payment_no=2016102723064902010072479276   //
real_amount=0.01                    //真实金额（扣去费率)
sign=101C1CE110CCCC61A553028BA1F54AA1   //j验签
status=                             //
timestamp=1477580832                //支付时间
```

