# StringSpli
 = SpamDetector($test)  ConsoleWrite($Output &amp; @CRLF) ; 1 = Spam , 0 = No Spam   Func SpamDetector($Text)     Local $Output = 0 , $tmp , $tmp2 , $tmp3 , $aTmp2[1][2] , $aTmp[1]     $aTmp[0] = 0     $aTmp2[0][0] = 0     $tmp = StringSplit($Text,@CRLF,1)     For $a = 1 To $tmp[0]         $tmp2 = StringSplit($tmp[$a]," ",1)         For $a2 = 1 To $tmp2[0]
