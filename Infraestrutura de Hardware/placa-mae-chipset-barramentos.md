# UC1 Placa-mãe, Chipset e Barramentos
A **placa-mãe** é o principal circuito do computador, interligando todos os componentes. O **chipset** megerencia a comunicação entre processador, memória, armazenamento e periféricos. Conhecer conectores e barramentos é essencial para montagem e diagnóstico.
---
## 1. Componentes da Placa-mãe
* **Soquete CPU e Slots RAM:** O soquete recebe o processador. Os slots RAM suportam DDR4 ou DDR5 — **não são intercambiáveis**. Consulte sempre o manual da placa.
* **PCIe, M.2 e SATA:** PCIe x16 para placas de vídeo. M.2 para SSDs NVMe modernos. SATA para HDs e SSDs SATA. Verifique compatibilidade e versão do padrão.
* **Conectores de Energia e I/O:** ATX 24 pinos (placa), EPS 4/8 pinos (CPU), USB e áudio frontal, fan headers e bateria CMOS que mantém configurações da BIOS/UEFI.
> **Atualizações recentes:** Placas modernas suportam DDR4/DDR5, SSD NVMe, PCIe 4.0/5.0, USB-C, Wi-Fi integrado, UEFI e TPM para segurança.
---
## 2. Processador, Memória RAM e Armazenamento
### Processador (CPU)
Executa instruções e cálculos. Características-chave: **núcleos, threads, clock, cache e soquete**. Mais núcleos = melhor multitarefa.
* **2 núcleos:** uso básico
* **4-6 núcleos:** escritório e jogos
* **8+ núcleos:** edição e uso profissional
### Memória RAM
Armazena dados temporários em uso. **DDR4 e DDR5 não são intercambiáveis** — consulte o manual da placa-mãe.

| Característica | DDR4 | DDR5 |
| :--- | :--- | :--- |
| **Desempenho** | Bom | Maior largura de banda |
| **Compatibilidade** | Placas DDR4 | Placas DDR5 |
| **Custo** | Menor | Maior |
| **Velocidades** | até 3200 MT/s | 4800-6000 MT/s |

### Tipos de Armazenamento
* **HD:** Partes mecânicas. Mais barato por GB. Mais lento. Ideal para grande volume de arquivos.
* **SSD SATA:** Sem partes mecânicas. Mais rápido que HD. Ótima opção para upgrade em computadores antigos.
* **SSD NVMe M.2:** Muito mais rápido. Usa slot M.2 e protocolo NVMe. Ideal para sistemas atuais e dispositivos modernos.
---
## 3. Fonte, Gabinete, Refrigeração e Periféricos
### Fonte de Alimentação
Transforma energia da tomada em tensões usadas pelo computador (12V, 5V, 3.3V). Escolha com **potência real, certificação e proteções:** OVP, OCP, SCP, OPP e OTP.
* **ATX 24 pinos:** alimentação principal
* **EPS 4/8 pinos:** processador
* **SATA Power:** SSDs e HDs
* **PCIe 6/8 pinos:** placas de vídeo
### Refrigeração e Gabinete
* **Air cooler e water cooler** para CPU.
* **Fans frontais** puxam ar frio; **traseiros** expulsam ar quente.
* **Gabinetes:** Mini, Mid e Full Tower.
* Compatível com placa-mãe, GPU e cooler.
> **Erros comuns:** Cooler mal encaixado, pasta térmica em excesso ou insuficiente, fan invertido, cabos bloqueando ventilação.
### Periféricos e Tecnologias Atuais
* **Monitores e Vídeo:** HDMI, DisplayPort e USB-C. Alta taxa de atualização para jogos e design.
* **Conectividade:** USB-C, Wi-Fi 6/6E/7, Bluetooth 5.x, NVMe, DDR5 e PCIe 4.0/5.0.
* **Entrada e Saída:** Teclado, mouse, headset, webcam e impressoras via USB, Bluetooth ou Wi-Fi.
---
## 4. Atividades Práticas e Estudos de Caso
Cada aula inclui atividades práticas para consolidar o aprendizado. Os alunos trabalham em grupos, simulam situações reais e apresentam soluções justificadas.
1. **Montando a Bancada Ideal (Aula 1):** Grupos montam bancada simulada com ferramentas corretas, peças organizadas, áreas separadas e checklist de segurança. Apresentam riscos evitados e ferramentas obrigatórias.
2. **Certo ou Errado na Bancada (Aula 2):** Alunos classificam situações como corretas ou incorretas: montar sobre carpete, segurar RAM pelos contatos, usar embalagem antiestática, retirar cabo de força antes de abrir.
3. **Laboratório de Medição (Aula 3):** Medições reais com multímetro: tomada (ACV), bateria CMOS (DCV), fonte (12V e 5V), fusível e cabo de força. Registro de valores e conclusões técnicas.
4. **Escolha do Hardware por Perfil (Aula 4):** Três clientes: escritório, aluno de TI e designer. Cada grupo recomenda CPU, RAM, armazenamento, fonte e periféricos com justificativa técnica.
---
## 5. Fechamento, Avaliação e Fixação
### Competências Desenvolvidas
* Preparar e organizar bancada técnica
* Identificar e usar ferramentas corretamente
* Aplicar proteção ESD nos componentes
* Medir tensão e continuidade com multímetro
* Identificar componentes de hardware
* Relacionar configuração com necessidade do usuário
### Critérios de Avaliação

| Critério | Peso |
| :--- | :--- |
| Organização da bancada | 20% |
| Uso correto das ferramentas | 20% |
| Proteção ESD aplicada | 20% |
| Uso seguro do multímetro | 25% |
| Registro técnico das medições | 15% |

### Perguntas Rápidas de Fixação
#### Módulo 3
* Para que serve a pulseira antiestática?
* Qual escala mede tomada? E bateria CMOS?
* Por que não medir resistência em circuito energizado?
#### Módulo 4
* Qual a diferença entre HD, SSD SATA e NVMe?
* Qual conector alimenta a placa-mãe? E o processador?
* Por que verificar compatibilidade antes da montagem?
