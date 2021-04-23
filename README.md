# robo_danilo

## Instalação

Baixar o pacote no workspace do ROS:

> git clone https://github.com/AndreCid/robo_danilo.git

Compilar pacote:

> catkin_make #caso esteja usando catkin_make
> catkin build #caso esteja usando build

## Utilizar robô simulado

> roscore

> coppelia


> roslaunch robo_danilo robo_danilo.launch #habilita as transformadas entre o robo e os sensores 

**No simulador:**
- Na aba superior, selecione a aba _file_, e em seguida open scene. A cena e o modelo do robô estão disponíveis na pasta _modelos_ do pacote.
- De o play na simulação e veja se ocorreu tudo bem.

## Mandando comando de velocidade para o robô
> rosrun  teleop_twist_keyboard teleop_twist_keyboard.py 

