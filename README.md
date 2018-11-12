package Percobaan1;


class Pesawat {
    //variabelnya
 String NomorPenerbangan;
 String JenisPesawat;
 String Maskapai;
int KecepatanMaksimal;
int KapasitasPenumbang;
   //Konstruktornya
    public Pesawat(String NP,String JP,String M,int KM, int KP)
    { this.NomorPenerbangan=NP;
      this.JenisPesawat=JP;
      this.Maskapai=M;
      this.KecepatanMaksimal=KM;
      this.KapasitasPenumbang=KP;
      
    }
    //Methode
    public void tampilData()
    {System.out.println("------Data Pesawat-----");
     System.out.println("Nomor Penerbangan            : "+this.NomorPenerbangan);
     System.out.println("Jenis Pesawat                : "+this.JenisPesawat);
     System.out.println("Maskapai                     : "+this.Maskapai);
     System.out.println("Kecepatan Maksimal  ( km/jam): "+this.KecepatanMaksimal)  ;
     System.out.println("Kapasitas Penumpang ( orang ): "+this.KapasitasPenumbang)  ;
            }
            }
    public class dataPesawat{
    public static void main(String args []){
    Pesawat flight1=new Pesawat("GA-187","Airbus A330-200","GARUDA INDONESIA",913 ,295 );    
    flight1.tampilData();
    Pesawat flight2=new Pesawat("JT-387","Boeing 747","Lion Air",988 ,400 );
    flight2.tampilData();
    }
    }
          


