# ��Ŀ�������
* ����Ŀ����[appium](https://github.com/appium/appium)��[Selenium](https://github.com/SeleniumHQ/selenium)��Դ���߷�װ���ɵ��Զ���app��web���Թ���

# ����
* ���ǻ���python3
* ���ǻ���webdriver���󲿷ִ��붼����ͨ�ã�ֻ�������ļ���һ��
* APP����˳��õ�men,cpu,fps
* ����ά���õ�YMAL
* �ʼ�����excel�Ĳ��Ա���

# �÷�

**������Ŀ:**

```
git clone git@github.com:284772894/appiumn_auto.git
```

**����ini**

```
[DEFAULT]
selenium_appium=appium
[appium]
devices=DU2TAN15AJ049163
Remote=127.0.0.1
appiumjs=node D:\\app\Appium\\node_modules\\appium\\bin\\appium.js
port=4723
[selenium]
selenium_jar = java -jar D:\\app\\appium_study\\img\\selenium-server-standalone-3.0.1.jar
sel_remote=http://127.0.0.1:4444/wd/hub
open_url=http://182.254.228.211:9000/index.php/Admin/index/login.html
```

**��������ymal**

* [case��api](mark.md)

```
--- 
- 
  element_info: cn.ibona.t1_beta:id/start_button
  find_type: by_id
  operate_type: click
  test_id: 1002
  test_intr: ��½
- 
  element_info: cn.ibona.t1_beta:id/passwordEditText
  find_type: by_id
  operate_type: send_keys
  test_id: 1002
  text: 111111
- 
  element_info: cn.ibona.t1_beta:id/phoneNumberEditText
  find_type: by_id
  operate_type: send_keys
  text: 18576759587
- 
  element_info: cn.ibona.t1_beta:id/loginButton
  find_type: by_id
  operate_type: click
- 
  element_info: cn.ibona.t1_beta:id/toolbar
  find_type: by_id

```



**����������:**

```
pyhton testRunner/runner.py
```

# ʹ�ý�ͼ

* ���з�ʽ

![run.gif](img/run.gif "run.gif")

* APP�������

![app.gif](img/app.gif "app.gif")

* ���չʾ

![testEmail.png](img/testEmail.png "testEmail.png")

![1.png](img/1.png "1.png")

![2.png](img/2.png "2.png")


# ����
* ������Ϣ�鿴�ҵ�[������־](channel_log.md)






