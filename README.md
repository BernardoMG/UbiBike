# UbiBike
 
 UbiBike  is  a  mobile  application  that  allows  cyclists  to  earn  and  share  points  as  they  cycle. Cyclists  earn  points  by  cycling  (more  traveled  distance  translates  into  more  earned  points).  Additionally,  cyclists  can:

 - send/receive  points  to/from  other  cyclists;
 - send/receive  text  messages  to/from  other  cyclists
 
 Communication between cyclists (sharing points and exchanging text messages) is done through WiFi Direct. The  target  platform  for  UbiBike  is  Android  version  >=  4.0.

The  UbiBike  application  is  responsible  for  tracking  the  trajectory  (using  GPS)  while  cycling.    The  tracking  starts  when the user approaches the bike. Using GPS, UbiBike tracks the distance (and trajectory) traveled using the bike  and stops when the user moves away from the bike. Each bike has attached a BLE (Bluetooth Low Energy) beacon  sticker, which allows UbiBike to detect when the user is using a (specific) bike or not. 
Bikes are picked and dropped at parking stations. All users must register (using UbiBike) in a central server. The  server  knows  about  all  users  currently  registered  in  the  system,  including  their  current  score  (total  number  of  points)  and  trajectories.  This  data  (score  and  trajectories)  is  opportunistically  uploaded  by  the  UbiBike  app  (running  on  users'  device)  to  the  central  server.  Additionally,  by  contacting  the  central  server,  the  mobile  application can be used to book an available bike from a particular parking station. 
