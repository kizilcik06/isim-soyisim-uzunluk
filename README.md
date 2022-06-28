# isim-soyisim-uzunluk

    String isimler = "Batuhan, Bengisu, Beyza, Bora, Emircan, Emir, İnci, İsmail";
    String soyisimler = "Kaya, Durmus, Aktas, Evren, Aydın, Yildiz, Cumen, Aytar";
    String[] arrSplitisim = isimler.split(", ");
    String[] arrSplitsoyisim = soyisimler.split(", ");
    String isimSoyisim ;
    int uzunluk ;
    int kisiSayisi = arrSplitisim.length;

    for (int i = 0 ; i < kisiSayisi ; i++) {
        isimSoyisim = arrSplitisim[i]+" "+arrSplitsoyisim[i];
        uzunluk = isimSoyisim.length();
        System.out.println(isimSoyisim+", Uzunluk:"+uzunluk);
    }
}
}
