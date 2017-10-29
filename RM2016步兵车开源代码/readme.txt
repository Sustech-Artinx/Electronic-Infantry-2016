该代码与RoboMasters官方提供的一代步兵车配合使用，集成编译环境为keil,所使用的单片机为意法半导体公司所生产的stm系列单片机。打开云台后盖可以看到该战车的控制板。
该代码主要功能为：能够通过遥控器控制该机器人平台的前后左右，原地旋转等移动，或者当遥控器连接到电脑后，操作手能够通过电脑控制机器战车。同时还能够控制战车的发射机构的运行，参加ICRA的队伍可以根据自己需求，拆解战车。
战车上有4个底盘电机，2个云台电机，2个摩擦轮电机，1个拨弹电机。
其中底盘电机为无刷电机加减速箱，云台电机为无刷直驱电机，摩擦轮电机为无感无刷电机，拨弹电机为直流减速电机。
其中底盘电机与云台电机通过Can总线控制，其余电机都是直接从主控板控制。

The code below used for the Infantry provided by Robomasters official uses Keil uVision5 as integrated compilation environment; STM series product produced by STMicroelectronics as microcontroller. The main controlling board can be seen once the gimbal lid is being opened.

The main functions of the code conclude: 
1)	Remote control, enable the infantry to have serials movement include forward, backward, turn left, turn right, left shift and right shift, or
2)	Enable keyboard control when connect the remote controller to a computer;
3)	Cannon system control, shoot plastic bullet.
The infantry, based on the requirements of the team who participating ICRA MMC, can be dismantled.

Four chassis motors (brushless with reduction gearbox), two gimbal motors (brushless direct drive), two motors for friction wheels (non-inductive brushless), one pulling motor (DC geared motor) have been assembled in an Infantry. Furthermore, chassis motors and gimbal motors are controlled through CAN-BUS, the others are being controlled by main controlling board directly.