# hse_hw3_chromhmm

## Соответствие меток и файлов
| Метка       | Файл                |
| :-------------: |:------------------:|
| control     | wgEncodeBroadHistoneCd20ControlAlnRep1.bam    |
| H3K27ac     | wgEncodeBroadHistoneA549H3k27acDex100nmAlnRep1.bam    |
| H3K27me3     | wgEncodeBroadHistoneA549H3k27me3Dex100nmAlnRep1.bam    |
| H3K36me3     | wgEncodeBroadHistoneA549H3k36me3Dex100nmAlnRep1.bam    |
| H3K4me1     | wgEncodeBroadHistoneA549H3k04me1Dex100nmAlnRep1.bam    |
| H3K4me2     | wgEncodeBroadHistoneA549H3k04me2Dex100nmAlnRep1.bam   |
| H3K4me3     | wgEncodeBroadHistoneA549H3k04me3Dex100nmAlnRep1.bam    |
| H3K79me2     | wgEncodeBroadHistoneA549H3k79me2Dex100nmAlnRep1.bam    |
| H3K9ac     | wgEncodeBroadHistoneA549H3k09acEtoh02AlnRep1.bam    |
| H3K9me3     | wgEncodeBroadHistoneA549H3k09me3Etoh02AlnRep1.bam    |
| H4K20me1    | wgEncodeBroadHistoneA549H4k20me1Etoh02AlnRep1.bam    |


| Состояние       |  Тип               | Описание                | Название                |
| :-------------: | :------------------: | :------------------ | :------------------: |
| 1     | ![](/data/1.png)     |  <ul><li> чаще всего попадает на ядерную ламину</li><li>наиболее выражено (но слабо) на метке H3K27me3</li><li>в основном  локализуется в межгенном пространстве</li> | **Repressed** |
| 2     | ![](/data/2.png)     |  <ul><li> часто попадает на ядерную ламину</li><li> занимает бОльшую часть генома (%)</li><li>плохо выражено на всех метках</li><li>в основном  локализуется в межгенном пространстве и на интронах</li> | **Repressed** (возможно, Weak transcribed/Unmapable, так как низкий уровень emission frequency и высокий уровень self-transition) |

| 3     | ![](/data/3.png)     |  <ul><li> часто попадает на ядерную ламину</li><li>Выраженна метке H3K9me3</li><li>в основном  локализуется в межгенном пространстве</li> | **Heterochromatin**  |
| 4     | ![](/data/4.png)     |  <ul><li> часто попадает на RefSeqTES, RefSeqGene, RefSeq Exon</li><li>Выраженна метке H3K9me3, H3K36me3</li><li>локализуется на интроне или экзон</li> | **WeakTranscribed**  |
