#include<iostream>
using namespace std;
char animales();
char autos();
char instrumentos();
main()
{
	char opcion;
	cout<<"seleciona una opcion(A,B o C) para el menu de animales, autos e instrumentos: \n";
	cin>>opcion;
	
	switch(opcion){  //se declara las opciones para que el usuario lo digite
		case 'A': animales();
		break;
		case 'B': autos();
		break;
		case 'C': instrumentos();
		break;
		default: cout<<"opcion invalida \n";
	}
	system ("pause");
	return 0;  // se termina para que el usuario pueda obtener las opciones
}	
	char animales() 
     {
		int opcion;
		cout<<"seleccione una opcion para mostrar La imagen \n";
		cout<<"1. perico \n";
		cout<<"2. leon \n";
		cout<<"3. caballo \n";
		cin>>opcion;
		
		
		switch(opcion)
		{
		

		    case 1:
		    cout<<"MMMMMMMMMMMWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";//aqui se pega las diferentes tipos de caracteres de imagenes
		    cout<<"MMMMMMMMMWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNX0OkxxxxkO0KXWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNKOOkkkkkxolc:;;;;;::::coxKWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMN0dlc;,,,;;::cccccccccccclcc:;cxXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXxc;,:cccccccccccccccc::cccc:;:cc:oKWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMW0lcc;;:ccccccccccccc;;lxxdddoc::cccdXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWKxdolc::cccccccccccc:;ckkdxO000Oxl:c;:dddKMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXd:;:cccccccccccccccc:,l0xcok0XWWWWKo:oKWNxkNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWO:,:::ccccccccccccccc:':Ok,.;lddkNMMWOdK0xdoldONMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWO:,:::ccccccccccccccc:':Ok,.;lddkNMMWOdK0xdoldONMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNklc:cccccccccccccccc,;k0:.oc.;OdxWMW0kkxxxkxxkd:;xNMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNkc::cccccccccccccccccc,,xKl....oOokWN0kxxxxkkkxxxxl,dWMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMKl;:cccccccccccccccccccc;.l0k:,cxOdxKXOxxxkxxxkxkxxxkc,OMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMKc,:::,;cccccccccccccccccc,'oOOdoocoxkxxkxxxxxkkxxxxxkl'xMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWx;lxxc,:ccccccccccccccccccc,.;lddolcldxxdxxxxxxxxxxxxkc'kMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNXXkc::ccccccccccccccccccccc:,''',';ddc:ldxxkkkxxxxxkx,;0MMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMW0l;:ccccccccccccccccccccccccccc:,:xxd:d0xlldxkkkkkkkl.lWMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNx:clcccccccccccccccccclllccccccc,'okxkdlkN0xol::cdxkd';KMMMMMMMMMMMMMMMMMMMMMWWMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMW0l:lllcccccccccccccccccccclllccccl:'lkkkkxoxXWWXOd,.co,,OMMMMMMMMMMMMMMMMMMMMMMWWMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWk::lolccccccccccccccccccccccllcccokx:':xkkkxdokNMWWO'..:0WMMMMMMMMMMMMMMMMMMMWWWMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNx:clllccccccccccccccccccccccccllcoxkkxl:cccclox0NMMWNdckNMMMMMMMMMMMMMMMMMMMMWWMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNd;clccccccccccccccccccccccccccccldOkdddddooolcldkO0KNWWWMMMMMMMMMMMMMMMMMMMMMWMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWk:ccccccccccccccccccccccccccccccclok0dlooooooc;:ccoooxkOO0KXNWMMMMMMMMMMMMWWWMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMk:ccccccccccccccccccccccccccccccccccx0kl::clccc;,;cccclollooodxxxxkkOO00KKKXXNWWWMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMKc:ccccccccccccccccccccccccccccccccc:d0Odol:::loc,',:ccccccllooollcc::::::::::ccclllllllo0W \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWd:cccccccccccccccccccccccccccccccccc;oOOO0o,:dO0kc;,,:cccccccccccllllllcccc::::;;;,,,'. 'OM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM0cclcccccccccccccccccccccccccccccccc:;oOOO0xdk000Olccccccccccccccccccccccccc::::;;,,,,..;0MM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWd:lcccccccccccccccccccccccccccccc:::;:xOOOOO0O000kl:cccccllllccccccccccccccccccc:;,,'.'oXMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM0c:lcccccccccccccccccccccccccc:::;,;;;oOOOOOOOOOO0kl:ccccloooolllccccccccccccccc:;''':dKWMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNd;ccccccccccccccccccccccc:c:::::;;,',ckkkOOOOOOOO0xc:cccclllllllllccc::::::;,,,;:lox0NMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMO::lcccccccccccccccccc::::::;:;;;:dc':xkkkkOOOOOOOOd::cccccccccccccc:;;:clllodkOKNWMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNl,cccccccccccccccc:::::::;;;;;;;cdkl;okkkkkkkkkOOOOl;ccllllccccccc:::;,;ldOKXNNWMMWMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWk,:lcccccccccccc:::::::;',;;;,,,cdxxooxkkkkkkkkkkOOx::olllllllcccc::::;;;,'':okKWMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMK:,lccccccccccc:::::;;:c,',,,',;cdxxxxxxxxkkkkkkkkkOl;looc;lolc::;;,,,,;:coxOKNMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXc':ccccccccc:::;;;;;:co:',,'.,lddddxxxxxxxxkkkkkkkkd:llclc:o0NXKK0OOOOO0XWWWMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMWMMMMMMMMMMMMMMMMMNl';ccccccc:::;;;,,;:cooc'.'';cdddddddxxxxxxxxxkxkkkd:dX0xl::;:xNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMWMMMMMMMMMMMMMMMMMMKc.;c:::::::::;,,;;cloooc'.,:loddddddddddxxxxxxxxxxkd;oXWWWN0xdoxXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMWWWMMMMMMMMMMMMWMMMNx,';::::;,,,,'',;cllooooolcloooodddddddddddddxxxxxxxo;oKXKKKKXXNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMWWWWMMMMMMMMMMMMWWMNk:.';,'''''''',,;lddooooolooooooooooddddddddddddxxxxo:;lkOxdddddddxxxkOKWMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMWWWMMMMMMMMMMMMMMMMMN0OOOx:,,;;;:::::;:lodoolllllooooooooooooddddddddxdl;;cxkkkkkxxdddooddolcoKMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMWWWMMMMMMMMMMMMMMMMMMMMMMWXxc;;;;;;;;;::::loolllllllloooooooooooooddddoc;;:ldxddxxddddxkkdooldd::0MMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMWWMMMMMMMMMMMMMMMMMMWMMMXxc;;;;;;;;;;;;;::ccccclllllllllooooooooooc:::clloxkxokKXXXK0OkdodxxdcdOXWMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMXxccc:;;;;;;;;;;;;;;;:ccccccllllllllcc:::clloxOKWNxdkkooKWWWWMMMWN0kdoc,dWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMWOoloc;;;;;;:;;;;;;;;;:lodxkxolllllllllldxOKNWMMWWWW0oll:oXMMMMMMMMMMMNKkONMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMXdldo:;;::::::;;;::;::coxdxOxodxxxkkkkkkxkkkO0XNNNXXXXKOxONMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMWMMWNkldkl:;;;;::;;;;;;:cllldxxoxk:lxxdddxxkxxdxxxxddddddxkxdKMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMMMMMMMMMMMMMMWMMNOlokkl;;;;:;;;;;;;coollodxxol0NkodxkOKXNWNX0kkxoxkxdooloxd0MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMMMMMMMMMMMMMMMNOllk0xc;::::;;;;;:cddlcldxxxdcxWMWWMMMMMMMMMMMMMNKkxdddd:ckXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMMMMMMMMMMMMMNxllkK0d::::;::;;:codolcldxxxkd:dNMMMMMMMMMMMMMMMMMMMMWXK0OOXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMMMMMMMMMMWKdclkKKOl::::;;;:codol:coxxxxxxo;dNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMMMMMMMMXklco0XX0xc:::::cldxdlcccdxxxxxxxc;xWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMMMMMNOollkXXXKKOddxxxkkkxlcld0kdkxxxxxo,c0WMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMWXOdooxKXXXXXKKKK0kxoc:cloONMXdokxxxo:;dNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"WXxc;,:dxxdddoolccc:cccldkXWMMMWOoxxxdc,lKWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWMMMM \n";
			cout<<"WXOkxdddoooooodxxkO0XNWMMMMMMMMNdokd:;lOWWWMMMMMMMWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWWMMMM \n";
			cout<<"MMMMMMWMMMMMMMMMMMMMMMMMMMMMMMMO:;::o0WWWMMMMMWWMWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWWMMMMMM \n";
			cout<<"MMMMMWMMMMMMMMWMMMMMMMMMMMMMMMM0cckXWWWMMMMWWWWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWWMMMMMMM \n";            
		    break;//al final de los caracteres se coloca break para no seguir con la opciones nadamas lo seleccionad		
			
		    
			
			case 2:
	    	cout<<"IMAGEN LEON \n";//aqui se pega las diferentes tipos de caracteres de imagenes
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWMMMMMMMNxoKWWMMWNXKOkdooldXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWMMMWNkc.:XNKxoc:;'......dWMMMMMMMMMMMMWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXx:'..cdc'...........lkkxxxkO0XNWMMWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWWWXx;....................'.......',:lkXWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWXXWMMMM \n";
	    	cout<<"MMMMMMMMMWWWMMMMMMMMMMMMMMMMMMMMMMMWWMMMMWWMMWKx0O:,'..............................,oOXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM0lxNMMM \n";
	    	cout<<"MMMMMMMWWWMMMMMMMMMMMMMMMMMMMMMWKkxdddxdxOKNWKl,::,'..............................':oxOKWMMMMMMMMMMMMMMMMMMMMMMMMMMMWMMMMWWNl'oXMM \n";
	    	cout<<"MMMMMMWMMMMMMMMMMMMMMMMMMMMMMW0c........ .;oko;,,'.............................'''''...,cdOXWMMMMMMMMMMMMMMMMMMMMMMMMMMN0KWKc..dWM \n";
	    	cout<<"MMMMWWWMMMMMMMMMMMMMMMMMMMMMWK; .. ...     .ldol;,,,;,'.......................',,....,:ccccdOXWMMMMMMMMMMMMMMMMMMMMMMMMXl,dd,..;0M \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMWWk' .. .. ..  ..coodoolooolc;;:cllcc:;;'...............,codolcclld0WMMMMMMMMMMMMMMMMMMMMMMWO,......'ON \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMWNOdc..   .. ..';loooodddoooddollclloddool:'...........,codoc:::ccclo0WMMMMMMMMMMMMMMMMMMMNXKc.......,kd \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMNkoddo:''',;:cldddddddddddddddolllcccldddooc,........;loddl:;:ccccccldKWWWWWMMMMMMMMMMMMWNx:;'.......':, \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMKdodddlldddddddddoddddddddddddddddddooodddooc,.......:ddol:;ccccccclo:;llcoKMMMMMMMMMMMW0l'............c \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMW0dodddlloddddddddddddddddddddddddddddddddddol:'......'clc:;cllcccclol,...:OWWWMMMMMMMMXo'.............:K \n";
	    	cout<<"NNNNWMMMMMMMMMMMMMMMMMMMMMXxooodolclodddddddddddddddddddddddddddddddddll:'......':::cccccclool,..;xXMMMMMMMMMMMMx'............,dXM \n";
	    	cout<<"WWNNNNNNWWMMMMMMMMMMMWWMMMMN0xoodoodolloooddddddddddddddddddddddddddddool:,'.....';:cclllolc:,...;dKWMMMMMMMMMMM0;...........;kWMM \n";
	    	cout<<"MMMMMWWNNNNNNNWMMMMMWNXXNWMMMN0OOkdc;ckOxc,;;;;;;;;codddddddddddddddddddool:'.........'''''........'lKWMMMMMMMMWKo;''......,cxKWMM \n";
	    	cout<<"MMMMMMMMMMMWNNNNNNNWMMWNNXNWMMXKN000ocOWK:         ..,codddddddddddddddddool:'.......................'xNMMMMMMWKdodk0kxxxkOXNWMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMWWNNNNNNNWWWWMMWXKOKWWX0KO,            .'cdddddddddddddddddolc,.........................oXMMMMMNkookWMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMWWNXXNNWMMMWNXWWMMNKl.              .cddddddddddddddddolc,................'::ccldxk0NMMMMWKxldKWMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMWWMMMMMMMMMMMMMWWWMMMMMMMMMMMW0,               ,oddddddddddddddoll:'.................oXMMWMMMMMMMMMWKdldXMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMWWNNNNNNNNNNNNNNNNNWMMMMMMMMMMMMWl     .....  ...,oddddddddddddoollc,......'''..........:OWMMMMMMMMMMWXxloKMMMMMMMMMWWMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMWWWWWNNWWMMMMMMMMMMMMO' .';;:cc:;;;:;;cdddddddddddoolll:,.....''''''''........'lONWMMMMMMMMWOllkWMMMMMMMMWWMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMWMMMMMMMMMMMWWMMMMMMMWWWM0;.,:llclllllc:::codddddoooooollc:,'....''',;;'..''..........lKWMMMMMMMMKdloKWMMMWWWWMMMMMM \n";
	    	cout<<"MMMMMMMMMMMWMMMMMMMMMMWNNXNWMMMMMMWNKKO:':ccclcclc:::;,:oddddooolllcc:,'.......''.,::,,,'....,;;:ldOXMWMMMMMMMMNkolxNMWWWWMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMWNNXXNNWMWXNWMMWWXXXl,::ckklc:c::;'.;odooolc::;;,'...........'''.',;;,.....lkKWMMMMMMMMMMMMMMW0oolOWWWMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMWNNNWMMWXNXNWMMMMWXXW0lcco0N0dc:;'..;odol:,''...................''','.......,l0WMMMMMMMMMMMMMMMKdolkNMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMWNXXNWMMMMMMMW00XKxcccxNWN0c..'cdol:,............................,clodk0XWMMMMMMMMMMMMMMMMWKdoldXMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMWNNXNWMMMMMMMMMMWOodxxxxxx0KKOo;coool;'..............................:d0KXNWMMMMMMMMMMMMMMMMMM0doloKMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMWWNNXNWWWMMMMMMMMMMMWNOdlooddxdoooodddoc;.................'............'',;loddkkO0KNWMMMMWMMMMMMNkooldXWWMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMNXXNNWMMMMMMMMMMMMMMMMMW0oooooooooooddoc,........................;::cclloddddddddoooodxk0NWWMMMWWKxooolkWMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMWNXXNWMMMMMMMMMMMMMMMMWWMWMWKxoloooodddool:'.............,,''''''''.'cddddddddddoddddddddooloxO0K0OkdoollxXMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMWNXXNWMMMMMMMMMMMMMMMMMMMMMMMMMMNkddolloollccc,...';,',,',,;lddoooooooollodddddddddddddddddddddoolccloollldONMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMWNXXNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWNXOkKKdloddo:.'lddddodddddddddddddddddddddddddddddddddddddddddollcldxOKNMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMWWNXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWWWKdoddddllddodddddddddddddddddddddddddddddddddddddddddddddolllOWMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWMMW0ooddddddddddddddddddddddddddddddddddddddddddddddddddddddolldXMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXdcloddddodddddddddddddddddddddddddddddddddddddddddddddddoollxNMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMKdlcloodolodddddooddoodddddddddddddddddodoodddddddddddddddoollkNWWWMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWkodolclolldddddddddolodddddddddddoooollllllodddddddddddddddoollxKWMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMKdoddollccoddddddddollddddddddoooolllllllllllodddddddddddddddoolloONWMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNOddddddoccdddddddddoclooooooollllllodxxolccc:coddddddddddddddddoolldkKNWMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWMMM0dddddddocodddddddddl:cllllllccldxk0XNWWKxllllccloddddddddddddddddooolo0WMMMMMWMMMM \n";
	    	cout<<"MMMMMMMMWWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNkddddddolldddddddddoccdddxxkkO0XNWWWMWWMMNKxllllclloddddddddddddddddoolxNMMMMMMMMMM \n";
	    	cout<<"MMMMMMMWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWMMMNkxxxdddolcoddddddddoocxNWWWWMMMMMMWWWWMMMMMMWXkdllllclloodddddddddddddoll0WMMMMMMMMM \n";
	    	cout<<"MMMMWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWNkdxddddolllddddddddolllkWMMMMMMMMWWWWMMMMMMMMMMMN0kdllllcllloodddddddddoolxXMMMMMMMMM \n";
	    	cout<<"MMMMWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNXX0xddddddolllodddddddolllxXMMMMMMMMMWWWMMMMMMMMMMMMMMWN0xllllllcllodddddddoollkNMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWX000K0kxdoooollcoddddddoollcdXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWKdlllllllcloddddddollo0WMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWX000K0kxdoooollcoddddddoollcdXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWKdlllllllcloddddddollo0WMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXOKX0KXXXK000KXXKkdodddoollONWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXK0kkkxxddolcloddddoollkWMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNK0OOKXX0k0KKKXXXXKkdodolldXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMW0OKXXXXNXXKkxkOkxdoddolcdXWMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNXKKKKO0XKKKXXXXXX0kkxdoOWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMW00K0XXKXXKO0XXXXX0OkxdddxXWMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWMMMMWK00O0XXKKXXXXXXXKOKMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNX00K0O00OOKKKXXXXXXXKK00NMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNK00K0OKXXXXXK0OKWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNNXXX000O0XK00XXXK00NMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNK0O0OOOOOkOXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXKOO0Oxk0OOO0NMMMMMMMM \n";
	    	
	    	break;//al final de los caracteres se coloca break para no seguir con la opciones nadamas lo seleccionad	
		
		    case 3:
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMW0xkkO0000K00Odcld0NNNNWWWMMMMMMMMMXxON0kNMMMMMMM \n";//aqui se pega las diferentes tipos de caracteres de imagenes
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXOdl,.;cc;',,....;;;;:::cldkKNMMMX;.lc.cXMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWKOkkkkkkOOOOdc;'.';:ldxkkkkxoldxdoc;;;lxKK:.'...cXMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWOllooollxK0o,';okKNMMWX0xoxxoo0WMMMNKOo:;,.;d'.:;lNMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNkc,,'',;;';dKNX0KWMN0OK0KNNNWMMMMMMMMMWO' .xd.,;'kMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMKocll:,.,kNNKOO0NMMWWWMMMMMWWWMMMMMMMNx;,::cx:''.cxONM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWN0ko,  ;0NXKKNMMMMMMMMMMMMWOkNMMWWWWO;.l0K0OKk:.;OOlo0 \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXOkkkkxdc..  :0K0XWMMMMMMMMMMWXXKxxKNOocoxc..dNWKOkkkd;'oK0c: \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWKxooxxc;:'.;OO0NMMMMMMMMMMMWKk00KXx;';;,..l0WMMMMMMWNx,;cc'' \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXK0Okxc,:, ,xO0WMMMMMMMMMMMNOoONW0:..''.;dKWMMNKkx0WMXc:Od:,.\n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMW0kol:;:,. .xKXMMMMMMMMMMMMMXolKWO'  .;d0WMMMMWx'..oNNd.:XXk:, \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWWWXOl;:xk:..lNMMMMMMMMMMMMMMMXcoNX:  :0WMMMMMMMWk'.lXNOl'oNNd;x \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMX0kdolc:cdOOo':KMMMMMMMMMMMMMMMMXdkM0,..oNMMMMMMMMMWXXWMNk:cKNkxKW \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWNOolc,,lOOc;OMMMMMMMMMMMMMMMMMWkkW0;;'.oNMMMMMN0XMMMMMNl;0MWWWMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXkoclkK0l,kWMMMMMMMMMMMMMMMMMMOxNX::x;.lNMMMXdxNMMMMMk;dWMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXOKX0d;.dWMMMMMMMMMMMMMMMMMMM0dKWd:0k.:XMMXxkNMMMMMNc:KMMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWKOkdc'.lNMMMMMMMMMMMMMMMMMMMMN0XM0:dk.:XMMWNMMMWWWXd,dWMMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWKOkl..lXMMMMMMMMMMMMMMMMMMMMMMMMMXc:k;.kWMMMMMW0OKo.:XMMMMMMMM\n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNx,,kWMMMMMMMMMMMMMMMMMMMMMMMMMMNc,o, ,OXKWMWOd0Xc'kWMMMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMW0c,lKMMMMMMMMMMMMMMMMMMMMMMMMMMMMWd...'.;kO0KxdKW0;lNMMMMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWNK0xdoc;cOWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMO..dO'.oKkc;dXKccKMMMMMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWX0kxdoooddxkO0KXNWNNXK0kdollccccllokKWMMMMMMMMMMMMMMMMMMMMMMMMKxkXMMMMK;.ox' ,dl,..;,:0MMMMMMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMN0dc:::clodxxxxdddoooolllccclodk0KXNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXc.oWMMMNc.':'.cKl.. .:KMMMMMMMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMWNKKKKKKOl;,:dOXWMMMMMMMMMMMMMWNXXXNWWMMMMMMMMMMMMMMMMMMMMMN00WMMMMMMMMMMMMMMMk,oWMMMWo'xWO,;l;,:oOKK0KNWMMMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMWXkxxdoool,.'cxXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM0ll0MMMMMMMMMMMMMMMOclOWMMMx,xMWKkk0XXOo::ccccxNMMMMMM \n";
		    cout<<"MMMMMMMMMMMW0oc;;:lxd;.'oKWMMMMMMMMMMMMMNKNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNd;lXMMMMMMMMMMMMMMXKx:kMMNx'lNMMNKkolldkk0XKc.xMMMMMM \n";
		    cout<<"MMMMMMMMMMNx:;c:;oOx;.:KWMMMMMMMMMMMMMMMNd:OWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNx:xWMMMMMMMMMMMMMMMNolXMOc';dolc;:oOKXKOkKXl,OMMMMMM \n";
		    cout<<"MMMMMMMMMWk::oolOXx:.;KMMMMMMMMMMMMMMMMMM0,:XMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWKOXMMMMMMMMMMMMMMMNo,ONkxd:,';lodoc;,'. ;o:dWMMMMMM \n";
		    cout<<"MMMMMMMMMXo;lxoOWOdl.lWMMMMMMMMMMMMMMMMMMXlcXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNKNMMMMMMMMMMMMMM0ccO0xxdddkKNKKXk,.l; ..cXMMMMMMM \n";
		    cout<<"MMMMMMMMMKdcdkdKWkkd.oWMMMMMMMMMMMMMMMMMMXdkWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXNMMMMMMMMMMMMNOdloxxkOKNMWN0kOX0;'o;  .dWMMMMMMM \n";
		    cout<<"MMMMMMMMMKxokkdKW00k'cNMMMMMMMMMMMMMMMMMXxONMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNXNWMMWWNXXWMMMMMMNOo:,..ld'cd.  .OMMMMMMMM \n";
		    cout<<"MMMMMMMMMXxoOOo0MK0O,;XMWWMMMMMMMMMMMMMN00WMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMKl:codk0NMMMMN00Kx:;o00; .',ko.'';KMMMMMMMM \n";
		    cout<<"MMMMMMMMMWxoxkoxWNOk;,0WOOMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWN0OOKNNNXKOOkdc;;dXWM0'  .cx,;x;cNMMMMMMMM \n";
		    cout<<"MMMMMMMMMM0doxooNWkx:'OWxxWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWKocodxKWMMXOkxolc:lkNMMMWx.  .:,;0O,lNMMMMMMMM \n";
		    cout<<"MMMMMMMMMMXxcddoKNkkc.OMkdXMMMMMMMMMMMMMMMMW00WMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXd'.....,lxxdolc:lxKWMMMMMNc.,';;.oKc;OMMMMMMMMM \n";
		    cout<<"MMMMMMMMMMXd:dxoK0k0:'OMNkOWMMMMMMMMMMMMMMNo'oWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNKko::oO0KKKkolloxOKNMMMMMMMMWx':x;',:xl:OWMMMMMMMMM \n";
		    cout<<"MMMMMMMMMWOc:OxoOkXO';KMMWNWMMMMMMMMMMMMMNo.'kNWMMMMMMMMMMMMMMMMMMMMMMMMMNKxollllx0NMMMMMMMMMMMMMMMMMMMMMMWx':KO..lOlcKMMMMMMMMMMM\n";
		    cout<<"MMMMMMMMMKl:x0l:xXWd.oWMMMMMMMMMMMMMMMMMNd.':;;:ldk0KXNWWWWWWWWWNNNXKOkdoc:coOXWMMMMMMMMMMMMMMMMMMMMMMMMMMNc.oKl.'o:;OMMMMMMMMMMMM \n";
		    cout<<"MMMMMMMWKockKo;dNMN:.kMMMMMMMMMMMMMMMWWKl.cKWKkoc,.'::cclllllllcccccclodkKNWMMMMMMMMMMMMMMMMMMMMMMMMMMWOoll;lk:.;Oo.cXMMMMMMMMMMMM \n";
		    cout<<"MMMMMMNOllOKxd0WMMK,'0WXXWMMMMMMMMNK0Oo,,dNMMMMMXo;xXXKKKKKKKKKKKKXNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNxl'.lOk:;::o:;0MMMMMMMMMMMMM \n";
		    cout<<"MMMMMWOodKNKXWMMMMk.:XMWWWMMMMMMMMWKx:,lKWMMMMNkloKWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMOlOO;;o;;0Xd',OWMMMMMMMMMMMMM \n";
		    cout<<"MMMMMWXKNMMMMMMMMNl.dWMMMWOkXWMMMW0l':OWMMMWXxlo0WMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM0cxWXo.'kWMWXXWMMMMMMMMMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMNo.cXMMMMMXOKWMW0l,:xNMMMWKxod0WMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWkckXdlOWMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMWKl'cXMMMMMMMNK0d:;lONMMMW0olkXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWx:;c0MMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMMMMMMMMMMWXkc;ckNMMMMWKxc;;:lxKWMMNKxllxXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNkdKMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMMMMMMMWKxl:cdKWMWXOdc;',lkKWMMNKkdood0NMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMMMMMMXo':xKWMWKdlll:..c0MMWXkdodxOXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMMMMMNo.cXMMWOold0NWd.;xXNOl:lkXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMMMMMO.,KMWOc:dXMMMNc.kNO:,lKWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMMMMNl.lN0c;oKWMMMM0''xd:o0WMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMMMWk..do:oKWMMMMMNc.,:lKWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMMWO' ';c0WMMMMMMNo...:KMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMWO' .'lXMMMMMMMXl. .,kWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"W0c...'cXMMMMMMM0;..''oNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"x';dd;;0MMMMMMMX:.xKl;OMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<",.kWk'oWMMMMMMMX:'OXcoNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"o.cKl,0MMMMMMMMWd.oO:dWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"0''kl;KMMMMMMMXx,.lx,:KMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"k.'Ox,lXMMMMMXdlllllc;xWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<";,:oo;'oNMMMMXllKWWMWxdNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"cKNNNNdcKMMMMWXxddxkOo;xNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"ooxOKNx,lKWMMMMMWN0kxx0NMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"N0xl:c;'lKWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    
		    
	    	break;//al final de los caracteres se coloca break para no seguir con la opciones nadamas lo seleccionad	
		
		    default:cout<<"opcion invalida \n";
		}
      }
	
	char autos()
	{
		int opcion;
		cout<<"seleccione una opcion para mostrar La imagen \n";
		cout<<"1. f-150 \n";
		cout<<"2. hummer \n";
		cout<<"3. ferrari \n";
		cin>>opcion;
		
		switch(opcion)
		{
		    case 1: 
			cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWWWWNNNNNXNNNNNWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";//es donde se coloca los caracteres de la imagen deseada depende si es carro etc	
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXOkkxxxxxxxxxxxdddddo:;,,,;;:cloodxkO0KNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
            cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNx,';::ccclccloooooddoolc,.       ...',;coxkk0NMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXo'.;cccccc:;:cclllllccc:::;..        ...';:llldxOXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXl,......',,....';;;;;'..',,,;,..          ..',;cccoxOXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXo,.     .''.    .........',,'.,,,..          ....',:::ld0NMWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	        cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNkc,.    ..................... ..;;'.......',,,,,,,,;;;clccxOxx0XXNNWWWMMMMMMMMMMMMMMMMMMMMMM \n";
		    cout<<"MMMMMMMMMMMWWWNNNXXKKK0000OOOkkkkkkkxdkOd;;::::;;:::::;'.....',''.....;c::::cccc:::::cc:::::;;;::cc:cxOOO000KKKKKKXXNWMMMMMMMMMMMM \n";
			cout<<"MMMMMMMMMMXxodoooollccccccccccccccll:;lolllllllcc::cccccc:::::::::;'.';c::cc:;;;;;cllc:;::cc:;,,,,,,,lOdlxxoooooooddkO0XWMMMMMMMMM \n";
		    cout<<"MMMMMMMMMM0oc;;;;;,,,,,,,,,,',''''''.'''''''''''....'...........'''...'.....',;;;:ldddoc;''cxOxddodxxdko,ldlclccllllodxoxNMMMMMMMM \n";
			cout<<"MMMMMMMMMWkdl'',''..',:clc,...............................................',,,,'....',;cc:;:oocc:,;dOl;c,;lc:::coolllooldKWMMMMMMM \n";
			cout<<"MMMMMMMMMNd:,......'''..',;;'.............................................'..        ...'',',;;;:;:oxl;,'.:ooloollcccccc:lKMMMMMMM \n";
			cout<<"MMMMMMMMMNd........       .................'''''''''''',,,,,,,,,,,,,,'.....            ...'.''.....:dd:...cdolc:;;,,''..''xWMMMMMM \n";
			cout<<"WWWWMMMWWNl.......         ...'''''''',,,,,,,,,,,,,;;;;;;;;;;;;:cccc;'...     ..'''''..  .....',;;;::::;;:ccccccc:;;,''.,':0MMMMMM \n";
			cout<<"WWWWWWWWN0c......    ...   .....................................''''.....  ..'.............,,,,;::::::;;:::;;;;;;;;;;;;;,''xWWWWWW \n";
			cout<<"WWWNNNNN0OO;.....  ....''.  ............................................  .'...:l:,';;....:xxddddddo,,coc,,;;;:;,''',,,,:c:dXWNNNN \n"; 
			cout<<"NNNNNNNWXxd:.......';,',...  ................................''''''''',. .'..;lx0d:cx0d,. ;OKKXKKKOd,;k0c........       .'.cKNNNNN \n";
		    cout<<"NNNNNNNNNK0Odlcc;..lkodd'..   .. ...      .  ...             ..........  ...:l.:OOOOOd,'' .;cclllll::cll'. .....'''',''....oXNNNNN \n";
			cout<<"XXXXXXXXXXXKOkkkd';dookx;..      ..  .,,'''..','.............',,;;;;.    ...lkdkkolldx::;...  ..........   ...........',;:d0XXKXXX \n";
			cout<<"KKK00KKKKKKKKK0Kk,,xocoxl..    'c:'     ..','.............,::ccccc:,.    ...:kdclddodkOk;..         ...       .........oKKKKKKKK00 \n";
			cout<<"00OO000000000000O:.oxddc'.    ;kOOxc,'.,ldkOo.           .oOOOOOOOOxollcc,. .:l;ckkl,:l:..   .::;,;;.           ..    ;OK000000000 \n";
			cout<<"OOOOOOOOOOOOOOOOOx;.:c:'.    'dkkkkOOOkOkkkkxc.  .      .:xxxxxkkkkkkOOOOd,...,:lddc:;'..   'dOOOOOOo.     ...       'dOOOOOOOOOOO \n";
			cout<<"kkkkkxxxxxkkkxxxddl'.       'loooooodddddddooo:.       .;looddddddddxxxxxxd:...........   .;dkkxxxxxxo,.           .;dkxxxxxxxxxxk \n";
		    cout<<"ddddddddddddddddol:'.       .;lllooooooooolllc,.       .';clllllllllooooooll;.           .,ccccccc:cccc;.         .:lllllooooodddd \n";
			cout<<"ooooooooooooooool;'';;,...   .;clooolcccloolc,.         ..:lllllllllooooolc,.. ......     .,:ccccccc:;,..          .,:cclllllloooo \n";
			cout<<"llllllllcclcllll:';llcc'......':clc;'...;ccc;.............,cclllccllllllc:'....,:ccc;'......;:clllll:,.......       .';cccccllllll \n";
			cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWWWWNNNNNXNNNNNWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n"; 
		    break;
		    
		    
		    case 2:
			cout<<"                                    .............................................'''''''''''''''''''''''''''''''''''''''.............................. \n";
		    cout<<"                                  ...................................'''''''''''''''''''''''',,,,,,,,,,,,''',,'''''''''''''''''''''''................. \n";
		    cout<<"                            .......................,:cc::::::;;;;;:::::::::::::::::;;:::::;;;;;;;;;;;;;;;,,,,,,,,,,,,,,,,,,,,,,,,'''''''''''''........ \n";
		    cout<<"                       ............................,:::cccllloooddxxxxdddddoooooolllcclllllcccc:::::::::::::::::;;;;;;;;;;;;,,,,,,,,,,,,,,'''''''''... \n";
		    cout<<"                ...............................''.   .........''',;;:ccllooooooddddddddoooolllllooollllllllllllcclcccc::;;;;;;;;;;;;;;,,,,,,,,,''''''' \n";
		    cout<<"          .................................'''''.   ..'''''''',''.''',,,,;;;;::ccllodddxkOOxllllccccccccc:::::cododdoc;:::::;,,;;;;;;;;;;;;,,,,,,,,''' \n";
		    cout<<"    ....................................''''',:'   .''',,,,,,,;;;;;;::;,,;;;::cclllodxox0KKk:'......'''''''',''dOxxxxc'...',,;,'',;:::::;;;;;;;,,,,,,, \n";
		    cout<<"....................................'''''',,,:c.  .,;;;;;;::::::cccccc;,,,;;;:cclllloxokKKXk:.......'''''......oOkxkkx:.......',;,'';:::::::;;;;;;;,,, \n";
		    cout<<"..................................',;;,;:cllc:;. ..,''''..........''''''',;;:::cccccllcOXKXk:,'''''',,'',''''..cOkkkkOd,.........,;;;::::::::::;;;;;;; \n";
		    cout<<"..........................'',;;::lldxdodxxxxddol::;;,,;,,,'.....'........',,;;;;:::::::OXKKxc:cooolllc::::;;;;'cOOkOOOOl,''''''''..,:ooc:::::::::;;;;; \n";
		    cout<<".....................',;:cldddxxkOkxkkO000000000Oxdddolllooxxollllccc:::::::::;;:;;::;cOKKKocokXX0O0XOlccccccc;lkOOOOOOkolllloooooooxO0Odc:::::::;;;;; \n";
		    cout<<".................',;:clllloooddxxxxxxxxxxxkkkkkkkkkkkkOOkkkOOkdollcccccccccccccclllc::cdkOOlcox00dldOkdddddddddxkxxkxxxxdddddddddddddddddl:::;;;;;;,,, \n";
		    cout<<"...............';:lodolcccccc:cccccccclloodddddddoodoodoollllccccllooooddddddddddddoodddxdollok0koodddddooooddxkOkolooollolllllccccccccccc:;;;;;,,,,,' \n";
		    cout<<"...........':clooxO0000000OOOkkkxddoollllccccccclodooollllllllooodxxkxxxxxxxxxdddddddddddooloxOOxoooooooooodddxkkkdooddddollllc::::::::::::::;,,'''''' \n";
		    cout<<"...........;do:d00dlOkdO0O0KKKXXXXXXKKKK000Okxdodxdddooooooddxxxddodollllllllllcloddddddddddodddddddddddddxxxxxxdxxxxxxxxddddddddxxxxxxxxxxkxc'....... \n";
		    cout<<"...........,lc:kNK;'d;.dl.ok;l0xlkKxx0K0KXNNNXXXXXKkxxddoodollccc:cccccllllllloooooodxxxxxxddxxkkkkOOOOOOOOOOOOOOOOOO00Okxxxxkkkoc:;,,''...,o:........ \n";
		    cout<<"............;l:cx0ddklcxl,do.:x,.ox..xd':OOlodO0OKXOddddooollcccllooddxxkkkkkOkkOOkdox0KK0kk0K0O0000000000000OOOOOOkONNOxxxkkko'           ........... \n";
		    cout<<".............;::cloxkO0K00KOkOOdokx:cko.c0d,;l00dOKd:ldxxxxxdodxxxddollc::;,,,''.,okkxO00OkkkkkkOOOOOkkkkkkkkkkkkxxxkKKkkOkkkl.        ............... \n";
		    cout<<".............'...   .',:cclodxxk000KKK00K0c..,ddlO0l:lddddxdool;....               ;xddkkkkkddxxxxxxxxddddddddddddddoddkOkkxc.      .  .,'.........    \n";
		    cout<<"..............''...............',,;::ccllol:cclld0kc:::;;,'....                    .coodddddoodoooooooooooollllllllllok0Okd:.   ...'''''...   .        \n";
		    cout<<"...............''...........................'',;;;,....              ....           ,lclooolcllcclllccccccccccccccccldkOxo;. . ..''....''.. ..         \n";
		    cout<<".......................,oollc:,'..'''''...............         .........'.....      .:ccccldxdc::::::::::::::::;;,,;loll:'.  ...'':olcc;''..  .        \n";
		    cout<<"............    .......;kklldkd,.....................      ....''..........''''.    .;;;;,;clc:::;;;;;;;;;;;,'.....,:;'..   ....;ol;..'c:....          \n";
		    cout<<"............      ..,,,:c:;;:dd,...   ..........         ...'''....,;::;'.....''..   .......,,,,,''''''...........';,..     ...,dc.    .:;..........   \n";
		    cout<<"...........         .,,;;;:c:co:''..''.......          ....'...':llllc::clol;...''.  ......................       .        ...'lo'...  .,;............ \n";
		    cout<<"..........        .. ...''',,,;;,;;;;c:;.            .........cxxl'      .:ldo'..'.   .  ..''''''''''''',;'.   .           ...;l;.,,,...,;............ \n";
		    cout<<" ...'''''..          ............'''''',;,.          .........cx:...         .co'....    ................,cc'.........      ...;c'..''..':;............\n";
		    cout<<"'''''''''..         .............'.........         ........:o;...........   .oc..'.      ...............''..........      ...,c,......,:'............ \n";
		    cout<<"',,,,,,,,'..             .''.   ............. .... ........,o:   ..''','..   .ll....       ...........................      ...;;... .,:,..'''........ \n";
		    cout<<",,,,,,,,,,,'.             .        ............''..........;o,  ...'','..    .c:....              ....................       ..';;;,',;'..','',''''''' \n";
		    cout<<";;;;;;;,,,,,,'..                 ...................  .....'oc.;;. ....,'    ,c,....                     ..............      ....,;;;,'.',;;,,,,,,,,,, \n";
		    cout<<"::::;;;;;;,,,''..                ..................    .....:o;,:.... .l0l. 'c;..... .   ..............................        ........';;;;;;;;;;;;;; \n";
		    cout<<":::::::::;;;,,''........             ............       .....;l:,. ..   ';:c:,......................................................',;::::c:::::::::; \n";
		    cout<<"cccccccc::::;;;;;,,,,''''..........  .....              ......,::;,''.',;:,'...........................''''''',,,,;;;;:::::::::cccclllllllllllcccccc:: \n";
		    cout<<"cclllcccccccccc::::::;;;;;,,,,''''...............         ......';;;;;;;'...............''''''',,,,;;;;;;:::::cccclllllloooooooooooooooooooollllllcccc \n";
		    cout<<"lllllllllllllcccccccccccc::::::;;;;;,,,,'''..........       ....................''',,,,;;;;::::cccclllllllooooooooodddddddoooooooooooooooooolllllllccc \n";
		    cout<<"lllllllllllllllllllllllllllccccccccc::::::;;;;;,,,''.....              .....',;;;::ccccllllloooooooooooodddddddddddddoooooooooooooooooooooollllllllccc \n";
		    cout<<"lllllllloollllllllllllllllllllllllllccccccccccc::::::;;,,'............',;::ccllllooooooooooodddddddoooooooooooooooooooooooooooooooooooooollllllllllccc \n";
		    break;
	    	
	    	
	    	case 3:
			cout<<"XXXXXXXXXXXXXXXXXXXXXXXNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNXXXKKK0OOkxddooooollllllllodxxO0KKKKXKXXXK0xdxkO0KKKKXXXXXXXXXXXNNNNNNNNWWWWWWWWWWWWWWWWW \n";
	    	cout<<"XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXNNNNNNNNNNNNNNNNNNNNNNXXXK0Okkxxxdo:,,;cc;''''..........';lOK0xolldOc....';ldxkkO00KKXXXXXXXXNNNNNNNNNNNNNNNNNNNNNN \n";
	    	cout<<"KKKKKKKKKKKKKKKKKKKXXXXXXXXXXXXXXXXXXXXXXXXXNXXNXXXNNXXKK0Okkxxxxxxkkkdoc;,,'.''.....',,. .',ckOc..  ...  ....',::clloddxkO000O00000000KKXXNNNNNNNNNNN \n";
	    	cout<<"KKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKXXXXXXXXXXKK00Okkxxxxxxxxxxkkkxo,.......   ...  .''.','..   .     ....',;;;;;;;;;:clllllcccccldxkO00KXNNNNNNN \n";
	    	cout<<"KKKKKKKKKKKKKKKKKKKXXXXXXXXXXXXXXKKKXXXXXXXKKKOkO00OOkkxxxddxdddddolc:;,.......     .   .,'.....     ..    .....',;:c:,'.......':clooddxxxkO00OKNNNNNN \n";
	    	cout<<"KKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKK0dclxOOkxxddoolcc:;,,'...... ...           .,,. ..  ......'......',;clodd;.......,:oodxxdoc;,',;ldxOXNNNNN \n";
	    	cout<<"00000000000000000000000O0000OOOkkxxxk00KKOkkxdxkkdolcc:;,''.............              ';,,.....',,'....',;;:clodxkkxo,. ...,lddxxxo:,........'ckKXXXXX \n";
	    	cout<<"OOOOOOOOOOOOOOOOOkkkkOOkkxdlc:;;:coxOKKKK00000OOOkxxxdoollcc::cc:::;;,''.......'',,'',:;,,,',,,......',;:lldxkkkkkkxo;. ..:odxxdl;'....';,'....o0KKKKK \n";
	    	cout<<"xxxxxxxxxddddddddxxkxdl:;'..',;cdxOOOOOOkkkkkkxxdoollccclloddoollc:;;,,''''',,;:ccldxxxxl;;;,..,;:cllloddxxkkxxddoccc:;,:lddol:'.......:xc'... ;kOOO00 \n";
	    	cout<<"llllloooooooooodddoc;'...,;:cooddddddoooollc:;,,'..,;::ccc:;,,;;,'',,,,;;;:::::;,''';clol;,'',codddddxxxxxxdddollc:::;;;;,,'....... ...;xc..l:.'okxxxx \n";
	    	cout<<"lllooooooooolodoc;'..,;;cllloollcccc::;,,'.....,;:ccc:,...';:;;;,;;;::ccc:,''..........,:lllllllc:;,,;;;;,,,'''......................'.,dl.'lo,.cdoooo \n";
	    	cout<<"lllllllllccldo:'..':ccclllcc:::;;,,''.......';clc;,.....';::;,;::ccllolc,....,lol:,,'.  .','.....................................  ..',:l,..,dc.;lllll \n";
	    	cout<<"ccccccc:clcxkdlc:cooccc::;;;;,,'..........,:cc;.... ..';;;;;:ccllooddl;...,;'.oOo:',:;.  ........................................  ..,;lc'..:0d';c:::: \n";
	    	cout<<"::::::::okkOkxddoooc:cc;,,,''''..........',,..''''...,,;;:ccloooollc:'...,'...:kxxc'ckl.  .......................................   .,;dl'.,o0c.;;,,,, \n";
	    	cout<<";;;;;;;;',:loddoolc::cc;,'''''''.............';,''',;:cllllccc:;;,,,....,;'...;xKdcclxx;  ............................ ...........   ;xx;.';do'.,,'''' \n";
	    	cout<<";;;;;;;;'   ...',,,,,,,,,,,,,,,,,''''''''......',:lollc::;,,'''''''.....,,..;c:oxc:l;:dc. ....................          .........    .ll''oxc...'''''' \n";
	    	cout<<";;;;;,,;,.            ..............            ..',,,'''''''''''....  .'...cdoxdclo;lKx.............       ................          .',:c,.......... \n";
	    	cout<<";;;;;;;,.                ....                      ...'''...........   ...  .coxc,cl;kWd.......      ...........                            .......... \n";
	    	cout<<",,,,,,,;:;.             ......                       ................   ..  ,okx,',;oK0;                                      ........................ \n";
	    	cout<<",,,,,,,,;:;,......       .....                     ..................   .'cdxoo; .,;xO:                              ................................. \n";
	    	cout<<",,',''''''''''''.....    ......                 .................        'xKxl,..;xxo,                    ............................................ \n";
	    	cout<<"''.................                                                       ..,clloxd;.       ..............................................'''''....... \n";
	    	cout<<"'...................                                                          ..... .......................................................''''....... \n";
	    	cout<<".........................                                                   ....................'''''''''''''''..'.....''.........'....'''..''''...... \n";
	    	cout<<"...................................................................................'''''''''''''''''''''''''''''''''''''''........'..........'........ \n";
	    	cout<<"........................................................''''''''.'''.''''''....''''''''''''''''''''''''''''''''''''''''.'''.......'................... \n";
	    	break;
		    
		    
			default:cout<<"opcion invalida \n";	
		}
	}
	
	char instrumentos()
	{
		int opcion;
		cout<<"seleccione una opcion para mostrar una imagen \n";
		cout<<"1. teclado \n";
		cout<<"2. guitarra electrica \n";
		cout<<"3. bateria \n";
		cin>>opcion;
		
		switch(opcion)
		{
			case 1:
			cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWXK0Oxdol:;,....:OWMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWNK0Okdolc:,'...............cOWMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWNK0Oxdlc:;,............................c0WMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWXK0Oxdlc:;'.... ..................................'l0WMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWXK0kxdlcc:;'.....  ............................................'oKWMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNK0Oxolc:,'...   ..........................................................,dXMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNX0Oxdlc:;'...   ......................................................................,xXMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNXKOkdol:;,...   .........................'.    ...................................................,xNMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMWNK0Oxdlc:,'...   .................. ....'',;::ccccllc'    ..........................................;cc,......;kNMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMWNXKOkdolc:,'............................  . .;:clllloooolllllll:'.    ..............................'..'''',,;cxKXkc'.....:OWMMMMMMM \n";
	    	cout<<"MMMMMMMWNXKOkxolc:;'.............................     .....    .cooollcc:;,'''.......  ......................'...,,''ckko:;;,,,,'',ckKKx:.....c0WMMMMM \n";
	    	cout<<"WXkxdlc:;'.................................  ...  .  . .....    .','.................. ..................''',oOkl;:::;;cxOxc,'',''::,lKWNOo,....l0WMMM \n";
	    	cout<<"O,.......................................... . ..... ........      ....................... .....'cdo;,;;;;;;,,;lkOd;,,;:,;xKOo:lxdxK0OXWWWWXxc...'oKWM \n";
	    	cout<<":..........................................     ..................  .......... ........':dd:,;cc;;lk0kl,,,,''',,'c0Kkc:dOdxKWNXKNWWWWWWWWWWNNXk,...,xN \n";
	    	cout<<"'  ....................................................................  ..';:,..,;,,::;;lkKOl,,::;,;d00o;':o::xkokNWNKXNWWWWWWWWWWNNNNXXXKKOOl......d \n";
	    	cout<<"x.  .......................................................... ..',;'.'::,,;lOXOl;;:;,,;;;,;dK0o;'cdl;oXWKxkKX0XNWWWWWWWWWWNNNNNXXKK0Oxdolc;,'.. .   ' \n";
	    	cout<<"WO,  .................................................. ..'..,;;';dKKx:,clcc;,ckKOl,';:;':oc,oXNKxxKNKKNWWWWWWWWWNNNNNNNXXX0Okxdolc;,'.......      ..; \n";
	    	cout<<"WW0:.  ...................................... ..'...;oxd:,:lc;;cc:,;dKKx;';cll;'lKNOo;lkxoOX00XWWWWWWWWWWWWNNNNXXXK00kxdolc;,'.......     ......';cdOX \n";
	    	cout<<"NXX0c.  ..................................,ldl;':oo:,ckXXx:';c:,';c:';kNKx:',dOxokNWNKKXWWWWNWWWNWWNNNNXNXKK0kkdolc:;'.......     ......';:loxk0KXNWMM \n";
	    	cout<<"XXKKOl.  .....................''..,:;';ll;;oONKd;,:oo;':xXKd;':ol,;xxlo0WNX000XWNNWWWWWWWWWWNNNNXXXK0Oxdolc:;'..........   .....',:codkOKXNWWMMMMMMMMM \n";
	    	cout<<"NXK0Oko.  ..............,:,';o0Kkc,:oo;,:lc,'cON0o,.:do,'dXNKdlxK0k0NNXNNWWNNWWWWWWNNNNXXXK00kxxolc:;,'........    ......,;cldxO0KNWWMMMMMMMMMMMMMMMMM \n";
	    	cout<<"WNXKOkxl'   ...... .;dc,:dxl,,lONKd;';lc,.:oc',kNN0o:o00xxXWNNNNNWWWNNNWNNNNNNXXXXKK0Okdolc:;''.........   ......';:loxk0KXNWMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MWNXKOxdl'.   ..  . .:Ok:';odc''oKN0l''oxc,cOkodKNNNXKXNWWWWWWNNWWNNNXXXXK000Oxxdlc:;,'..........  ......',;codkO0XNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMWNXKkdlc,.   .......'x0d,.ckx;'lKNXOdd0X0OKNNNNNWNNNWWNNNNXXXXKKKOOkdooc::;,'.........    ......,;:ldxO0KNNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMWNXKkdlc,.   .......'x0d,.ckx;'lKNXOdd0X0OKNNNNNWNNNWWNNNNXXXXKKKOOkdooc::;,'.........    ......,;:ldxO0KNNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMWWXKOdl:,.   .. .....c0OlcxXKkkKNNNNWNNNWNNNNWNNNNXXXXK00Oxxolc:;,'..........    ......',:coxkOKXNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMWNKOxlc;.   .. .....,xXXXNNWWNNWWNNNNNXNXXKXK00Okddlc:;,'.........      .....',;cldxO0XNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMWWX0koc;.   .........l0NWNNNNXXXXXKK0Okkdooc:;,'..........    ......',;:loxk0KXNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMWNKOdl:'.  .........;kXXK00Okxxolc:;,'..........    ......',;codkOKKXNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMWX0koc,.  .........cddlc:;,''...........   ......,;:ldxO0KXNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMWNKOdl;.  ...................     ......',:coxk0KXNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMWX0ko:.  ..        .     .....',;cldxO0XNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMWNXOxl,.          ....';:loxO0KXNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMWNKOd:......',;codkOKXNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMWWX0kl::codk0XNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM\n";
	    	break;
            
            
			case 2:
			cout<<"MMMMMMMMMMMMMMMMMMMNKOkxdddddxxkOKNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMMMMMMMMMMMMMWXOdl:;;;;;;;,'...':d0NWMMMMMMMMMMMMMMMMMMMMWNXXXXXNNNNNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMW0d:,,;;;;;,,'..........:d0NWWMMMMMMMMMMMWNXKOkkkkOOOO0000kxONMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMW0o;,,,,,,,,'............. .':dOXNNNWWNNXK0Oxdlcc:;,,,;:ldddl;'lk0NMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMNx:,,,,,,,'............... ..  ..,:lodddolc:,'...    ..:oOKXKK0O0KXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMNd,,,,,,''..........................  .....          .,d0NWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMWx,'''''..............      ..     ........          .:KWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMK:'''....... ........                   ......       .OMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNKNMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMWx'......... ......'.   ....     ..      ... ....     .oNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWW0lkWOdKWNXWMMMMMMMMM \n";
	    	cout<<"MMMMMMMNl.......... .;;cdooc. ;xxxkc.  .d0c.   .o0l...''......,lkkkkkOkOOkOOOOOOOOOO00O0000000KKKKKKKKKKKKKKKKKKXXXXXXXXXXXNNNXK0kxkKXxoKNdoXKd0WMMMMM \n";
	    	cout<<"MMMMMMMKc......... .'c;lxdoc..lKXKKd.  ,kXo....,kXd..''''''''''''''''''''',,'','','',,',,,,;,,,;,,,;,,,;;,,,;,,',;,,,;;;,,;cld000xdkOod00kx0XOo0WMMMMM \n";
	    	cout<<"MMMMMMXd,......... .,c;lddoc..oKXKKd.  ,kXd. . 'kXx'..'''..''..''..'.'..'.''..'..''.''',,'',,''''.',,'',,''','''''...''....;:o00Ooloo:cxxoxOdokKXWMMMM \n";
	    	cout<<"MMMMMMNO;...... ..  ,c;lddoc..oKKKKd.  ,OXo. . 'kXd...'''.''.........'.....'..'..'..'..'''',''',''',,'',,'',,,'',,''',,'''':cd000OxddxdldO00kdxkONMMMM \n";
	    	cout<<"MMMMMMMXc...... .   ':;cddoc..cOOOOc.  .xKl.   .dKo..',coodddddddddddxdxxxxkxxkxxkkxkkkkOkkOOOO0OOO000000000KKKKKKKKKKKKKKKXXXNXK0OddOKOx0NNKOkOKWMMMM \n";
	    	cout<<"MMMMMMMWd.....      .;:codol;',;,'.     .,.     .,...cONMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNNNxl0XddNMMWWWMMMMMM \n";
	    	cout<<"MMMMMMMMO;..  ..     .........',,,,,,''',,''''.  ...,OMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM0xKWNNMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMNo.. .          ..         .....     .....  ,0MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMKc...         ..    ..          ......     .;ONMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMW0:..        ..      .      .  .''''...... ..:xKXNNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMKl'..    ... ..      .    ..;ldkOOOxoc;,''';ldxkkkdkNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMNOc'.. ...  ..       ..':okKNWMMMMWWX0kxolllodddlckWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<" MMMMMMMMMMMMNOc'.. ...  ..       ..':okKNWMMMMWWX0kxolllodddlckWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM\n";
	    	cout<<"MMMMMMMMMMMMMMMMWKkoc:;,,,;:coxOKNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMWWNXKKKKXNNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			break;
			
		
			case 3:
			cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNNNNNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
			cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMKxdllxXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXK0Okkkkkkkkkkl;,,,;x0KXNNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWOl:;,'''''''.....'''',',,,,;:clodxO0XNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWKkdlc;''...........','..............,;ld0WMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXK0kxdolcc:;,,;c;............'',,;ckWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWNNXX0dx00OOOOOO000KKXXNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXdkMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMKokMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNXK0OkkkkkOO0XNWMMMMMMMMMMMMMMMKlkMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWWX0xdc:,'.........',:lok0NMMMMMMMMMMM0lkMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMW0dl:;,'...................':dk0WMMMMMMM0lkMMMMMMMMWX0Oxdooooodk0XWMMMMMMMMMMMWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWKo:;,''....'''',,,,,'...........,dNMMMMMMKlkMMMMWKxl:,....    ....,cxXWWMMMMMMNXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMW0o;,c,.,,,,,,,lddxddl,'....',,....;OMMMMMMKoOMWXk:.''.................,coKMMMMMX0NMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXd;'cx::c,,,,,,dOkkxdc,.....',,,'.,,lXMMMMMKd0Nxc'..':,',,,,::cccc:;,....,kWMMMWkdXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWk,.,xOlco;,,,,,;;;,,,,'......,,,;:lc;kMMMMMKxOo....,oOdc;'';x000OOOOkl'.'lKWMMWO;'lKMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNo.',oOc,l:,,,,,,,,,,,,'......',',xXx;kMMMMMKxo' .',,dKxl;,,,cllccclldl,:kXXKK0d;;::lxO0KKXNWMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNo',,lkl:c;,,,,,,,,''''.......',''cdc:kXXXXXOoc;,;;',ckd:;,,,,,,,,,''',';k0xd:,,;,;cccccldx0NMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM0c,,cko:,''''..........     .......'cdk000Kxlcoxo;'',::'',,,,,,,,,'',,,,cc,:lc,.  ..,clodxOXWMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMO:'cOd'............''''............;;cOXXNOodooc'..',;'...............''.,lKM0,  .dNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMKc,;ll. ..,:clloddddxxxdddolc:;,.. ...,,,;;,,'..  ...,,.       ...     ..,ckWNl..oNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMXx;..,;codxxxxxxxxxxxxxxxdddddddoc,. .dd'..;dkc.     .'..',;;::::::;;,'..  cNWKlcKMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWk;.,cdxxxxxxxxxxxxxxddddddddddoooooc..d0,..;0Kc.   ..,:clllccccccccccccc;' ,0MWo:KMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMK:.;oxxxxxxxxxdddddddddddddoooooolloo;.o0, .:0K,  .,:ccccclcccccccc:::::::;.;KMNc;KMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMX:.cxxxxxxddddddddddooooooooollllllll''OO,..:0Nc .;:::::::::::::::;;;;;;;;. .ldo;,oxxkkkkkkOOkkOkkkkkkkkk0NWMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMWNNXKKK00OOOOOkkkkkkkkkd,.;lodddddooooollllllllllccccc:,''l0WM0:,':0M0, ..',,,,,,,,,,,,;,'..':lc;. ....      .....         ....,lo0MMMMMMMM \n";
	    	cout<<"MMMMMMMW0ddxxxxxxxxxxxxkkkkkkkxxxxddl'.,:cloolllllllcccccccc:;,'',:dKWMMM0c,,:0MW0kdc,'..........';:coxKWK;.. .','......''.''........''''';ooOMMMMMMMM \n";
	    	cout<<"MMMMMMMXocl:;;;;;:::::;;;;;;,,,'''...... ...',,,;;;;,,,'''',;:lokXWMMMMWNk:,,:0MMMMMMNKOkxxxxxkOOKXWMMMMMKc.. ..,'......'.........',;:;,;,.,;kMMMMMMMM \n";
	    	cout<<"MMMMMMMXxl:'...                      .  ...   ;oooooooodxkOKNWMMMMWNXKKkc,;;;l0MMMMMMMMMMMMMMMMMMMMMMMMMMKc.   .''...............';:cl:;;,,;c0MMMMMMMM \n";
	    	cout<<"MMMMMMMMNd,,,'''...'''''''''''......','.....  oWMMMMMMMMMMMMWN0xol:,,;,..:c;;:ldxOXWMMMMMMMMMMMMMMMMMMMMMNx;.  ','.....''.''.....'',;;;,,,::cKMMMMMMMM \n";
	    	cout<<"MMMMMMMMWx,,,,,,''',,,,,,,,,,,'....',,,'....  lWMMMMMMMMMWKxc,..     ...';,,'.'...';lkKWMMMMMMMMMMMMMMMMMNo.   ... ....''''''....''',,,''.',xWMMMMMMMM \n";
	    	cout<<"MMMMMMMMMk:,,,,,,',,,,,,,,,,,,'....',,'....   cWMMMMMWXKOl,..               .......   .;d0NMMMMMMMMMMMMMMWXo.          ......       ..    .,OMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMOc;,,,,,,,,,'',,,,,,,''...'''.....   cNMMMMMKc....         ...',;;:::::::;;,''...,cd0NMMMMMMMMMMMMWKo.    ...  ...            .:lkXWMMMMMMMMM \n";
	    	cout<<"MMMMMMMMM0l::,',,,,,,,;;::::;;;'...'''.....   :XMMMWOc'...     ..';clooddddddddddddooollc:,'..,cdKMMMMMMMMMMNx:ol',odldk0d;lkkkkkkkkkkkKWMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMWX0o;,..',,,,,colloxdclo;...'''...... .:KWMNd'.,,.... .,coddxxxxkkkkkkkkkkkkxxxxdddolc:'..,xXNNWMMMMKol0W0cdNN0OXMOckWMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMWX0o;,..',,,,,colloxdclo;...'''...... .:KWMNd'.,,.... .,coddxxxxkkkkkkkkkkkkxxxxdddolc:'..,xXNNWMMMMKol0W0cdNN0OXMOckWMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMXxkd;'..',,,,,;::::c::::'...'''...... .;0MKl....'.':;:odxxxkkkkkOkkkOkkkkkkkkkkkxxxxddolc;,'',dXMMW0oxNMMO:xWMW0OXx:kWMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMNkkkl,..',,,,,,,,,'.',''.....'''..'.. .;OXc.. .,'.,ldxxkkkkkkOOOOOOOOOOOOkkkkxxxkxdddxxddoc;..:ONXxo0WMMMk,dWMMWKxc;OMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMNkdko;.',,,,,,,,,,,,,,''......''..... ..ll.. .,::cdxxkkkdllloxxoxdllcc:c::;;:,,;cc;lxxxxxddoc;..::ckO0OO0l'l0KKKKx,,OMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMWXklcc;',,,,,,,,,,,,,,,'.............   .'......;oxxkkOkddo',ldd:,;;;'.':::;:c;::cllxOkkxxxxdol;. .cdddddc..':xkOOk;'kWMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMWXklcc;',,,,,,,,,,,,,,,'.............   .'......;oxxkkOkddo',ldd:,;;;'.':::;:c;::cllxOkkxxxxdol;. .cdddddc..':xkOOk;'kWMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMW0lcoc,,,,,,,,,,,,,,,,'.............   .,'....cdxkkkkOOxddccoxkxdxxxddxkxkkkOkOOkkOkkkkkkxxxdol:. 'OMMMWd';.,0MMMNl'lONMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMNd:oo,',,,,,,,,,,,,,,'.............   .,....cdxkkkkOOOOkkkkkOOOOOOOOOOOOOOOOOOOOOOOkkkkkkxxxddo;. ;KWXdcO0,,KMMMNc'dxxXMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMNd:oo,',,,,,,,,,,,,,,'.............   .,....cdxkkkkOOOOkkkkkOOOOOOOOOOOOOOOOOOOOOOOkkkkkkxxxddo;. ;KWXdcO0,,KMMMNc'dxxXMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMWx,:l,',,,,,,,,,,,,,'..............   ... .cdxkkkOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOkkkkkkxxxdol,  ;oco0WO';KMMMNl'kNkdKWMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMWx,:l,',,,,,,,,,,,,,'..............   ... .cdxkkkOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOkkkkkkxxxdol,  ;oco0WO';KMMMNl'kNkdKWMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMOccc,.................           ...,;c. ;dxkkkOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOkkkkkkkxxxddo:.  ,xXNXd.;kK0kd;.oO0kd0WMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMKxkxc'..                 ...',:ldO0XXxc..ldxkkOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOkkkkkkkxxxddoc.  lXNNXo.,dx;......;do:kWMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMXOXMWNK0OOkxxdddoddddd:lO0KXNWMMMMMMNd..'oxkkkOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOkkkkkkkkkxxxdol'  lWWXO:.:dccdl.'d0Odc;,c0WMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMNOXMMMMMMMMMMMMMMMMMMNdkMMMMMMMMMMMMWo. ,oxkkkOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOkkkkkkkkkkxxxdol'  cNXc.  'cxkxx,'0MMWKo'.lNMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMNk0MMMMMMMMMMMMMMWNKKOkXMMMMMMMMMMMMWd. ,oxkkkOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOkkkkkkkkkkkkkxxxddol.  :OOd,.;xNNox0',0MMW0lcdooONMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMWkkWMMMMMMMMMMMMXloNMMMMMMMMMMMMMMMMMk. .cdxkkkOOOOOOOOOOkkkkkkkOOOOOOOOkkkkkkkkkkkkkkkkxxxdddl,  ;d;;0WMNXXko;..;KKll0WMMMMW0ocdXWMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMWkkWMMMMMMMMMMMMXloNMMMMMMMMMMMMMMMMMk. .cdxkkkOOOOOOOOOOkkkkkkkOOOOOOOOkkkkkkkkkkkkkkkkxxxdddl,  ;d;;0WMNXXko;..;KKll0WMMMMW0ocdXWMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMOxNMMMMMMMMMMMMWNNMMMMMMMMMMMMMMMMMMK:  ,oxxkkkkkOOkkkkkkkkkkOOOOOOOOOOkkkkkkkkkkkkkkkxxxxddo:. .xNXNMMMOloONx. .::dNMMMMMMMMWKdld0WMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMOxNMMMMMMMMMMMMWNNMMMMMMMMMMMMMMMMMMK:  ,oxxkkkkkOOkkkkkkkkkkOOOOOOOOOOkkkkkkkkkkkkkkkxxxxddo:. .xNXNMMMOloONx. .::dNMMMMMMMMWKdld0WMMMMMMMM \n";
	    	cout<<"MMMMMMMMMM0xXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMK; .:dxxkkkkkkkkkkkkkkkOOOOOOOkkkkkkkkkkkkkkkkkkxxxxddoc.  cNMMMMMMk'lXMWklox0WMMMMMMMMMMMMXxclkXMMMMMM \n";
	    	cout<<"MMMMMMMMNXOKWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMO. .cdxxkkkkkkkkkkkkkkOOOkkkkkkkkkkkkkkkkkkkxxxxxdddo:.  ,KMMMMMMMXdOMMMMMMMMMMMMMMMMMMMMMMMNd',xNMMMM \n";
	    	cout<<"MMMMMWNKKXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWx. .cdxxkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkxxxxxxxdddo;.  ,0MMMMMMMWOkNMMMMMMMMMMMMMMMMMMMMMMMMWKOXWMMMM \n";
	    	cout<<"MMMWX0KXWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMX:  .:odxxxxkkkkkkkkkkkkkkkkkkkkkkkkkkxxxxxxxxddoc'   ;KMMMMMMMWOoKMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMNkkNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNO:  .'cddxxkkkkkkkkkkkkxxxxxxxkkkkkxxxxxxxxdddl,..'.:kOKNMMMMWk.:NMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMx.dMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWN0OOx;.',;odxxkkkxxxxxxxxxxxxxxxkkxxxxxxxxdddoc,.  .:cOWKOkk0XNNo;kWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMOlOMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWKOk0NMMXd:. .,:lddxxxxxxxxxxxxxxxxxxxxxxddddol;...'.'cxXMMMMWKkl;lKWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMN0kOKWMMMMMWxc;.'..';codddddxxxxxxxxxxdddddol:,..   ,ookNNWMMMMMMMXxdXMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXOkkONMMMMMMMMMNNXxo:.   ..';:lloooddoollcc:,'..   .,lkNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWXOkkONMMMMMMMMMNNXxo:.   ..';:lloooddoollcc:,'..   .,lkNMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMNo':kNMMMMMMMMMMMMMMMMWKxl;.      ........      ..;lx0NMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWOkNMMMMMMMMMMMMMMMMMMMMMMWXOxoc:,''...''';:codkKNWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWNNNNNNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";
	    	cout<<"MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM \n";

			
			break;
		default:cout<<"opcion invalida \n";	 	
		}
	return 0;
	}
