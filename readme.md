# TUGASBESAR_PKS2
#include <iostream>   
using namespace std; 
int main(){          

	string jenis, kode, selesai, lagi;   
	char pilihan,loop ;
	int i,total, jumlah, harga;
    int hargamenu[10]={35000,35000,30000,30000,25000,20000,15000,20000,15000,20000};
	
	do{  
		for(int i=0; i<1; i++){
			cout << "-------------------------------------------------------" <<endl;
			cout << "      Vending Machine 013- TERMINAL B Domestic         " <<endl;
			cout << "-------------------------------------------------------" <<endl;
			cout << " SUMATERA    `~ /|/| /|             ____                "<<endl;
			cout << " INTERNATIONAL /|/_|/_|     X      (___/| JANJI ENAKK   "<<endl; 
			cout << " AIRPORT      |||  |  |            | j || TOAST n COFFE "<<endl;  
			cout << "  -SIA        =========            =====               "<<endl;                          
			cout << "-------------------------------------------------------" <<endl; 
			cout << "-------------------------------------------------------" <<endl;
			cout << "            | JANJI ENAKK TOAST n COFFE |              " <<endl;
			cout << "-------------------------------------------------------" <<endl;
			cout<<endl;
		}
		cout << "Hallo, Traveler :) Lapar ya... Haus ya...."<< endl;
		cout<<endl;
		cout << "--------------------------------------------------------"<<endl;
		cout << " kode | Menu                                |   Harga   "<<endl;
		cout << "--------------------------------------------------------"<<endl;
		cout << "  A   |  BEEF RENDANG TOAST                 | IDR 35000 "<<endl;
		cout << "  B   |  TUNA CURRY SAUCE TOAST             | IDR 35000 "<<endl;
		cout << "  C   |  CHICKEN MENTAI SAUCE TOAST         | IDR 30000 "<<endl;
		cout << "  D   |  CHICKEN CURRY SAUCE TOAST          | IDR 30000 "<<endl;
		cout << "  E   |  EGG CURRY CHEESE n SAUSAGE TOAST   | IDR 25000 "<<endl;
		cout << "  F   |  EGG CURRY MAYO                     | IDR 20000 "<<endl;
		cout << "  G   |  AVOCADO ICE COFFE                  | IDR 15000 "<<endl;
		cout << "  H   |  ICE LATTE                          | IDR 20000 "<<endl;
		cout << "  I   |  ICE AMERICANO (less sugar)         | IDR 15000 "<<endl;
		cout << "  J   |  ICE CAPPUCINO                      | IDR 20000 "<<endl;
		cout << "--------------------------------------------------------"<<endl;
		cout << " Pembayaran hanya bisa melalui:      "<<endl;
		cout << "  * Scan Qris di layar               "<<endl;
		cout << "  * E-money                          "<<endl;
		cout << "  * Uang Cash (pastikan uang pas)    "<<endl;
		cout <<endl;
		cout << "--------------------------------------------------------"<<endl;
		cout << "  Anda mau beli yang mana ? (klik salah satu kode)"; cin>>pilihan;
		cout << "--------------------------------------------------------"<<endl;
		cout << "                    Berapa pcs? "; cin >> jumlah;
		cout << "--------------------------------------------------------"<<endl;
		cout <<endl;

		if(jumlah >=6){
			cout << "--------------------------------------------------------"<<endl;
			cout << "   maaf,pembelian dibatasi maksimal 5 untuk satu menu     "<<endl;
			cout << "           Harap ulangi, Berapa pcs? ";
			cin >>jumlah;
			cout << "--------------------------------------------------------"<<endl;
			cout <<endl;
		}
		switch(pilihan){                                  
				case 'A' :                                
				jenis = "BEEF RENDANG TOAST";             
                for (i=0; i<=11; i++){                     
                    harga= hargamenu[0];}
				total= jumlah * harga;
				break;
            case 'B' :
				jenis = "TUNA CURRY SAUCE TOAST";
				for (i=0; i<=11; i++){
                    harga= hargamenu[1];}
				total= jumlah * harga;
				break;
			case 'C' :
				jenis = "CHICKEN MENTAI SAUCE TOAST";
				for (i=0; i<=11; i++){
                    harga= hargamenu[2];}
				total= jumlah * harga;
				break;
            case 'D' :
				jenis = "CHICKEN CURRY SAUCE TOAST";
				for (i=0; i<=11; i++){
                    harga= hargamenu[3];}
				total= jumlah * harga;
				break;
            case 'E' :
				jenis = "EGG CURRY CHEESE n SAUSAGE TOAST";
				for (i=0; i<=11; i++){
                    harga= hargamenu[4];}
				total= jumlah * harga;
				break;
            case 'F' :
				jenis = "EGG CURRY MAYO";
				for (i=0; i<=11; i++){
                    harga= hargamenu[5];}
				total= jumlah * harga;
				break;
            case 'G' :
				jenis = "AVOCADO ICE COFFE";
				for (i=0; i<=11; i++){
                    harga= hargamenu[6];}
				total= jumlah * harga;
				break;
            case 'H' :
				jenis = "ICE LATTE";
				for (i=0; i<=11; i++){
                    harga= hargamenu[7];}
				total= jumlah * harga;
				break;
            case 'I' :
				jenis = "ICE AMERICANO (less sugar) ";
				for (i=0; i<=11; i++){
                    harga= hargamenu[8];}
				total= jumlah * harga;
				break;
            case 'J' :
				jenis = "ICE CAPPUCINO";
				for (i=0; i<=11; i++){
                    harga= hargamenu[9];}
				total= jumlah * harga;
				break;
			}
//penjelasan ke3
//			
		cout << "   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~" << endl;
		cout << "   |  #NGOPIDULU                |          ____   |  "<<endl;
		cout << "   |  #TOASTDULU   #SUMATERA    |  JANJI  (___/|  |  "<<endl;
		cout << "   |  #SAVEFLIGHT  #INDONESIA   |  ENAKK  | j ||  |  "<<endl;
		cout << "   |  #HAVEFUN                  |         ======  |  "<<endl;
		cout << "   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~" << endl;
		cout << "   |                PESANAN ANDA                  |" << endl;
		cout << "   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~" << endl;
		cout  << endl;
		cout << "      Menu dipesan | "<< jenis<< "             "<<endl;
		cout << "      Jumlah       | "<< jumlah<<" pcs         "<<endl;
		cout << "      Harga        | IDR "<< harga<< "         "<<endl;
		cout << endl;
		cout << "   ------------------------------------------------"<<endl;
		cout << "       Total       | IDR "<< total <<"       "  << endl;
		cout << "   ------------------------------------------------"<<endl;
		cout << "    Harap melakukan pembayaran:                    "<<endl;
		cout << "    melalui scan Qris/E-money/Uang cash*           "<<endl;
		cout << "      *Pastikan Uang pas, tidak ada kembalian serta"<<endl;
		cout << "        uang tidak terlipat dan tidak robek        "<<endl;
		cout << "    ___________                                    "<<endl;
		cout << "   |           |                 tempelkan    >>   "<<endl;
		cout << "   |   scan    |                E-money anda  >>   "<<endl;  
		cout << "   |   Qris    |                 disamping    >>   "<<endl;
		cout << "   |  disini   |                   layar      >>   "<<endl;
		cout << "   |___________|                                   "<<endl;
		cout << "                                  masukkan    >>   "<<endl;
		cout << "    ____                          uang anda   >>   "<<endl;
		cout << "   (___/| JANJI                   disamping   >>   "<<endl;
		cout << "   | j || ENAKK                     layar     >>   "<<endl;  
		cout << "   ======                                          "<<endl;
		cout << "   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"<<endl;
		cout<<endl;
		cout << "   ------------------------------------------------"<<endl;
		cout << "   Jika telah melakukan pembayaran, (klik OK) "; cin>>selesai;
		cout << "   ------------------------------------------------"<<endl; cout<<endl;
		cout << "   ------------------------------------------------"<<endl;
	    cout << "             pesanan anda sedang diproses          "<<endl;
		cout << "                    mohon ditunggu                 "<<endl;
		cout << "                        ~~~~                       "<<endl;
		cout<<endl; cout<<endl; cout<<endl; 
		cout << "   ------------------------------------------------"<<endl;
		cout << "                    Terima kasih                   "<<endl;
		cout << "             silahkan ambil pesanan anda           "<<endl;
		cout << "                      v v v v                      "<<endl;
		cout << "   ------------------------------------------------"<<endl;
		cout << "   ------------------------------------------------"<<endl;
		cout << "              Ingin memesan lagi (Y/N)? "; cin >> lagi;
	}	while(loop == 'Y');
		cout << "   ------------------------------------------------ "<<endl;
		cout << "   ------------------------------------------------  "<<endl;
		cout << "       Selamat menikmati makanan/ minuman anda       "<<endl;
		cout << "        & selamat menikmati perjalanan anda :)       "<<endl;
		cout << "   ------------------------------------------------   "<<endl;
		cout << "   |  #NGOPIDULU                |          ____   |  "<<endl;
		cout << "   |  #TOASTDULU   #SUMATERA    |  JANJI  (___/|  |  "<<endl;
		cout << "   |  #SAVEFLIGHT  #INDONESIA   |  ENAKK  | j ||  |  "<<endl;
		cout << "   |  #HAVEFUN                  |         ======  |  "<<endl;
		cout << "   ------------------------------------------------  "<<endl;
		cout << "      SUMATERA INTERNATIONAL AIRPORT- TERMINAL B     "<<endl;
		cout << "   ------------------------------------------------  "<<endl;
		cout<<endl;
		cout<<endl;
		cout<<endl;
		cout<<endl;
		cout<< "    (c) Alber Analafean"<<endl; 
		return 0;
}


