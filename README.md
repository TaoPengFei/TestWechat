# TestWechat
С����ͬѧ��΢�Ź��ںſ���֮·:smirk:  

## ��һ�� С����ȹ��Ŀ� :blush:
 - 1.����org.xmlpull.v1.XmlPullParserException��
     - xstream�������ģ���Ҫͬʱ����xmlpull_xx.jar������
 - 2.������Ϣû��Ӧ
     - ��鷵����Ϣ�ı�Ԫ�ؽڵ��Сд����[TextMessage.java](https://github.com/WuqingVika/TestWechat/blob/master/src/com/wq/po/TextMessage.java)���������ֶδ�д����һ��ʼСд�ġ�
 - 3.��������
     - ����req��respΪutf-8�����[WechatServlet.java](https://github.com/WuqingVika/TestWechat/blob/master/src/com/wq/servlet/WechatServlet.java)�е�doPost����ǰ���д��롣
 
 
## �ڶ��� ��������
 - 1.���ںſ�������׼��
     - natappע�ᡢʵ����֤,����natapp.exe;
     - ����ѧϰ����https://natapp.cn/ ����������
     - ����config.ini�ŵ�natapp.exe�ļ�ͬ��Ŀ¼������accessToken����
     - ����natapp.exe ���������Ӧ����Ϣ����ӳ��ɹ��ˡ���֤���������Խ�localhost:8080�滻��ӳ���ĵ�ַ�ܷ��ʾ����ˡ�

 - 2.����������Ϣ����
     - ��дУ��Signature�ࣺ[CheckUtil.java](https://github.com/WuqingVika/TestWechat/blob/master/src/com/wq/util/CheckUtil.java)(����checkSignature��sha1���ܷ���)
     - ��д[WechatServlet.java](https://github.com/WuqingVika/TestWechat/blob/master/src/com/wq/servlet/WechatServlet.java)(����doget��dopost����)
     - ��д[MessageUtil.java](https://github.com/WuqingVika/TestWechat/blob/master/src/com/wq/util/MessageUtil.java),������xmlת�� Map���ϡ����ı���Ϣ ת����xml�ķ�����
     - �����Լ�΢�����ںŷ����ı����ܷ����ط��͵��ı���Ϣ��

 - 3.��ʾ�����˵�
     - �޸�[MessageUtil.java](https://github.com/WuqingVika/TestWechat/blob/master/src/com/wq/util/MessageUtil.java)�ࣺ(������Ϣ�����ֶΡ��������˵�����������ı���Ϣ�����������һ�Ͷ�)
     - ���ùؼ��ֱַ���:1��2����Ӣ���ʺţ����ض�Ӧ����Ϣ
����git