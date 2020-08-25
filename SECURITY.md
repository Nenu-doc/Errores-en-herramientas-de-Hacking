<!DOCTYPE html>
<html>
<head>
          <title>Herramientas de Hacking</title>
    </head>       
             
             
       <h1><strong> Terminal Termux para Android </strong></h1>
    
    <body>
        <article>
        
        
            #! /data/data/com.termux/files/usr/bin/bash/

clear
<!--#este code esta corregido por Juan angel Luzardo-->

#variables



				red='\033[1;31m'                                        green='\033[1;32m'                                      yellow='\033[1;33m'                                     blue='\033[1;34m'                                       magenta='\033[1;35m'                                    cyan='\033[1;36m'                                       reset='\033[0m'

printf $cyan
figlet -f smslant hacktaller | lolcat
printf $blue
echo "AUTOR:    Juan Angel Luzardo"
echo "TOOL:     HACKTALLER"
echo "VERSION:  1.0"
    

echo ""
#opciones
</article><br /><br />


<article>
echo -e "\e[0;34m[01]\033[1;33mFRAMEWORK METASPLOIT      \033[0;34m[11]\033[1;33mFRAMEWORK HAKKU"
echo -e "\e[0;34m[02]\033[1;33mFRAMEWORK SQLMAP          \033[0;34m[12]\033[1;33mFRAMEWORK PHONEINFOGA"
echo -e "\e[0;34m[03]\033[1;33mFRAMEWORK A-Rat           \033[0;34m[13]\033[1;33mFRAMEWORK TH3INSPECTOR"
echo -e "\e[0;34m[04]\033[1;33mFRAMEWORK XERXES          \033[0;34m[14]\033[1;33mFRAMEWORK GOOGLE-DORKS"
echo -e "\e[0;34m[05]\033[1;33mFRAMEWORK SAYCHEESE       \033[0;34m[15]\033[1;33mFRAMEWORK WIFITE"
echo -e "\e[0;34m[06]\033[1;33mFRAMEWORK SHELLPHISH      \033[0;34m[16]\033[1;33mFRAMEWORK IPSCAN"
echo -e "\e[0;34m[07]\033[1;33mFRAMEWORK WEEMAN          \033[0;34m[17]\033[1;33mFRAMEWORK EVIL-URL"
echo -e "\e[0;34m[08]\033[1;33mFRAMEWORK RED_HAWK        \033[0;34m[18]\033[1;33mFRAMEWORK SQLISCAN"
echo -e "\e[0;34m[09]\033[1;33mFRAMEWORK IP-GEOLOCATION  \033[0;34m[19]\033[1;33mFRAMEWORK THE-FAT-RAT"
echo -e "\e[0;34m[10]\033[1;33mFRAMEWORK TBOMB-EMAIL     \033[0;34m[00]\033[1;33mEXIT"
</article>


<article><br />
function reiniciar {
        echo $(clear)
        bash $HOME/HACKTALLER/HACK-TALLER
}



echo ""                                                 #Menu
echo -e "\e[1;36m"
echo -n "SELECT YOUR FRAMEWORK #>> ";

read opcion


trap ctrl_c INT
ctrl_c() {
clear
printf $yellow
echo "[ ] LOS FRAMEWORKS QUE INSTALASTE"
echo "[ ] ESTAN EN EL DIRECTORIO DE HERRAMIENTAS"
echo "[ ] GRACIAS POR USAR HACKTALLER "
echo "[ ] #BanderaBlancaHackingEtico"
printf $cyan
figlet -f smslant JWhiteFlag


exit

}
#Opciones
case $opcion in
01)echo ""
chmod +x $HOME/HACKTALLERJWhiteFlag.sh                    cd --
                                                        bash $HOME/HACKTALLER/JWhiteFlag.sh
</article><br />


<article>

          <h1> #INSTALANDO SQLMAP </h1>
02)git clone https://github.com/sqlmapproject/sqlmap.git
echo -e "${y} cd sqlmap-master;ls"
echo -e "${y} chmod +x sqlmap.py;ls"
echo -e "${y} python2 sqlmap.py"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
</article>


<article><br />

          <h1> #INSTALANDO A-RAT </h1>
03)git clone https://github.com/Xi4u7/A-Rat.git
echo -e "${y} cd A-Rat;ls"
echo -e "${y} chmod +x A-Rat.py;ls"
echo -e "${y} python2 A-Rat.py"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
</article>


              <h1> #INSTALANDO XERXES </h1>
<article>
04)git clone https://github.com/Dev0uss/xerxes.git
echo -e "${y} cd xerxes-master;ls"
echo -e "${y} chmod +x xerxes.c;ls"
echo -e "${y} gcc xerxes.c -o xerxes;ls"
echo -e "${y} ./xerxes www.nombredelapagina.com 80"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
</article><br />
;;
               <h1> #INSTALANDO SAYCHEESE </h1>
<article><br />
05)git clone https://github.com/thelinuxchoice/saycheese.git
echo -e "${y} cd saycheese;ls"
echo -e "${y} chmod +x saychees.sh;ls"
echo -e "${y} bash saycheese.sh"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
;;
</article><br />
            <h1> #INSTALANDO SHELLPHISH </h1>
<article><br />
06)git clone https://github.com/thelinuxchoice/shellphish.git
echo -e "${y} cd shellphish;ls"
echo -e "${y} chmod +x shellphish.sh;ls"
echo -e "${y} ./shellphish.sh"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
;;
</article><br />
                    <h1> #INSTALANDO WEEMAN </h1>
<article><br />  
                    
07)git clone https://github.com/evait-security/weeman.git
sleep 2.5
echo -e "${y} cd weeman;ls"
echo -e "${y} chmod +x weeman.py;ls"
echo -e "${y} python2 weeman.py"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
;;
</article>
                 <h1> #INSTALANDO RED HAWK </h1>
<article><br />
08)git clone https://github.com/Tuhinshubhra/RED_HAWK.git
echo -e "${y} Installer RED_HAWK..."
echo -e "${y} cd RED_HAWK "
echo -e "${y} php r_hawk.php"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
;;
</article><br />
                                                                      <h1>#INSTALANDO IPGEOLOCATION </h1>
<article><br />

09)git clone https://github.com/maldevel/IPGeoLocation.git
echo -e "${y} pip install --upgrade pip"
echo -e "${y} pip install -r requirements.txt"
echo -e "${y} chmod +x ipgeolocation.py"
echo -e "${y} python ipgeolocation.py"
echo -e "${y} python ipgeolocation.py -m"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
;;
</article><br />

<article><br />
            <h1> #INSTALANDO TBomb </h1>
10)git clone https://github.com/TheSpeedX/TBomb.git
echo -e "${y} cd TBomb"
echo -e "${y} chmod +x TBomb.sh"
echo -e "${y} ./TBomb.sh"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
;;
</article>


<article><br />      <h1> #INSTALANDO HAKKU </h1>

11)git clone https://github.com/4shadoww/hakkuframework.git
echo -e "${y} cd hakkuframework"
echo -e "${y} ./hakku"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
;;
</article>


<article><br />   <h1> #INSTALANDO PHONEINFOGA </h1>

12)git clone https://github.com/sundowndev/PhoneInfoga.git
echo -e "${y} cd PhoneInfoga"
echo -e "${y} chmod +x phoneinfoga.py"
echo -e "${y} pip install -r requirements.txt"
echo -e "${y} ./phoneinfoga.py"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
;;
</article>
       
       
             <h1> #INSTALANDO GOOGLE THEINSPECTOR </h1>

<article><br />
13)git clone https://github.com/Moham3dRiahi/Th3inspector.git
echo -e "${y} cd Th3inspector"
echo -e "${y} ./ainstall.sh"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
;;
</article>
       
               <h1> #INSTALANDO GOOGLE-DORKS </h1>
<article><br />
14)git clone https://github.com/XG77Z10/Google-Dork.git
echo -e "${y} cd Google-Dork"
echo -e "${y} chmod +x Google.py"
echo -e "${y} python2 Google.py"
echo -e "${y} INSTALADO.... "
sleep 3.5
reiniciar
;;
</article>


<article><br />      <h1> #INSTALANDO WIFITE </h1>

15)git clone https://github.com/derv82/wifite.git
echo -e "${y} cd wifite"
echo -e "${y} chmod +x wifite.py"
echo -e "${y} python2 wifite.py"
sleep 3.5
echo -e "${y} INSTALADO.... "
reiniciar
;;
</article><br />


                 <h1> #INSTALANDO IPSCAN </h1>
<article><br />
16)git clone https://github.com/sysadminteam/IPscan.git
echo -e "${y} cd IPscan"
echo -e "${y} chmod +x ipscan.sh"
echo -e "${y} ./ipscan.sh"
sleep 3.5                                               echo -e "${y} INSTALADO.... "
reiniciar
;;
</article><br />
         
                 <h1>  #INSTALANDO EVIL-URL </h1>
<article><br />
17)git clone https://github.com/UndeadSec/EvilURL.git
echo -e "${y} cd EvilURL"
echo -e "${y} chmod +x evilurl.py"
echo -e "${y} python evilurl.py"
sleep 3.5                                               echo -e "${y} INSTALADO.... "
reiniciar
;;
</article><br />
         

               <h1>  #INSTALANDO SQLISCAN </h1>
<article><br />
18)git clone https://github.com/thelinuxchoice/sqliscan.git
echo -e "${y} cd sqliscan"
echo -e "${y} chmod +x sqliscan.sh"
echo -e "${y} ./sqliscan.sh"
sleep 3.5
echo -e "${y} INSTALADO.... "
reiniciar
;;
</article><br />
         
               <h1>  #INSTALANDO THEFATRAT </h1>
<article><br />

19)git clone https://github.com/Screetsec/TheFatRat.git
echo -e "${y} cd TheFatRat"
echo -e "${y} chmod +x setup.sh && ./setup.sh"
echo -e "${y} chmod +x fatrat"
echo -e "${y} ./fatrat"
echo -e "${y} chmod +x powerfull.sh"
sleep 3.5                                               echo -e "${y} INSTALADO.... "
reiniciar
;;
</article><br />

<!--00)echo "AUTOR: JWhiyeFlag"
echo    "BaanderaBlancaHackingEtico"
printf $magenta
figlet -f smslant JWiteFlag-->


exit

;;

                                                        *) <!--Hecho "GRACIAS POR INSTALARLO, NO PUDISTE ROBAR INFORMACIÓN.  
"ESTA PENSADO Y CREADO CON EL OBJETIVO DE QUE TE CONOZCAS
Y CALMES ESA PARTE OSCURA DE TI. EL HACKING ES PARA AYUDAR
A CORREGIR ERRORES, NO PARA APROVECHARSE DE LAS PERSONAS" -->
                                                        sleep 2.5
                                                        reiniciar

esac
</section>
    
   </body>
</html>
