1. ��̬ѧ����
     ��ʴ: imerode   ȥ���߽�㣬������
     ����: imdilate    ��ն�
     ������: imopen   �ȸ�ʴ��������
        smooth boundaries, narrow isthmuses broken, and eliminate small noise regions
     ������: imclose  �����ͣ���ʴ 
        smooth boundaries, narrow gaps joined, and fill small noise holes
    Morphology methods perform  quite  well  in  general  for removing noise in binary 
    images. In case of document images,  however, they  may  significantly  damage  the 
    sharpness of the text and graphics components.

2. kFill filter 
    It's designed specifically for document images to reduce salt-and-pepper noise while 
    maintaining readability.
    kfill: The original kFill filter
    kfill_m: a single iteration filter based on kFill