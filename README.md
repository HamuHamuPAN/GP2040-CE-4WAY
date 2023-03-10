# GP2040-CE | Community Edition Firmware＋４WAY Joystick Mode


Adds 4-way joystick function to GP2040-CE.
Oh ... SOCD function changed MPG ... orz


It operates as a mode of the SOCD function, and while it is set, it will not output anything other than up, down, left, and right.

After switching to SOCD-N mode by entering S1 (HOME) + R2 (START) + UP, you can switch to 4WAY-X mode by performing the same operation again.
Each time you repeat the same operation, SOCD-N and 4WAY-X modes are switched.
Similarly, S1 (HOME) + R2 (START) + DOWN switches SOCD-U to 4WAY-Y, and S1 (HOME) + R2 (START) + LEFT switches SOCD-L to 4WAY-L.

4WAY-X (X-axis priority mode)
If both the X-axis and Y-axis are input, the X-axis will be output with priority.
UP + RIGHT = RIGHT, 
UP + LEFT = LEFT, 
DOWN + RIGHT = RIGHT, 
DOWN + LEFT = LEFT
Both up/down and left/right inputs will output as neutral.

4WAYーY (Y-axis priority mode)
If both the X and Y axes are input, the Y axis will be output with priority.
UP + RIGHT = UP, 
UP + LEFT = UP, 
DOWN + RIGHT = DOWN, 
DOWN + LEFT = DOWN
Both up/down and left/right inputs will output as neutral.

4WAY-L (Latest input priority mode)
The last input direction is prioritized and output.
UP → UP + RIGHT = RIGHT, 
RIGHT → UP + RIGHT = UP


原文

GP2040-CEに４方向ジョイスティック機能を追加します。

SOCD機能のモードとして動作し、設定している間は上下左右以外の出力をしないようになります。

S1（HOME）＋R2（START）＋UPの入力でSOCDｰNモードにした後、もう一度同じ操作を行うことにより4WAYｰXモードに切り替わります。
同じ操作を繰り返す毎に、SOCD-Nと4WAYｰXモードが切り替わります。
同様にS1（HOME）＋R2（START）＋DOWNでSOCDｰUは4WAYｰYに、S1（HOME）＋R2（START）＋LEFTでSOCDｰLは4WAYｰLに切り替わります。

4WAYｰX（X 軸優先モード）
X軸とY軸が両方入力されている場合X軸を優先して出力します。
UP＋RIGHT＝RIGHT、UP＋LEFT＝LEFT、DOWN＋RIGHT＝RIGHT、DOWN＋LEFT＝LEFT
上下や左右 の両方の入力はニュートラルとして出力します。

4WAYｰY（Y 軸優先モード）
X軸とY軸が両方入力されている場合Y軸を優先して出力します。
UP＋RIGHT＝UP、UP＋LEFT＝UP、DOWN＋RIGHT＝DOWN、DOWN＋LEFT＝DOWN
上下や左右 の両方の入力はニュートラルとして出力します。

4WAYｰL（後入力優先モード）
最後に入力された方向が優先されて出力されます。
UP→UP＋RIGHT＝RIGHT、RIGHT→UP＋RIGHT＝UP
