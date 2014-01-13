#!/bin/bash

echo "Aby przerwac nacisnij ctr +c , Dostepne radia to:"
select radio in tokfm luz jedynka dwojka trojka euro anty ram sfera zlote Zakoncz

do
    case $radio in
	"tokfm" ) adres="http://olsztyn.radio.pionier.net.pl:8000/z/radiotok4.ogg" ;;
	"luz" ) adres="http://radioluz.pwr.wroc.pl/listen.pls" ;;
	"jedynka" ) adres="mms://stream.polskieradio.pl/program1 ";;
	"dwojka" ) adres="mms://stream.polskieradio.pl/program2" ;;
	"trojka" ) adres="mms://stream.polskieradio.pl/program3" ;;
	"euro" ) adres="mms://stream.polskieradio.pl/program4" ;;
	"anty" ) adres="http://94.23.89.48:7000" ;;
	"ram" ) adres="http://poznan5-1.radio.pionier.net.pl:8000/radioram.mp3" ;;
	"sfera" ) adres="http://serv.radiosfera.pl:7098" ;;
	"zlote" ) adres="http://szczecin.radio.pionier.net.pl:8000/pl/zloteprzeboje.ogg" ;;
    "Zakoncz") exit ;;
  esac
break
done
mplayer $adres
