
Description: the scene which I send the message : I added the Spanish version of 'help online', the English and Spanish versions were placed in different folders under 'help' folder, switching to a different lanuage, dev need to modify the url of 'help online' manually.

Hi Marcelo,
I have added the translation(Spanish) of 'Help Online' into ux2.2. In fact, we only used the 'Help Online' in English before, and the modifications are:
1. Added two new folders under 'help' folder: en_US and es_ES, put the English version of 'help' into en_US and Spanish version into es_ES.
2. Modified the url of 'help', the path(eg. RUI) changed from 'help/richui/Default.htm' into 'help/en_US/richui/Default.htm'.
But now, ux2.2 cannot dynamically switch language for 'Help Online'. We have to switch  manually in the configuration file, if use the Spanish version of 'Help Online', url should be 'help/es_ES/richui/Default.htm'.
Thanks and Regards,
Shirley
