�ô�����RoboMasters�ٷ��ṩ��һ�����������ʹ�ã����ɱ��뻷��Ϊkeil,��ʹ�õĵ�Ƭ��Ϊ�ⷨ�뵼�幫˾��������stmϵ�е�Ƭ��������̨��ǿ��Կ�����ս���Ŀ��ư塣
�ô�����Ҫ����Ϊ���ܹ�ͨ��ң�������Ƹû�����ƽ̨��ǰ�����ң�ԭ����ת���ƶ������ߵ�ң�������ӵ����Ժ󣬲������ܹ�ͨ�����Կ��ƻ���ս����ͬʱ���ܹ�����ս���ķ�����������У��μ�ICRA�Ķ�����Ը����Լ����󣬲��ս����
ս������4�����̵����2����̨�����2��Ħ���ֵ����1�����������
���е��̵��Ϊ��ˢ����Ӽ����䣬��̨���Ϊ��ˢֱ�������Ħ���ֵ��Ϊ�޸���ˢ������������Ϊֱ�����ٵ����
���е��̵������̨���ͨ��Can���߿��ƣ�����������ֱ�Ӵ����ذ���ơ�

The code below used for the Infantry provided by Robomasters official uses Keil uVision5 as integrated compilation environment; STM series product produced by STMicroelectronics as microcontroller. The main controlling board can be seen once the gimbal lid is being opened.

The main functions of the code conclude: 
1)	Remote control, enable the infantry to have serials movement include forward, backward, turn left, turn right, left shift and right shift, or
2)	Enable keyboard control when connect the remote controller to a computer;
3)	Cannon system control, shoot plastic bullet.
The infantry, based on the requirements of the team who participating ICRA MMC, can be dismantled.

Four chassis motors (brushless with reduction gearbox), two gimbal motors (brushless direct drive), two motors for friction wheels (non-inductive brushless), one pulling motor (DC geared motor) have been assembled in an Infantry. Furthermore, chassis motors and gimbal motors are controlled through CAN-BUS, the others are being controlled by main controlling board directly.