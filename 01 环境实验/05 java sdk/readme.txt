0 ǰ�� 
 fabric ����������
 ./network_setup.sh up

1 ����java-sdk�ٷ�����
https://github.com/hyperledger/fabric-sdk-java/tree/release-1.2
git clone -b release-1.2 https://github.com/hyperledger/fabric-sdk-java.git
git clone -b release-1.2  https://gitee.com/xugy/fabric-sdk-java-object.git

2 �޸�pom.xml
��properties�м�������һ�仰��
<os.detected.classifier>windows-x86_64</os.detected.classifier>

3 ����maven���� 
--���빤��
mvn install 

--��������
--ɾ��.project �� .classpath�ļ� 
--��������
mvn eclipse:eclipse

--���빤��
ȷ��maven ���� ͬeclipse 


https://gitee.com/xugy/fabric-sdk-java-object.git


4 ���й���
--�޸�����
TestConfig.java
1. LOCALHOST ��ӦIP 

	
5 ���в���
	End2endIT.java


6 ע������
 1) ʱ��ͬ������ʱ�䱣��һ��



https://github.com/xiangxingchina/study.git


 x

Failed to read the project description file (.project) for 'fabric-sdk-java'.  The file has been changed on disk, and it now contains invalid information.  The project will not function properly until the description file is restored to a valid state.
