# ☁️ DOMINANDO O ARMAZENAMENTO NO AZURE  
 
<p align="center">
  <img src="https://i.postimg.cc/Gmxtwttm/azure-fundamentals.png" width="256">
</p>

---  
## ⏯️ INTRODUÇÃO  

<p align='justify'>Neste laboratório do bootcamp <i>Azure Essencials</i>, foram abordadas questões referentes ao armazenamento no portal <a href='https://portal.azure.com/'><i>Microsoft Azure</i></a>. Através do projeto, foram exploradas as funcionalidades para criar blobs, filas, tabelas. </p>     

<p align="center">
  <img src='images/armazenamento-conta.png' width=450> 
</p>

--- 
## 🗒️RESUMO DOS TÓPICOS:  

<p align='justify'>- Uma conta de armazenamento pode receber dados de vários tipos: blobs, pastas de arquivos, filas e tabelas; deve ter um nome único.</p>     

<p align="center">
  <img src='images/armazenamento-conta-criada.png' width=550> 
</p>

<p align='justify'>- O desempenho Standard tem a cobrança somente pelo uso e o Premium cobra a alocação total, mesmo sem utilização, e utiliza discos mais performáticos, tem velocidade mais rápida.</p> 

<p align="center">
   <img src='images/armazenamento-compartilhamento-arq.png' width=550>

<p align='justify'>- Para conectar o recurso de Compartilhamento de Arquivos, é mais recomendado criar uma VM no Azure e executar o script fornecido pelo Azure no Power Shell, utilizando o protocolo SMB e a porta TCP 445.</p>      

<p align="center">  
  <img src='images/armazenamento-compart-arq-script.png' width=550>
</p>

<p align='justify'>- As filas podem ser criadas para usar com aplicações, como fila de mensagens, tem o termo 'queue' na sua URL.</p>    

<p align="center">
  <img src='images/armazenamento-fila.png' style="display: inline-block; width: 45%;">
  <img src='images/armazenamento-fila-mensagem.png' style="display: inline-block; width: 45%;">
</p>

<p align='justify'>- Ao criar tabelas, estas terão o termo 'table' na sua URL; é possível configurar políticas de acesso para usuários.</p>     

<p align="center">
  <img src='images/armazenamento-tabela.png' width=550>
  <img src='images/armazenamento-table-criada.png' width=550>
</p>

<p align='justify'>- Em Migrações para Azure, akguns recursos podem ser disponibilizados como VERSÃO PRÉVIA e, por estar ainda em desenvolvimento, não é indicado o uso por não ter SLA garantido, não é ressarcido o prejuízo do cliente caso o serviço caia.</p>    

<p align="center">
  <img src='images/armazenamento-migracoes.png' width=550> 
</p>

<p align='justify'>- Na contratação do serviço Data Box, é importante ter noção da quantidade de dados que é atribuído a cada modelo de solução (Disk, Box, Heavy, Import/Export Job).</p>    

<p align="center">
  <img src='images/armazenamento-databox.png' style="display: inline-block; width: 45%;">
  <img src='images/armazenamento-databox-capcidades.png' style="display: inline-block; width: 45%;">
</p>

<p align='justify'>- O uso do recurso AzCopy requer uma conta de armazenamento e a criação de um Token de Acesso Compartilhado (token SAS) para fazer a transferência de dados via CMD (linha de comando). O AzCopy é mais prático, embora não seja agradável visualmente. Pode ser usado também o <i>Storage Microsoft Explorer</i>. Se o volume de dados for muito grande, cabe usar os produtos da família Data Box. </p>    

<p align="center">
 <img src='images/armazenamento-azcopy-token.png' width=550>  
</p>

---    
## ✍️ AUTORA    

Carla Edila Silveira  
Contato: rosa.carla@pucpr.edu.br  

---  
## ©️ LICENÇA

[MIT](https://choosealicense.com/licenses/mit/)  

---  
## 🔗 LINKS ÚTEIS  

- [Introdução ao AzCopy](https://learn.microsoft.com/pt-br/azure/storage/common/storage-use-azcopy-v10?tabs=dnf)
- [Gerenciador de Armazenamento do Microsoft Azure](https://azure.microsoft.com/pt-br/products/storage/storage-explorer/#:~:text=Fa%C3%A7a%20upload,%20baixe%20e%20gerencie%20blobs,?msockid=0918e6742c7f677b085cf2a02d0666cb)
- [Preços do Azure Data Box](https://azure.microsoft.com/pt-br/pricing/details/databox/)
  
---
