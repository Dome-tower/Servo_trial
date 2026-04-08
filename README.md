trying to figure out the servo nature and logic using arduino uno to connect
this uses C++ language
 what did i learn ?
1. sg90 cant handle 3.3v, only use 5.5v
2. the maximum angle the servo use is 180 degree
3. each servo can only handle limited torque, so even if the volatage is constant it can only hadle a certain limit of current
4. torque needs current and speed of the arm in servo needs proper voltage
5. in the for loops it should go something like this [ for( intialization, condition, increment ) ]
