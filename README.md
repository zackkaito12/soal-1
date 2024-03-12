# soal-1
#include <iostream>

using namespace std;

int main()
{
  float kalk,pengm,andt,bindo,bing,kim,fis,agama,skskalk,skspm,sksand,sksbind,sksbing,skskim,sksfis,sksag,Totkalk,Totpengm,Totandt,Totbind,Totbing,Totkim,Totfis,Totag,Totsks,IP;

  cout<<" masukkan nilai kalkulus(dalam bentuk angka) = "; cin>>kalk;
  cout<<" masukkan jumlah sks  = "; cin>>skskalk;
  Totkalk=kalk*skskalk;

  cout<<" masukkan nilai pengmat(dalam bentuk angka) = "; cin>>pengm;
  cout<<" masukkan jumlah sks = "; cin>>skspm;
  Totpengm=pengm*skspm;

  cout<<" masukkan nilai analisis data(dalam bentuk angka) = "; cin>>andt;
  cout<<" masukkan jumlah sks = "; cin>>sksand;
  Totandt=andt*sksand;

  cout<<" masukkan nilai bahasa indonesia(dalam bentuk angka) = "; cin>>bindo;
  cout<<" masukkan jumlah sks = "; cin>>sksbind;
  Totbind=bindo*sksbind;

  cout<<" masukkan nilai bahasa inggris(dalam bentuk angka) = "; cin>>bing;
  cout<<" masukkan jumlah sks = "; cin>>sksbing;
  Totbing=bing*sksbing;

  cout<<" masukkan nilai kimia(dalam bentuk angka) = "; cin>>kim;
  cout<<" masukkan jumlah sks = "; cin>>skskim;
  Totkim=kim*skskim;

  cout<<" masukkan nilai fisika(dalam bentuk angka) = "; cin>>fis;
  cout<<" masukkan jumlah sks = "; cin>>sksfis;
  Totfis=fis*sksfis;

  cout<<" masukkan nilai agama(dalam bentuk angka) = "; cin>>agama;
  cout<<" masukkan jumlah sks = "; cin>>sksag;
  Totag=agama*sksag;


  Totsks=skskalk+skspm+sksand+sksbind+sksbing+skskim+sksfis+sksag;
  cout<< " Total sks semester 1 = ";cout<<Totsks<<endl;

  IP=(Totkalk+Totpengm+Totandt+Totbind+Totbing+Totkim+Totfis+Totag)/Totsks;
  cout<< " IP semester 1 = ";cout<<IP<<endl;

}


