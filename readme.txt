һ�����ܽ���

��Ҫ���ڻ�����Ϣ�ɼ����ɼ�����Ϣ������
(1).Ӳ�������Ϣ��CPU���ڴ棬���磬�洢ϵͳ���
(2).ϵͳ���أ����縺�أ�CPU���أ��ڴ�ռ�����
(3).����ʹ�����ϵͳ����
(4).����ϵͳ�����Ϣ����������ϵͳ���汾��32λ��64λ
(5).���ֱ��ݴ���ģ��İ汾����Ͱ�װ·��
����ͨ�������в�����ָ�������ĳһ�

 
����	              ����	                                    ����˵��
  

������Ϣ	-v   �Cversion                    		 �ű��汾��Ϣ
	       	 -a   -all	                                 ��ȡ�������Ļ�����Ϣ
	        -f   -file=[path]	                        ����ȡ�û���������Ϣ�ŵ�ָ�����ļ��У���xml�ļ���ʽ��ţ�Ĭ��:info.xml
	        -h -help	                                ��ʾ�����ĵ�





Ӳ��������Ϣ	
        	   -u  -uname	                                        ��ʾ����ϵͳ��Ϣ������ϵͳ���͡��������������汾��ϵͳ�汾�š����������͡���������Ϣ���磺('Windows', 'pan-PC', '7', '6.1.7601', 'AMD64', 'Intel64 Family 6 Model 58 Stepping 9, GenuineIntel')
 		-A -architecture	                       �����ܹ�������λ�������ӷ�ʽ���磺('64bit', 'WindowsPE')
		-c -cpu	                                        ��ȡcpu��Ϣ(�磺Intel(R) Xeon(R) CPU E5-2603 v2 @ 1.80GHz)
		-n -network	                                �������Ϣ��������Ϣ��ip��ַ��������mac��ַ�������������
		-m -memory	                                �ڴ���Ϣ�������ڴ棬�����ڴ棩
		-d -disk	                              ���̵Ļ�����Ϣ����ʹ�������	
       	 	-N �Cnetwork I/O	                      ϵͳ���������ܣ�����bytes_sent�������ֽ�������bytes_recv�������ֽ�������packets_sent���������ݰ�������packets_recv���������ݰ������ȣ�
		-D �Cdisk  I/O	                              ���̶�дI/o������IO��Ϣ����read_count����IO������write_count��дIO������read_bytes��IO���ֽ�������write_bytes��IOд�ֽ�������read_time�����̶�ʱ�䣩��write_time������дʱ�䣩�ȣ�



����Դ�Ļ�����Ϣ	
 		�Cmysql                 	 ��ʾ������mysql�Ļ�����Ϣ���汾������װ·�������ݴ洢·������������־�Ƿ�������������־·����
		-oracle  			��ʾ������oracle�Ļ�����Ϣ���汾������װ·�������ݴ洢·����
	     	�Cdb2				��ʾ������db2�Ļ�����Ϣ���汾������װ·�������ݴ洢·����
		-sybase				��ʾ������sybase�Ļ�����Ϣ���汾������װ·�������ݴ洢·����
		-sqlserver			��ʾ������sqlserver�Ļ�����Ϣ���汾������װ·�������ݴ洢·����


����ʹ��˵��

1����Ҫ���ذ�װpsutil�⣬���ص�ַURL��https://pypi.python.org/pypi/psutil#downloads

2��windwosϵͳ��Ҫ֧��WMI�����ص�ַURL��https://pypi.python.org/pypi/WMI/#downloads

�����������

1.win7 mysql5.1  ����           ��mysql��ͨ��mysqld�����ȡ��Ϣ�ģ�

2.readhat5.6  mysql5.0.77 ����

3.windwos server 2008   oracle11.2.0.1.0 ���� ����windowsϵͳ����ͨ����ѯoracl.exe��������ȡ��Ϣ�ģ�

4.centos6.4  oracle11.2.0.1.0 ���� ����linuxϵͳ����ͨ����ѯoracle�ļ�������������ȡ��Ϣ�� �� 

5.windows server 2003  sqlserver2005  ������ͨ�����sqlservr.exe��������ȡ��װ·����

6.windows server 2003  sybase ase1254 ������ͨ�����sqlsrvr.exe��������ȡ��װ·����

7.SunOS  sunv440        ��֧��