# Especificação Suplementar

## 1. Introdução
&emsp;&emsp; A especificação suplementar é responsável por capturar os requisitos não funcionais do sistema os quais não são prontamente capturados nos artefatos de requisitos comportamentais, como por exemplo os casos de uso, servindo de complemento e melhor especificação dos requisitos, incluindo:

-  Requisitos legais e de regulamentação, incluindo padrões de aplicativos.

-  Atributos de qualidade do sistema a ser criado, incluindo requisitos de utilidade, confiabilidade, desempenho e suportabilidade.

-  Outros requisitos como sistemas e ambientes operacionais, requisitos de compatibilidade e restrições de design.
## 1.1 Objetivo
&emsp;&emsp; O objetivo deste documento é definir os requisitos do aplicativo mobile do Google Maps. "Trata-se de um documento em linguagem natural, no qual são descritos os requisitos não funcionais" de acordo com Maurício e Milene Serrano.

## 1.2 Escopo

Uma breve descrição do escopo desta Especificação Suplementar: a qual(is) Projeto(s) ele está associado e tudo mais que seja afetado ou influenciado por este documento.

## 1.3 Definições, Acrônimos e Abreviações

- Giroscópio: é um sensor que mede a velocidade angular de um objeto em torno de um eixo.
- Acelerômetro: é um sensor que mede a aceleração de um objeto em relação a um referencial.
- GPS: "Global Positioning System". É um sistema de navegação por satélite que permite determinar a posição de um objeto em qualquer lugar da Terra.
- Android: é um sistema operacional móvel baseado em Linux, desenvolvido pela Google.
- iOS: é um sistema operacional móvel desenvolvido pela Apple.
- Chrome: é um navegador da web desenvolvido pela Google.
- Firefox: é um navegador da web desenvolvido pela Mozilla.
- Safari: é um navegador da web desenvolvido pela Apple.
- Microsoft Edge: é um navegador da web desenvolvido pela Microsoft.
- Windows Phone: é um sistema operacional móvel desenvolvido pela Microsoft.
- 3D: é uma representação tridimensional de um objeto.
- Earth View: é uma funcionalidade do Google Maps que permite visualizar a Terra em 3D.
- Tecnófobo: é uma pessoa que não tem facilidade para usufruir de tecnologia.
- Tecnófilo: é uma pessoa que gosta de tecnologia.
- On-line: De modo a estar em uma conexão ou na internet no exato momento em que acessa.
- Javascript: Linguagem de programação que permite a você implementar itens complexos em páginas web.
- React Native: React Native é uma biblioteca Javascript criada pelo Facebook. É usada para desenvolver aplicativos para os sistemas Android e iOS.

## 1.4 Visão Geral

&emsp;&emsp; Este documento apresenta inicialmente uma introdução ao projeto para ambientação com o aplicativo. A seguir estão expostos os requisitos suplementares distribuídos em tabelas, utilizando o FURPS+ para montar as mesmas. Dessa forma, construímos as especificações suplementares divididas em requisitos de sistema, usabilidade, confiabilidade, desempenho, suportabilidade, restrições de design, sistema de ajuda e documentação, interface e licenciamento.

## 2. Funcionalidade

&emsp;&emsp; Os requisitos foram captados através das técnicas de observação, entrevista e questionário. A observação foi realizada através da análise do aplicativo mobile do Google Maps, enquanto as entrevistas e questionários foram realizados com usuários do aplicativo.
## 2.1 Requisitos de Sistema

&emsp;&emsp; O aplicativo móvel do Google Maps é compatível com os seguintes sistemas operacionais: Android 6.0 ou superior e iOS 13.4 ou superior. O dispositivo deve possuir giroscópio, acelerômetro, GPS, +128MB de memória RAM e sinal de internet ou dados para que seja possível visualizar o mapa em 3D e usufruir de todas as funcionalidades do aplicativo.

## 3. Usabilidade

&emsp;&emsp; A usabilidade é um dos atributos de qualidade mais importantes de um sistema. Ela é definida como a facilidade com que um usuário pode aprender a usar um sistema, bem como a facilidade com que ele pode realizar tarefas específicas. As especificações suplementares de usabilidade são apresentadas na tabela 1.

<figcaption align="center">Tabela 1: Especificação suplementar de usabilidade</figcaption>

| Descrição                                                                                                                             | Tipo |
| :------------------------------------------------------------------------------------------------------------------------------------ | :--: |
| O usuário é capaz de realizar ações críticas em no máximo 5 clicks                                                                    | ES01 |
| Um usuário tecnófobo deve conseguir facilmente traçar rotas no aplicativo em uma semana de uso                                        | ES02 |
| Um usuário tecnófilo deve conseguir facilmente realizar todas as ações principais do aplicativo em uma semana de uso                  | ES03 |
| O sistema deve possuir ícones e descrições intuitivas o suficiente para que direcionem o uso do aplicativo pelo usuário               | ES04 |
| O sistema deve possuir cores intuitivas o suficiente para que ajudem o usuário na identificação de ações desejadas                    | ES05 |
| O sistema deve possuir uma interface intuitivo o suficiente para que o usuário consiga navegar facilmente pelo aplicativo             | ES06 |

<figcaption align="center">Fonte: Elaboração própia</figcaption>

## 4. Confiabilidade

&emsp;&emsp; A confiabilidade é definida como a capacidade de um sistema de funcionar corretamente, mesmo em condições adversas. As especificações suplementares de confiabilidade são apresentadas na tabela 2.

<figcaption align="center">Tabela 2 Especificação suplementar de confiabilidade</figcaption>

|   Descrição                                                                               | Tipo |
| :---------------------------------------------------------------------------------------- | :--: |
| As localizações registradas devem ter uma margem de erro de 5 metros com a localização real     | ES01 |
| O sistema deve estar disponível 24 horas por dia, 7 dias por semana                       | ES02 |
| O aplicativo deve disponibilizar o histórico de pesquisa do usuário apenas para o usuário | ES03 |
| As rotas devem ser traçadas de acordo com as políticas de trânsito de cada cidade         | ES04 |
| Devem ser traçadas áreas de alerta de acordo com o perigo de cada região                  | ES05 |

<figcaption align="center">Fonte: Elaboração própia</figcaption>

## 5. Desempenho

&emsp;&emsp; O desempenho é definido como a capacidade de um sistema de responder a uma solicitação em um tempo aceitável. As especificações suplementares de desempenho são apresentadas na tabela 3.

<figcaption align="center">Tabela 3: Especificação suplementar de desempenho</figcaption>

| Descrição                                                                                            | Tipo |
| :--------------------------------------------------------------------------------------------------- | :--: |
| A rota requisitada pelo usuário deve ser disponibilizada pelo sistema em menos de 5 segundos         | ES01 |
| Deve ser possível usar o sistema pelo navegador caso ocorra algum erro com o aplicativo (degradação) | ES02 |
| O software deve ser capaz de suportar milhões de usuários simultâneos                                | ES03 |

<figcaption align="center">Fonte: Elaboração própia</figcaption>

## 6. Suportabilidade

&emsp;&emsp; A suportabilidade é definida como a capacidade de um sistema de ser executado em diferentes ambientes. As especificações suplementares de suportabilidade são apresentadas na tabela 4.

<figcaption align="center">Tabela 4: Especificação suplementar de suportabilidade</figcaption>

| Descrição                                                                                                 | Tipo |
| :-------------------------------------------------------------------------------------------------------- | :--: |
| O aplicativo deve ter visualização para tela horizontal e tela vertical                                   | ES01 |
| Todo os elementos do aplicativo devem estar visualmente disponíveis para as telas dos sistemas suportados | ES02 |
| A linguagem de programação utilizada deve ser compatível com todos os sistemas operacionais suportados    | ES03 |

<figcaption align="center">Fonte: Elaboração própia</figcaption>

## 7. Restrições de Design

&emsp;&emsp; As restrições de design são definidas como as restrições que devem ser seguidas para que o sistema seja desenvolvido. As especificações suplementares de design são apresentadas na tabela 5.

<figcaption align="center">Tabela 5: Especificação suplementar de design</figcaption>

| Descrição                                                                                 | Tipo |
| :---------------------------------------------------------------------------------------- | :--: |
| O design do sistema deve estar no padrão de tecnologia do Google                          | ES01 |
| A linguagem de programação usada deve ser o JavaScript                                    | ES02 |
| O sistema deve ser desenvolvido em React Native                                           | ES03 |

<figcaption align="center">Fonte: Elaboração própia</figcaption>

## 8. Documentação do Usuário On-line e Requisitos do Sistema de Ajuda

&emsp;&emsp; A documentação do usuário on-line e os requisitos do sistema de ajuda são definidos como a capacidade de um sistema de fornecer ajuda ao usuário. As especificações suplementares de documentação e ajuda são apresentadas na tabela 6.

<figcaption align="center">Tabela 6: Especificação suplementar de documentação e ajuda</figcaption>

| Descrição                                                                                 | Tipo |
| :---------------------------------------------------------------------------------------- | :--: |
| O sistema deve possuir uma documentação on-line de como utilizar o aplicativo             | ES01 |
| Deve haver um ícone de ajuda ao usuário na página inicial com cores destacadas            | ES02 |

<figcaption align="center">Fonte: Elaboração própia</figcaption>

## 9. Requisitos de Interface

&emsp;&emsp; Esta seção define as interfaces que devem ser suportadas pelo aplicativo. As especificações suplementares de interface são apresentadas na tabela 7.

<figcaption align="center">Tabela 7: Especificação suplementar de requisitos de interface</figcaption>

| Descrição                                                                                 | Tipo |
| :---------------------------------------------------------------------------------------- | :--: |
| O sistema deve possuir uma interface gráfica utilizada para a interação com o usuário     | ES01 |
| A comunicação entre as estações será feita através de uma rede global de satélites        | ES02 |

<figcaption align="center">Fonte: Elaboração própia</figcaption>

## 10. Requisitos de Licenciamento

&emsp;&emsp; Esta seção define os requisitos de licença do usuário do aplicativo. As especificações suplementares de licenciamento são apresentadas na tabela 8.

<figcaption align="center">Tabela 8: Especificação suplementar de requisitos de licenciamento</figcaption>

| Descrição                                                                                 | Tipo |
| :---------------------------------------------------------------------------------------- | :--: |
| A utilização do software está sujeita a aceitação de uma licença de uso do Google Maps    | ES01 |

<figcaption align="center">Fonte: Elaboração própia</figcaption>

## 11. Histórico de Versão

|    Data    | Versão |                          Modificações                           |    Autor(es)     |  Revisor(es)  |
| :--------: | :----: | :-------------------------------------------------------------: | :--------------: | :-----------: |
| 08/12/2022 |  1.0   |  Criação da página de Especificação suplementar                 | Lucas            | Alexia e Iago |
| 08/12/2022 |  1.1   |  Adição de requisitos de sistema e restrições de design         | Alexia e Iago    |     Marcus    |
| 09/12/2022 |  1.2   |  Correções de ortografia e padronizações         | Lucas    |     Marcus    |

## 5. Bibliografia

> Artefato: Especificações Suplementares. Disponível em: [link](https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html#:~:text=Artefato%3A%20Especifica%C3%A7%C3%B5es%20Suplementares&text=Esse%20artefato%20captura%20os%20requisitos,especifica%C3%A7%C3%B5es%20de%20casos%20de%20uso.). Acesso em dez. de 2022.

> Samily Rocha Gois: Especificação Suplementar, 27 out. 2012. Disponível em: [link](https://silo.tips/download/php-software-company-samily-rocha-gois-francisco-luiz-sobrinho-projeto-de-softwa). Acesso em dez. de 2022.

> SERRANO, Milene e SERRANO, Maurício. Requisitos – Aula 13. 11 jan. 2019. Apresentação em pdf. Disponível em: [link](https://aprender3.unb.br/pluginfile.php/2307510/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em 08 dez. 2022.

> Software Requirements. Disponível em: [link](https://sites.google.com/site/projectucfcampusmap/home/software-requirements). Acesso em dez. de 2022.

> API Google Maps. Disponível em: [link](https://developers.google.com/maps/). Acesso em dez. de 2022.

> FURPS+. Disponível em: [link](https://qualidadebr.wordpress.com/2008/07/10/furps/). Acesso em dez. de 2022.
