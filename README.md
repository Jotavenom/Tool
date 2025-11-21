#Herramientas Bioinformáticas

##### PROYECTO DE CURSO


#Título del Proyecto: Minería Genómica y Caracterización In Silico de una Metaloproteinasa de Veneno de Serpiente de Clase P-III (SVMP-III) en el genoma de Bothrops brazili mediante ensamblaje dirigido

#Hipótesis: El genoma de Bothrops brazili contiene secuencias codificantes para SVMP-III altamente conservadas en el dominio catalítico (sitio de unión a Zinc), pero con alta variabilidad alélica en los dominios C-terminales, lo cual correlaciona con la patofisiología específica del envenenamiento por esta especie en la Amazonía.

#Objetivo General: Identificar, ensamblar y anotar funcionalmente la secuencia completa del gen codificante para una SVMP-III a partir de librerías de lecturas crudas (SRA) de Bothrops brazili, mediante técnicas de bioinformática comparativa.
Objetivos Específicos:

#OE1 (Recuperación de Datos): Identificar y descargar subconjuntos de reads genómicos/transcriptómicos de B. brazili desde NCBI SRA utilizando filtrado de calidad.

#OE2 (Ensamblaje Dirigido): Reconstruir la secuencia consenso del gen SVMP-III utilizando una estrategia de alineamiento contra referencia (Reference-guided assembly) usando B. jararaca como molde.

#OE3 (Anotación): Predecir el marco de lectura abierto (ORF), intrones/exones y traducir la secuencia a proteína in silico.

#OE4 (Caracterización Estructural): Modelar la estructura terciaria (3D) de la proteína predicha y analizar sus dominios funcionales en comparación con estructuras cristalograficas conocidas.

###ESTRATEGIAS: 
#Genomica comparativa: Numero de secuencias (especies) : 5 a 7
#Tarjet- B. brazili
#Referencia - B. jararaca (jararhagin)
#Secuencias hermanas - B. atrox , B. asper
#Outgroup - Crotalus durissus o Lachesis muta. Para rootear el arbol y definir la relacion evolutiva



##PIPELINE:
#Trimming
#Ensamblaje del transcriptoma
#Local Blast- Usando la secuencia del gen de referencia de B. jararaca 
#Alineamiento múltiple


#REPOSITORIOS A CLONAR


##SRA Toolkit: (Ya instalado) Para descarga de datos.

##FastQC: Diagnóstico de calidad.

#Source: apt-get install fastqc

##Trimmomatic: Recorte de secuencias.

#Source: usadellab/Trimmomatic (GitHub) o vía apt-get.

##SPAdes: Ensamblador.

#Source: ablab/spades (GitHub) o binarios precompilados.

##NCBI-BLAST+: Motor de búsqueda local.

#Source: ncbi/blast_plus_docs (GitHub) o vía apt-get.
