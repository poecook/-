Android�¼��ַ�������
	�򵥽� Android �¼��ַ������Ѹ����������й�
	ontouchEvent
	ondispatchTouchEvent
	��onInterceptTouchevetnt
	viewGroup������������
	view��ȱ��onInterceptTouchEvent��
	
�����������з���ֵ
	Ĭ��������Ƿ��ص�false ������ִ��˳���� ������viewgroup ���� ondispatchTouchEvent������Ȼ�� onInterceptTouchevetnt Ȼ�������viewgroup��dispathTouchevent
	��onInterceptTouchevetnt ���view��OndispathTouchevent ��OntouchEvent ������OntouchEvent��������onTouchEvent
	
����������ְ��
	ondispatchTouchEvent �������ַ��� 
			��dispath����true�� ��ʾֹͣ�ַ�
			������false�ͱ�ʾ�����ַ� �����viewgroup�ͽ���onInterceptTouchevetnt�����view�ͽ���ontouchEvent
	onInterceptTouchevetnt �Ǹ������ص� 
			������trueʱ���ͽ���ontouchevent 
			������falseʱ,�ͽ�����һ���㼶��dispathTouchevent����
			
	ontouchEvent��������������
			������true �¼���������
			������false �¼��������ݸ���һ���㼶��ontouchEvent
			
	
���� ����view/viewgroup�ϰ��¼���ʱ�� ���OnTouchListener����ontouchevent֮ǰ�� ��� OnTouchListener�е�ontouch�¼�����false ��ᴥ�� ontouchevent �����¼����ٴ����ϲ�
		click�¼���������ontouch�¼�֮���
