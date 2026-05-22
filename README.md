# TelePronto - Protótipo de Baixa Fidelidade (IHC & UX)

Repositório destinado à entrega da Lista de Exercícios XIX da disciplina de Interação Humano Computador e UX (Centro Universitário UNA).

---

## 👥 Equipe
* Ana Gomes
* Nátali Fialho
* Nicolas
* Ricardo
* Samuel Franco

---

## 📱 O Projeto
O **TelePronto** é um aplicativo de saúde para o hospital universitário com o objetivo de desafogar o pronto-socorro físico. Ele realiza triagem de casos leves, conecta pacientes a médicos via vídeo-chamada e gerencia receitas digitais e alarmes.

### 🛠️ Telas Prototipadas (Miro)
1. **Home / Dashboard:** Atalhos para "Consulta Agora", "Meus Remédios" e farmácias.
2. **Fluxo de Triagem:** Seleção rápida de sintomas e onde dói.
3. **Sala de Espera Virtual:** Exibição da fila e tempo estimado de espera.
4. **Interface de Vídeo-Chamada:** Controles de mídia e visualização do médico.
5. **Minha Farmácia / Receita:** Exibição de receitas e atestados com QR Code.

---

## 🧠 Análise de IHC e UX

### 🦽 1. Análise de Acessibilidade
Projetado para idosos ou usuários com mal-estar (visão turva/dedos trêmulos):
* **Fontes ampliadas** e alto contraste para facilitar a leitura.
* **Áreas de clique generosas** (botões grandes) para evitar erros de toque.

### 🚨 2. Fluxo Crítico (Urgência)
Caminho mais curto possível para o atendimento:
`Home (Botão "Consulta Agora") -> Triagem Rápida (Sintomas) -> Entrada na Sala de Espera Virtual`.

### 🚫 3. Prevenção de Erros
* **Confirmação de saída:** O botão de "Encerrar Chamada" exige dupla confirmação via *pop-up* antes de desligar, evitando cliques acidentais por nervosismo.

### ✨ 4. Desafios Extras (Opcional)
* **Modo Baixa Conexão:** Alerta em tela avisa que o vídeo foi desligado para priorizar o áudio devido à instabilidade da internet.
* **Fluxo de Dependente:** Menu rápido no topo para alternar perfis (ex: pais gerenciando consultas dos filhos).

---

## 📁 Estrutura do Repositório
* `/prototipo`: Arquivos `prototipo.png` e `prototipo.pdf` exportados do Miro.
* `README.md`: Documentação do projeto.
