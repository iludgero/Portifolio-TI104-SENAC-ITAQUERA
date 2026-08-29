#  UC1 - Fundamentos de Hardware, Elétrica e Montagem

Conteúdos desenvolvidos com o professor Urquiza sobre a infraestrutura física dos computadores, eletrônica e boas práticas de montagem.

---

##  1. Geração, Distribuição e Grandezas Elétricas

No Brasil, o padrão residencial de distribuição é de **60 Hz** com tensões de **127V e 220V**:
* **Monofásico:** 1 fase + neutro (Uso residencial comum).
* **Bifásico:** 2 fases (220V entre fases, usado em chuveiros e equipamentos de maior potência).
* **Trifásico:** 3 fases defasadas em 120° (Alta eficiência para indústrias e Data Centers).

###  Grandezas Fundamentais:
* **Tensão (V):** Diferença de potencial elétrico (Volt - V).
* **Corrente (I):** Fluxo de cargas elétricas por unidade de tempo (Ampère - A).
* **Resistência (R):** Oposição à passagem da corrente (Ohm - Ω).
* **Potência (P):** Taxa de consumo ou fornecimento de energia (Watt - W). *Fórmula: P = V × I*
* **Frequência (f):** Número de ciclos por segundo (Hertz - Hz).

---

##  2. Leis Fundamentais e Tipos de Corrente

* **Lei de Ohm:** Relaciona as três grandezas principais em um circuito: V = R × I.
* **Leis de Kirchhoff:**
  * **LCK:** A soma das correntes em um nó é igual a zero.
  * **LVK:** A soma das tensões em uma malha é igual a zero.

###  Tipos de Corrente:
* **Corrente Contínua (CC / DC):** Flui em um único sentido. Presente em pilhas, baterias e nas saídas da fonte do PC (+12V, +5V, +3,3V).
* **Corrente Alternada (CA / AC):** Inverte o sentido periodicamente em forma de onda senoidal (Rede elétrica residencial).

---

##  3. Componentes Eletroeletrônicos
Compreensão de componentes **discretos** (com terminais visíveis) e **SMD** (soldados diretamente na placa):

* **Capacitor:** Armazena energia no campo elétrico, filtra ruídos e estabiliza tensão em fontes.
* **Resistor:** Limita a corrente elétrica, identificado por código de cores.
* **Diodo e Transistor:** O diodo conduz corrente em apenas um sentido; o transistor amplifica sinais ou atua como chave eletrônica.
* **Transformador e Indutor:** O transformador altera a tensão CA; o indutor armazena energia no campo magnético (fontes chaveadas).
* **Fotoacoplador e Termistor:** O fotoacoplador isola circuitos usando luz; o termistor varia a resistência com a temperatura (proteção térmica).

###  Circuitos Retificadores (CA → CC):
Etapa fundamental das fontes de alimentação de PCs para converter a corrente da tomada em corrente contínua:
* **Meia Onda:** Usa 1 diodo, conduz apenas 1 semiciclo (baixa eficiência).
* **Onda Completa:** Usa 4 diodos (ponte retificadora), mais eficiente e padrão em fontes ATX.

---

##  4. Multímetros: Procedimento de Medição

O multímetro digital é o principal instrumento de diagnóstico do técnico. Passos para utilização segura:
1. **Selecionar Função:** Escolher entre Tensão (V), Corrente (A), Resistência (Ω), continuidade ou capacitância.
2. **Escolher Escala:** Iniciar pela escala mais alta para evitar danos ao aparelho.
3. **Conectar Pontas:** Vermelha no terminal positivo e preta no COM.
4. **Interpretar Leitura:** Identificar unidade, sinal e mensagens de sobrecarga ("OL").

---

##  5. Riscos Elétricos, Aterramento e ESD

###  Efeitos da Corrente no Corpo Humano:
* **1 mA:** Formigamento leve.
* **10 mA:** Contração muscular (perda do controle motor).
* **30 mA:** Risco de fibrilação ventricular.
* **100 mA:** Potencialmente fatal.
* *Regra de ouro: Nunca trabalhe em circuitos energizados sem EPI adequado!*

###  Proteção e Aterramento:
* **Aterramento Funcional:** Referência de tensão para o circuito.
* **Aterramento de Proteção:** Desvia correntes de fuga para a terra (fio verde/amarelo).
* **Proteção ESD (Eletrostática):** Uso obrigatório de **pulseira antiestática**, **manta ESD** e **bolsas antiestáticas** para transporte de placas e memórias RAM.
* **Por que é crítico?** Descargas eletrostáticas podem ultrapassar **3.000V** — sendo imperceptíveis ao toque, mas suficientes para queimar componentes sensíveis como CPUs e chipsets.
* *Aviso: Nunca toque nos contatos dourados dos componentes com os dedos.*

---

##  6. Ferramentas e Equipamentos de Bancada

* **Instrumentos de Medição:** Multímetro, testador de fontes ATX e testador de portas USB. Verificam tensões, continuidade e erros de comunicação.
* **Chaves e Alicates:** Chaves Phillips, fenda, estrela (Torx) e porca. Alicates de corte, bico e pressão. Pinças para manipulação de componentes SMD.
* **EPIs e Proteção:** Luvas isolantes, óculos de proteção, chave-teste e lanterna LED.
* **Materiais de Montagem:** Pasta térmica (renovar a cada 2 anos), lubrificantes para coolers, parafusos, porcas e arruelas organizados.

---

##  7. Manuais de Fabricante e Montagem de Computadores

Consultar o manual da placa-mãe antes de qualquer montagem é prática obrigatória. Ele contém informações cruciais sobre soquete, slots, jumpers, BIOS e limites de potência.

###  Análise de Compatibilidade:
* **Soquete CPU:** Intel (ex: LGA 1700) vs. AMD (ex: AM5) — o processador e o soquete da placa devem ser idênticos.
* **Memória RAM:** DDR4 vs. DDR5 — possuem encaixes físicos e tensões elétricas diferentes.
* **Placa de Vídeo:** Verificação do slot PCIe x16 e do espaço físico disponível no gabinete.
* **Fonte de Alimentação:** Calcular o TDP total dos componentes e adicionar uma margem de segurança de 30%.
  * *Exemplo prático:* Ryzen 7 7800X3D (120W) + RTX 4070 (200W) + demais componentes ≈ 400W ⮕ Fonte mínima recomendada: **650W 80 Plus Bronze**.

###  Melhores Práticas e Sequência de Montagem:
Seguir a ordem correta reduz retrabalho e riscos de danos às peças:
1. **Verificar compatibilidade:** Checar manuais e peças antes de começar.
2. **Montar componentes na bancada:** Instalar CPU, memória RAM e o cooler antes de fixar a placa-mãe no gabinete.
3. **Aplicar pasta térmica:** Colocar uma quantidade equivalente a um grão de arroz no centro da CPU.
4. **Instalar no gabinete:** Fixar a placa e conectar todos os cabos da fonte e do painel frontal.
5. **Organizar cabos:** Garantir o gerenciamento de cabos para manter o fluxo de ar adequado.
6. **Teste inicial (Boot Mínimo):** Testar o funcionamento básico dos componentes antes de fechar totalmente o gabinete.
7. **Configuração inicial:** Acessar a BIOS para checar o reconhecimento das peças e atualizá-la antes de instalar o Sistema Operacional.
   
