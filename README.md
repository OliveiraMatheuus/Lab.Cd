# 💡 Projetos de Circuitos Digitais (Quartus Prime)

Este repositório reúne projetos e exercícios desenvolvidos na disciplina de **Circuitos Digitais**, utilizando o **Intel Quartus Prime**.  
O objetivo é versionar e manter salvo todo o progresso, evitando perdas de arquivos.

---

## 📂 Estrutura do Repositório

- `Aula 1/` → Testes no Quartus Prime 
- `Aula 2/` → Decodificador

---

## 🛠️ Como abrir os projetos

1. Abra o **Quartus Prime**.
2. Vá em **File → Open Project...**.
3. Selecione o arquivo `.qpf` ou `.qsf` da pasta do projeto desejado.
4. Compile o projeto (**Processing → Start Compilation**).
5. (Opcional) Rode a simulação com o arquivo `.vwf` ou com um testbench.

---

## ⚙️ Requisitos

- [Intel Quartus Prime Lite](https://fpgasoftware.intel.com/)  
- (Opcional) ModelSim Intel Edition, caso use simulação com testbench escrito.

---

## 📌 Observações

- Arquivos temporários de compilação (`db/`, `incremental_db/`, `output_files/`) não são versionados aqui, para manter o repositório limpo.
- Apenas arquivos importantes estão salvos:  
  - **.vhd / .v** → códigos em VHDL ou Verilog  
  - **.qsf / .qpf** → configurações do projeto Quartus  
  - **.vwf** → arquivos de simulação (Waveform)  
  - **.bdf** → diagramas em Block Design File (se usados)  

---

## 👤 Autor

- Matheus Oliveira
