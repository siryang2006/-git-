./while.bat https://username@xxx.git

::while.bat
for /l %%i in (1,1,100) do (git clone %1)
