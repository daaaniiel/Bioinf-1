# Bioinf-1

# Trabajo Bioinformática practico 01
## Parte 1: Enfermedades genéticas y genes

##### Enfermedad: La distrofia muscular de Duchenne o distrofia muscular progresiva (DMD)
La distrofia muscular de Duchenne (DMD), es una enfermedad hereditaria de tipo recesivo ligado al cromosoma X, que generalmente se manifiesta en hombres y rara vez en mujeres, que normalmente son las portadoras de esta enfermedad. Es causada por mutaciones en el gen de la distrofina conllevando a células musculares degenerativas.
1. #### ¿Cuál(es) gene(s) han sido relacionados con esta enfermedad?
_DMD ha sido el gen relacionado a la enfermedad.

2. #### ¿Tiene nombres alternativos el gen? 
_Sí, estos se pueden encontrar como : BMD; CMD3B; MRX85; DXS142; DXS164; DXS206; DXS230; DXS239; DXS268; DXS269; DXS270; DXS272.

3. #### ¿En qué cromosoma está? ¿Cuántos exones tiene? ¿Cuántas isoformas de transcritos?  
 _En el cromosoma Xp21.2-p21.1
Posee 89 exones
Según NG 012232.1, se encuentran 17 isoformas revisadas, además, a través de ensamblaje primario, según GRCh38.p7 existen 13 isoformas más.
 
4. #### ¿Qué tipo de proteina es codificada por este gen? ¿Cuál es su número EC? 
 _Proteína Distrofina, no posee EC. 
 
5. #### ¿Qué genes están inmediatamente río arriba/abajo?
_Según la orientación de mi gen (3->5), río arriba encontraremos el gen  LOC646506 y rio abajo el gen FTHL17.

6. #### ¿Cuál es la longitud de tu gen?
 _El gen posee un rango genómico apróximado de 2,9Mpb según National Center for Biotechnology Information (ncbi), aunque en la página Uniprot se informa que es de 2,4 Mpb.
 
7. #### ¿Cuántas variantes de tu gen hay descritas y en qué posiciones?
 _Hay 1856 variantes descritas de mi gen.(FALTA LA POSICIÓN)
 
8. #### ¿Las sustituciones corresponden a cambios sinónimos o no sinónimos?  
 _439 sustituciones corresponden a cambios sinónimos, y 831 no sinónimas según el filtro que nos arroja NCBI (RefSeq).

9. #### ¿Existen ortólogos de tu gen en otras especies? ¿Cuántos?  
 _Si, existen 165 organismos ortólogos con el gen humano (DMD)

10. #### ¿Y paralógos? ¿Hay pseudogenes? ¿Cuántos?
 _En ncbi no fue posible encontrar esta información, sin embargo, KEGG	indica que existen 296.
 
## Parte 2: Rutas y procesos biológicos
1. #### Anteriormente encontraste nombres alternativos de tu gen ¿Existen otros reportados por Kegg? ¿Cuáles?
_Si, si bien Kegg posee nombres alternativos identicos, la página posee un gen mas adicional, MRX85 (que no aparece en ncbi).

2. #### ¿En qué rutas metabólicas participa la proteina codificada por tu gen? 
_En la cardiomiopatía hipertrófica (HCM) 
http://www.kegg.jp/kegg-bin/show_pathway?hsa05410+1756

3. #### 	¿Cuál es el número de identificación de tu gen (entry number)?  
_El numero de identificación de mi gen es el 	hsa.1756.
 
 4. #### En general, cada unidad dentro de una base de datos tiene un número o código de identificación único. De esta forma, uno puede obtener exactamente lo que quiere dentro de un oceano de otras cosas ¿En qué otras bases de datos está tu gen presente y cuáles son sus números de acceso?
 _El gen DMD es posible encontrarlo en otras bases de datos, las cuales poseen un código de acceso diferente que pueden ser encontradas como: 
NCBI-GeneID:1756
NCBI-ProteinID:NP_003997
OMIM:300377
HGNC:2928
Ensembl:ENSG00000198947
Vega: OTTHUMG00000021336
Pharos:P11532(Tbio)
UniProt:P11532
 
5. #### ¿En qué otras rutas metabólicas está involucrado tu gen?
_Cardiomiopatía Arritmogénica del ventrículo izquierdo (ARVC).
Cardiomiopatía dilatada (DCM).
Miocarditis viral.
	
6. #### ¿Qué significan los cuadros verdes en el diagrama?
_La presencia de identificadores génicos, indica que el gen está presente en la ruta metabólica y además la integridad dentro de la vía.
	
7. #### ¿Con qué rutas se cruza la ruta metabólica?
_Con la vía de señalizacion de JAK-STAT, vía de señalización TGFB y con la ruta del sistema renina-angiotensina.

### GO (Gene Ontology) →

8. #### ¿Cuántos "dominios" forman la anotación GO?
_Tres dominios forman la anotacion de GO, tales como funcion molecular, componentes celulares, procesos biologicos, las cuales permiten poder definir conceptos y clases, y de esta manera lograr definir la función del gen.

### >	Ve a "Tools" --> "AmiGO 2" y escribe en la casilla de búsqueda GO:0006096  
9. ####	¿A qué corresponde este término y qué información te entrega la página?
_El término corresponde a un número de acceso el cual indica un proceso glucolítico, cabe destacar que la informacion que entrega la pagina se divide en dos secciones, la primera, se basa en informacion específica del número de acceso (GO:0006096)en la cual podemos observar y analizar informacion detallada sobre el proceso glucolítico, anotaciones directas e indirectas del proceso y además genes y productos de los genes asociados a procesos glucolíticos. Por otra parte, se encontrará con informacion mas general respecto al gen. 
### >	Haz clic en "Graph Views" y examina el gráfico. 
10. #### Anota 10 sub-categorías GO a la cual GO:0006096 pertenece.
_10 sub-categorías la cual GO:0006096 pertenece: proceso biosintesis de ATP, proceso catabolico de carbohidratos, proceso biosintetico de nucleotidos de nicotinamida, proceso catabólico de nucleotidos, proceso de generacion de ATP a partir de ADP, proceso biosintetico del piruvato. Los demás procesos que se pueden observar corrsponden a las sub-categorias de las sub-categorias de mi gen de interés.

## Parte 3: Descargando secuencias, convirtiendo formatos.

1. #### ¿Cuántos items fueron encontrados? ¿cuántos en animales?
_Fueron encontrados 70748 items en ncbi, de los cuales 13419 corresponden a animales.
	
  ### >Probablemente tus resultados fueron una mezcla de fragmentos de genes, regiones codificantes parciales, genes completos, etc. Filtra tus datos por mRNA, animales, RefSeq. Haz clic en la entrada para la secuencia de GAPDH de gallina. 
2. ####	¿Cuál es la longitud del gen?
_La longitud del gen es de 1288pb.

3. #### ¿Cuál es la referencia bibliográfica más reciente?
_La referencia bibliográfica más reciente que nos entrega la página es Ren X, Zhang L, Gao Y, Gao H, Wang Y, Liu C, Cui H, Zhang Y, Jiang L, Qi X and Wang X.
 TITLE: Binding chicken Anx2 is beneficial for infection with infectious bursal disease virus JOURNAL   Virus Res. 210, 232-240 (2015)
 
4. ####	¿Cuál es el número de acceso?
_El número de acceso es NM_204305

### >	Descarga la secuencia en formato fasta y agrégala a tu informe.
_>NM_204305.1 Gallus gallus glyceraldehyde-3-phosphate dehydrogenase (GAPDH), mRNA
ACCTTCTCACTGCGCGCTGGGGCCGTTGACGTGCAGCAGGAACACTATAAAGGCGAGATGGTGAAAGTCG
GAGTCAACGGATTTGGCCGTATTGGCCGCCTGGTCACCAGGGCTGCCGTCCTCTCTGGCAAAGTCCAAGT
GGTGGCCATCAATGATCCCTTCATCGATCTGAACTACATGGTTTACATGTTCAAATATGATTCTACACAC
GGACACTTCAAGGGCACTGTCAAGGCTGAGAACGGGAAACTTGTGATCAATGGGCACGCCATCACTATCT
TCCAGGAGCGTGACCCCAGCAACATCAAATGGGCAGATGCAGGTGCTGAGTATGTTGTGGAGTCCACTGG
TGTCTTCACCACCATGGAGAAGGCTGGGGCTCATCTGAAGGGTGGTGCTAAGCGTGTTATCATCTCAGCT
CCCTCAGCTGATGCCCCCATGTTTGTGATGGGTGTCAACCATGAGAAATATGACAAGTCCCTGAAAATTG
TCAGCAATGCATCGTGCACCACCAACTGCCTGGCACCCTTGGCCAAGGTCATCCATGACAACTTTGGCAT
TGTGGAGGGTCTTATGACCACTGTCCATGCCATCACAGCCACACAGAAGACGGTGGATGGCCCCTCTGGG
AAGCTGTGGAGAGATGGCAGAGGTGCTGCCCAGAACATCATCCCAGCGTCCACTGGGGCTGCTAAGGCTG
TGGGGAAAGTCATCCCTGAGCTGAATGGGAAGCTTACTGGAATGGCTTTCCGTGTGCCAACCCCCAATGT
CTCTGTTGTTGACCTGACCTGCCGTCTGGAGAAACCAGCCAAGTATGATGATATCAAGAGGGTAGTGAAG
GCTGCTGCTGATGGGCCCCTGAAGGGCATCCTAGGATACACAGAGGACCAGGTTGTCTCCTGTGACTTCA
ATGGTGACAGCCATTCCTCCACCTTTGATGCGGGTGCTGGCATTGCACTGAATGACCATTTCGTCAAGCT
TGTTTCCTGGTATGACAATGAGTTTGGATACAGCAACCGTGTTGTGGACTTGATGGTCCACATGGCATCC
AAGGAGTGAGCCAGGCACACAGCCCCCCTGCTGCCTAGGGAAGCAGGACCCTTTGTTGGAGCCCCTGCTC
TTCACCACCGCTCAGTTCTGCATCCTGCAGTGAGAGGCCAGTTCTGTTCCCTTCTGTCTCCCCCACTCCT
CCAATTTCTTCCTCCACCTGGGGGAGGTGGGAGAGGCTGATAGAAACTGATCTGTTTGTGTACCACCTTA
CATCAATAAAAGTGTTCACCATCTGAAG
 
### >Ve a la página de Seqret del EBI. Luego copia y pega la secuencia de GAPDH en fasta en la casilla.

_#NEXUS
begin data;
dimensions ntax=1 nchar=1288;
format interleave datatype=DNA missing=N gap=-;
matrix

NM_204305.1          ACCTTCTCACTGCGCGCTGGGGCCGTTGACGTGCAGCAGGAACACTATAA

NM_204305.1          AGGCGAGATGGTGAAAGTCGGAGTCAACGGATTTGGCCGTATTGGCCGCC

NM_204305.1          TGGTCACCAGGGCTGCCGTCCTCTCTGGCAAAGTCCAAGTGGTGGCCATC

NM_204305.1          AATGATCCCTTCATCGATCTGAACTACATGGTTTACATGTTCAAATATGA

NM_204305.1          TTCTACACACGGACACTTCAAGGGCACTGTCAAGGCTGAGAACGGGAAAC

NM_204305.1          TTGTGATCAATGGGCACGCCATCACTATCTTCCAGGAGCGTGACCCCAGC

NM_204305.1          AACATCAAATGGGCAGATGCAGGTGCTGAGTATGTTGTGGAGTCCACTGG

NM_204305.1          TGTCTTCACCACCATGGAGAAGGCTGGGGCTCATCTGAAGGGTGGTGCTA

NM_204305.1          AGCGTGTTATCATCTCAGCTCCCTCAGCTGATGCCCCCATGTTTGTGATG

NM_204305.1          GGTGTCAACCATGAGAAATATGACAAGTCCCTGAAAATTGTCAGCAATGC

NM_204305.1          ATCGTGCACCACCAACTGCCTGGCACCCTTGGCCAAGGTCATCCATGACA

NM_204305.1          ACTTTGGCATTGTGGAGGGTCTTATGACCACTGTCCATGCCATCACAGCC

NM_204305.1          ACACAGAAGACGGTGGATGGCCCCTCTGGGAAGCTGTGGAGAGATGGCAG

NM_204305.1          AGGTGCTGCCCAGAACATCATCCCAGCGTCCACTGGGGCTGCTAAGGCTG

NM_204305.1          TGGGGAAAGTCATCCCTGAGCTGAATGGGAAGCTTACTGGAATGGCTTTC

NM_204305.1          CGTGTGCCAACCCCCAATGTCTCTGTTGTTGACCTGACCTGCCGTCTGGA

NM_204305.1          GAAACCAGCCAAGTATGATGATATCAAGAGGGTAGTGAAGGCTGCTGCTG

NM_204305.1          ATGGGCCCCTGAAGGGCATCCTAGGATACACAGAGGACCAGGTTGTCTCC

NM_204305.1          TGTGACTTCAATGGTGACAGCCATTCCTCCACCTTTGATGCGGGTGCTGG

NM_204305.1          CATTGCACTGAATGACCATTTCGTCAAGCTTGTTTCCTGGTATGACAATG

NM_204305.1          AGTTTGGATACAGCAACCGTGTTGTGGACTTGATGGTCCACATGGCATCC

NM_204305.1          AAGGAGTGAGCCAGGCACACAGCCCCCCTGCTGCCTAGGGAAGCAGGACC

NM_204305.1          CTTTGTTGGAGCCCCTGCTCTTCACCACCGCTCAGTTCTGCATCCTGCAG

NM_204305.1          TGAGAGGCCAGTTCTGTTCCCTTCTGTCTCCCCCACTCCTCCAATTTCTT

NM_204305.1          CCTCCACCTGGGGGAGGTGGGAGAGGCTGATAGAAACTGATCTGTTTGTG

NM_204305.1          TACCACCTTACATCAATAAAAGTGTTCACCATCTGAAG
;

end;
begin assumptions;
options deftype=unord;  
end;

## PARTE 4: Buscando artículos científicos en línea
confirmación de ncbi y google scholar.

