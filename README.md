# tableau
This is a repository where I publish my studies with Tableau.

This link is for the [Dashboard number 1](https://public.tableau.com/app/profile/lucas.quemelli/viz/Livro07_16707905911710/DashboardMedalhas?publish=yes).

# Exploração

<img width="1574" alt="image" src="https://user-images.githubusercontent.com/81119854/206906916-b1cf3490-8e81-4715-a766-c2891c3302c3.png">

<img width="1557" alt="image" src="https://user-images.githubusercontent.com/81119854/206907135-10f4a633-31a8-4e82-9c76-951dc19dee6f.png">

<img width="1578" alt="image" src="https://user-images.githubusercontent.com/81119854/206907618-18163bf7-51bf-461d-b678-feca116b2152.png">

<img width="1575" alt="image" src="https://user-images.githubusercontent.com/81119854/206908241-f88041a3-ae00-4f26-9339-b7fa074fd33c.png">

<img width="1576" alt="image" src="https://user-images.githubusercontent.com/81119854/206908402-c855aba5-ec8e-4f5c-9907-dad88b4a7f56.png">

# Classificar/Ordenar no Tableau

<img width="1579" alt="image" src="https://user-images.githubusercontent.com/81119854/206908568-7ce17415-9a58-4838-8bdd-b54927146311.png">

# Filtrar os 05 países com o maior número de medalhas

<img width="1580" alt="image" src="https://user-images.githubusercontent.com/81119854/206908729-c1561ed0-a155-4610-b654-820dffd981ef.png">

<img width="1556" alt="image" src="https://user-images.githubusercontent.com/81119854/206909716-aa0daa63-38d7-4cfd-bc4a-8e8d66e7610c.png">

# Escolhendo tipo DISCRETO para os valores do ano

<img width="850" alt="image" src="https://user-images.githubusercontent.com/81119854/206924715-9b4cc9ed-0109-4e4d-aaa8-1109f049ce51.png">

<img width="1573" alt="image" src="https://user-images.githubusercontent.com/81119854/206924927-6e0216b3-bb8b-4d82-a1a4-e0074bdcf090.png">

# Criando campo calculado 

<img width="915" alt="image" src="https://user-images.githubusercontent.com/81119854/207054623-27de8a73-c338-45a8-a13f-8f169196d94d.png">

<img width="797" alt="image" src="https://user-images.githubusercontent.com/81119854/207055921-ee03fdd4-5da3-426e-9e56-308c65f0d788.png">

# Criando parâmetro

<img width="1266" alt="image" src="https://user-images.githubusercontent.com/81119854/207419854-6b21ba17-0b68-446e-8763-1c6ec122a853.png">

# Mostrando parâmetro

<img width="1767" alt="image" src="https://user-images.githubusercontent.com/81119854/207420182-f3b0e332-834e-4f7d-957e-c47e4e849555.png">

# Identificando valores nulos

<img width="1421" alt="image" src="https://user-images.githubusercontent.com/81119854/207618164-43789a01-a750-4362-a3f5-3fd847a11718.png">

# Identificando o percentual de nulos

<img width="979" alt="image" src="https://user-images.githubusercontent.com/81119854/207687767-c4f2f67e-9aa6-496a-badf-34cd3e3552de.png">

# Mudando dimensão do percentual para porcentagem

<img width="1580" alt="image" src="https://user-images.githubusercontent.com/81119854/207620282-071c904b-bfc1-4cad-9da7-9053bcc0dcf0.png">

<img width="1781" alt="image" src="https://user-images.githubusercontent.com/81119854/207620561-3c6bf3e4-fd18-412f-93c1-c64adfcc7713.png">

<img width="1583" alt="image" src="https://user-images.githubusercontent.com/81119854/207620688-825c0b50-271c-48f7-b3b1-67a8ca715fa3.png">

# Corrigindo valores nulos

#### Para corrigir o problema de valores nulos na coluna Region, nós criamos um novo campo chamado Region Resolvida, da seguinte forma:

- Adicionando um novo parâmetro de número 8:

<img width="595" alt="image" src="https://user-images.githubusercontent.com/81119854/207688352-1c248772-d372-4733-a3e7-77e577bf4c2e.png">

- Criando o campo Region Resolvida:

<img width="1420" alt="image" src="https://user-images.githubusercontent.com/81119854/207686121-1e12110a-5e15-4dd3-88d6-f902fda1f9b7.png">

- Caso queiramos contruir o Campo de Region Resolvida de forma simplificada, podemos usar o Excel da seguinte maneira para segurar e arrastar:

<img width="1661" alt="image" src="https://user-images.githubusercontent.com/81119854/207712568-9cbfacea-b3f1-41fe-ac7d-47afad3de227.png">

# Descobrindo o dado nulo

- Note que na imagem anterior ainda não temos 100% dos dados para Region Resolvida iguais a "linhas com valores". Ainda resta algum registro nulo. Para identificar, basta fazer uma visão que retorne os valores de Region Resolvida por país. Na sequência, podemos adicionar como Marcas o número de registros (Number of records). Assim, identificamos o país que Region Resolvida é nulo. 

<img width="1419" alt="image" src="https://user-images.githubusercontent.com/81119854/207709891-2320b957-7e70-4253-92d7-f6dca79374f8.png">

- Basta pesquisar onde se encontra a região e adicionar manualmente no campo Region Resolvida:

<img width="1049" alt="image" src="https://user-images.githubusercontent.com/81119854/207711115-2ee7f587-9e99-478f-8c87-79022a9b350b.png">

- Resultado:

<img width="1580" alt="image" src="https://user-images.githubusercontent.com/81119854/207711325-532116cc-1af6-43e3-b816-401ceceb58fa.png">

# Separação de texto

- Abaixo, na coluna "Diagnosis", queremos apenas o código e o diagnóstico do paciente. O restante é sujeira. 

<img width="465" alt="image" src="https://user-images.githubusercontent.com/81119854/207872936-27957ba1-eca2-4891-8949-692b2224a50d.png">

- Ao carregar a planilha .csv no Tableau, o Tableau pode interpretador o separador de texto como sendo o carcter espaço, daí ele separa as informações em mais de uma coluna. Contudo, queremos apenas a coluna Diagnosis.

<img width="1519" alt="image" src="https://user-images.githubusercontent.com/81119854/207873527-fd033710-39e8-4d52-8e2e-1cc543d6a615.png">

- Para corrigir, seguimos a sequência de passos:

1. Propriedades de arquivo de texto.

<img width="1003" alt="image" src="https://user-images.githubusercontent.com/81119854/207874624-4e7a5c29-3f3d-4cd4-b128-efdfdeeccf8f.png">

2. Selecionar separador igual a Tab ou Guia (mesma coisa).

<img width="771" alt="image" src="https://user-images.githubusercontent.com/81119854/207875426-7f445d96-bb74-410a-8185-e0ab34f213ca.png">

3. Resultado: dados em uma coluna.

<img width="1524" alt="image" src="https://user-images.githubusercontent.com/81119854/207875698-c8c563bc-596c-490e-83c7-c57721cd2bfe.png">

4. Agora vamos criar um campo chamado DX. Nele, capturamos apenas o primeiro elemento de cada linha:

<img width="883" alt="image" src="https://user-images.githubusercontent.com/81119854/207878590-98e3f1fc-d718-422f-80a6-29f692a621c0.png">

- Assim, conseguimos identificar se o SEGUNDO elemento de DX se trata de um número realmente (como esperado).

<img width="626" alt="image" src="https://user-images.githubusercontent.com/81119854/207879561-61fa8fd7-1de7-40e9-9fdc-0d0747cf916b.png">

<img width="684" alt="image" src="https://user-images.githubusercontent.com/81119854/207881788-a367d33b-0095-4a34-b66f-567f5eaa254a.png">

- Para tanto, criamos uma fórmula que busca o segundo elemento de uma cadeia de caracteres e exibe ele (comprimento 1). Depois, convertemos esse valor para inteiro. Se o resultado for de fato um inteiro, então a fórmula retorna um número. Se não for, então retorna NULO. 

<img width="876" alt="image" src="https://user-images.githubusercontent.com/81119854/207882092-a8a8777a-ccc7-459c-84e9-2e98e624b3c0.png">

<img width="697" alt="image" src="https://user-images.githubusercontent.com/81119854/207883537-787b14eb-4269-49c9-8609-6f43004adf9c.png">

<img width="690" alt="image" src="https://user-images.githubusercontent.com/81119854/207883661-e6860135-37db-4424-823a-0ad7bfd20bb5.png">

- LEMBRANDO QUE, para funcionar a exibição acima, devemos colocar o campo Null Hunting como discreto (cor AZUL). 
