// Helper.php

Line 309 code must be :
$_avatar = $_avatar ? '<img border="0" height="50" width="50" align="middle" src="' . $_avatar . '"  />' : '' ;
instead of : $_avatar = $_avatar ? '<img src="' . $_avatar . '" border="0" height="50" width="50" align="middle" />' : '' ;
