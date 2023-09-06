Using the `signal` keyword you can create new signals inside a script.
![[Pasted image 20230905190739.png]]
Using the `emit_signal()` method you can call this custom signals:
![[Pasted image 20230905190718.png]]

## Parameters
You can define parameters inside custom signals.
![[Pasted image 20230905193920.png]]
When emiting the custom signal with parameters defined, you need to provide the arguments on `emit_signal()` use, following the signal name:
![[Pasted image 20230905194052.png]]
When the signal is connected, arguments can be accesed as the connected function parameters:
![[Pasted image 20230905225158.png]]