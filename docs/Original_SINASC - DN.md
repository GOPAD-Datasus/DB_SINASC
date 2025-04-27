> Initial version of the dictionary, do not use yet. A lot of info is yet to be fact-checked

> This dictionary is meant for easy access of all columns present in SINASC DN
> For more details on each variable, visit [[In Depth - SINASC Docs|In Depth]]
# **Mother**
``CODOCUPMAE`` : Código CBO 2002 de ocupação da mãe
``DTULTMENST`` : Data da última menstruação, no formato ``ddmmaaaa``
``DTNASCMAE`` : Data de nascimento da mãe, no formato ``ddmmaaaa``
``IDADEMAE`` : Idade da mãe (em anos)
``RACACORMAE`` : Tipo de raça e cor da mãe
- 1. Branca
- 2. Preta
- 3. Amarela
- 4. Parda
- 5. Indígena
``ESTCIVMAE`` : Situação conjugal da mãe
- 1. Solteira
- 2. Casada
- 3. Viúva
- 4. Separada judicialmente/divorciada
- 5. União estável
- 9. Ignorada
### **Past Child Births**
``QTDFILVIVO`` : Número de filhos vivos
``QTDFILMORT`` : Número de perdas fetais e abortos / Número de filhos mortos (?)
``QTDGESTANT`` : Número de gestações anteriores
``QTDPARTNOR`` : Número de partos vaginais anteriores
``QTDPARTCES`` : Número de partos cesáreos anteriores
### **Education related**
``ESCMAE`` : Escolaridade, em anos de estudo concluídos
- 1. Nenhuma
- 2. 1 a 3 anos
- 3. 4 a 7 anos
- 4. 8 a 11 anos
- 5. 12 e mais
- 9. Ignorado
``ESCMAE2010`` : Escolaridade 2010
- 0. Sem escolaridade
- 1. Fundamental I (1a a 4a série)
- 2. Fundamental II (5a a 8a série)
- 3. Médio (antigo 2o Grau)
- 4. Superior incompleto
- 5. Superior completo
- 9. Ignorado
``SERIESCMAE`` : Série escolar da mãe. Valores de 1 a 8.
### **Residence**
``CODMUNRES`` : Código IBGE do município de residência
``NATURALMAE`` : Se a mãe for estrangeira, constará o código do país de nascimento
``CODMUNNATU`` : Código do município de naturalidade da mãe
``CODPAISRES`` : Código do país de residência
# **Pre Natal**
``SEMAGESTAC`` : Número de semanas de gestação.
``GESTACAO`` : Classificação de semanas de gestação
- 1. Menos de 22 semanas
- 2. 22 a 27 semanas
- 3. 28 a 31 semanas
- 4. 32 a 36 semanas
- 5. 37 a 41 semanas
- 6. 42 semanas e mais
- 9. Ignorado
``GRAVIDEZ`` : Tipo de gravidez
- 1. Única
- 2. Dupla
- 3. Tripla ou mais
- 9. Ignorado 
``PARTO`` : Tipo de parto
- 1. Vaginal
- 2. Cesário
- 9. Ignorado 
``CONSPRENAT`` : Número de consultas pré‐natal
``CONSULTAS`` : Número de consultas de pré‐natal
- 1. Nenhuma
- 2. de 1 a 3
- 3. de 4 a 6
- 4. 7 e mais
- 9. Ignorado
``MESPRENAT`` : Mês de gestação de inicio do pré‐natal
# **New Born**
``SEXO`` : Sexo do recém nascido
- 1. Masculino
- 2. Feminino
- 0. Ignorado
``RACACOR`` : Tipo de raça e cor do nascido
- 1. Branca
- 2. Preta
- 3. Amarela
- 4. Parda
- 5. Indígena
``RACACORN`` : Tipo de raça e cor do nascido
- 1. Branca
- 2. Preta
- 3. Amarela
- 4. Parda
- 5. Indígena
``IDANOMAL`` : Anomalia identificada
- 1. Sim
- 2. Não
- 9. Ignorado
``CODANOMAL`` : Código da anomalia (CID-10)
### **Birth**
``DTNASC`` : Data de nascimento, formato ``ddmmaaaa``
``HORANASC`` : Horário de nascimento
``APGAR1`` : Apgar no 1° minuto 00 a 10
``APGAR5`` : Apgar no 5° minuto 00 a 10
``TPAPRESENT`` : Tipo de apresentação
- 1. Cefálico
- 2. Pélvica ou podálica
- 3. Transversa
- 9. Ignorado
``STTRABPART`` : Trabalho de parto induzido
- 1. Sim
- 2. Não
- 3. Não se aplica
- 9. Ignorado
``STCESPARTO`` : Cesárea ocorreu antes do trabalho de parto iniciar?
- 1. Sim
- 2. Não
- 3. Não se aplica
- 9. Ignorado
``TPROBSON`` : Código do Grupo de Robson, gerado pelo sistema
# **Hospital**
``CODESTAB`` : Código onde ocorreu o nascimento
``CODMUNNASC``  : Código IBGE onde ocorreu o nascimento
``LOCNASC`` : Local de nascimento
- 1. Hospital
- 2. Outros estabelecimentos de saúde
- 3. Domicílio
- 4. Outros
- 5. Aldeia Indígena
# **System**
``CONTADOR`` : Identificador de registros a nível estadual
``ORIGEM`` : Banco de dados de origem
- 1. Oracle
- 2. FTP
- 3. SEAD
``NUMEROLOTE`` : Número do lote
``VERSAOSIST`` : Versão do sistema
``DTRECEBIM`` : Data do último recebimento do lote, dada pelo Sisnet
``DIFDATA`` : Diferença entre a data de nascimento e data do recebimento original da DN
$$DIFDATA = DTNASC - DTRECORIGA$$
``DTCADASTRO`` : Data do cadastro da DN no sistema
# **Registry Office**
``CODCART`` : Código do Cartório
``NUMREGCART``: Número do Registro do Cartório
``DTREGCART`` : Data do registro no Cartório
# **Others**
``IDADEPAI`` : Idade do pai
``TPMETESTIM`` : Método utilizado
- 1. Exame físico
- 2. Outro método
- 9. Ignorado
``STDNEPIDEM`` : Status de DO Epidemiológica
- 1. SIM
- 0. NÃO
``STDNNOVA`` : Status de DO Nova
- 1. SIM
- 0. NÃO

