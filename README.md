# Personal Space
Sean's Personal Space


banger
<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/mFih47l1pVI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>


### Schedule

| Campion | Monday | Wednesday | Friday |
|-- | ------- |--------|--------|
| 7:30 - 8:00 | [Homeroom/Assembly](https://meet.google.com/vxc-wjwt-qar) | [Homeroom/Assembly](https://meet.google.com/vxc-wjwt-qar)| [Homeroom/Assembly](https://meet.google.com/vxc-wjwt-qar) |
| 8:00 - 8:45 | [Filipino](http://meet.google.com/cov-qdmp-oeb) | [Math](https://meet.google.com/ryj-uirv-fyi) | [Math](https://meet.google.com/ryj-uirv-fyi) |
| 9:00 - 9:45 | [Filipino](http://meet.google.com/cov-qdmp-oeb) | [Filipino](http://meet.google.com/cov-qdmp-oeb) | [Math](https://meet.google.com/ryj-uirv-fyi) |
| 10:00 - 10:45 | [Math](https://meet.google.com/ryj-uirv-fyi) | [CLE](https://meet.google.com/dof-hyim-jmk) | [CLE](https://meet.google.com/dof-hyim-jmk) |
| 11:00 - 11:45 | [Math](https://meet.google.com/ryj-uirv-fyi) | [AP](https://meet.google.com/vio-fquf-svw) | [Filipino](http://meet.google.com/cov-qdmp-oeb) |
| 12:45 - 1:30 | - | - | [AP](https://meet.google.com/vio-fquf-svw) |


| Campion | Monday | Wednesday | Friday |
|-- | ------- |--------|--------|
| 7:30 - 8:00 | [Homeroom/Assembly](https://meet.google.com/vxc-wjwt-qar) | [Homeroom/Assembly](https://meet.google.com/vxc-wjwt-qar)| [Homeroom/Assembly](https://meet.google.com/vxc-wjwt-qar) | |
| 8:00 - 8:45 | [English](https://meet.google.com/kwa-foqe-cyo) | [PE & Health](https://meet.google.com/euq-mehm-ggn) | [Science](https://meet.google.com/zdq-kicu-arj) |
| 9:00 - 9:45 | [PE & Health (Merged)](https://meet.google.com/sdj-vfhg-zzd) | [Science](https://meet.google.com/zdq-kicu-arj) | [Science](https://meet.google.com/zdq-kicu-arj) |
| 10:00 - 10:45 | [Science](https://meet.google.com/zdq-kicu-arj) | [English](https://meet.google.com/kwa-foqe-cyo) | [English](https://meet.google.com/kwa-foqe-cyo) |
| 11:00 - 11:45 | - | [Computer](https://meet.google.com/cym-wtwy-kxc) | [English](https://meet.google.com/kwa-foqe-cyo) |
| 12:45 - 1:30 | [Music & Arts](https://meet.google.com/jrj-aqoh-qxj) | [Music & Arts](https://meet.google.com/jrj-aqoh-qxj) | - |
| 2:45 - 3:30 | - | - | [Computer](https://meet.google.com/cym-wtwy-kxc) |


### Links for synchronous sessions:
- [Homeroom](https://meet.google.com/vxc-wjwt-qar)
- [English](https://meet.google.com/kwa-foqe-cyo)
- [PE & Health](https://meet.google.com/euq-mehm-ggn)
- [PE & Health (Merged)](https://meet.google.com/sdj-vfhg-zzd)
- [Science](https://meet.google.com/zdq-kicu-arj)
- [Music & Arts](https://meet.google.com/jrj-aqoh-qxj)
- [Computer](https://meet.google.com/cym-wtwy-kxc)
- [CLE](https://meet.google.com/dof-hyim-jmk)
- [Filipino](http://meet.google.com/cov-qdmp-oeb)
- [Math](https://meet.google.com/ryj-uirv-fyi)
- [AP](https://meet.google.com/vio-fquf-svw)
- [Homeroom](https://meet.google.com/vxc-wjwt-qar)




![Alt Text](https://c.tenor.com/1rkyTODR2qQAAAAi/rikka-takanashi-takanashi-rikka.gif)

int main() {
    float A = 0, B = 0;
    float i, j;
    int k;
    float z[1760];
    char b[1760];
    printf("\x1b[2J");
    for(;;) {
        memset(b,32,1760);
        memset(z,0,7040);
        for(j=0; j < 6.28; j += 0.07) {
            for(i=0; i < 6.28; i += 0.02) {
                float c = sin(i);
                float d = cos(j);
                float e = sin(A);
                float f = sin(j);
                float g = cos(A);
                float h = d + 2;
                float D = 1 / (c * h * e + f * g + 5);
                float l = cos(i);
                float m = cos(B);
                float n = sin(B);
                float t = c * h * g - f * e;
                int x = 40 + 30 * D * (l * h * m - t * n);
                int y= 12 + 15 * D * (l * h * n + t * m);
                int o = x + 80 * y;
                int N = 8 * ((f * e - c * d * g) * m - c * d * e - f * g - l * d * n);
                if(22 > y && y > 0 && x > 0 && 80 > x && D > z[o]) {
                    z[o] = D;
                    b[o] = ".,-~:;=!*#$@"[N > 0 ? N : 0];
                }
            }
        }
        printf("\x1b[H");
        for(k = 0; k < 1761; k++) {
            putchar(k % 80 ? b[k] : 10);
            A += 0.00004;
            B += 0.00002;
        }
        usleep(30000);
    }
    return 0;
}

