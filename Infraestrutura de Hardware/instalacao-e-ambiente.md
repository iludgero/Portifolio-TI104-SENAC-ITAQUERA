#  UC1 Infraestrutura, Equipamentos e Documentação de Instalação

Conteúdos da Aula 2 com o professor Urquiza, focados no mercado de trabalho, ferramentas de teste, riscos elétricos, preparação do ambiente físico e interpretação de documentos técnicos.

---

##  1. O Técnico em Informática: Atribuições e Mercado

O profissional atua na instalação, configuração, manutenção e suporte de sistemas computacionais em diversos ambientes (empresas, hospitais, escolas, órgãos públicos), exigindo conhecimento técnico e postura profissional.

###  Principais Áreas de Atuação:
* **Manutenção e Suporte:** Diagnóstico de falhas, substituição de componentes, atualização de hardware e suporte técnico presencial ou remoto.
* **Redes e Infraestrutura:** Instalação de redes cabeadas e wireless, configuração de roteadores, switches e pontos de acesso.
* **Segurança da Informação:** Implementação de políticas de acesso, backups, antivírus e proteção de dados em conformidade com a LGPD.
* **Documentação Técnica:** Elaboração de relatórios, inventário de equipamentos, leitura de manuais e esquemas elétricos.

---

##  2. Equipamentos e Tipos de Testes Aplicáveis

Instrumentos específicos utilizados para diagnosticar falhas elétricas e eletrônicas com precisão e segurança na bancada:

* **Multímetro Digital:** Instrumento essencial para medir tensão, corrente e resistência. Usado para verificar tomadas, fontes e cabos.
* **Tester de Fonte ATX:** Verifica rapidamente as tensões de saída da fonte de alimentação (3,3V, 5V, 12V) sem a necessidade de um multímetro.
* **Cartão POST:** Placa de diagnóstico que exibe códigos de erro da BIOS durante o boot, auxiliando na identificação rápida de falhas de hardware que impedem o vídeo.
* **Tester de Cabos:** Verifica a continuidade e a pinagem de cabos de rede (RJ-45) e telefônicos (RJ-11), detectando fios rompidos ou invertidos.

---

##  3. Riscos na Instalação: Ausência de Aterramento e Sobretensão

Instalar equipamentos sem os devidos cuidados elétricos pode resultar em danos irreversíveis, incêndios e acidentes pessoais graves.

* **Ausência de Aterramento:** Sem ele, a carcaça do equipamento pode ficar energizada, causando choques elétricos ao usuário. Componentes internos ficam vulneráveis a descargas eletrostáticas (ESD) e ruídos elétricos, reduzindo sua vida útil e causando mau funcionamento intermitente.
* **Sobretensão (Surto Elétrico):** Picos de tensão causados por raios, manobras na rede ou falhas na concessionária que podem ultrapassar 1.000V em milissegundos. Sem proteção, queimam a fonte, a placa-mãe e periféricos. O uso de filtros de linha com varistor e nobreaks é altamente recomendado.
* **Tomadas e Conexões Inadequadas:** Tomadas com polaridade invertida, neutro e terra trocados ou com mau contato geram aquecimento, faíscas e risco de incêndio. Sempre verifique a pinagem com multímetro antes de conectar os equipamentos.

###  Como Medir a Tensão da Tomada Elétrica:
1. Configurar o multímetro em ACV 750V (Corrente Alternada).
2. Conectar as pontas de prova em fase e neutro.
3. Ler o valor no display (Valores esperados em instalações brasileiras: **127V ±10%** ou **220V ±10%**).
4. Verificar a relação fase-terra (deve ser igual a fase-neutro) e neutro-terra (deve ser próximo de 0V).
* **Aviso de Segurança:** Nunca toque nas pontas de prova com os dedos durante a medição. Use luvas isolantes se necessário.*

---

##  4. Condições Físicas do Ambiente de Instalação

O ambiente onde os computadores serão instalados impacta diretamente no desempenho, na vida útil dos equipamentos e na segurança dos usuários.

* **Temperatura:** Manter entre **18°C e 24°C** para operação ideal. Acima de 30°C, os componentes superaquecem e a vida útil cai drasticamente. É recomendado o uso de ar-condicionado em salas com muitas máquinas.
* **Consumo de Energia:** Calcular a potência total dos equipamentos para dimensionar corretamente circuitos, disjuntores e nobreaks, evitando sobrecarga em um único circuito (distribuir a carga entre fases).
* **Disposição das Máquinas:** Respeitar distâncias mínimas de ventilação (**10 cm das paredes**), organizar cabos com canaletas, posicionar monitores na altura dos olhos e garantir ergonomia para os usuários.
* **Umidade e Poeira:** Manter a umidade relativa entre **40% e 60%**. Umidade excessiva causa corrosão; baixa umidade favorece a ocorrência de descargas eletrostáticas (ESD). Ambientes empoeirados exigem limpeza periódica e filtros de ar para não obstruir os coolers.

---

##  5. Interpretação de Manuais, Esquemas Elétricos e Documentos Técnicos

A compreensão de documentos e normas técnicas é o pilar para uma atuação profissional segura e dentro dos padrões. No Brasil, a **NBR 5410** regula todas as instalações elétricas de baixa tensão.

###  Tipos de Documentação:
* **Manuais dos Fabricantes:** Contêm especificações técnicas essenciais, como pinagem de conectores, tensões suportadas, procedimentos de instalação e tabelas de códigos de erro. Devem ser sempre consultados antes de manusear qualquer componente.
* **Esquemas Elétricos:** Representam graficamente os circuitos usando símbolos padronizados (IEC/ABNT). O técnico deve ser capaz de identificar as linhas de fase, neutro, terra, disjuntores, tomadas e as cargas conectadas.
* **Ficha Técnica (Datasheet):** Documento detalhado contendo todas as especificações e limites elétricos/técnicos de um componente.
* **Diagrama de Blocos:** Visão geral e simplificada da estrutura do sistema.
* **Planta Baixa Elétrica:** O desenho e layout de onde a instalação física e as tomadas estão posicionadas no ambiente.
* **Ordem de Serviço (OS):** Registro formal de toda a intervenção realizada no equipamento do cliente.
* **Laudo Técnico:** Documento oficial que formaliza o diagnóstico encontrado e a solução aplicada pelo técnico.

---

##  Resumo Prático para o Dia a Dia do Técnico
1. **Domine os Conceitos Elétricos:** Revise constantemente tensão, corrente, resistência e potência. Pratique medições seguras com o multímetro.
2. **Adote Sempre a Proteção ESD:** Pulseira antiestática e embalagens adequadas não são opcionais ao manipular hardware.
3. **Verifique o Aterramento Antes de Instalar:** Avalie a tomada e confirme a presença do fio terra de proteção.
4. **Consulte a Documentação:** Nunca monte peças no "achômetro". Leia os manuais e registre seus serviços em OSs.
5. 
