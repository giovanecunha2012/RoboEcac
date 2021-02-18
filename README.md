## RoboEcac
Estou tentando criar uma ferramenta que faça Web Scrapping no Porta da RFB, o E-CAC. Acessando-o e fazendo o download do Relatório de Pendências Fiscais automaticamente de várias empresas vinculadas ao meu certificado por procuração. A Linguagem Utilizada é Python.

# Em que pé estamos agora?
  - Já consigo acessar o E-cac e fazer o download de relatorio de uma Empresa, porém preciso fazer a seleção do Certificado Digital manualmente, como uma vez acessado o E-cac eu posso mudar para outras empresas sem precisar selecionar o Certificado Digital novamente, não vou priorizar a automação disso agora, talvez nem no futuro por questões de segurança.
  - Preciso corrigir alguns pequenos bus desse codigo apesar de ele ser funcional, não está devidamente limpo nem organizado. Por que estou fazendo o curso de Pytnho enquanto crio o código o que ainda me impoe alguma barreira de conhecimento que preciso adiquir.
  - Os Próximos passos serão dividir o código em funções, importar planilhas com nome de empresa e cnpj, para poder usar um "for cnpj in planilha" para repetir o processo e emitir para cada cnpj um relatório.

# O que eu ainda não sei fazer?
  - Escolher o nome e local em que salvar o Relatório
  - Trocar o time.sleep() por algo que utilize uma condição da página para aguardar

# Futuramente Pretendo:
  - conseguir ler as pendências diretamente do banco de dados do site, para gerar análise posterior
  - gerar outros relatorio de dentro do e-cac como Parcelamentos, PGFN
  - gerar Darfs de Pagamentos de Pendências e Parcelamentos
  - analisar todos os dados do e-CAC Relativos a Pendencias/Parcelamentos e gerar relatorio para conciliação das contas da Contabilidade
  - em evolução ao item anterior, gerar planilha para lançamento automatico das contas na contablidade
