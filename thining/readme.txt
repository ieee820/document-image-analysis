Thining/Skeletonizing/Core-line detection
  Goal: To reduce the image components to their essential information.
  Requirements:
   (1) connected image regions must thin to connected line structures
   (2) the thinned result sholud be minimally eight-connected
   (3) approximate endline locations should be maintained
   (4) the thinning results sholud approximate the medial lines
   (5) extraneous spurs(short branches) caused by thinning should be minimized
  Matlab Function: 
    bwmorph�������ڻ������ͣ���ʴ�Ͳ��ұ���������ʵ�ֶ��ֲ�����
    ������﷨:  g = bwmorph(f, operation, n) 
      ��operationΪskew/thinʱ��ִ��Skeltonizing/Thining
      ��Skeltonizing/Thining�����п��ܻ����һЩspurs(ë��),��
      ����operationΪspur��ȥ����Щë�̵�     