��Ѷ΢������ƽ̨C# SDK
֧�ֻ��� windows xp�� windows 7  (VS2010, .NET 4.0,  �Ͱ汾��.Net��Ҫ�Լ��ֶ�����)


���ߣ� heloyue
���ڣ� 2011-06-20



�������ã��ֳ���������QWeiboSDK �� QAPITool

QWeiboSDK 

SDK ��Ϊ�����㼶
	��һ���� QWeiboRequest.cs �ṩ��ͬ���첽���ַ��������Ļ����ӿڣ�SyncRequest��AsyncRequest�����������ӿڿ������ԱȽ�ǿһЩ��ͬʱ��Ҫ���õĲ���Ҳ�Ƚ϶ࡣ
	�ڶ������ڵ�һ���ӿ��Ϸֱ�ʵ���˸���api�� �����Ƕ�Ӧ��ϵ
		 QauthKey.cs  	OAuth ��Ȩ
		 statuses.cs  	ʱ����
		 t.cs		΢������
		 user.cs, 	�ʻ�����	
		 friends.cs	��ϵ������
		 private.cs	˽������
		 search.cs	��������
		 trends.cs	�ȶȣ�����
		 info.cs	���ݸ�������
		 fav.cs		�����ղ�
		 ht.cs		��������
		 tag.cs		��ǩ����
		 other.cs 	����

         ������api �� ��api��Ӧ��uri�ж�Ӧ��ϵ�����磬ʱ���ߵ�uriΪ statuses/xxxx��statuses/home_timeline����  ��ô����Ӧ�Ľӿ���Ϊstatuses, ����Ӧ�Ľӿ�Ϊxxxx() 
	  ��home_timeline().

QAPITool
	�ǲ������̣�ѡ���������Ƚ��д����ԵĽӿ�����Ӧ����ʾ����һΪ��ҳʱ����statuses/home_timeline��GET��, ������t/add_pic����һ����ͼƬ��΢����POST, ��ͼƬ���� �����ӿ�ʹ�������������ơ�ps һ�£�������verifierҪ���������е�ַ����ȥȡ��



����ѡ�

Ŀǰ�ṩ��������ѡ�� Debug �� Release

