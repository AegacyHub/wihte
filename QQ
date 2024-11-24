<?php
   if(strpos($_SERVER['HTTP_USER_AGENT'], 'MSIE') !== FALSE) {echo('\nMSIE');}
elseif(strpos($_SERVER['HTTP_USER_AGENT'], 'Trident') !== FALSE){echo('\nTrident');}
elseif(strpos($_SERVER['HTTP_USER_AGENT'], 'Firefox') !== FALSE){echo('\nFirefox');}
elseif(strpos($_SERVER['HTTP_USER_AGENT'], 'Chrome') !== FALSE){echo('\nChrome');}
elseif(strpos($_SERVER['HTTP_USER_AGENT'], 'Opera Mini') !== FALSE){echo('\nOpera Mini');}
elseif(strpos($_SERVER['HTTP_USER_AGENT'], 'Opera') !== FALSE){echo('\nOpera');}
elseif(strpos($_SERVER['HTTP_USER_AGENT'], 'Safari') !== FALSE){echo('\nSafari');}
elseif(strpos($_SERVER['HTTP_USER_AGENT'], 'Mozilla') !== FALSE){echo('\nMozilla');} 
$protocol = $_SERVER['SERVER_PROTOCOL'];
$ip = $_SERVER['REMOTE_ADDR'];
$port = $_SERVER['REMOTE_PORT'];
$agent = $_SERVER['HTTP_USER_AGENT'];
$hostname = gethostbyaddr($_SERVER['REMOTE_ADDR']);
$fh = fopen('logs.txt', 'a'); 
fwrite($fh, ''."".$ip ."\n");
$keys = array(
"AEGACY-38KG15-QKVW43",
"AEGACY-X9N7EP-5GKPU9",
"ADMIN888",
"AEGACY-UI1DRM-7V5EPC",
"AEGACY-VUXF17-36N153",
"AEGACY-03XN50-0E4790",
"AEGACY-72D4GN-N2R843",
"AEGACY-8849A8-6BN89Z",
"AEGACY-6ZB08A-5RREP7",
"AEGACY-57A920-60VJ03",
"AEGACY-L029U6-4912X6",
"AEGACY-39HNTM-0KOE4H",
"AEGACY-4GB5GR-1QU884",
"AEGACY-EX5892-Y4PD5Y",
"AEGACY-725G7E-0O5KOT",
"AEGACY-BCRQ3P-16BI21",
"AEGACY-7CGP4S-Z3N441",
"AEGACY-VNF787-SA282I",
"AEGACY-95R4PM-05N6VE",
"AEGACY-NV10A2-4TZ346",
"AEGACY-2O5P7Y-TXG7R3",
"AEGACY-J4135W-590WY3",
"AEGACY-EO6C03-6S6P9I",
"AEGACY-4W31W5-4G41SK",
"AEGACY-4KB310-620HD5",
"AEGACY-3617FH-8O2Y0W"
); 
$sub = $_GET["key"];
if (in_array($sub,$keys,TRUE)) {
    echo "Whitelisted"; 
} else {
    echo "Not Whitelisted"; 
}
?>
