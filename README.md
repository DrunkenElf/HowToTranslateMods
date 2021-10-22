# HowToTranslateMods
Maybe a bit silly but working method to translate mods

1. Download dnSpy then run `dnSpy.exe`
2. Open mod's `.dll` file ![how_to_open](imgs/how_to_open.png)
    ![Screenshot_1](imgs/Screenshot_1.png)
3. Expand assembly ![expand](imgs/expand.png) then search for the part of the code which responsible for rendering 
4. Find some text that you want to translate ![foc_on_what_to_trans](imgs/foc_on_what_to_trans.png)
5. Right click on the line where this text located then select `Edit IL Instructions..` ![fo_editIl_inst](imgs/fo_editIl_inst.png)
6. Replace it with translated text and click `OK` ![editIl_ins1](imgs/editIl_ins1.png) ![editIl_ins2](imgs/editIl_ins2.png). You'll see that text has changed ![editIl_ins3](imgs/editIl_ins3.png)
7. Save changes ![save1](imgs/save1.png)
    - click `ok` on this screen ![save2](imgs/save2.png)
    
8. Profit ![result](imgs/result.png)

## Important moment
As wee see above, our translated text can overflow

To resolve this you can change size of the view on which text located ![some_side](imgs/some_side.png) 
