# 2026teamProgram
# 2026teamProgram
el codigo del robok funciona asi:
primero los controles los programa segun el gusto del driver
GAMEPAD 1: MOVIMIENTOSS
| Control              | Función                      
| Joystick izquierdo ↑ | Avanzar                      
| Joystick izquierdo ↓ | Retroceder                   
| Joystick derecho ←   | Girar izquierda              
| Joystick derecho →   | Girar derecha                
| Y                    | Reiniciar referencia del IMU 
 GAMEPAD2 MECANISMOS
  BotONES      | Función                           
 R1       Lanzadora arriba ON/OFF           
 L1       Lanzadora abajo ON/OFF            
 X        Recolectora hacia adelante ON/OFF 
 B        Recolectora reversa ON/OFF        
 A        Banda hacia adelante ON/OFF       
 Y        Banda reversa ON/OFF              
 D-Pad    Escalador subir ON/OFF            
 D-Pad    Escalador bajar ON/OFF            
 Mi programa está dividido en dos partes principales: el drivetrain y los mecanismos. El Gamepad 1 controla el movimiento del robot mediante los joysticks, mientras que el Gamepad 2 controla la recolectora, banda, lanzadoras y escalador mediante botones configurados como toggle. También implementé un IMU para conocer el yaw, pitch y roll del robot. Utilizo el yaw con un control proporcional para corregir pequeñas desviaciones mientras avanzamos y el pitch para reducir la potencia cuando detectamos una inclinación que pueda provocar un caballito. ya de ultimo, utilizo telemetría para monitorear el estado de todos los mecanismos y los valores del IMU
