* Tablespace é: ÁREA/ESTRUTURA LÓGICA. PARA CLASSIFICAR E ORGANIZAR O BANCO DE DADOS. GAVETA.

* Alterar tablespace para read only: ALTER TABLESPACE NOME_DA_TABLESPACE READ ONLY;

* Criar uma tablespace: CREATE TABLESPACE NOME_DA_TABLESPACE DATA01 DATAFILE '$ORACLE_DATA/DATA01.DBF' SIZE 100M;

* Informações sobre o banco de dados: SHOW SGA;

* Usuário e senha: SYSTEM/MANAGER;

* Arquivo físico em disco: DATA FILE -> DATA01.DBF;

* Visualizar estrutura física: CD $ORACLE_HOME;

* Grava informações das tablespace: DBA_DATA_FILES;

* Tablespace vão se adequar aos databases;

* Segmento: ESTRUTURA LÓGICA DO BANCO DE DADOS;

* Uma tablespace pode conter uma ou mais data files;

* Estrutura física: DATA FILE.

* Estrutura lógica: SEGMENTS, TABLESPACE...;
 
* Verificar os arquivos físicos das tablespaces: SELECT * FROM DBA_DATA_FILES;

* Adicionar novo data file em uma tablespace: ALTER TABLESPACE DATA01 ADD DATAFILE "$ORACLE_DATA/data01_01.dbf" SIZE 5M;


