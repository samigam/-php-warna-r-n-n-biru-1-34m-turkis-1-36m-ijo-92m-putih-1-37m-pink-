<?php

//warna
$r="\n\n";
$biru="[1;34m";
$turkis="[1;36m";
$ijo="[92m";
$putih="[1;37m";
$pink="[1;35m";
$red="[1;31m";
$kuning="[1;33m";
$t="\n";
@system("clear");
system('gem install lolcat');
system('apt install toilet -y');
system('clear');
system("toilet --width 33 -f pagga -F border --gay '  earning premium ' && toilet --width 30 -f term -F border --gay '           SUBCRIBE                   Earning Premium      ' | lolcat&& toilet --width 34 -f term '[>] creator : Sami Gaming' -F gay | lolcat && toilet --width 34 -f term '[x] support : Earning Premium' | lolcat && toilet --width 38 -f term '[>] a propos de la discussion telegram[+] : @sami_gaming123 ' | lolcat && toilet --width 34 -f term '[-] support : @baleki13' | lolcat");
system("toilet --width 30 -f term -F border --gay '             BOT                        Spin_Wheel      ' | lolcat");


sleep(0); 
//Link
$link1 = "http://gkwallet.in/Posts/save_spin_task_Yr7ZjN045x8Bgl2B";


echo $turkis."⫸$putih Start Bot";
$ar=0;$is=5;while($ar<$is){
sleep(1);
$ar++;
echo $putih.".";
}
sleep(1);
echo $putih."✔".$r;
sleep(1);

//Platinum
function platinum($link1){ 
      $yn = array("1","2","3","4","5");
      require("cfg.php");
      $body = ''.$data.'';{ 
      $ch = curl_init(); 
curl_setopt($ch, CURLOPT_URL, $link1);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, 1);
$headers = array ();
			 $headers[] = "Content-Type: application/x-www-form-urlencoded; charset=UTF-8";
		curl_setopt($ch, CURLOPT_HTTPHEADER, $headers);
curl_setopt($ch, CURLOPT_POST, 1);
curl_setopt($ch, CURLOPT_POSTFIELDS, $body); 
$turkis="\033[1;36m";
$putih="\033[1;37m";
    $result = curl_exec($ch);
    curl_close($ch);
$json = json_decode($result, true);
echo $red."[✓] Claim Video : $turkis ".$json["msg"]."\n";
sleep(30);
 }
}
while (True){
platinum($link1);
}

?>
